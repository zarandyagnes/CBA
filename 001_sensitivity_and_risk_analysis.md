---
id: risk_001
title: Érzékenységvizsgálat és kockázatelemzés (Sensitivity and Risk Analysis)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 5. Érzékenységvizsgálat és kockázatelemzés
source_page: 69-76
domain: risk_analysis
subdomain: sensitivity_and_risk
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - sensitivity_analysis
  - risk_analysis
  - critical_variables
  - scenario_analysis
  - risk_matrix
related_ids:
  - econ_008
  - fin_005
  - method_004
---

# Érzékenységvizsgálat és kockázatelemzés

## Áttekintés

Az érzékenységvizsgálat és a kockázatelemzés célja annak vizsgálata, hogy a pénzügyi és közgazdasági elemzés során alkalmazott feltételezések és felhasznált input adatok változása milyen hatással van a pénzügyi és közgazdasági teljesítménymutatók alakulására.

## 5.1 Érzékenységvizsgálat

### Célja

Az érzékenységi vizsgálat célja a projekt kritikus változóinak és paramétereinek meghatározása, amelyek változása a legnagyobb hatást gyakorolja az alapesetben kiszámított teljesítménymutatókra.

### Alapelvek

**Változók egyenkénti változtatása:**
A változók egy időben változhatnak úgy, hogy más paraméterek nem módosulnak.

**Kritikus változó definíciója (EU CBA Útmutató):**
```
"Kritikus" minden olyan változó, amelynek 1%-os változása (pozitív vagy negatív 
értelemben) a teljesítménymutatók (elsősorban a nettó jelenérték) 1%-os vagy 
annál nagyobb mértékű változását okozza.
```

**Matematikai kifejezés:**
```
Rugalmasság = (ΔTeljesítménymutató / Teljesítménymutató) / (ΔVáltozó / Változó)

Ha Rugalmasság ≥ 1 → Kritikus változó
```

### Jelentős tényezők

#### Közvetlen hatótényezők

**Pénzügyi teljesítménymutatókra (FNPV, FRR):**
- Pénzügyi bevételek
- Pénzügyi beruházási költség
- Pénzügyi működési költség

**Közgazdasági teljesítménymutatókra (ENPV, ERR, BCR):**
- Közgazdasági beruházási és működési költségek korrekciós tényezői
- Hasznok

#### Közvetett hatótényezők

**Jellemzők:**
- Némelyik csak egy közvetlen tényezőre hat, a többitől függetlenül
- Másik része több közvetlen hatótényezőre van kihatással
- Összetett hatást fejtenek ki a teljesítménymutatókban

**Vizsgálati módszer:**

1. **Első lépés:** Közvetlen hatótényezők vizsgálata
2. **Szűrés:** Ha a közvetlen hatótényező nem éri el a kritikus változó szintet (1%-os változása nem hat 1%-nál nagyobb mértékben)
3. **Következtetés:** Azokat a közvetett tényezőket nem kell továbbvizsgálni, amelyek:
   - Egyedül erre a közvetlen tényezőre hatnak
   - Nincsenek összefüggésben más közvetett tényezőkkel

### A projekt kritikus változóinak azonosítása

**Módszer:**
Meg kell állapítani, hogy a vizsgált változók közül melyik rugalmassága nagyobb 1-nél.

**Képlet:**
```
Rugalmasság = (ΔNPV / NPV) / (ΔX / X)

ahol:
ΔNPV = NPV változása
NPV = Nettó jelenérték
ΔX = Változó változása
X = Változó értéke
```

**Következmény:**
A kritikus változókat a kockázatelemzés és a kockázati stratégia kialakítása során részletesebben vizsgálni kell.

### A küszöbértékek számítása

**Definíció:**
Küszöbértéknek nevezzük a kritikus változók olyan arányú változását, mely mellett a pénzügyi és közgazdasági teljesítménymutatók olyanná válnak, amelyek nem támogathatóvá teszik a projektet.

**Jelentőség:**
A küszöbérték számításnak elsősorban a közgazdasági teljesítménymutatók vizsgálatánál van jelentősége.

**Küszöbértékek:**

**Közgazdasági mutatók:**
```
ENPV = 0 → Projekt éppen támogatható
ERR = 3% → Projekt éppen támogatható
BCR = 1 → Projekt éppen támogatható
```

**Pénzügyi mutatók:**
```
FNPV(C) = 0 → Projekt éppen megtérül (kohéziós politika)
FRR(C) = pénzügyi diszkontráta → Projekt éppen megtérül
```

**Példa számítás:**

