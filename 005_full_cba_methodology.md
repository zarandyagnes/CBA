---
id: econ_005
title: Teljes közgazdasági elemzés (Full CBA Methodology)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 3.6 Teljes közgazdasági elemzés
source_page: 33-34
domain: economic_analysis
subdomain: full_cba
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - economic_analysis
  - cost_adjustments
  - fiscal_corrections
  - shadow_prices
related_ids:
  - econ_001
  - econ_002
  - econ_004
  - method_001
  - method_003
---

# Teljes közgazdasági elemzés (Full CBA Methodology)

## Áttekintés

A teljes közgazdasági elemzés a pénzügyi költségek és bevételek közgazdasági értékekké történő átalakítását jelenti három fő kiigazítási dimenzió mentén.

## Kiigazítási dimenziók

A pénzügyi költségeket ki kell igazítani a következő vonatkozásokban:

1. **Költségvetési (fiskális) kiigazítások**
   - ÁFA kezelése
   - Támogatások kezelése
   - Adók és transzferek eliminálása

2. **Piaci árról való áttérés elszámoló árra**
   - Árnyékárak (shadow prices) alkalmazása
   - Piaci torzulások korrekciója
   - Erőforrások valós társadalmi értékének meghatározása

3. **Externális hatások**
   - Környezeti externáliák
   - Társadalmi externáliák
   - Hasznok becslésénél kerülnek figyelembevételre

## 3.6.1 A projekt közgazdasági költségeinek becslése

### Kiigazítások sorrendje

1. **Költségek becslésénél:**
   - Költségvetési (fiskális) kiigazítások
   - Piaci árról való áttérés elszámoló árra

2. **Hasznok becslésénél:**
   - Externális hatások figyelembevétele

## 3.6.1.1 Költségvetési (fiskális) kiigazítások

### Alapelvek

**Közvetett adók:**
- A közgazdasági elemzés közvetett adókat nem tartalmazhat
- Közvetett adó: az adóalany különbözik az adóteher viselőjétől
- Példa: ÁFA, jövedéki adó

**Közvetlen adók:**
- Az adóalany megegyezik azzal a személlyel, akit gazdasági értelemben az adó terhel
- Példa: vagyonadó
- Ezek a közgazdasági elemzésben maradnak

### Szükséges input adatok

A költségvetési kiigazításokhoz szükséges adatok:

- **ÁFA:**
  - ÁFA kulcsok
  - Beruházási költségekben az ÁFA alapja és részaránya
  - Működési költségekben az ÁFA alapja és részaránya

- **Támogatások:**
  - Konkrét költségelemekhez kapcsolódó támogatások
  - Támogatások típusa és mértéke

### ÁFA kezelése

#### Alapelv

**Minden költségtételből az ÁFA tartalmat le kell vonni:**
- Független attól, hogy beruházási vagy működési költségről van-e szó
- Független attól, hogy az ÁFA visszaigényelhető-e vagy sem
- Az ÁFA visszaigényelhetősége csak a pénzügyi költségek meghatározásában játszik szerepet

#### Módszertani lépések

**1. ÁFA elkülönítése:**
```
Ha a pénzügyi költségbecslés tételesen elkülöníti az ÁFÁ-t:
→ Az elkülönítetten megjelenő ÁFA értékét le kell vonni a bruttó költségekből
```

**2. ÁFA becsülése (ha nem elkülönített):**
```
ÁFA kulcsonként:
1. Meg kell becsülni a költségtételek között az adó alapját
2. Ki kell számítani a hozzátartozó ÁFA összeget
3. Le kell vonni a bruttó költségből
```

#### ÁFA kezelése a bevételi oldalon

**Korrekció szükségessége:**
- Ha a társadalmi hasznok becslésének kiinduló pontja a pénzügyi bevétel
- És a fogyasztó nem ÁFA visszaigénylő

**Módszertani lépések:**

1. **Használói kör vizsgálata:**
   - Meg kell vizsgálni, hogy a használók körében vannak-e ÁFA visszaigénylésre jogosultak

2. **ÁFA tartalom becslése:**
   - Az ÁFA visszaigénylő körben a bevétel ÁFA tartalmát is meg kell becsülni

3. **Korrekció végrehajtása:**
   - A becsült ÁFA tartalmat le kell vonni a bruttó bevételből

### Támogatások kezelése

#### Konkrét költségelemekhez kapcsolódó támogatások

**Példák:**
- Ingyenes területhasználat
- Kedvezményes bérleti díj
- Közüzemi díj támogatás

**Kezelés:**
```
Pénzügyi költség + Támogatás értéke = Társadalmi költség
```

A pénzügyi költségeket ezekkel a támogatásokkal ki kell egészíteni, hogy társadalmi költségeket kapjunk.

#### Általános támogatások

**Típusok:**
- Árkiegészítés
- Normatív támogatás
- Általános működési támogatás

**Kezelés:**
- A támogatást nem kell a költségoldali korrekciónál figyelembe venni
- Ezek nem konkrét költségelemhez kapcsolódnak

## Gyakorlati alkalmazás

### Költségkiigazítási folyamat

```
1. Kiindulás: Pénzügyi költségek (bruttó)
   ↓
2. ÁFA levonása
   ↓
3. Támogatások hozzáadása (ha konkrét költségelemhez kapcsolódnak)
   ↓
4. Eredmény: Fiskálisan korrigált költségek
   ↓
5. Árnyékárak alkalmazása (lásd: econ_006)
   ↓
6. Eredmény: Közgazdasági költségek
```

### Példa: Beruházási költség kiigazítása

**Kiindulási adat:**
- Beruházási költség (bruttó): 120 M Ft
- ÁFA tartalom (27%): 25,5 M Ft
- Ingyenes területhasználat piaci értéke: 10 M Ft

**Kiigazítás:**
```
Pénzügyi költség (nettó) = 120 - 25,5 = 94,5 M Ft
Támogatás hozzáadása = 94,5 + 10 = 104,5 M Ft
Fiskálisan korrigált költség = 104,5 M Ft
```

## Kapcsolódó fogalmak

- **Közvetett adó:** Az adóalany különbözik az adóteher viselőjétől
- **Közvetlen adó:** Az adóalany megegyezik az adóteher viselőjével
- **Fiskális korrekció:** Adók és támogatások hatásának eliminálása
- **Társadalmi költség:** A társadalom számára valós erőforrás-felhasználás

## Következő lépések

A fiskális kiigazítások után következik:
1. Piaci árról való áttérés elszámoló árra (árnyékárak alkalmazása) → econ_006
2. Externális hatások figyelembevétele (hasznok becslésénél)

## Minőségi megjegyzések

⚠️ **Figyelem:**
- Az ÁFA kezelése minden esetben kötelező, függetlenül a visszaigényelhetőségtől
- A támogatások kezelése függ attól, hogy konkrét költségelemhez kapcsolódnak-e
- A fiskális kiigazítások a közgazdasági elemzés alapvető lépései

⚠️ **Értelmezési kérdés:**
- A dokumentum nem részletezi, hogy milyen esetekben kell közvetlen adókat is kiigazítani
- A vagyonadó példája alapján a közvetlen adók általában maradnak a költségekben

## Hivatkozások

- EU Regulation 2015/207 (CBA methodology)
- Pénzügyi elemzés módszertana → fin_001
- Árnyékárak alkalmazása → econ_006
- Differenciális módszer → method_001