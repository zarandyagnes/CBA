---
id: fin_001
title: Pénzügyi elemzés célja és módszertana / Financial Analysis Purpose and Methodology
source_document: TOP PLUSZ KPÚ.pdf
source_section: 4.1 A pénzügyi elemzés célja, 4.4 A pénzügyi elemzés módszertana
source_page: 56, 60
domain: financial_analysis
subdomain: methodology
language: hu
status: validated
confidence: high
tags:
  - TOP_PLUSZ
  - financial_analysis
  - FNPV
  - FRR
  - financial_sustainability
  - optimal_support
related_ids:
  - meth_004
  - meth_006
  - meth_007
  - fin_002
  - fin_003
---

# Pénzügyi elemzés célja és módszertana / Financial Analysis Purpose and Methodology

## Forrás / Source

**Dokumentum:** TOP PLUSZ Közgazdasági és Pénzügyi Útmutató  
**Fejezet:** 4.1, 4.4  
**Oldal:** 56, 60

## Áttekintés / Overview

A pénzügyi elemzés két fő célt szolgál: (1) az optimális támogatási mérték megállapítása, és (2) a projekt pénzügyi fenntarthatóságának igazolása.

---

## A pénzügyi elemzés célja / Purpose of Financial Analysis

### Két fő cél / Two Main Objectives

**1. Optimális támogatási mérték megállapítása:**
> "A pénzügyi elemzés alapján kell megállapítani, hogy mi az optimális támogatási mérték"

**2. Pénzügyi fenntarthatóság:**
> "illetve, hogy a projekt pénzügyileg fenntartható-e"

### Részletes célok / Detailed Objectives

**Pénzügyi teljesítménymutatók számítása:**
> "A pénzügyi elemzés célja, hogy a kiválasztott változatra vonatkozóan a projekt pénzáramainak becslésével kiszámításra kerüljenek a projekt pénzügyi teljesítménymutatói (FNPV: pénzügyi nettó jelenérték, FRR: pénzügyi belső megtérülési ráta) támogatással és támogatás nélkül."

**Pénzügyi fenntarthatóság bemutatása:**
> "A pénzügyi elemzésben kerül bemutatásra továbbá a projekt pénzügyi fenntarthatósága, ami annak vizsgálatát jelenti, hogy az elemzési időszakban elegendő pénzügyi forrás áll-e rendelkezésre, hogy a fejlesztés által elért szolgáltatási színvonalat fenn lehessen tartani."

---

## A pénzügyi elemzés tartalma / Content of Financial Analysis

### Gyakorlati megvalósítás / Practical Implementation

> "A pénzügyi elemzés gyakorlatilag a beruházás pénzáramait bemutató táblázatok összeállításából áll"

**Tartalmaznia kell:**
- Beruházási költségeket
- Működési költségeket (üzemeltetés, fenntartás, pótlás)
- Bevételeket
- Finanszírozás forrásait
- Halmozott nettó pénzáramot

### Különbözeti módszer alkalmazása / Application of Differential Method

> "A pénzáramokat be kell mutatni mind a projekt nélküli esetben, mind a projekt megvalósulása esetén külön-külön, illetve a különbözetet is."

**Három pénzáram bemutatása szükséges:**
1. Projekt nélküli eset pénzárama
2. Projekt megvalósulása esetén pénzáram
3. Különbözet (projekt hatása)

---

## Fő fogalmak / Key Concepts

### 1. Pénzügyi nettó jelenérték / Financial Net Present Value (FNPV)

**Definíció:**
> "Pénzügyi nettó jelenérték (Financial Net Present Value: FNPV) a várható beruházási és működési költségek, valamint bevételek diszkontált értékeinek különbözete."

**Értelmezés:**
> "A projekt pénzügyi megtérülésének mutatószáma: az adott országra jellemző pénzügyi diszkontrátát használva, ha értéke pozitív, a projekt pénzügyileg megtérülő, ha negatív, nem megtérülő."

**Képlet:**
```
FNPV = Σ(t=0 to n) [X(t) / (1+i)^t]
```

Ahol:
- X(t) = adott évre vonatkozó pénzáramlás
- i = pénzügyi diszkontráta
- t = aktuális év

**Értékelés:**
- FNPV > 0 → Projekt pénzügyileg megtérülő
- FNPV < 0 → Projekt pénzügyileg nem megtérülő
- FNPV = 0 → Projekt éppen megtérül

### 2. Pénzügyi megtérülési ráta / Financial Rate of Return (FRR)

**Definíció:**
> "Pénzügyi megtérülési ráta (Financial Rate of Return: FRR): azt a diszkontrátát fejezi ki, amelynél az FNPV=0, azaz, amikor a projekt pénzügyileg megtérülővé válik."

**Számítás:**
```
Ha FNPV = Σ(t=0 to n) [X(t) / (1+i)^t] = 0, akkor i = FRR
```

**Értelmezés:**
- FRR > pénzügyi diszkontráta → Projekt megtérülő
- FRR < pénzügyi diszkontráta → Projekt nem megtérülő
- FRR = pénzügyi diszkontráta → Projekt éppen megtérül

### 3. Pénzügyi fenntarthatóság / Financial Sustainability

**Definíció:**
> "Pénzügyi fenntarthatóság: a vizsgálat célja a projekt hosszú távú pénzügyi egyensúlyának bemutatása."

**Cél:**
Annak igazolása, hogy a projekt működtetéséhez szükséges pénzügyi források rendelkezésre állnak az elemzési időszak teljes időtartama alatt.

---

## ÁFA kezelése / VAT Treatment

### Alapelv / Basic Principle

