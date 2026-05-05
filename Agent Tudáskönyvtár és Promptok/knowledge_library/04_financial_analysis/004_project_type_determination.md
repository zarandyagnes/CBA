---
id: fin_004
title: Projekttípus megállapítása pénzügyi elemzés szempontjából (Project Type Determination for Financial Analysis)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 4.3 A pénzügyi elemzés a különböző projekttípusok esetén
source_page: 57-62
domain: financial_analysis
subdomain: project_classification
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - financial_analysis
  - project_types
  - state_aid
  - support_calculation
related_ids:
  - fin_002
  - fin_003
  - fin_006
---

# Projekttípus megállapítása pénzügyi elemzés szempontjából

## Áttekintés

A pénzügyi elemzés elvégzését alapvetően meghatározza, hogy a támogatási összeg milyen módon kerül meghatározásra, illetve hogy a projekt várhatóan nettó bevételtermelő lesz-e. Ennek megfelelően többféle projekttípust különböztetünk meg.

## Alapelvek

### Meghatározó tényezők

**1. Támogatási összeg meghatározásának módja:**
- Pályázati Felhívás (PF) szerinti maximális arány
- Finanszírozási hiány ráta számítás
- Állami támogatási szabályok szerint
- Nettó működési bevétel levonásával

**2. Nettó bevételtermelés:**
- Bevételtermelő projekt
- Nem bevételtermelő projekt
- Költségmegtakarítást eredményező projekt

**3. Állami támogatás:**
- Állami támogatás alá eső
- Nem állami támogatás alá eső
- Vegyes (állami és nem állami)

### Komplex projektek

**Definíció:**
Olyan projektek, ahol a megvalósítást jelentő tevékenységek egyes csoportjai a támogatási szabályok szempontjából eltérő megítélés alá esnek.

**Kezelés:**
- Elkülönült projektelemként kell kezelni
- Pénzügyi elemzést projektelemenként kell elvégezni
- Minden projektelemre külön támogatási számítás

## Döntési folyamat

### 1. lépés: Állami támogatás megállapítása

**Kérdés:** A projekt az állami támogatási szabályok alá esik-e?

**Eszköz:** Excel sablon Főoldalán rövid kérdőív (igen/nem válaszok)

**Segítség:** Magyarázat oszlop szabályozás bemutatásával és példákkal

**Speciális eset:**
Lehetnek olyan projektek, amelyek:
- Állami támogatási szabályok alá esnek, DE
- Folytatnak közcélú tevékenységet, amely már nem sorolható állami támogatás alá
- Példák: közszolgáltatások ellentételezése, állam által támogatott gyógyászati/oktatási feladatok

### 2. lépés: Támogatási jogcím megjelölése

**Helye:** Excel sablon Főoldala

**Opciók (legördülő listából):**
- Nem állami támogatás
- Állami támogatás esetén: felhívásban megjelenő támogatási jogcímek

**Több jogcím:** Egy projektben több állami támogatási jogcím is megjelölhető

### 3. lépés: Elemzés fő paramétereinek megadása

**Helye:** Excel sablon Főoldala

**Paraméterek:**
- Referencia időszak
- Pénzügyi diszkontráta
- Közgazdasági diszkontráta
- Egyéb projekt-specifikus paraméterek

### 4. lépés: Nettó működési bevétel megállapítása

**Eszköz:** Működési_input oldal kitöltése

**Kitöltési logika:**

**Állami támogatás alá eső projektek:**
- "Állami támogatás" sorok kitöltése

**Nem állami támogatás alá eső projektek:**
- "Nem állami támogatás" sorok kitöltése

**Vegyes projektek:**
- Beruházási költségek megbontása
- Működési költségek megbontása
- Bevételek megbontása
- Mindkét sor kitöltése

### 5. lépés: Nyilatkozat közcélú tevékenységekről

**Feltétel:** Nettó bevétel esetén

**Tartalom:**
"A projekttel érintett tevékenységre vonatkozó működési támogatása a nettó bevétel mértékével csökkenni fog."

**Következmény:**
Ha alátámasztható módon lenyilatkozható → 100%-os támogatási arány megítélhető

## Projekttípusok és követelmények

### A. Nem állami támogatás

#### A1. PF szerinti maximális támogatási arány

