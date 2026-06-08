# Expert Flow — Teljes Lead Magnet Rendszer

> **Célcsoport:** 1–4 fős szolgáltató vállalkozók (coachok, tanácsadók, ügynökségek, helyi szolgáltatók)
> **Forrás-elv:** Alex Hormozi — „How to Make Better Offers and Lead Magnets"
> **Vezérelv:** Ne „AI-szolgáltatást" adj el, hanem **kockázatcsökkentett, könnyű belépésű
> üzletfejlesztési segítséget**. Az AI csak a háttérmotor — a kommunikáció üzleti haszonról szól.
> **Végcél:** alacsony kockázatú belépés → **ingyenes konzultáció** → fő ajánlat.

---

## TARTALOM
1. A funnel egy ábrán
2. A lead magnet: „Ügyfélút-térkép"
3. Weboldal-szövegek (a blokkhoz)
4. Az audit kérdései
5. A mögötte futó AI-prompt
6. A kész „termék" sablonja (amit az érdeklődő kap)
7. Követő email-sorozat (5 email)
8. Az ingyenes konzultáció forgatókönyve
9. A fő ajánlat (kockázatfordítással)
10. Megvalósítás kódolás nélkül
11. Mérés (PostHog)
12. Indítási checklista (Hormozi)

---

## 1) A FUNNEL EGY ÁBRÁN

```
Hirdetés / social / organikus
   (üzenet: elvesztett idő és érdeklődők — NEM "AI")
            │
            ▼
   ÜGYFÉLÚT-TÉRKÉP  ◄── a lead magnet (automatizált audit, valódi érték)
   5 kérdés → email → azonnali személyre szabott térkép
            │
            ▼
   A térkép vége: „tömjük be a réseket együtt" → KONZULTÁCIÓ CTA
            │
     ┌──────┴───────┐
     ▼              ▼
 Azonnal foglal   Nem foglal → 5 részes EMAIL-SOROZAT viszi a konzultációig
     │              │
     └──────┬───────┘
            ▼
   INGYENES KONZULTÁCIÓ (30 perc)
   = az igazi "trial of solution": élőben elindul az első AI-munkatárs
            │
            ▼
   FŐ AJÁNLAT (kockázatfordítással) → értéklépcső
```

### Miért lead magnet, és nem közvetlen „foglalj hívást"?

Egy közvetlen „kérj ajánlatot / foglalj hívást" hirdetés csak a piac **legmelegebb**, döntésre kész
részét éri el — ez kicsi szelet. Rövid távon jobb a megtérülése (ROAS), mert aki kattint, már venni
akar. De **kevés embert** ér el, és **nehezen skálázódik**.

A lead magnet **puhítja a kérést**: a sokkal nagyobb, „érzem a problémát, de még nem döntöttem"
közönséget is bevonja. Az első napon alacsonyabb a ROAS, **időtávban viszont magasabb** (az
email-sorozat + a konzultáció konvertál), és **jóval jobban skálázódik**.

**Gyakorlati következmény:**
- A ROAS-t **időtávban** nézd (30/60/90 nap), ne csak az első kattintásból — különben idő előtt
  „kivégzed" a jól működő lead magnetet.
- A közvetlen ajánlatot tartsd meg a legmelegebb közönségre (retargeting) — a kettő kiegészíti egymást.

---

## 2) A LEAD MAGNET: „ÜGYFÉLÚT-TÉRKÉP"

**Egymondatos ígéret:**
„Megmutatom, hol szivárog el az időd és az érdeklődőid — és melyik 3 folyamatot érdemes először
megtámogatnod, hogy ne rajtad múljon minden."

**Miért ez a nyerő (Hormozi 3 típusa alapján):**
- **Problémafeltáró + a megoldás próbája** egyszerre: a vállalkozó érzi a káoszt, te megnevezed,
  és máris megmutatod az irányt.
