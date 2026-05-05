---
id: econ_008
title: Közgazdasági teljesítménymutatók (Economic Performance Indicators)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 3.6.3 Közgazdasági teljesítménymutatók
source_page: 36-37
domain: economic_analysis
subdomain: performance_indicators
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - ENPV
  - ERR
  - BCR
  - performance_indicators
related_ids:
  - econ_005
  - econ_006
  - econ_007
  - method_004
---

# Közgazdasági teljesítménymutatók (Economic Performance Indicators)

## Áttekintés

A közgazdasági teljesítménymutatók a projekt társadalmi hasznosságának számszerű kifejezései. Ezek alapján dönthető el, hogy a projekt támogatható-e, és hogyan rangsorolható más projektekhez képest.

## Kötelezően számítandó mutatók

A következő három közgazdasági teljesítménymutatót kell kiszámolni és értékelni:

1. **ENPV** - Gazdasági nettó jelenérték (Economic Net Present Value)
2. **ERR** - Gazdasági belső megtérülési ráta (Economic Rate of Return)
3. **BCR** - Haszon-költség arány (Benefit-Cost Ratio)

## 1. ENPV - Gazdasági nettó jelenérték

### Definíció

Az ENPV a jövőbeni nettó haszonáramok diszkontált értéke. A projekt megítélésének kulcseleme.

### Képlet

```
ENPV = Σ [Xt / (1+i)^t]
       t=0 to n

ahol:
Xt = az adott évre vonatkozó pénzáramlás (hasznok - költségek)
i = diszkontráta (3% reálérték)
t = aktuális év (0 = beruházás kezdete)
n = referencia időszak vége
```

### Számítási módszer

**Lépések:**

1. **Éves nettó cash flow számítása:**
   ```
   Nettó CF(t) = Hasznok(t) - Költségek(t)
   ```

2. **Diszkontálás:**
   ```
   Diszkontált CF(t) = Nettó CF(t) / (1 + 0,03)^t
   ```

3. **Összegzés:**
   ```
   ENPV = Σ Diszkontált CF(t)
   ```

### Értékelési kritérium

**Támogathatósági feltétel:**
```
ENPV > 0
```

**Csak pozitív ENPV-vel rendelkező projektek támogathatók.**

### Értelmezés

- **ENPV > 0:** A projekt társadalmi hasznai meghaladják a társadalmi költségeket
- **ENPV = 0:** A projekt társadalmi hasznai egyenlők a társadalmi költségekkel
- **ENPV < 0:** A projekt társadalmi költségei meghaladják a társadalmi hasznokat

**Nagyobb ENPV = Nagyobb társadalmi hasznosság**

### Előnyök

- Abszolút értéket ad (Ft-ban)
- Figyelembe veszi a pénz időértékét
- Összeadható (portfólió szinten)
- Legmegbízhatóbb mutató

### Hátrányok

- Nem alkalmas különböző méretű projektek rangsorolására
- Érzékeny a diszkontráta változására
- Nem mutatja a hatékonyságot (csak az abszolút értéket)

## 2. ERR - Gazdasági belső megtérülési ráta

### Definíció

Az ERR azon diszkontráta, amely mellett az ENPV nulla. A projekt "belső" megtérülési rátája.

### Képlet

```
0 = Σ [Xt / (1+ERR)^t]
    t=0 to n

ahol:
ERR = keresett belső megtérülési ráta
```

**Más megfogalmazásban:**
Az ERR az a diszkontráta (i), amelyre:
```
ENPV(i=ERR) = 0
```

### Számítási módszer

**Iteratív megoldás:**

1. Kezdő érték: i = 3%
2. Számítsd ki ENPV(i)-t
3. Ha ENPV > 0, növeld i-t
4. Ha ENPV < 0, csökkentsd i-t
5. Ismételd, amíg ENPV ≈ 0

**Excel függvény:**
```
=IRR(értéktartomány)
vagy
=MIRR(értéktartomány; finanszírozási_ráta; újrabefektetési_ráta)
```

### Értékelési kritérium

**Támogathatósági feltétel:**
```
ERR > 3%
```

**Az ERR-nek nagyobbnak kell lennie, mint az alkalmazott közgazdasági diszkontráta (3%).**

### Értelmezés

- **ERR > 3%:** A projekt megtérülése meghaladja a társadalmi elvárást
- **ERR = 3%:** A projekt éppen eléri a társadalmi elvárást
- **ERR < 3%:** A projekt nem éri el a társadalmi elvárást

**Nagyobb ERR = Hatékonyabb erőforrás-felhasználás**

### Előnyök

