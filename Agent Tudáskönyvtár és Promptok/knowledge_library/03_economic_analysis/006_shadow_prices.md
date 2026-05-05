---
id: econ_006
title: Árnyékárak és gazdasági konverziós tényezők (Shadow Prices and Economic Conversion Factors)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 3.6.1.2 Piaci árról való áttérés elszámoló árra
source_page: 34-36
domain: economic_analysis
subdomain: shadow_prices
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - shadow_prices
  - conversion_factors
  - market_failures
  - economic_valuation
related_ids:
  - econ_005
  - econ_001
  - method_003
  - method_004
---

# Árnyékárak és gazdasági konverziós tényezők

## Áttekintés

Az árnyékárak (shadow prices) és gazdasági konverziós tényezők alkalmazása szükséges, amikor a piaci árak nem tükrözik az erőforrások valós társadalmi költségét vagy hasznát.

## Alapelvek

### Piaci kudarcok

**Definíció:**
Egyes termékek, szolgáltatások esetében a piac a legkülönfélébb torzulások miatt nem képes az erőforrásokat reálisan értékelni, nem tudja kifejezni azok tényleges társadalmi költségét.

**Következmények:**
- Több erőforrás esetében nem beszélhetünk piacról
- Az értékelés elveszti azt a támpontot, amit a piaci ár jelent
- Állami beavatkozás szükségessége

### Állami beavatkozás módjai

1. **Jogrendszeren keresztül:**
   - Biztosítja az erőforrások használóinak olyan alkuját
   - Ami társadalmilag optimális értékre mozdítja azok árát

2. **Adók/szubvenciók révén:**
   - Megfelelő nagyságú adókkal/szubvencióval
   - Korrigálhatja az általa optimálisnak tartott szintre

**⚠️ Fontos:**
- Ahogy a piacok, úgy az állam sem működik tökéletesen
- Az erőforrások tényleges társadalmi költségének meghatározása komplex feladat

## Árnyékárak alkalmazása

### Mikor szükséges?

Árnyékárakat kell alkalmazni, ha:
- A piaci ár nem tükrözi a valós társadalmi költséget/hasznot
- Piaci torzulások jelentősek
- Externális hatások jelentősek
- Nincs piaci ár (közjavak, környezeti erőforrások)

### Főbb alkalmazási területek

1. **Munkaerő árnyékára**
   - Munkanélküliség esetén
   - Regionális munkaerőpiaci különbségek
   - Képzettségi szintek szerinti korrekciók

2. **Tőke árnyékára**
   - Társadalmi diszkontráta
   - Tőkeköltség korrekciója

3. **Földterület árnyékára**
   - Alternatív használati értékek
   - Környezeti értékek

4. **Energia árnyékára**
   - Externális költségek (környezetszennyezés)
   - Ellátásbiztonság értéke

5. **Környezeti erőforrások árnyékára**
   - CO₂ kibocsátás társadalmi költsége
   - Biodiverzitás értéke
   - Ökoszisztéma szolgáltatások

## Konverziós tényezők

### Definíció

**Konverziós tényező (Conversion Factor - CF):**
```
CF = Árnyékár / Piaci ár
```

A konverziós tényező megmutatja, hogy a piaci árat milyen arányban kell korrigálni a társadalmi érték eléréséhez.

### Típusok

1. **Standard konverziós tényező (SCF):**
   - Általános korrekciós tényező
   - Minden nem-kereskedett javakra alkalmazható
   - Országspecifikus érték

2. **Specifikus konverziós tényezők:**
   - Adott erőforrásra, termékre vonatkozó
   - Például: munkaerő CF, energia CF

### Alkalmazási módszertan

**1. Kereskedett javak (traded goods):**
```
Árnyékár = Világpiaci ár (határparitáson)
```
- Import esetén: CIF ár (Cost, Insurance, Freight)
- Export esetén: FOB ár (Free On Board)

**2. Nem-kereskedett javak (non-traded goods):**
```
Árnyékár = Piaci ár × Standard konverziós tényező (SCF)
```

**3. Munkaerő:**
```
Árnyékár = Piaci bér × Munkaerő konverziós tényező
```

Munkaerő CF függ:
- Munkanélküliségi rátától
- Regionális különbségektől
- Képzettségi szinttől
- Alternatív foglalkoztatási lehetőségektől

## Gyakorlati alkalmazás

### Lépések az árnyékárak meghatározásához

1. **Erőforrás azonosítása:**
   - Mely erőforrások igényelnek árnyékár korrekciót?
   - Kereskedett vagy nem-kereskedett javak?

2. **Piaci ár meghatározása:**
   - Aktuális piaci ár azonosítása
   - Releváns időszak és földrajzi terület

3. **Konverziós tényező kiválasztása:**
   - Standard vagy specifikus CF?
   - Forrás: nemzeti útmutatók, EU ajánlások, szakirodalom

4. **Árnyékár számítása:**
   - Piaci ár × Konverziós tényező
   - Vagy: Világpiaci ár (kereskedett javak esetén)

5. **Dokumentálás:**
   - Feltételezések rögzítése
   - Források megjelölése
   - Érzékenységvizsgálat

### Példa: Munkaerő árnyékárának számítása

**Kiindulási adatok:**
- Piaci bér: 500 000 Ft/hó
- Regionális munkanélküliségi ráta: 15%
- Munkaerő konverziós tényező: 0,85

**Számítás:**
```
Munkaerő árnyékára = 500 000 × 0,85 = 425 000 Ft/hó
```

