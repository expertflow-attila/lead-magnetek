# Ügyfélút-térkép — Canva PDF sablon (élesre kész)

> A lead magnet „terméke", amit az érdeklődő 48 órán belül megkap.
> 4 oldalas A4 PDF. A statikus szöveget egyszer beállítod, a `[[...]]` helyőrzőkbe
> oldalanként bemásolod az AI-kimenetet (lásd 5. rész: megfeleltetés).

---

## 1) DOKUMENTUM-BEÁLLÍTÁS (Canva)
- **Típus:** Canva → „Egyéni méret" → **210 × 297 mm (A4, álló)**, vagy „Dokumentum (A4)".
- **Oldalszám:** 4 (Borító / Ügyfélút + szivárgás / Megoldások / Konzultáció CTA).
- **Margó:** kb. 18–20 mm minden oldalon (Fájl → Beállítások → Margók mutatása).
- **Export:** Megosztás → Letöltés → **PDF Standard** (vagy PDF Nyomtatás, ha postáznád).

## 2) SZÍNPALETTA (alapértelmezett — cseréld a saját brandedre, ha van)
| Szerep | HEX | Hol |
|---|---|---|
| Tinta / főcím | `#1A2238` | címek, sötét sávok |
| Akcent (megoldás) | `#00B5A5` | gombok, „megoldás" kártyák, kiemelés |
| Figyelem (szivárgás) | `#E07A5F` | a 3 „szivárgási pont" kártya |
| Halvány panel | `#F4F6F8` | kártyák háttere |
| Másodlagos szöveg | `#5B6472` | alcímek, lábléc |
| Háttér | `#FFFFFF` | oldalháttér |

## 3) BETŰTÍPUSOK (Canva-ban elérhető, ingyenes)
- **Címsorok:** Poppins (SemiBold / Bold)
- **Szövegtörzs:** Inter (Regular / Medium) — alternatíva: Lato
- Méretek: H1 ~32–36 pt · H2 (szekciócím) ~18–20 pt · törzs ~11–12 pt · lábléc ~9 pt

---

## 4) OLDALANKÉNTI ELRENDEZÉS + PONTOS SZÖVEG

### ── 1. OLDAL — BORÍTÓ ──
**Elrendezés:** felül vékony akcent-sáv (`#00B5A5`), középen a cím, alul sötét lábléc-sáv (`#1A2238`).

- **Felső kis címke** (akcent szín, nagybetűk, betűköz +1):
  `SZEMÉLYRE SZABOTT AUDIT`
- **Főcím (H1, Poppins Bold, tinta):**
  `Ügyfélút-térkép`
- **Alcím (Inter, másodlagos szín):**
  `Hol szivárog el az időd és az érdeklődőid — és mit lehet vele kezdeni.`
- **Kinek készült (panel `#F4F6F8`, lekerekített):**
  `Készült: [[Vállalkozás neve]] részére`
- **Lábléc-sávban (fehér szöveg a sötét sávon):**
  `Expert Flow · [Te neved] · [[dátum]]`