**Feltételek:**
- Nem minősül állami támogatásnak
- PF meghatároz maximális támogatási arányt
- Nem keletkezik bevétel vagy költségmegtakarítás

**Pénzügyi elemzés követelményei:**
- Működési költségek meghatározása
- Bevételek meghatározása (ha vannak)
- Pénzáramok nagyvonalú becslése
- Pénzügyi fenntarthatóság bemutatása

**Támogatási arány:**
```
Támogatási arány = PF szerinti maximális arány
```

**Alátámasztás szükséges:**
Miért nem keletkezik bevétel vagy költségmegtakarítás

#### A2. Finanszírozási hiány ráta számítás

**Feltételek:**
- Nem minősül állami támogatásnak
- Finanszírozási hiány ráta számítása szükséges
- Bevétel vagy költségmegtakarítás keletkezik

**Pénzügyi elemzés követelményei:**
- Teljes pénzügyi elemzés
- Működési költségek és bevételek meghatározása
- Projekt pénzáramainak meghatározása
- Pénzügyi teljesítménymutatók számítása (FNPV, FRR)
- Részletes pénzügyi fenntarthatóság alátámasztása

**Támogatási arány számítása:**
```
Finanszírozási hiány ráta = 
  (Diszkontált beruházási költség - Diszkontált nettó bevétel) / 
  Diszkontált beruházási költség
```

**Excel sablon:** Számítási módszer bemutatva

**Működési többletforrás:**
Ha szükséges → biztosításáról és forrásáról nyilatkozni kell

### B. Állami támogatás

#### B1. PF/támogatási szabály szerinti maximális arány

**Feltételek:**
- Állami támogatásnak minősül
- PF vagy támogatási szabály meghatároz maximális arányt
- Nem keletkezik jelentős nettó bevétel

**Pénzügyi elemzés követelményei:**
- Működési költségek és bevételek alapján
- Pénzáramok nagyvonalú bemutatása
- Pénzügyi fenntarthatóság számítása
- Támogatási összeg meghatározása

**Speciális követelmény:**
- Vizsgálatot minden érintett támogatási jogcímre külön-külön kell elvégezni
- Költségeket az érintett állami támogatási jogcímekre külön-külön kell megbontani

**Támogatási arány:**
```
Támogatási arány = PF/szabály szerinti maximális arány
```

#### B2. Nettó működési bevétel levonásával

**Feltételek:**
- Állami támogatásnak minősül
- Nettó működési bevétel levonásával kell vizsgálni
- Releváns szabály szerint

**Pénzügyi elemzés követelményei:**
- Teljes pénzügyi elemzés
- Működési költségek és bevételek meghatározása
- Projekt pénzáramainak meghatározása
- Pénzügyi teljesítménymutatók számítása
- Részletes pénzügyi fenntarthatóság alátámasztása

**Speciális követelmény:**
- Vizsgálatot minden érintett támogatási jogcímre külön-külön kell elvégezni
- Költségeket az érintett állami támogatási jogcímekre külön-külön kell megbontani

**Támogatási összeg számítása:**
```
Támogatási összeg = 
  Diszkontált beruházási költség - Diszkontált működési eredmény
```

**Excel sablon:** Számítási módszer megadva

**Működési többletforrás:**
Ha szükséges → biztosításáról és forrásáról nyilatkozni kell

### C. Vegyes állami és nem állami támogatás

**Feltételek:**
- Állami és nem állami támogatás is érintett a projektben

**Pénzügyi elemzés követelményei:**
- Külön számítás állami forrásból származó támogatásra
- Külön számítás nem állami forrásból származó támogatásra
- Költségek megbontása támogatási típusok szerint

**Támogatási arány megadása:**

**Több állami vagy nem állami jogcím esetén:**
```
Összesített támogatási arány = 
  Σ(Támogatási összegek) / Σ(Elszámolható költségek)
```

**Bemutatás:**
- Külön az állami támogatásra
- Külön a nem állami támogatásra
- Összesítve (ha több jogcím)

## Elszámolhatóság

### Elszámolható költségek

**Alapelv:**
Támogatás csak az elszámolható költségekre adható

**Nem elszámolható költségek:**
- Kedvezményezett hozzájárulásával valósulnak meg

### ÁFA kezelése

