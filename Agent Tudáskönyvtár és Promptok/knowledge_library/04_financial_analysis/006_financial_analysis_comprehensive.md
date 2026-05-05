---
id: fin_006
title: Pénzügyi elemzés átfogó útmutató (Comprehensive Financial Analysis Guide)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 4.7, 4.8, 4.10, 4.11, 4.12
source_page: 62-68
domain: financial_analysis
subdomain: comprehensive_guide
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - financial_analysis
  - residual_value
  - revenue
  - support_calculation
  - sustainability
  - excel_template
related_ids:
  - fin_001
  - fin_004
  - fin_005
---

# Pénzügyi elemzés átfogó útmutató

## 4.7 Maradványérték (Residual Value)

### Definíció és jelentőség

**Maradványérték:**
A költség-haszon elemzés által figyelembe vett időtáv után is értéket képviselő létesítmények, eszközök értéke a vizsgált időszak utolsó évében.

**Miért szükséges?**
A CBA időtávja nem feltétlenül esik egybe a beruházás során létrejött létesítmények, eszközök élettartamával.

### Számítási módszerek

#### Javasolt módszer (2021-2027): Értékcsökkenés alapú

**Számítás:**
```
Maradványérték = Könyv szerinti érték az időszak végén
```

**Lépések:**
1. Eszköz/létesítmény beszerzési értéke
2. Élettartam meghatározása
3. Éves értékcsökkenés számítása
4. Halmozott értékcsökkenés a referencia időszak végéig
5. Maradványérték = Beszerzési érték - Halmozott értékcsökkenés

**Példa:**
```
Épület beszerzési értéke: 1,000 M Ft
Élettartam: 50 év
Referencia időszak: 15 év
Éves értékcsökkenés: 1,000 / 50 = 20 M Ft/év
Halmozott értékcsökkenés (15 év): 15 × 20 = 300 M Ft
Maradványérték: 1,000 - 300 = 700 M Ft
```

#### Alternatív módszer: Nettó haszon alapú

**Alkalmazás:**
Indokolt esetben (pl. értékesítési szándék, piaci érték jelentősen eltér)

**Számítás:**
```
Maradványérték = Becsült piaci érték a referencia időszak végén
```

### Összefüggés karbantartással és pótlással

**Fontos:**
A maradványérték összefüggésben van a vizsgált élettartam alatti karbantartással, illetve pótlással.

**Logika:**
- Jó karbantartás → Magasabb maradványérték
- Elhanyagolt karbantartás → Alacsonyabb maradványérték
- Pótlások → Növelik a maradványértéket

### Maradványérték figyelembevétele

#### Pénzügyi fenntarthatóság számításánál

**Szabály:**
Csak akkor kell figyelembe venni, ha:
- Ténylegesen értékesítésre kerül az eszköz vagy épület
- Értéke pénzben is megjelenik

**Nem kell figyelembe venni:**
- Ha az eszköz/épület továbbra is használatban marad
- Ha nincs értékesítési szándék

#### FRR/C számításánál

**Szabály:**
Mindig figyelembe kell venni az FRR/C (a beruházási költség pénzügyi belső megtérülési rátája) érték kiszámításánál.

**Indok:**
A beruházás teljes megtérülésének vizsgálatakor a maradványérték része a megtérülésnek.

## 4.8 Pénzügyi bevételek becslése

### Alapelvek

#### Támogatások kizárása

**Szabály:**
A bevételek között nem szerepelhet semmilyen támogatás.

**Kizárt tételek:**
- Önkormányzat által továbbadott fogyasztói árkiegészítés
- Önkormányzat által fizetett egyéb veszteség kiegyenlítő támogatás
- Működési támogatások (költségmegtakarítást okozó projektek esetében sem)

**Logika:**
A működési támogatások változása nem tekintendő a megtakarításokkal szembe állítható bevételnek.

### Feltételezések bemutatása

**Követelmény:**
A bevételek számítása során alkalmazott feltételezéseket mindig az adott projekt szintjén kell vizsgálni és részletesen bemutatni.

**Dokumentálandó elemek:**
- Bevételi források azonosítása
- Mennyiségi feltételezések
- Árképzési feltételezések
- Növekedési ütemek
- Piaci trendek

### Releváns bevételi tételek

**Kötelező:**
Valamennyi releváns bevételi tételt fel kell tüntetni azok becslési módszerével együtt.

**Tipikus bevételi tételek:**
- Szolgáltatási díjak
- Bérleti díjak
- Belépőjegyek
- Értékesítési bevételek
- Koncessziós díjak
- Egyéb üzemeltetési bevételek

### Adatok rendelkezésre állása

#### Közvetlenül kapcsolható bevétel