Kiindulási helyzet:
- ENPV = 200 M Ft
- Beruházási költség = 1,000 M Ft

Kérdés: Hány %-os beruházási költség növekedés mellett válik a projekt nem támogathatóvá?

Számítás:
```
ENPV = 0 esetén:
Beruházási költség növekedés = 200 M Ft
Százalékos növekedés = 200 / 1,000 = 20%

Küszöbérték: +20% beruházási költség növekedés
```

### Forgatókönyv-elemzés

**Definíció:**
A változók kritikus csoportjára vonatkozó forgatókönyv elemzés, amely az alapeset mellett az "optimista" és a "pesszimista" változatot vizsgálja.

**Jellemzők:**
- Rövidített, egyszerűsített eljárás
- Nem helyettesíti az érzékenységvizsgálatot és a kockázatelemzést
- Hasznos információkkal szolgál a projekt megítéléséhez

**Lépései:**

1. **A kritikus változók kiválasztása**
   - Érzékenységvizsgálat alapján
   - Rugalmasság ≥ 1

2. **Forgatókönyv értékek meghatározása**
   - Optimista forgatókönyv: kedvező értékek
   - Pesszimista forgatókönyv: kedvezőtlen értékek

3. **Teljesítménymutatók kiszámítása**
   - Optimista forgatókönyvre
   - Pesszimista forgatókönyvre

**Példa forgatókönyvek:**

| Változó | Pesszimista | Bázis | Optimista |
|---------|-------------|-------|-----------|
| Beruházási költség | +20% | 0% | -10% |
| Működési költség | +15% | 0% | -10% |
| Bevételek | -20% | 0% | +15% |
| Hasznok | -25% | 0% | +20% |

**Eredmények értékelése:**

```
Pesszimista: ENPV = -50 M Ft → Nem támogatható
Bázis: ENPV = 200 M Ft → Támogatható
Optimista: ENPV = 450 M Ft → Erősen támogatható

Következtetés: Projekt érzékeny a paraméterek változására, 
kockázatkezelési intézkedések szükségesek.
```

## 5.2 Kockázatelemzés

### Célja és jelentősége

**Szükségessége:**
A beruházási projektek esetén mindig fennálló bizonytalansági tényezők kezelése érdekében van szükség.

**Előnyei:**
- A fejlesztő jobban átláthatja, hogyan változhatnak a várható hatások
- Biztosítja az alapot a megfelelő kockázatkezelési stratégiához
- Fontos szerepet játszik a projekt tervezése során

**Speciális figyelem:**
Különös figyelmet kell fordítani az éghajlatváltozással és a környezettel kapcsolatos szempontokra. A klímakockázatokat az elemzésbe integrálni kell.

### Kvalitatív kockázatelemzés

#### Elemei

**1. Kockázati események azonosítása**

**Definíció:**
Kockázatnak tekinthető bármi olyan esemény, mely költségtúllépést vagy csúszást okoz a kivitelezésben.

**Példák:**
- Szükséges engedélyek kiadásának csúszása
- Rendkívüli időjárás
- Civilek tiltakozása
- Műszaki problémák
- Finanszírozási nehézségek
- Beszállítói problémák

**2. Kockázati mátrix összeállítása**

**Tartalom:**
- Kockázati esemény neve
- A kockázati esemény hatásának rövid leírása
- Bekövetkezés valószínűsége
- Hatás súlyossága
- Kockázat mértéke (valószínűség × hatás)
- Kapcsolat érzékenységi elemzéssel
- Megelőzési és mérséklési intézkedések
- Felelős szervezet
- Fennmaradó kockázatok értékelése

#### Bekövetkezési valószínűség kategóriái

| Kategória | Valószínűség | Leírás |
|-----------|--------------|--------|
| A - Elhanyagolható | 0-10% | Rendkívül ritka esemény |
| B - Kis valószínűségű | 10-33% | Ritkán előforduló esemény |
| C - Közepes | 33-66% | Időnként előforduló esemény |
| D - Nagyon valószínű | 66-90% | Gyakran előforduló esemény |
| E - Biztos esemény | 90-100% | Szinte biztosan bekövetkező esemény |

#### Hatás súlyossága kategóriái