> "A pénzügyi elemzésben attól függően kell szerepeltetni az áfát, hogy a vizsgált szereplő (a beruházó, a működtető-fenntartó, illetve ezen feladatok finanszírozásért felelős szereplő) jogosult-e az áfa visszaigénylésére, illetve, hogy elszámolhatja-e az áfát."

### Szabályozás / Regulation

**Hivatkozások:**
- Pályázati Felhívás
- Kapcsolódó útmutató
- Elszámolási útmutató

**Forrás:**
https://www.palyazat.gov.hu/ltalnos-tmutat-a-felhvsokhoz-szerzds-mintk-szf-avdh-tjkoztat-2021-2021

### Döntési logika / Decision Logic

```
Vizsgált szereplő jogosult ÁFA visszaigénylésre?
    ├─ IGEN → ÁFA NEM szerepel a pénzügyi elemzésben
    └─ NEM → ÁFA SZEREPEL a pénzügyi elemzésben
         ↓
         Elszámolható az ÁFA?
         ├─ IGEN → ÁFA szerepel az elszámolható költségekben
         └─ NEM → ÁFA nem szerepel az elszámolható költségekben
```

---

## Kapcsolat más módszertani elemekkel / Relationship to Other Elements

### Különbözeti módszer (meth_001)
- Projekt nélküli eset vs. projekt esettel
- Különbözet számítása minden pénzáram elemre

### Konszolidált megközelítés (meth_006)
- Tulajdonos és üzemeltető közti pénzmozgások kiszűrése
- Konszolidált pénzügyi elemzés

### Amortizáció kezelése (meth_007)
- Amortizáció NEM szerepel a pénzáramokban
- Eszközpótlás SZEREPEL tényleges kiadásként

### Diszkontráta (meth_004)
- Pénzügyi diszkontráta: TVI referencia ráta
- Alkalmazás: FNPV és FRR számításhoz

---

## Pénzügyi elemzés vs. Közgazdasági elemzés / Financial vs. Economic Analysis

| Szempont | Pénzügyi elemzés | Közgazdasági elemzés |
|----------|------------------|----------------------|
| **Perspektíva** | Projekt tulajdonos/üzemeltető | Társadalom egésze |
| **Diszkontráta** | Pénzügyi (TVI ráta) | Társadalmi (3% reál) |
| **Árak** | Piaci árak | Árnyékárak (ha szükséges) |
| **Externáliák** | Nem tartalmazza | Tartalmazza |
| **Transzferek** | Tartalmazza | Kiszűri |
| **Cél** | Megtérülés, fenntarthatóság | Társadalmi hasznosság |
| **Mutató** | FNPV, FRR | ENPV, ERR |

---

## Ellenőrzési lista / Checklist

### Pénzügyi elemzés előkészítése:
- [ ] Kiválasztott változat azonosítva
- [ ] Elemzési időtáv meghatározva
- [ ] Pénzügyi diszkontráta meghatározva (TVI ráta)
- [ ] ÁFA kezelés tisztázva
- [ ] Konszolidáció szükségessége eldöntve

### Pénzáramok összeállítása:
- [ ] Beruházási költségek becsülve
- [ ] Működési költségek becsülve
- [ ] Bevételek becsülve
- [ ] Projekt nélküli eset pénzárama
- [ ] Projekt esettel pénzáram
- [ ] Különbözet számítva

### Teljesítménymutatók:
- [ ] FNPV számítva (támogatás nélkül)
- [ ] FNPV számítva (támogatással)
- [ ] FRR számítva
- [ ] Pénzügyi fenntarthatóság vizsgálva

### Dokumentálás:
- [ ] Feltételezések dokumentálva
- [ ] Becslési módszerek bemutatva
- [ ] Adatforrások hivatkozva
- [ ] Eredmények értelmezve

---

## Értelmezési kérdések / Interpretation Issues

### Tisztázott:
- ✅ Két fő cél: optimális támogatás és fenntarthatóság
- ✅ FNPV és FRR definíciók egyértelműek
- ✅ Különbözeti módszer alkalmazása kötelező
- ✅ ÁFA kezelés szabályozott
- ✅ Pénzügyi diszkontráta: TVI referencia ráta

### Nyitott kérdések:
- ⚠️ **"Optimális támogatási mérték" pontos definíciója:** Mikor tekinthető optimálisnak?
- ⚠️ **Pénzügyi fenntarthatóság kritériumai:** Konkrét küszöbértékek hiányoznak
- ⚠️ **Konszolidáció részletei:** Mikor és hogyan kell alkalmazni pontosan?

---

## Kapcsolódó szabályok / Related Rules

- **Különbözeti módszer:** meth_001
- **CBA paraméterek:** meth_004
- **Konszolidált megközelítés:** meth_006
- **Amortizáció:** meth_007
- **Beruházási költségek:** fin_002 (tbd)
- **Működési költségek:** fin_003 (tbd)
- **Bevételek:** fin_004 (tbd)
- **Támogatási összeg:** fin_005 (tbd)

---

## Hivatkozások / References

**Forrás dokumentum:**
- TOP PLUSZ Közgazdasági és Pénzügyi Útmutató, 4.1 és 4.4 fejezetek, 56., 60. oldal

**Kapcsolódó jogszabályok:**
- 256/2021 (V. 18.) Korm. rendelet

**Külső hivatkozások:**
- Elszámolási útmutató: https://www.palyazat.gov.hu/

---

## Frissítési információk / Update Information

**Utolsó frissítés:** 2026-04-01  
**Frissítés oka:** Kezdeti kinyerés a forrás dokumentumból  
**Következő felülvizsgálat:** TVI referencia ráta vagy jogszabály változásakor