- *(Opcionális vizuál: egy egyszerű, vonalas „útvonal" ikon vagy térkép-motívum középre, halványan.)*

---

### ── 2. OLDAL — AZ ÜGYFÉLUTAD + A SZIVÁRGÁS ──
**Elrendezés:** felül szekciócím-sáv, alatta a lépéssor; lejjebb 3 figyelem-színű kártya.

**Szekció A — szekciócím (H2, tinta, elé 🗺️ ikon):**
`Az ügyfélutad most`

- Alatta számozott lépéssor, mindegyik egy halvány panelben (`#F4F6F8`), nyíllal összekötve:
  ```
  1. [[lépés 1]]
  2. [[lépés 2]]
  3. [[lépés 3]]
  4. [[lépés 4 — ha van]]
  ```

**Szekció B — szekciócím (H2, elé 🕳️ ikon):**
`A 3 legnagyobb szivárgási pont`

- 3 kártya egymás alatt, bal oldalon vastag `#E07A5F` csík (figyelem):
  ```
  ● 1. [[szivárgási pont címe]]
      [[1 mondat: miért kerül ez érdeklődőbe vagy időbe]]

  ● 2. [[…]]
      [[…]]

  ● 3. [[…]]
      [[…]]
  ```

---

### ── 3. OLDAL — A MEGOLDÁS ──
**Elrendezés:** 3 akcent-színű „megoldás" kártya, alatta egy kiemelt „amivel kezdenék" doboz.

**Szekció C — szekciócím (H2, elé 🔧 ikon):**
`Az első 3 folyamat, amit leveszek a válladról`

- 3 kártya, bal oldalon vastag `#00B5A5` csík (megoldás), jobbra egy „megtakarítás" badge:
  ```
  ✓ 1. [[folyamat]]
       [[mit old meg — 1 mondat]]        [ kb. [[X]] óra/hét ]

  ✓ 2. [[…]]
       [[…]]                              [ kb. [[X]]/hó ]

  ✓ 3. [[…]]
       [[…]]                              [ kb. [[X]] ]
  ```

**Szekció D — kiemelt doboz (tinta háttér, fehér szöveg, elé 👉):**
`Amivel a helyedben kezdenék`
`[[1–2 mondat: a legnagyobb hatású lépés és miért épp az]]`

---

### ── 4. OLDAL — A KÖVETKEZŐ LÉPÉS (KONVERZIÓ) ──
**Elrendezés:** nagy címsor, rövid szöveg, 3 pipa, nagy gomb + QR-kód, bizalom-sor, lábléc.

- **Címsor (H1, tinta):**
  `Most már látod, hol szivárog. Tömjük is be — együtt.`
- **Szöveg (Inter):**
  `A térkép megmutatja a réseket. A következő lépés, hogy ne csak lásd, hanem működjön is.
  Egy 30 perces ingyenes konzultáción kiválasztjuk a legnagyobb időrablódat, és ott helyben
  elindítjuk az első AI-munkatársadat. Működő dologgal távozol — nem újabb teendőlistával.`
- **Mit kapsz a híváson (3 pipa, akcent színű ✓):**
  ```
  ✓ A legnagyobb időrablód közös kiválasztása
  ✓ Az első AI-munkatárs élő elindítása
  ✓ Egy világos terv a következő lépéshez
  ```
- **CTA gomb (kitöltött, akcent `#00B5A5`, fehér szöveg, lekerekített):**
  `Foglalok egy ingyenes konzultációt →`
  - Kösd a gombra a foglaló linket (Canva: elem kijelölése → link 🔗 → [foglaló URL]).
  - Mellé tegyél egy **QR-kódot** ugyanarra a linkre (Canva → Alkalmazások → „QR Code" → illeszd be a linket). PDF-ben ez aranyat ér, mert telefonról is azonnal foglalható.
- **Bizalom-sor (másodlagos szín, kicsi):**
  `Ingyenes · Nincs kötelezettség · Működő dologgal távozol · Nem kell AI-t értened`
- **Lábléc-sáv (sötét):**
  `Expert Flow · [Te neved] · [email] · [weboldal]`

---

## 5) PLACEHOLDER → AI-KIMENET MEGFELELTETÉS
Az AI-prompt (a rendszer-dokumentum 5. pontja) pontosan ezeket adja vissza — csak másold a helyére:

| Sablon helyőrző | Honnan jön (AI-kimenet szekció) |
|---|---|
| `[[lépés 1–4]]` | 🗺️ Az ügyfélutad most |
| `[[szivárgási pont 1–3]]` + magyarázat | 🕳️ A 3 legnagyobb szivárgási pont |
| `[[folyamat 1–3]]` + `[[X]]` megtakarítás | 🔧 Az első 3 folyamat… |
| „Amivel a helyedben kezdenék" szöveg | 👉 Amivel a helyedben kezdenék |
| `[[Vállalkozás neve]]`, `[[dátum]]` | a kérdőív 1. válaszából / aznapi dátum |

---

## 6) HOGYAN TÖLTSD KI (2 mód)

**A) Kézi (ajánlott induláshoz — ez a „valódi audit" trükk):**
1. Canva → a sablon jobb felül **„Sablon készítése"** vagy egyszerűen **másold a tervet** minden új érdeklődőnél (Fájl → Másolat készítése).
2. Illeszd be az AI-kimenetet a `[[...]]` helyekre, fusd át 5 percben (te vagy a szakértő — itt finomíthatsz).
3. Letöltés PDF-ben → küldd emailben (a rendszer 1. emailje).

**B) Automatizált (ha már sok a lead — Canva Bulk Create / autofill):**
1. Canva Pro → **Bulk Create** (Alkalmazások): a `[[...]]` mezőket összekötöd egy táblázat oszlopaival.
2. A Make/Zapier az AI-kimenetet beírja a táblázatba → Canva legenerálja a PDF-eket.
3. *(Akkor érdemes erre váltani, ha napi több tíz audit jön — addig a kézi mód jobban konvertál.)*

---

## 7) MINI CHECKLISTA EXPORT ELŐTT
- [ ] Minden `[[...]]` helyőrző kitöltve? (Ctrl+F a Canva-ban nincs — szemrevételezd oldalanként.)
- [ ] A CTA gombon ÉS a QR-kódon a helyes foglaló link?
- [ ] A vállalkozás neve és a dátum stimmel a borítón?
- [ ] Nincs AI-szakszó a szövegben (workflow, API stb.)?
- [ ] PDF Standard méret, < 10 MB (hogy emailben átmenjen)?
```
```