- **Üzleti probléma-központú**, nem AI-zsargon → nem összehasonlítható „AI-szolgáltatásként".
- **Valódi érték, amiért mások pénzt kérnek** (személyre szabott audit, nem „10 tipp" PDF).
- **Alacsony kockázat + könnyű igent mondani** → magas feliratkozási arány.

**Az érték-vektorok beépítve:**
- **Gyorsaság:** „48 órán belül a kezedben."
- **Kockázat:** „Nem kell rendszerbe beruháznod — előbb csak feltérképezünk."
- **Könnyűség:** „Nem kell AI-t tanulnod. Te elmondod, hogy működik most; a többi az enyém."

### A 3 lead magnet típus — mikor melyiket

Az „Ügyfélút-térkép" fent egy **problémafeltáró + a megoldás próbája** kombó. De ha a számok ezt
kérik, válthatsz vagy tesztelhetsz másikat. A három típus (Hormozi):

| Típus | Mit ad az érdeklődőnek | Mikor válaszd | Expert Flow példa |
|---|---|---|---|
| **Problémafeltáró** | Megnevezi a rejtett bajt, amit eddig csak érzett | Hidegebb közönség, aki még nem látja pontosan a problémát | „Ügyfélút-térkép" (a jelenlegi) • „5 pont, ahol elvesznek az érdeklődőid" |
| **Próba a megoldásból** | Egy kis, valódi eredményt máris megtapasztal | Már érzi a bajt, de bizalom kell, hogy lépjen | „Ingyen elindítom az első AI-munkatársad vázát 48 órán belül" • „Küldd el az érdeklődő-kezelésed, megmutatom, hol veszítesz leadet" |
| **Splinter (egy lépés a teljesből)** | A fő szolgáltatás egy értékes, kiszakított szelete | Közel a vásárláshoz, gyorsabb upsell kell | „AI működési térkép 48 óra alatt" • „Ügyfélút audit" • „Első onboarding email-sorozat vázlata" |

**Hogyan dönts a számokból:**
- Gyenge a **feliratkozás** (kevesen adják meg az emailt)? → kézzelfoghatóbb **próba a megoldásból**.
- Jó a feliratkozás, de kevés a **foglalás**? → **splinter**: vidd közelebb a fő ajánlathoz.

### Belépő: ingyenes magnet vs. erős kedvezmény (tripwire)

Nem csak ingyenes magnettel lehet belépőt adni. Két út, eltérő haszonnal:
- **Ingyenes magnet:** a legtöbb lead, a legkisebb elköteleződés — hideg közönségre ideális.
- **Erős kedvezményű, kis fizetős lépés (tripwire):** kevesebb, de **előminősített** érdeklődő —
  aki fizet (bármilyen keveset), az komolyabban gondolja.

Hormozi figyelmeztetése: a **10–20% kedvezmény gyenge**, nem változtat viselkedést. Ha kedvezményt
adsz, az legyen **80–90%** egy olyan részre, ami neked **olcsón előállítható, de az ügyfélnek
értékes**. Például: *„AI működési audit — normál ár 80 000 Ft, most elsőre 9 900 Ft"* → majd innen
upsell a fő ajánlatra (lásd `§ 9`).

---

## 3) WEBOLDAL-SZÖVEGEK (a lead magnet blokkhoz)

### 3.1 Hero — fő variáció (kockázat + könnyűség)
**Címsor:**
Megmutatom, hol szivárog el az időd és az érdeklődőid — 48 órán belül.

**Alcím:**
Ha 1–4 fős szolgáltató vállalkozásod van, valószínűleg te vagy az értékesítő, az ügyfélszolgálat és
az adminisztrátor is egyszerre. Készítek neked egy ügyfélút-térképet: megmutatom, hol vesznek el
érdeklődők és órák, és melyik 3 folyamatot érdemes először levenned a válladról. AI-t tanulnod sem kell.

**CTA gomb:** Kérem az ingyenes ügyfélút-térképet →
**Bizalom-sor:** Ingyenes • 48 órán belül • Személyre szabott diagnózis, nem reklám

### 3.2 Hero — fájdalompont-variáció (A/B teszthez)
**Címsor:**
Sok a káosz, de nem tudod pontosan, hol akad el?

**Alcím:**
A legtöbb 1–4 fős szolgáltató nem rossz szolgáltatás miatt nem nő, hanem mert minden rajta múlik —
és közben csendben elvesznek az érdeklődők. Megnézem helyetted, pontosan hol. És megmutatom, mit
lehet vele kezdeni.

**CTA gomb:** Megnézem, hol veszítek →
**Bizalom-sor:** Ingyenes • Nincs kötelezettség • Nem kell AI-t értened hozzá

### 3.3 „Ez NEM egy újabb ingyenes PDF" blokk (a hero alá, hitelesít)
**Címsor:** Ez nem egy letölthető e-book.
**Szöveg:**
Nem általános tippeket kapsz, amiket már százszor láttál. A saját vállalkozásodra nézem meg, mi
történik attól a pillanattól, hogy valaki érdeklődik nálad, addig, hogy fizető ügyfél lesz — és
megmutatom a 3 legnagyobb rést, ahol idő, érdeklődő vagy ügyfélélmény szivárog el.

### 3.4 Email-bekérő képernyő (a kérdések után, a térkép előtt)
**Címsor:** Kész a térképed ✅
**Szöveg:** Add meg az emailed, és 48 órán belül elküldöm a személyre szabott ügyfélút-térképedet.
**Mező:** Email cím
**Gomb:** Kérem a térképem →
**Apró betű:** Hasznos, gyakorlati tippeket is küldök 1–4 fős vállalkozóknak. Bármikor leiratkozhatsz.

### 3.5 Eredmény / köszönő-oldal — híd a konzultációhoz (LEGFONTOSABB)
**Címsor:** Most már látod, hol szivárog. Tömjük is be — együtt.
**Szöveg:**
A térkép megmutatja a réseket. A következő lépés, hogy ne csak lásd, hanem működjön is. Egy 30 perces
ingyenes konzultáción kiválasztjuk a legnagyobb időrablódat, és **ott helyben elindítjuk az első
AI-munkatársadat**. Konkrét, működő dologgal távozol — nem újabb teendőlistával.
**CTA gomb:** Foglalok egy ingyenes konzultációt →
**Bizalom-sor:** Nincs kötelezettség • Működő dologgal távozol • Nem kell AI-t értened

### 3.6 Fájdalom-számszerűsítés (a státusz quo ára)

Az ember akkor lép, ha **számot** lát a veszteségre — nem elég, hogy „sok a káosz". A landingen és a
térképben tedd nagyságrenddé a mostani veszteséget (mindig „kb.", **sosem garantált bevétel**):

**Egyszerű képlet:**
`(elveszett érdeklődő/hó × egy ügyfél átlagos értéke) + (kézi munkára menő óra/hét × a te órád értéke) = a státusz quo becsült havi ára`

**Példa copy:**
„Ha hetente kb. 5 óra megy el kézi adminra, és havonta akár 2 érdeklődő elsikkad, az nagyságrendileg
több tízezer forint és egy teljes munkanap — **minden hónapban, újra.** A térkép megmutatja, pontosan hol."

> A személyre szabott számot az audit AI-kimenete adja (lásd `§ 5`–`§ 6`): a 🕳️ rész alatt ott a
> „státusz quo becsült havi ára". Ez teszi a fájdalmat kézzelfoghatóvá — anélkül, hogy bevételt ígérnél.

---

## 4) AZ AUDIT KÉRDÉSEI

> Cél: elég kevés, hogy könnyű legyen (Hormozi: ease!), de elég gazdag a jó kimenethez. 6 kérdés + 1 záró.

**1. Milyen szolgáltatást nyújtasz, és hányan vagytok?**
*szabad szöveg* — pl. „Marketing tanácsadás, 2 fő."

**2. Honnan jönnek ma az érdeklődőid?** *(több is választható)*
☐ Ajánlás ☐ Social media ☐ Hirdetés ☐ Google-keresés ☐ Networking/élő ☐ Egyéb

**3. Mi történik, amikor valaki érdeklődik nálad? Írd le lépésről lépésre, ahogy MOST csinálod.**
*szabad szöveg* — pl. „ír egy DM-et → válaszolok, amikor ráérek → küldök árat → ha nem jelez vissza,
általában elfelejtem utánakérdezni."

**4. Mi történik, miután valaki ügyfél lett?** *(onboarding, kommunikáció, számlázás)*
*szabad szöveg*

**5. Melyik 3 ismétlődő feladat viszi el a legtöbb idődet hetente?**
*szabad szöveg*

**6. Ha EGY dolgot megoldhatnál holnap, mi lenne az?**
*szabad szöveg*

**Záró (a konzultáció személyre szabásához):** Mi a legnagyobb akadályod most?
- A) Jönnek az érdeklődők, de sokan „elsikkadnak" / nincs utánkövetés
- B) Túl sok időt visz az adminisztráció és a kézi munka
- C) Rendszertelen az egész, fejben tartom a dolgokat
- D) Van ötletem, de nincs időm/energiám bevezetni