- Százalékos érték (könnyen értelmezhető)
- Alkalmas különböző méretű projektek rangsorolására
- Független a diszkontráta megválasztásától

### Hátrányok

- Nem mindig számítható ki
- Több megoldás is lehet
- Nem ad információt az abszolút értékről

### Speciális esetek

**⚠️ Amikor az ERR nem számítható:**

1. **Nincs gyök:**
   - A pénzáramok előjele nem vált
   - Minden pénzáram negatív vagy pozitív
   - Példa: Csak költségek, nincs haszon

2. **Több gyök van:**
   - A pénzáramok előjele többször vált
   - Annyi ERR, ahányszor a pénzáram előjelet vált
   - Példa: Beruházás → Hasznok → Pótlás → Hasznok

**Megoldás:**
Ha az ERR nem számítható ki, csak az ENPV alapján lehet dönteni.

## 3. BCR - Haszon-költség arány

### Definíció

A BCR a teljes időszakra vonatkozóan a jelenértékre átszámított hasznok és költségek arányát mutatja.

### Képlet

```
BCR = Σ [Hasznok(t) / (1+i)^t] / Σ [Költségek(t) / (1+i)^t]
      t=0 to n                    t=0 to n

vagy egyszerűbben:

BCR = PV(Hasznok) / PV(Költségek)
```

### Számítási módszer

**Lépések:**

1. **Hasznok jelenértéke:**
   ```
   PV(Hasznok) = Σ [Hasznok(t) / (1,03)^t]
   ```

2. **Költségek jelenértéke:**
   ```
   PV(Költségek) = Σ [Költségek(t) / (1,03)^t]
   ```

3. **Arány számítása:**
   ```
   BCR = PV(Hasznok) / PV(Költségek)
   ```

### Értékelési kritérium

**Támogathatósági feltétel:**
```
BCR > 1
```

**A BCR-nek nagyobbnak kell lennie, mint 1.**

### Értelmezés

- **BCR > 1:** A hasznok meghaladják a költségeket
- **BCR = 1:** A hasznok egyenlők a költségekkel
- **BCR < 1:** A költségek meghaladják a hasznokat

**Példák:**
- BCR = 1,5: Minden 1 Ft költségre 1,5 Ft haszon jut
- BCR = 2,0: Minden 1 Ft költségre 2 Ft haszon jut

### Előnyök

- Egyszerű, intuitív mutató
- Hatékonyságot mutat
- Alkalmas rangsorolásra

### Hátrányok

- Önmagában kevés információt ad
- Nem ad tájékoztatást az abszolút értékről
- Érzékeny a költség/haszon besorolásra

## Mutatók közötti kapcsolat

### Konzisztencia

**Ha ENPV > 0, akkor:**
- ERR > 3%
- BCR > 1

**Ha ENPV = 0, akkor:**
- ERR = 3%
- BCR = 1

**Ha ENPV < 0, akkor:**
- ERR < 3%
- BCR < 1

### Matematikai kapcsolat

```
ENPV = PV(Hasznok) - PV(Költségek)

BCR = PV(Hasznok) / PV(Költségek)

Ebből:
ENPV = PV(Költségek) × (BCR - 1)
```

## Gyakorlati alkalmazás

### Példa számítás

**Projekt adatok:**
- Beruházási költség (0. év): 1,000 M Ft
- Éves működési költség (1-15. év): 50 M Ft/év
- Éves haszon (1-15. év): 150 M Ft/év
- Diszkontráta: 3%

**1. ENPV számítása:**

```
Éves nettó CF = 150 - 50 = 100 M Ft

ENPV = -1,000 + Σ [100 / (1,03)^t]
                 t=1 to 15

ENPV = -1,000 + 100 × 11,938 = 193,8 M Ft
```

**2. ERR számítása:**

```
0 = -1,000 + Σ [100 / (1+ERR)^t]
             t=1 to 15

ERR ≈ 7,2%
```

**3. BCR számítása:**

```
PV(Hasznok) = 150 × 11,938 = 1,790,7 M Ft
PV(Költségek) = 1,000 + 50 × 11,938 = 1,596,9 M Ft

BCR = 1,790,7 / 1,596,9 = 1,12
```

**Értékelés:**
- ENPV = 193,8 M Ft > 0 ✓
- ERR = 7,2% > 3% ✓
- BCR = 1,12 > 1 ✓

**Következtetés:** A projekt támogatható.

## Rangsorolás és döntéshozatal

### Egyedi projekt értékelése

**Döntési szabály:**
```
Ha ENPV > 0 ÉS ERR > 3% ÉS BCR > 1
→ Projekt támogatható
```

### Több projekt rangsorolása