**Ha rendelkezésre áll adat:**
- Figyelembe kell venni a projekt megvalósulása esetén
- Figyelembe kell venni a projekt nélküli esetben is

**Fajlagos bevételek változása:**
Ha a projekt megvalósulása esetében a fajlagos bevételek változása feltételezhető:
- Mindkét esetet részletesen be kell mutatni
- Indoklás szükséges

### Meglévő létesítmények bővítése

**Differenciális módszer:**
- Különbözeti módszerrel számolt eredmények bemutatása mellett
- Be kell mutatni mind a projekt, mint a projekt nélküli eset adatait is

**Kivétel:**
Bizonyos esetekben, amikor az input adatok (naturáliák) csak különbözetként becsülhetők:
- Ennek feltüntetése mellett
- Elegendő a különbözeti adatok bemutatása

### Ingatlanok értékesítése/bérbeadása

#### Alapelv

**Figyelembe vétel:**
A fejlesztés helyszínén, a projekttel kapcsolatba hozható ingatlanok eladásából vagy bérbeadásából származó bevételek esetében figyelembe kell venni a projekt hatására bekövetkező változásokat.

#### Kötelező fenntartási időszakon túli bevétel

**Szabály:**
Az értékesítést vagy egyéb bevétel változást a kötelező fenntartási időszakon túli felmerülés esetében is figyelembe kell venni a támogatás számítása során.

#### Vizsgálandó szempontok

**1. Projekt nélküli eset:**
- Figyelembe került-e az ingatlan esetleges hasznosítása során keletkezett bevétel?

**2. Realizálhatóság:**
- A feltételezett bevétel ténylegesen realizálható?
- Vagy adminisztratív módon korlátozott?

**Példák:**
- Zöldmezős beruházás: nincs projekt nélküli bevétel
- Meglévő ingatlan felújítása: lehet projekt nélküli bevétel is (pl. jelenlegi bérleti díj)

## 4.10 A támogatási összeg meghatározása

### Meghatározási módok (2021-2027)

**Nem állami támogatás alá tartozó projektek esetén:**

1. **Pénzügyi elemzésből levezetve**
   - Finanszírozási hiány ráta számítás
   - FNPV alapú számítás

2. **Pályázati Felhívásban meghatározott támogatási arány alapján**
   - Maximális támogatási arány
   - Előre meghatározott százalék

3. **Állami támogatási szabályok szerint**
   - Jogszabályi előírásoknak megfelelően
   - Specifikus számítási módszerek

### Bevétel/költségmegtakarítás nélküli projektek

**Feltétel:**
Amennyiben a projekthez sem bevétel, sem költségmegtakarítás nem kapcsolódik.

**Követelmények:**
- Nem kell a nettó bevételre vonatkozó számításokat végezni
- Alátámasztani kell, hogy miért nem keletkezik bevétel vagy költségmegtakarítás
- PF-ben lévő maximális támogatási arány figyelembe vehető
- Pénzügyi fenntarthatóság bemutatása ebben az esetben is szükséges

### Pályázati Felhívás által meghatározott arány

**Alapja:**
Korábbi hasonló projektek tapasztalati adataiból kiindulva.

**Alkalmazás:**
Ha meghatározásra került, a projekteknek alkalmazni kell a támogatási arány kiszámításakor, amennyiben igazolják, hogy a meghatározott feltételeknek megfelelnek.

### Állami támogatások

#### Működési eredményt figyelembe vevő

**Példák:**
- Kultúrát és kulturális örökség megőrzését előmozdító támogatás
- Helyi infrastruktúra fejlesztés
- Sportlétesítményhez és multifunkcionális szabadidős létesítményhez nyújtott támogatás
- Személyszállítási közszolgáltatásért járó ellentételezés

**Számítás:**
```
Támogatási összeg = f(Működési eredmény)
```

#### Működési eredményt figyelembe nem vevő

**Egyszerűbb esetek:**
- Regionális beruházási támogatás
- Képzési támogatás
- Támogatási arány az elszámolható beruházási költség arányában

**Bonyolultabb esetek:**
- Egyes környezetvédelmi beruházások
- Megújuló energia termelési támogatás
- Energiahatékonysági beruházások támogatása
- Támogatási arány külön definiált elszámolható költségre vonatkozik
- Nem a beruházási költség, hanem pl. jogszabályi követelményekhez képest elért eredményekhez kapcsolódó többletköltség

### Komplex projektek

**Definíció:**
Olyan projektek, ahol a megvalósítást jelentő tevékenységek egyes csoportjai a támogatási szabályok szempontjából eltérő megítélés alá esnek.

**Kezelés:**
- Elkülönült projektelemnek kell tekinteni
- Pénzügyi elemzést projektelemenként kell elvégezni