---

## 5) A MÖGÖTTE FUTÓ AI-PROMPT (rendszerprompt — élesre kész)

```
Szerepkör: Üzletfejlesztési és folyamat-tanácsadó vagy, aki 1–4 fős szolgáltató
vállalkozóknak segít befoltozni az ügyfélút réseit. Az AI/automatizáció csak
eszköz a háttérben — SOHA ne használj technikai szakszót (workflow, API,
integráció, CRM, pipeline). Üzleti, emberi nyelven beszélj. Stílus: konkrét,
gyakorlatias, meleg, túlzások és üres szlogenek nélkül. Megszólítás: „te".

Feladat: Az alábbi válaszokból
1) rajzold fel egyszerű lépéssorként az ügyfélutat (érdeklődéstől a fizető ügyfélig),
2) azonosíts PONTOSAN 3 szivárgási pontot (hol veszik el érdeklődő, idő vagy
   ügyfélélmény), mindegyikhez 1 mondat, hogy miért fáj ez üzletileg, és ahol
   lehet, egy óvatos „kb." becslés (óra/hét vagy elveszett érdeklődő/hó),
3) javasolj 3 konkrét folyamatot, amit először levennél a vállukról, mindegyikhez
   a várható haszon (felszabaduló idő VAGY kevesebb elveszett érdeklődő),
4) jelöld meg, mivel kezdenél a helyükben, és miért.

Szabályok:
- Csak a megadott adatból dolgozz; ne találj ki tényt. Ahol becsülsz, írd oda: „kb.".
- Ha egy válasz túl homályos, fogalmazz óvatosan, és 1 mondatban jelezd, mit lenne
  érdemes pontosítani — de attól még adj használható kimenetet.
- Ne ígérj garantált bevételnövekedést. Idő- és érdeklődő-megtartásról beszélj.
- Max ~220 szó.

Bemenet:
- Szolgáltatás / csapatméret: {{q1}}
- Érdeklődők forrása: {{q2}}
- Jelenlegi folyamat érdeklődéskor: {{q3}}
- Mi történik ügyféllé válás után: {{q4}}
- Top 3 időrabló feladat: {{q5}}
- Az 1 dolog, amit megoldana: {{q6}}
- Legnagyobb akadály (A/B/C/D): {{q7}}

Kimenet pontosan ebben a szerkezetben, magyarul:

🗺️ Az ügyfélutad most
(3–6 lépéses, számozott lépéssor a válaszaiból, egyszerű nyelven)

🕳️ A 3 legnagyobb szivárgási pont
1. (pont) — (1 mondat: miért kerül ez érdeklődőbe vagy időbe) [+ „kb." becslés, ha van]
2. …
3. …

💸 A státusz quo becsült havi ára
(1 sor: a fenti rések összegezve „kb." óra/hét és/vagy elveszett érdeklődő/hó —
sosem garantált bevétel, csak a mostani veszteség nagyságrendje)

🔧 Az első 3 folyamat, amit levennék a válladról
1. (feladat) → (mit oldana meg, 1 mondat) — kb. (X) óra/hét vagy (X) elveszett
   érdeklődő/hó megtakarítás
2. …
3. …

👉 Amivel a helyedben kezdenék
(1–2 mondat: a legnagyobb hatású pont, és miért épp az. Kapcsold a megadott
akadályhoz [{{q7}}].)

Zárás: 2 mondat arról, hogy ezt egy ingyenes 30 perces konzultáción együtt el is
indítjátok, és működő megoldással távozik — nem újabb teendőlistával.
```