| Kategória | Leírás |
|-----------|--------|
| I - Elhanyagolható hatású | Minimális hatás a projektre; könnyen kezelhető |
| II - Kis hatású | Kisebb zavarok; a projekt fő céljai nem veszélyeztetettek |
| III - Mérsékelt hatású | Jelentős zavarok; a projekt fő céljai részben veszélyeztetettek; korrekciós intézkedések szükségesek |
| IV - Kritikus hatású | Jelentős társadalmi-gazdasági károk; a projekt fő funkciójában okoz károkat; komoly javító intézkedések sem elegendőek |
| V - Katasztrofális hatású | A projekt kudarca; súlyos vagy teljes mértékben károsítja a projekt funkcióját; fő hatások közép- ill. hosszú távon nem jelentkeznek |

#### Kockázati szint értékelése

**Kockázati mátrix:**

| Valószínűség / Hatás | I Elhanyagolható | II Kis | III Mérsékelt | IV Kritikus | V Katasztrofális |
|---------------------|------------------|--------|---------------|-------------|------------------|
| A Elhanyagolható (0-10%) | alacsony | alacsony | alacsony | alacsony | mérsékelt |
| B Kis (10-33%) | alacsony | alacsony | mérsékelt | mérsékelt | magas |
| C Közepes (33-66%) | alacsony | mérsékelt | mérsékelt | magas | magas |
| D Nagyon valószínű (66-90%) | alacsony | mérsékelt | magas | nagyon magas | nagyon magas |
| E Biztos (90-100%) | mérsékelt | magas | nagyon magas | nagyon magas | nagyon magas |

**Kockázati szintek:**
- **Alacsony:** Elfogadható, különösebb intézkedés nem szükséges
- **Mérsékelt:** Figyelemmel kísérés, mérséklési intézkedések mérlegelése
- **Magas:** Mérséklési vagy megelőzési intézkedések szükségesek
- **Nagyon magas:** Megelőzési és mérséklési intézkedések együttes alkalmazása kötelező

#### Kockázatkezelési stratégiák

**Stratégia mátrix:**

| Valószínűség / Hatás | I Elhanyagolható | II Kis | III Mérsékelt | IV Kritikus | V Katasztrofális |
|---------------------|------------------|--------|---------------|-------------|------------------|
| A Elhanyagolható | nincs | mérséklés | mérséklés | mérséklés | megelőzés és mérséklés |
| B Kis | megelőzés | megelőzés vagy mérséklés | megelőzés vagy mérséklés | megelőzés és mérséklés | megelőzés és mérséklés |
| C Közepes | megelőzés | megelőzés vagy mérséklés | megelőzés vagy mérséklés | megelőzés és mérséklés | megelőzés és mérséklés |
| D Nagyon valószínű | megelőzés | megelőzés és mérséklés | megelőzés és mérséklés | megelőzés és mérséklés | megelőzés és mérséklés |
| E Biztos | megelőzés és mérséklés | megelőzés és mérséklés | megelőzés és mérséklés | megelőzés és mérséklés | megelőzés és mérséklés |

#### Elfogadható kockázat mértéke

**Alapelv:**
Meg kell határozni a még elfogadható kockázat mértékét (pl. legfeljebb mérsékelt kockázat elfogadható).

**Kötelezettség:**
Az ezt meghaladó kockázatokra mérséklési és/vagy megelőzési intézkedéseket kell kidolgozni.

**Fennmaradó kockázatok:**
A mérséklési és/vagy megelőzési intézkedések után fennmaradó kockázat elemzése is a kockázatelemzés részét képezi.

**Főszabály:**
Elfogadhatatlan mértékű kockázat nem maradhat a projektben.

#### Mennyiségi kockázatelemzés

**Mikor szükséges:**
Amennyiben jelentős kockázat marad a kvalitatív elemzés és intézkedések után, mennyiségi kockázatelemzést kell végrehajtani.

**Egyéb indokolt esetek:**
Az elemzés egyéb indokolt esetben is végrehajtható.

### Klímakockázatok

**Speciális követelmények:**

**Éghajlatváltozási rezilienciavizsgálat:**
- EU-s és hazai útmutató részletesen meghatározza a klíma kockázatelemzés módszertanát
- A projekt életciklusa során a klímaadaptáció érdekében végrehajtandó beruházási vagy működési típusú költségeit figyelembe kell venni

**Kezelési kötelezettség:**
- Minden lényeges klímakockázatot kezelni kell
- Elfogadható szintre csökkenteni
- A klímaadaptációs intézkedések költségeit (CAPEX és OPEX) be kell illeszteni a projekt költségei közé

## 5.3 Kockázatkezelési stratégia

### Általános elvek

**Komplexitás:**
A kockázatkezelés olyan összetett feladat, amely:
- Többféle kompetenciát igényel
- Jelentős forrásokat igényel
- Professzionális szakembernek kell ellátnia