**Korlátlan költségvetés esetén:**
- Minden ENPV > 0 projekt támogatható
- Rangsorolás nem szükséges

**Korlátozott költségvetés esetén:**

**1. Azonos méretű projektek:**
- Rangsorolás ENPV szerint
- Vagy ERR szerint
- Vagy BCR szerint
- Mindhárom konzisztens eredményt ad

**2. Különböző méretű projektek:**
- **NE használd az ENPV-t rangsorolásra!**
- Használd az ERR-t vagy BCR-t
- Vagy számítsd ki a "haszon/költség" hatékonyságot

**3. Kölcsönösen kizáró alternatívák:**
- Számítsd ki az inkrementális ENPV-t
- Válaszd a legnagyobb ENPV-vel rendelkező alternatívát

### Referencia mutató

**Az ENPV a legfontosabb és legmegbízhatóbb társadalmi költség-haszon elemzési indikátor.**

A projekt értékelésénél az ENPV-t kell a fő közgazdasági teljesítményjelző referenciaként tekinteni.

## Kivételes esetek

### Negatív ENPV esetén is támogatható projekt

**Feltételek:**

1. **Fontos pénzben nem kifejezhető hasznai vannak**
2. **Kivételes esetként kell kezelni**
3. **Meggyőző indoklás szükséges:**
   - Strukturált
   - Megfelelő adatokkal alátámasztott
   - Bizonyítja, hogy a társadalmi hasznok meghaladják a társadalmi költségeket
   - Még akkor is, ha a pályázó nem tudja teljes mélységében számszerűsíteni

**Példák:**
- Kulturális örökség megőrzése
- Társadalmi kohézió erősítése
- Stratégiai jelentőségű projektek
- Esélyegyenlőségi célok

**⚠️ Figyelem:**
Ez valóban kivételes eset, nem általános gyakorlat!

## Számítás a CBA sablonban

### Automatikus számítás

A közgazdasági teljesítménymutatókat a CBA sablonban kell kiszámolni a beírt input adatok és paraméterek alapján.

**A sablon automatikusan számítja:**
- ENPV-t
- ERR-t (ha számítható)
- BCR-t

### Ellenőrzési pontok

**Konzisztencia ellenőrzés:**
- [ ] ENPV előjele konzisztens az ERR-rel és BCR-rel
- [ ] Számítások helyesek
- [ ] Diszkontráta megfelelő (3%)
- [ ] Referencia időszak helyes

## Érzékenységvizsgálat

### Kötelező elemek

**Minden mutató esetén vizsgálni kell:**

1. **Diszkontráta változása:**
   - 3% → 5% (növelés)
   - 3% → 1% (csökkentés)

2. **Kulcs paraméterek változása:**
   - Beruházási költség ±20%
   - Működési költség ±20%
   - Hasznok ±20%

3. **Forgatókönyvek:**
   - Pesszimista (alacsony hasznok, magas költségek)
   - Bázis (várható értékek)
   - Optimista (magas hasznok, alacsony költségek)

### Kritikus értékek

**Switching values:**
Azon paraméter értékek, amelyeknél:
- ENPV = 0
- ERR = 3%
- BCR = 1

**Példa:**
"A beruházási költség hány %-os növekedése mellett válik a projekt nem támogathatóvá?"

## Kapcsolódó fogalmak

- **Nettó jelenérték (NPV):** Diszkontált cash flow-k összege
- **Belső megtérülési ráta (IRR):** Diszkontráta, ahol NPV = 0
- **Diszkontráta:** Időpreferencia kifejezése (3% reálérték)
- **Referencia időszak:** Elemzési időhorizont (jellemzően 15-30 év)
- **Cash flow:** Pénzáramlás (hasznok - költségek)

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- Az ENPV a legfontosabb mutató
- Mindhárom mutatónak konzisztensnek kell lennie
- ERR nem mindig számítható
- Érzékenységvizsgálat kötelező

⚠️ **Gyakori hibák:**
- ENPV használata különböző méretű projektek rangsorolására
- ERR számítása atipikus cash flow esetén
- BCR félreértelmezése (nem profitabilitási mutató)
- Diszkontráta helytelen alkalmazása

⚠️ **Validációs igény:**
- Számítások helyességének ellenőrzése
- Konzisztencia vizsgálat
- Érzékenységvizsgálat eredményeinek értékelése

## Hivatkozások

- EU Regulation 2015/207 (CBA methodology)
- European Commission: Guide to Cost-Benefit Analysis
- Közgazdasági költségek → econ_005
- Közgazdasági hasznok → econ_007
- Érzékenységvizsgálat → risk_001
- CBA paraméterek → method_004