---

## 6) A KÉSZ „TERMÉK" SABLONJA (amit az érdeklődő kap)

> Ez a kimenet váza — az AI tölti ki, te 5 percben véglegesíted, mielőtt kimegy.
> A fejléc/lábléc adja a „fizetős audit" érzetet.

```
────────────────────────────────────────
   ÜGYFÉLÚT-TÉRKÉP — [Vállalkozás neve]
   Készítette: [Te] | Expert Flow
   Dátum: [dátum]
────────────────────────────────────────

🗺️ AZ ÜGYFÉLUTAD MOST
1. …
2. …
3. …
(rövid, vizuális lépéssor)

🕳️ A 3 LEGNAGYOBB SZIVÁRGÁSI PONT
1. [pont] — [üzleti hatás]
2. …
3. …

💸 A STÁTUSZ QUO BECSÜLT HAVI ÁRA
[kb. óra/hét és/vagy elveszett érdeklődő/hó — a mostani veszteség nagyságrendje]

🔧 AZ ELSŐ 3 FOLYAMAT, AMIT LEVENNÉK A VÁLLADRÓL
1. [feladat] → [haszon, becsült megtakarítás]
2. …
3. …

👉 AMIVEL A HELYEDBEN KEZDENÉK
[a legnagyobb hatású lépés + 1 mondat indoklás]

────────────────────────────────────────
   A KÖVETKEZŐ LÉPÉS
   Ezt nem kell egyedül megoldanod. Egy 30 perces
   ingyenes konzultáción kiválasztjuk a legnagyobb
   időrablódat, és ott helyben elindítjuk az első
   AI-munkatársadat. Működő dologgal távozol.

   [ Foglalok egy időpontot → ]
────────────────────────────────────────
```