**Felelősség:**
- Irányító Hatóság hatáskörében
- Kedvezményezett hatáskörében

**Minimális követelmény:**
A projekt kezdeményezőjének minimálisan meg kell állapítania azokat az intézkedéseket, amelyekkel a beazonosított kockázatok a nemzetközi legjobb gyakorlatnak megfelelően csökkenthetők.

### Kockázatok kezelésének főbb módszerei

**Együttesen is alkalmazhatók:**

#### Előkészítés alatti lehetséges kezelési stratégiák

**1. Tartalékképzés:**
- Határidőkre
- Költségekre

**2. Kockázatok áthárítása:**
- Különböző garanciális kötelezettségvállalásokkal
- Biztosítás útján
- Kezességvállalás útján

**3. Kockázat megosztása:**
- Az érdekeltek között
- A bizonytalanság befolyásolási képessége alapján

**4. Üzemeltetővel való folyamatos egyeztetés**

**5. Kivitelezés időzítése:**
- Időintervallumok kisforgalmú időszakra való tervezése (késő tavasz – kora ősz)

**6. Független közbeszerzési szakértők bevonása**

#### Megvalósítás alatti lehetséges kezelési stratégiák

**1. Projekttől vagy projektrészektől való elállás**

**2. Felelősség megosztáson alapuló szerződések kötése**

**3. Folyamatos költségkontroll**

### Kockázat időbeli változása

**Általános tapasztalat:**
A projekt legkockázatosabb szakasza az indulás időszaka.

**Indokok:**
- A beruházási költségek legnagyobb része ebben a szakaszban merül fel
- Üzemeltetési szempontból ekkor még nem kapunk semmiféle visszajelzést

**Működési fázis:**
Amikor a beruházás üzemi/működési fázisba lép, az érintett kockázat csökken, mivel a visszajelzés egyre nyilvánvalóbbá válik.

## Gyakorlati alkalmazás

### Érzékenységvizsgálat lépései

```
1. Jelentős tényezők azonosítása
   ↓
2. Közvetlen hatótényezők vizsgálata
   ↓
3. Kritikus változók meghatározása (rugalmasság ≥ 1)
   ↓
4. Küszöbértékek számítása
   ↓
5. Forgatókönyv-elemzés
   ↓
6. Eredmények értékelése
```

### Kockázatelemzés lépései

```
1. Kockázati események azonosítása
   ↓
2. Kockázati mátrix összeállítása
   ↓
3. Valószínűség és hatás értékelése
   ↓
4. Kockázati szint meghatározása
   ↓
5. Kezelési stratégia kiválasztása
   ↓
6. Intézkedések meghatározása
   ↓
7. Fennmaradó kockázatok értékelése
   ↓
8. Mennyiségi elemzés (ha szükséges)
```

## Kapcsolódó fogalmak

- **Kritikus változó:** 1%-os változása ≥1%-os hatást okoz a teljesítménymutatókban
- **Rugalmasság:** Teljesítménymutató változásának és változó változásának aránya
- **Küszöbérték:** Változó azon értéke, amelynél a projekt nem támogathatóvá válik
- **Kockázati mátrix:** Kockázatok strukturált bemutatása
- **Kockázati szint:** Valószínűség és hatás kombinációja
- **Megelőzés:** Kockázat bekövetkezésének megakadályozása
- **Mérséklés:** Kockázat hatásának csökkentése

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- Érzékenységvizsgálat és kockázatelemzés kötelező minden projektre
- Kritikus változók azonosítása alapvető fontosságú
- Klímakockázatok integrálása kötelező
- Elfogadhatatlan kockázat nem maradhat a projektben
- Kockázatkezelési intézkedések költségeit be kell építeni

⚠️ **Gyakori hibák:**
- Érzékenységvizsgálat és forgatókönyv-elemzés összekeverése
- Kockázati mátrix hiányos kitöltése
- Fennmaradó kockázatok értékelésének elmulasztása
- Klímakockázatok figyelmen kívül hagyása
- Kockázatkezelési költségek nem tervezése

⚠️ **Validációs igény:**
- Kritikus változók helyességének ellenőrzése
- Kockázati mátrix teljességének vizsgálata
- Kezelési stratégiák megfelelőségének értékelése
- Fennmaradó kockázatok elfogadhatóságának validálása

## Hivatkozások

- Közgazdasági teljesítménymutatók → econ_008
- Pénzügyi teljesítménymutatók → fin_005
- CBA paraméterek → method_004
- EU CBA útmutató
- Éghajlatváltozási rezilienciavizsgálat útmutató