### Elszámolhatóság

**Alapelv:**
Támogatás csak az elszámolható költségekre adható.

**Nem elszámolható költségek:**
A kedvezményezett hozzájárulásával valósulnak meg.

**ÁFA:**
Csak akkor lehet figyelembe venni a költségek között, ha az elszámolhatósági szabályok alapján elszámolható.

### Excel sablon

**Tartalom:**
Az Excel sablon tartalmazza az egyes esetekben a támogatási összeg számításának módszerét.

## 4.11 Pénzügyi fenntarthatóság vizsgálata

### Célja

**Definíció:**
A projekt hosszú távú pénzügyi egyensúlyának bemutatása.

**Jelentőség:**
Az elemzés során kapott eredmények a kedvezményezett szempontjából kötelezettséget jelentenek.

### Fő szempontok

#### 1. Halmozott nettó pénzáram

**Alapkövetelmény:**
```
A (diszkontálatlan) halmozott nettó pénzáram a teljes vizsgált referencia-időszak során egyik évben sem negatív.
```

**Vizsgálat:**
Minden év végén:
```
Halmozott CF(t) = Σ Nettó CF(i) ≥ 0
                  i=0 to t
```

#### 2. Vizsgált nettó pénzáramok tartalma

**Tartalmazzák:**
- Beruházási költségeket
- Valamennyi (nemzeti és uniós) pénzügyi erőforrást
- Bevételeket
- Üzemeltetési költségeket
- Pótlási költségeket
- Azok kifizetésének időpontjában
- Szervezet pénzügyi kötelezettségeinek törlesztését
- Tőkehozzájárulásokat
- Kamatokat
- Közvetlen adókat

**Nem tartalmazzák:**
- ÁFÁ-t (kivéve, ha nem visszaigényelhető)
- Maradványértéket (kivéve, ha az eszköz az elemzés utolsó vizsgált éve során ténylegesen értékesítésre kerül)

#### 3. Nettó bevételt nem termelő műveletek

**Követelmény:**
Be kell mutatni, hogyan tervezik fedezni a költségeket.

**Kötelezettségvállalás:**
A kedvezményezettnek/üzemeltetőnek egyértelmű kötelezettséget kell vállalnia arra vonatkozóan, hogy más forrásokból megfelelő finanszírozást biztosít a projekt fenntarthatóságának megőrzése érdekében.

#### 4. Jövőbeni negatív pénzáramok

**Ha várhatók:**
Be kell mutatni a fedezeti forrásokat.

**Egyéb bejövő pénzáramok:**
A pénzügyi bevételnek nem számító, a működési költségek finanszírozását szolgáló források az egyéb bejövő pénzáramok között jeleníthetők meg.

### Beruházás finanszírozásának hatása

#### Hiteltörlesztés nélkül

**Ha biztosított:**
- Adott díjstruktúra mellett
- Projekt halmozott pénzárama minden évben pozitív

#### Hiteltörlesztéssel

**Vizsgálandó:**
- Kamatfizetés és hiteltörlesztés hatása
- Esetleg egyes években negatív halmozott pénzáram
- Kezelési lehetőségek:
  - Rövid lejáratú hitellel
  - Elvárt megtérülés növelése
  - Díjak emelése

### Fenntarthatóság biztosítása

**Feltétel:**
```
Halmozott nettó pénzügyi pénzáram egyik évben sem negatív
```

**Ha nem biztosítható:**
A kedvezményezettnek a CBA sablonban a forrás megadásával le kell nyilatkoznia, hogy a fenntarthatósághoz szükséges többletforrást biztosítja.

**Nyilatkozat tartalma:**
- Többletforrás mértéke évenkénti bontásban
- Forrás megnevezése
- Biztosítás módja

## 4.12 Pénzügyi elemzés az Excel sablon segítségével

### Általános elvek

**Támogatási jogcímenként külön:**
A pénzügyi elemzést minden támogatási jogcím esetében külön-külön kell elvégezni.

**Több jogcím esetén:**
Minden egyes jogcímre külön kell elvégezni a szükséges számításokat.

**Összesítés:**
A támogatási jogcímenként külön-külön elvégzett pénzügyi számításokat a "Pénzügyi elemzés" nevű munkalapon kell összesíteni.

### Nem állami támogatás

#### PF szerinti maximális támogatási arány

**Munkalapok:**
- Működési_input: nem állami támogatásra megadott adatok
- Pénzügyi elemzés: összesítés

**Tartalom:**
- Működési költségek meghatározása
- Bevételek meghatározása
- Pénzáramok nagyvonalú becslése
- Pénzügyi fenntarthatóság bemutatása

#### Finanszírozási hiány ráta számítás