**Formátum:** PDF (pl. Canva-sablon) vagy szép HTML-oldal. A PDF „foghatóbb", könnyebb továbbküldeni.

---

## 7) KÖVETŐ EMAIL-SOROZAT (5 email)

> Cél: aki nem foglal azonnal, azt elvinni a konzultációig. Hangnem: üzleti haszon, nem AI-zsargon.
> Mindegyik 1 gondolat + 1 CTA. A {{keresztnév}} és [foglaló link] behelyettesítendő.

### Email 1 — Kézbesítés (azonnal)
**Tárgy:** Itt az ügyfélút-térképed 🗺️
**Szöveg:**
Szia {{keresztnév}}!

Elkészült a személyre szabott ügyfélút-térképed — csatolva / itt találod: [link].

A lényeg, amit nézz meg először: a **3 szivárgási pont**. Ezek azok a helyek, ahol most
csendben elvesznek érdeklődők vagy órák — anélkül, hogy észrevennéd.

Olvasd át nyugodtan. Ha látod bennük magad (a legtöbben szoktak 🙂), a térkép végén ott a
következő lépés.

Üdv,
[Te]

### Email 2 — Felismerés (1. nap)
**Tárgy:** A leggyakoribb hiba, amit 1–4 fős vállalkozók elkövetnek
**Szöveg:**
Szia {{keresztnév}}!

Megnéztem már sok hasonló méretű vállalkozást, és szinte mindig ugyanaz a fő gond:
**te magad vagy a szűk keresztmetszet.**

Nem azért, mert rossz, amit csinálsz — épp ellenkezőleg. Hanem mert minden rajtad megy
keresztül: az érdeklődő is, a válasz is, az utánkövetés is. És amikor sok a dolgod, pont
az utánkövetés marad el — vagyis pont ott veszíted a pénzt, ahol a legkönnyebb lenne megtartani.

A térképeden valószínűleg ezt is látod. A jó hír: pont ez az, amit elsőként le lehet venni
a válladról.

Üdv,
[Te]

### Email 3 — Kifogáskezelés / sztori (3. nap)
**Tárgy:** „Nem volt időm arra, hogy időt spóroljak"
**Szöveg:**
Szia {{keresztnév}}!

A leggyakoribb mondat, amit hallok: *„Tudom, hogy rendszerezni kéne, de nincs rá időm."*

Értem — és pont ez a csapda. Minél kevesebb az időd, annál inkább rád fér, hogy néhány
ismétlődő dolog magától menjen.

Ezért nem hosszú projektet ajánlok. Egy 30 perces hívás alatt **kiválasztunk egyetlen
folyamatot** a térképedről, és azt indítjuk el — úgy, hogy neked semmit nem kell tanulnod.
Te beszélsz, én építek.

Ha kíváncsi vagy, hogy nálad mi lenne az első: [foglaló link]

Üdv,
[Te]

### Email 4 — A meghívó, kockázatfordítással (5. nap)
**Tárgy:** Megépítem veled az első AI-munkatársad (ingyen, 30 perc)
**Szöveg:**
Szia {{keresztnév}}!