**Értelmezés:**
- A társadalom számára a munkaerő valós költsége alacsonyabb
- Mert a projekt munkahelyeket teremt magas munkanélküliségű régióban
- Az alternatív költség (elmaradt termelés) alacsonyabb, mint a piaci bér

### Példa: Energia árnyékárának számítása

**Kiindulási adatok:**
- Piaci villamosenergia ár: 50 Ft/kWh
- CO₂ externális költség: 10 Ft/kWh
- Ellátásbiztonság prémium: 5 Ft/kWh

**Számítás:**
```
Energia árnyékára = 50 + 10 + 5 = 65 Ft/kWh
```

**Értelmezés:**
- A társadalmi költség magasabb, mint a piaci ár
- Tartalmazza a környezeti externáliákat
- Tartalmazza az ellátásbiztonság értékét

## Adatforrások és referenciák

### Ajánlott források

1. **EU szintű útmutatók:**
   - European Commission: Guide to Cost-Benefit Analysis
   - EIB: Economic Appraisal of Investment Projects

2. **Nemzeti útmutatók:**
   - Magyar Fejlesztési Bank útmutatói
   - Ágazati minisztériumok módszertanai

3. **Nemzetközi szervezetek:**
   - Világbank: Shadow Price Guidelines
   - OECD: Cost-Benefit Analysis Handbook

4. **Specifikus árnyékárak:**
   - CO₂ társadalmi költsége: EIB ajánlások
   - Munkaerő CF: Nemzeti munkaügyi statisztikák
   - Energia CF: Energetikai szabályozó hatóság adatai

## Minőségbiztosítás

### Érzékenységvizsgálat

**Kötelező elemek:**
- Konverziós tényezők változtatása ±20%-kal
- Alternatív árnyékár források összehasonlítása
- Kritikus paraméterek azonosítása

### Dokumentálási követelmények

**Minden árnyékár esetén rögzíteni kell:**
- Alkalmazott érték és forrás
- Számítási módszertan
- Feltételezések és korlátozások
- Alternatív értékek (ha releváns)
- Érzékenységvizsgálat eredményei

## Kapcsolódó fogalmak

- **Piaci kudarc:** A piac nem képes az erőforrásokat hatékonyan allokálni
- **Externális hatás:** Harmadik félre gyakorolt, piaci árakban nem tükröződő hatás
- **Társadalmi költség:** Az erőforrás valós költsége a társadalom számára
- **Határparitás:** Világpiaci ár a hazai határon (import: CIF, export: FOB)
- **Standard konverziós tényező (SCF):** Általános korrekciós tényező nem-kereskedett javakra

## Speciális esetek

### CO₂ kibocsátás árnyékára

**Forrás:** EIB ajánlások (rendszeresen frissített)

**Alkalmazás:**
```
CO₂ társadalmi költsége = Kibocsátás (tonna) × CO₂ árnyékár (EUR/tonna)
```

**⚠️ Figyelem:**
- Az árnyékár időben változik (növekvő trend)
- Különböző forgatókönyvek (alacsony, közepes, magas)
- Érzékenységvizsgálat kötelező

### Munkaerő árnyékára regionális különbségekkel

**Tényezők:**
- Regionális munkanélküliségi ráta
- Képzettségi szint
- Ágazati jellemzők
- Alternatív foglalkoztatási lehetőségek

**Általános képlet:**
```
Munkaerő CF = 1 - (α × Munkanélküliségi ráta)
ahol α = korrekciós paraméter (jellemzően 0,5-0,8)
```

## Gyakorlati korlátok

### Adathiány

**Probléma:**
- Nem minden erőforrásra állnak rendelkezésre megbízható árnyékárak
- Helyi/regionális specifikus értékek hiánya

**Megoldás:**
- Benefit transfer módszer alkalmazása
- Szakértői becslések
- Érzékenységvizsgálat széles tartományban

### Módszertani bizonytalanság

**Probléma:**
- Különböző módszertanok eltérő eredményeket adhatnak
- Értékelési módszerek korlátai

**Megoldás:**
- Több módszer alkalmazása és összehasonlítása
- Konzervatív becslések preferálása
- Transzparens dokumentálás

## Következő lépések

Az árnyékárak alkalmazása után:
1. Externális hatások számszerűsítése → econ_007
2. Közgazdasági költségek és hasznok összesítése
3. Teljesítménymutatók számítása (ENPV, ERR, B/C) → econ_010

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- Az árnyékárak alkalmazása jelentősen befolyásolhatja a projekt értékelését
- Minden árnyékár forrását és számítási módját dokumentálni kell
- Érzékenységvizsgálat kötelező a kritikus árnyékárakra

⚠️ **Értelmezési kérdések:**
- A dokumentum nem ad konkrét konverziós tényező értékeket
- Nemzeti vagy ágazati útmutatókra való hivatkozás szükséges
- A munkaerő CF számítási módszertana részletesebb specifikációt igényelhet

⚠️ **Validációs igény:**
- Szakértői validáció szükséges az alkalmazott árnyékárakra
- Különösen környezeti és társadalmi externáliák esetén
- Regionális és ágazati specifikus értékek esetén

## Hivatkozások

- EU Regulation 2015/207 (CBA methodology)
- European Commission: Guide to Cost-Benefit Analysis
- EIB: Economic Appraisal of Investment Projects
- Fiskális kiigazítások → econ_005
- Externális hatások → econ_007
- Teljesítménymutatók → econ_010