**Munkalapok:**
- Működési_input: részletes adatok
- Pénzügyi elemzés: teljes elemzés és számítások

**Tartalom:**
- Teljes pénzügyi elemzés
- Működési költségek és bevételek meghatározása
- Projekt pénzáramainak meghatározása
- Pénzügyi teljesítménymutatók számítása
- Részletes pénzügyi fenntarthatóság alátámasztása
- Támogatási összeg és arány meghatározása

### Állami támogatás

#### Beruházási költségek

**Munkalap:** Beruházási_input

**Megadás:**
Támogatási jogcímek alapján.

**Több jogcím esetén:**
Költségek megbontása szükséges.

#### Működési költségek

**Munkalap:** Működési_input

**Csak állami támogatásra:**
Azonban több állami támogatási jogcím esetén költségeket meg kell osztani.

**Megosztás módja:**
- Pl. beruházási költségarányok alapján
- Bemutatás a "Háttérszámítások" lapon
- Rövid indoklás szükséges

#### PF/támogatási szabály szerinti maximális arány

**Munkalapok:**
- Működési_input: állami támogatásra
- Pénzügyi elemzés: összesítés

**Tartalom:**
- Működési költségek és bevételek alapján
- Pénzáramok nagyvonalú bemutatása
- Pénzügyi fenntarthatóság számítása
- Támogatási összeg meghatározása

**Speciális:**
- Vizsgálatot minden érintett támogatási jogcímre külön-külön
- Költségeket az érintett állami támogatási jogcímekre külön-külön megbontani

#### Nettó működési bevétel levonásával

**Munkalapok:**
- Működési_input: részletes adatok
- Pénzügyi elemzés: teljes elemzés

**Tartalom:**
- Teljes pénzügyi elemzés
- Működési költségek és bevételek meghatározása
- Projekt pénzáramainak meghatározása
- Pénzügyi teljesítménymutatók számítása
- Részletes pénzügyi fenntarthatóság alátámasztása
- Támogatási összeg és arány meghatározása

**Számítás:**
```
Támogatási összeg = 
  Diszkontált beruházási költség - Diszkontált működési eredmény
```

**Speciális:**
- Vizsgálatot minden érintett támogatási jogcímre külön-külön
- Költségeket az érintett állami támogatási jogcímekre külön-külön megbontani

### Vegyes állami és nem állami támogatás

**Követelmény:**
Támogatási arányt külön az állami és a nem állami forrásból származó támogatásokra kell megadni.

**Több jogcím esetén:**
```
Összesített támogatási arány = 
  Σ(Támogatási összegek) / Σ(Elszámolható költségek)
```

**Bemutatás:**
- Külön az állami támogatásra
- Külön a nem állami támogatásra
- Összesítve (ha több jogcím)

### Beruházás finanszírozása

**Források típusai:**

1. **Európai alap hozzájárulása:**
   - Támogatási arány alapján
   - Elszámolható költségekre

2. **Nemzeti hozzájárulás:**
   - Hazai központi költségvetési támogatás (ha stratégiai döntés)
   - Saját forrás:
     - Önerő
     - Idegen forrás:
       - Hitel
       - Egyéb (pl. osztalék, előleg)

## Kapcsolódó fogalmak

- **Maradványérték:** Eszközök értéke a referencia időszak végén
- **Nettó bevétel:** Bevételek - működési költségek
- **Működési eredmény:** Állami támogatási szabályok szerinti eredmény
- **Finanszírozási hiány ráta:** Támogatási arány számítási módszer
- **Halmozott pénzáram:** Kumulált cash flow
- **Pénzügyi fenntarthatóság:** Hosszú távú pénzügyi egyensúly

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- Maradványérték számítása befolyásolja a megtérülést
- Bevételek becslése megalapozott legyen
- Támogatások nem szerepelhetnek bevételként
- Pénzügyi fenntarthatóság biztosítása kötelező
- Excel sablon helyes kitöltése elengedhetetlen

⚠️ **Gyakori hibák:**
- Maradványérték helytelen számítása
- Támogatások bevételként való kezelése
- Ingatlanértékesítés bevételének figyelmen kívül hagyása
- Pénzügyi fenntarthatóság hiányának nem kezelése
- Projektelemek elkülönítésének elmulasztása

⚠️ **Validációs igény:**
- Maradványérték számítás helyességének ellenőrzése
- Bevételi feltételezések realitásának vizsgálata
- Pénzügyi fenntarthatóság biztosításának validálása
- Excel sablon konzisztenciájának ellenőrzése

## Hivatkozások

- Pénzügyi elemzés célja → fin_001
- Projekttípusok → fin_004
- Pénzügyi teljesítménymutatók → fin_005
- Amortizáció kezelése → method_007
- Közgazdasági elemzés → econ_001-009