Tegyük konkréttá. Foglalj egy 30 perces ingyenes konzultációt, és **a hívás végére lesz egy
működő AI-munkatársad** a legnagyobb időrablódra. Nem prezentáció, nem „majd küldünk ajánlatot" —
hanem valami, ami már aznap dolgozik helyetted.

Mi a kockázatod? Semmi: ingyenes, és ha a végén úgy érzed, nem neked való, akkor is nyertél egy
kész ügyfélút-térképet és egy működő folyamatot.

[ Foglalok egy időpontot → ]

Üdv,
[Te]

### Email 5 — Utolsó emlékeztető (7. nap)
**Tárgy:** Lezárom a térképed (utolsó emlékeztető)
**Szöveg:**
Szia {{keresztnév}}!

Nem akarlak nyomasztani — ez az utolsó emlékeztetőm ehhez a térképhez.

Ha a 3 szivárgási pont közül akár csak egyet befoltozol, az hetente órákat vagy havonta több
elveszett érdeklődőt jelenthet. A hívás ingyenes, és működő megoldással távozol.

Ha most nem aktuális, semmi gond — a tippeket ezután is küldöm. De ha igen, itt az időpont:
[ Foglalok egy időpontot → ]

Üdv,
[Te]

---

## 8) AZ INGYENES KONZULTÁCIÓ FORGATÓKÖNYVE (30 perc)

> Cél (Hormozi): az ügyfél **működő dologgal távozzon** — ez maga a „trial of solution".

- **0–5 perc — Hol tartasz:** átnézitek a térképét, megerősíted a fő szivárgási pontot.
- **5–10 perc — A cél kiválasztása:** közösen kiválasztjátok az EGY folyamatot, ami a legtöbbet érné
  (kapcsold a záró kérdés A/B/C/D válaszához).
- **10–22 perc — Élő építés:** ott helyben elindítod az első AI-munkatársat erre a folyamatra.
  (Akár egy egyszerű, működő váz is elég — a lényeg, hogy lássa: működik.)
- **22–28 perc — A teljes kép:** megmutatod, hogyan állna össze rendszerré a többi folyamattal
  → itt jön a fő ajánlat (lásd 9. pont).
- **28–30 perc — Következő lépés:** vagy belevág, vagy „gondold át" — utóbbihoz küldd el a hívás
  összefoglalóját + az aznap elindított dolgot.

**Aranyszabály:** a hívás akkor is sikeres, ha nem vásárol — mert akkor is kapott valami működőt.
Ettől lesz hiteles és ajánlott a folyamat.

### Változatok akadálytípus szerint (A/B/C/D)

A záró kérdés (4. rész) akadály-válasza megmondja, **melyik EGY folyamatot** indítsd el élőben, és
milyen kerettel:

| Akadály | Amit élőben elindítasz | A keret-mondat |
|---|---|---|
| **A** — elsikkadnak az érdeklődők, nincs utánkövetés | Automatikus érdeklődő-rögzítés + utánkövetés-emlékeztető | „Mostantól egy lead se vesszen el." |
| **B** — sok az admin és a kézi munka | A leggyakoribb ismétlődő admin (visszaigazolás, számlázási emlékeztető) automatizálása | „Heti pár órát visszaadunk neked." |
| **C** — rendszertelen, fejben tartja a dolgokat | Egy helyen követhető ügyfélállapot / napi összefoglaló | „Ne a fejedben legyen — lásd egy helyen." |
| **D** — van ötlete, de nincs ideje bevezetni | Az ő saját ötletéből egy apró, működő szelet, élőben | „Ma elindul — és nem rajtad múlik." |

---

## 9) A FŐ AJÁNLAT (kockázatfordítással)