**Szabály:**
Az ÁFÁ-t csak akkor lehet figyelembe venni a költségek között, ha az elszámolhatósági szabályok alapján elszámolható

**Tipikus esetek:**
- ÁFA visszaigénylő: ÁFA nem elszámolható
- ÁFA nem visszaigénylő: ÁFA elszámolható

## Excel sablon használata

### Főoldal

**Kitöltendő elemek:**
1. Állami támogatás kérdőív (igen/nem)
2. Támogatási jogcím kiválasztása (legördülő lista)
3. Elemzés fő paraméterei
4. Projekt alapadatok

### Működési_input oldal

**Kitöltési logika:**
- Állami támogatás sorok: állami támogatás alá eső tevékenységek
- Nem állami támogatás sorok: nem állami támogatás alá eső tevékenységek
- Vegyes projektek: mindkét sor kitöltése

### Beruházási_input oldal

**Állami támogatás esetén:**
- Költségek megadása támogatási jogcímek alapján
- Több jogcím esetén költségek megbontása

### Pénzügyi elemzés oldal

**Összesítés:**
- Támogatási jogcímenként külön számítások
- Projekt egészére vonatkozó összesítés
- Átlátható bemutatás

## Gyakorlati példák

### Példa 1: Nem bevételtermelő közösségi projekt

**Jellemzők:**
- Közösségi ház felújítása
- Nem keletkezik bevétel
- Nem állami támogatás

**Projekttípus:** A1 - PF szerinti maximális támogatási arány

**Elemzés:**
- Egyszerűsített pénzügyi elemzés
- Fenntarthatóság bemutatása
- PF szerinti max. arány alkalmazása

### Példa 2: Bevételtermelő turisztikai projekt

**Jellemzők:**
- Szálláshely fejlesztés
- Bevétel keletkezik
- Nem állami támogatás

**Projekttípus:** A2 - Finanszírozási hiány ráta számítás

**Elemzés:**
- Teljes pénzügyi elemzés
- FNPV, FRR számítása
- Finanszírozási hiány ráta alapján támogatás

### Példa 3: Regionális beruházási támogatás

**Jellemzők:**
- Ipari létesítmény
- Állami támogatás (regionális)
- Bevétel keletkezik

**Projekttípus:** B2 - Nettó működési bevétel levonásával

**Elemzés:**
- Teljes pénzügyi elemzés
- Működési eredmény számítása
- Támogatás = Beruházási költség - Működési eredmény NPV

### Példa 4: Komplex vegyes projekt

**Jellemzők:**
- Kulturális központ + kereskedelmi egységek
- Kulturális rész: állami támogatás
- Kereskedelmi rész: nem állami támogatás

**Projekttípus:** C - Vegyes

**Elemzés:**
- Költségek megbontása
- Külön számítás mindkét részre
- Összesített támogatási arány

## Kapcsolódó fogalmak

- **Finanszírozási hiány ráta:** Támogatási arány számítási módszer
- **Nettó működési bevétel:** Bevételek - működési költségek
- **Működési eredmény:** Állami támogatási szabályok szerinti eredmény
- **Elszámolható költség:** Támogatásból fedezhető költség
- **Projektelemek:** Elkülönült kezelést igénylő tevékenységcsoportok

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- A projekttípus helyes meghatározása alapvető fontosságú
- Komplex projekteknél projektelemenként külön elemzés szükséges
- Vegyes projekteknél költségek pontos megbontása elengedhetetlen
- Excel sablon logikája követi a döntési folyamatot

⚠️ **Gyakori hibák:**
- Állami támogatás alá esés téves megítélése
- Költségek helytelen megbontása vegyes projekteknél
- Projektelemek elkülönítésének elmulasztása
- Támogatási jogcímek helytelen kiválasztása

⚠️ **Validációs igény:**
- Állami támogatás alá esés jogi validálása
- Költségmegbontás helyességének ellenőrzése
- Támogatási számítások konzisztenciája
- Excel sablon helyes kitöltése

## Hivatkozások

- Projekttípusok és támogatás → fin_002
- Mérföldkövek → fin_003
- Támogatási összeg meghatározása → fin_006
- Pénzügyi fenntarthatóság → fin_007
- Állami támogatási szabályok (külső jogszabályok)