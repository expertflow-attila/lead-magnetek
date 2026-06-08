# PostHog mérés — beállító útmutató

> Projekt: **Exper Flow** (EU, `eu.posthog.com`, project id: 110419)
> Cél: végigmérni a lead magnet tölcsért, hogy lásd, hol esik ki a legtöbb érdeklődő.
> Megjegyzés: a PostHog közvetlen írását (insight létrehozás) az asszisztens engedélyezője
> blokkolta — ezért itt a kész recept van, amit a csapat (vagy az asszisztens, külön engedéllyel)
> 1 lépésben végrehajthat.

---

## 1) A KÖVETENDŐ ESEMÉNYEK

| Esemény neve | Mikor küldd | Hol instrumentáld |
|---|---|---|
| `audit_started` | elkezdte a kérdőívet | weboldal / kérdőív első lépés |
| `audit_completed` | kitöltötte az auditot | kérdőív utolsó lépés |
| `email_captured` | megadta az emailt | email-bekérő képernyő |
| `map_delivered` | kiment a térkép PDF | Make/Zapier a kézbesítéskor |
| `consultation_booked` | időpontot foglalt | Cal.com / Calendly webhook |
| `consultation_completed` | megtörtént a hívás | manuálisan / naptár-státusz |
| `became_customer` | vásárolt | fizetési/számlázási webhook vagy manuálisan |

**Ajánlott esemény-tulajdonságok (property-k)** — ezekre később szegmentálhatsz:
- `source` — honnan jött az érdeklődő (a kérdőív 2. kérdése: ajánlás / social / hirdetés / Google…)
- `obstacle` — a záró kérdés válasza (A / B / C / D)
- `service_type` — mit csinál a vállalkozó (1. kérdés)

---

## 2) HOGYAN KÜLDD AZ ESEMÉNYEKET (instrumentálás)

### a) Weboldal (ha a kérdőív a saját oldaladon van)
A PostHog web-snippet már fut az oldaladon (ha nem, tedd be a fejléybe). Aztán:
```js
posthog.capture('audit_started')
// az audit végén:
posthog.capture('audit_completed', {
  source: '...', obstacle: 'A', service_type: '...'
})
// email megadásakor — kösd a személyhez is:
posthog.identify(email)          // így a tölcsér végigköveti ugyanazt az embert
posthog.capture('email_captured')
```

### b) Tally / Typeform → Make (Zapier) → PostHog
Ha külső kérdőívet használsz, a kitöltés után Make/Zapier-rel küldd az eseményt a PostHog
EU ingest végpontjára:
```
POST https://eu.i.posthog.com/capture/
Content-Type: application/json

{
  "api_key": "<PROJECT_API_KEY>",
  "event": "audit_completed",
  "distinct_id": "{{email}}",
  "properties": { "source": "{{forras}}", "obstacle": "{{akadaly}}" }
}
```
*(A PROJECT_API_KEY a PostHog → Settings → Project → Project API Key alatt van.)*

### c) Cal.com / Calendly foglalás → PostHog
A foglaló eszköz webhookját kösd Make-be, és küldd:
```
event: "consultation_booked", distinct_id: "{{email}}"
```
Így ugyanahhoz az emberhez fűződik, akit az `email_captured`-nél azonosítottál.

### d) became_customer
Stripe/számlázó webhook → Make → `became_customer` esemény, vagy eleinte kézzel a PostHogban.

---

## 3) A FŐ TÖLCSÉR (kész funnel — másold be a query-funnel hívásba)

Ezt a JSON-t használva létrejön a fő konverziós tölcsér (utolsó 90 nap):

```json
{
  "kind": "FunnelsQuery",
  "series": [
    { "kind": "EventsNode", "event": "audit_started",       "name": "Audit elkezdve" },
    { "kind": "EventsNode", "event": "email_captured",      "name": "Email megadva" },
    { "kind": "EventsNode", "event": "consultation_booked", "name": "Konzultáció foglalva" },
    { "kind": "EventsNode", "event": "became_customer",     "name": "Ügyfél lett" }
  ],
  "dateRange": { "date_from": "-90d" },
  "funnelsFilter": {
    "funnelOrderType": "ordered",
    "funnelVizType": "steps",
    "funnelWindowInterval": 14,
    "funnelWindowIntervalUnit": "day"
  }
}
```

**Bontás iparág vagy akadály szerint** (opcionális) — add hozzá:
```json
"breakdownFilter": { "breakdown_type": "event", "breakdown": "obstacle" }
```
Így látod, melyik akadály-típusú (A/B/C/D) érdeklődő konvertál a legjobban.

---

## 4) JAVASOLT DASHBOARD ("Lead magnet tölcsér")
3 csempe elég az induláshoz:
1. **Fő tölcsér** (a fenti funnel) — hol esik ki a legtöbb ember.
2. **Audit-kitöltések időben** (trends, `audit_completed`, napi bontás) — működik-e a forgalom.
3. **Foglalás → ügyfél konverzió** (funnel: `consultation_booked` → `became_customer`) — jó-e a zárás.

---

## 5) MIT NÉZZ A SZÁMOKBÓL
- **audit_started → audit_completed** alacsony? → túl hosszú/nehéz a kérdőív (rövidíts).
- **audit_completed → email_captured** alacsony? → gyengén indokolod, miért adja meg az emailt.
- **email_captured → consultation_booked** alacsony? → erősítsd a térkép végi CTA-t + email-sorozatot.
- **consultation_booked → became_customer** alacsony? → a konzultáció zárásán/ajánlaton csiszolj.
```
```