**Pozicionálás (NEM „AI-szolgáltatás"):**
„Felépítem helyetted azt a néhány folyamatot, amitől a vállalkozásod nem rajtad múlik —
úgy, hogy neked nem kell AI-eszközöket tanulnod."

**Csomag-váz:**
- Ügyfélút-átvilágítás → a 3 legnagyobb folyamat felépítése → bevezetés → 30 nap támogatás.

**Kockázatfordító garancia (Hormozi 2. vektor — válassz EGYET, ne halmozd):**

| Garancia-típus | Példa megfogalmazás |
|---|---|
| Díjelengedés / pénzvisszafizetés | „Ha 30 napon belül nem működik élesben legalább egy ügyfélfolyamat, a következő hónap díja elmarad." |
| Eredmény-/teljesítménygarancia | „Ha az első hónapban nem szabadít fel legalább heti 2 órát, közösen újraépítjük díjmentesen." |
| Idő-/határidőgarancia | „Ha az első működő folyamat nem áll élesben X napon belül, a bevezetés díját nem számítom fel." |
| „Biztosítás" a legnagyobb félelemre | Nevezd meg a fő félelmet (pl. elakad, leáll, elveszik adat), és vedd le: „Ha bármi elakad, 24 órán belül helyreállítom." |

**Tesztelés:** egyszerre **egy** garanciát kommunikálj, és nézd PostHogban, melyik mellett nő a
`consultation_booked` → `became_customer` arány. A garancia annál erősebb, minél konkrétabban az
ügyfél **legnagyobb félelmét** oldja (kapcsold a záró kérdés akadálytípusához, `§ 8`).

**Árazás — miért prémium (és miért nem árverseny):**
Mivel **gyorsabb + kevésbé kockázatos + könnyebb**, mint egy „csináld magad AI", **nem ugyanazt
árulod**, mint a piac — így kilépsz az árversenyből.
- Ne azt kérdezd: „meg tudom-e csinálni olcsóbban?" Hanem: **„mi kéne, hogy 1/3 idő alatt
  meglegyen?"** — és a többletköltséget (jobb eszköz, előkészítés, gyorsabb válaszidő) **beárazod**.
- Ha az átlagügyfél ezt nem fizeti meg, az nem baj: **menj feljebb a piacon**, ahol a gyorsaság és a
  biztonság többet ér az olcsóságnál.
- A konkrét számot a **saját költséged + a felszabadított idő / megtartott érdeklődő értéke** adja —
  ne 10–20% kedvezménnyel versenyezz (a belépő logikája: `§ 2`).

---

## 10) MEGVALÓSÍTÁS KÓDOLÁS NÉLKÜL
- **Kérdőív:** Tally vagy Typeform.
- **AI-kimenet:** Make / Zapier → Claude (vagy OpenAI) API a fenti prompttal. Vagy ScoreApp.
- **„Valódi audit" trükk:** a generált térképet **te véglegesítsd 5 percben**, mielőtt kimegy —
  így nem automatának, hanem személyes auditnak érződik (sokkal jobban konvertál).
- **Email-sorozat:** MailerLite / ActiveCampaign — időzítve (0 / 1 / 3 / 5 / 7 nap).
- **Foglalás:** Cal.com vagy Calendly, a térkép végén és minden emailben.
- **Térkép formátum:** Canva-PDF sablon (egyszer megcsinálod, az AI-szöveget beilleszted).

---

## 11) MÉRÉS (PostHog)
Kövesd végig a tölcsért külön eseményekkel:
- `audit_started` — elkezdte a kérdőívet
- `audit_completed` — kitöltötte
- `email_captured` — megadta az emailt
- `map_delivered` — kiment a térkép
- `consultation_booked` — időpontot foglalt
- `consultation_completed` — megtörtént a hívás
- `became_customer` — vásárolt

**Fő tölcsér:** audit_started → email_captured → consultation_booked → became_customer.
Ebből látod, hol esik ki a legtöbb ember, és azt a lépést optimalizálod.
*(Ha kéred, segítek beállítani ezeket a PostHogban — látom, hogy él a projekted.)*

---

## 12) INDÍTÁSI CHECKLISTA (Hormozi)
- [ ] Üzleti probléma-központú a kommunikáció, NEM AI-zsargon?
- [ ] Valódi érték, amiért más pénzt kérne? (ne PDF-reklám legyen)
- [ ] Az ő nyelvükön ígér konkrét eredményt? (elvesztett idő/érdeklődő, nem „AI tudás")
- [ ] Ráerősít legalább 1 érték-vektorra? (gyors / kockázatmentes / könnyű)
- [ ] A belépő alacsony kockázatú, és könnyű rá igent mondani?
- [ ] A konzultáció végén az ügyfél MŰKÖDŐ dologgal távozik?
- [ ] A fő ajánlatban van kockázatfordító garancia?
- [ ] Van mérés, hogy lásd, hol esik ki az ember?
