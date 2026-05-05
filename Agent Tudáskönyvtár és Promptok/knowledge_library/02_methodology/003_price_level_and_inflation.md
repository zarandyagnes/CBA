---
id: meth_003
title: Árszint és infláció kezelése / Price Level and Inflation Treatment
source_document: TOP PLUSZ KPÚ.pdf
source_section: 2.1.3 Az elemzés árszintje
source_page: 12
domain: methodology
subdomain: price_treatment
language: hu
status: validated
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - price_level
  - inflation
  - constant_prices
  - relative_prices
related_ids:
  - meth_001
  - meth_002
  - meth_004
---

# Árszint és infláció kezelése / Price Level and Inflation Treatment

## Forrás / Source

**Dokumentum:** TOP PLUSZ Közgazdasági és Pénzügyi Útmutató  
**Fejezet:** 2.1.3 Az elemzés árszintje  
**Oldal:** 12

## Szabály / Rule

### Változatlan áras elemzés / Constant Price Analysis

**Explicit követelmény:**
> "Az elemzéseket változatlan áron, azaz egy adott év árszínvonalán kell végezni"

**Kötelező dokumentálás:**
> "Az elemzésben meg kell adni, hogy az árak milyen időpontra vonatkoznak."

### Alkalmazás / Application

**Általános elv:**
- Minden elemzést változatlan (konstans) áron kell végezni
- Egy adott év árszínvonalát kell rögzíteni
- Az árszint időpontját explicit módon dokumentálni kell

**Speciális eset - Relatív árváltozások:**

Ha az alábbi feltételek teljesülnek:
1. Az elemzés változatlan árakon történik, ÉS
2. Az inflációs előrejelzések alapján a relatív árak változása jelentős

Akkor: **a relatív árak korrekciója szükséges**

## Fogalmak / Concepts

### Változatlan ár (Constant Price)
Inflációval kiigazított, a kiinduló évhez rögzített ár.

### Relatív árváltozás (Relative Price Change)
Amikor egyes árak az általános inflációtól eltérő mértékben változnak.

## Adatforrás / Data Source

**Rövid távú fogyasztói árszínvonal-előrejelzés:**
- Forrás: Magyar Nemzeti Bank (MNB)
- Dokumentum: Inflációs jelentés
- Rendszeresen közzétett

## Gyakorlati alkalmazás / Practical Application

### Lépések:

1. **Árszint rögzítése:**
   - Válasszon egy bázis évet (általában a beruházás első éve)
   - Dokumentálja az árszint időpontját

2. **Adatok gyűjtése:**
   - Minden költség és bevétel adat a bázis év árszínvonalán
   - Ha más időpontból származó adat van, inflációval kiigazítva

3. **Relatív árváltozás vizsgálata:**
   - Ellenőrizze az MNB inflációs előrejelzéseket
   - Azonosítsa a jelentős relatív árváltozásokat
   - Ha szükséges, korrigálja a relatív árakat

4. **Dokumentálás:**
   - Rögzítse a bázis év árszínvonalát
   - Dokumentálja a relatív ár korrekciókat (ha voltak)
   - Hivatkozza az MNB forrásokat

## Kapcsolódó szabályok / Related Rules

- **Elemzés kezdő éve:** A beruházás első éve (lásd: meth_004)
- **Árfolyam kezelés:** Forint alapú elemzés, technikai árfolyam (lásd: meth_005)
- **Diszkontálás:** Változatlan áras cash-flow diszkontálása (lásd: meth_006, meth_007)

## Értelmezési kérdések / Interpretation Issues

### Tisztázott:
- ✅ Változatlan áras elemzés kötelező
- ✅ Árszint időpontját dokumentálni kell
- ✅ MNB inflációs jelentés az adatforrás

### Nyitott kérdések:
- ⚠️ **Jelentős relatív árváltozás küszöbértéke:** A dokumentum nem határozza meg, hogy pontosan mekkora relatív árváltozás számít "jelentősnek". Szakértői validáció szükséges.
- ⚠️ **Korrekciós módszertan:** A relatív árak korrekciójának konkrét módszertana nincs részletezve. Szakértői útmutatás szükséges.

## Példa / Example

**Projekt indítása:** 2025
**Bázis év árszínvonala:** 2025

**Költségek:**
- 2024-ben felmerült előkészítési költség: 10 M Ft (2024 áron)
- Átszámítva 2025 árszínvonalra: 10 M Ft × (1 + infláció_2024-2025)

**Relatív árváltozás példa:**
- Általános infláció: 5%
- Építőipari árak növekedése: 8%
- Relatív árváltozás: +3 százalékpont
- Ha ez "jelentős", akkor korrekció szükséges

## Kapcsolat más módszertani elemekkel / Relationship to Other Methodological Elements

```
Árszint kezelés
    ↓
Költségbecslés (változatlan áron)
    ↓
Bevételbecslés (változatlan áron)
    ↓
Cash-flow előrejelzés (változatlan áron)
    ↓
Diszkontálás (reál diszkontráta)
    ↓
NPV, IRR számítás
```

## Minőségbiztosítási ellenőrzőlista / Quality Assurance Checklist

- [ ] Árszint bázis éve dokumentálva
- [ ] Minden adat ugyanazon árszínvonalon
- [ ] Múltbeli adatok inflációval kiigazítva
- [ ] MNB inflációs előrejelzés ellenőrizve
- [ ] Relatív árváltozások azonosítva
- [ ] Szükség esetén relatív ár korrekció alkalmazva
- [ ] Korrekciók dokumentálva és indokolva

## Hivatkozások / References

**Forrás dokumentum:**
- TOP PLUSZ Közgazdasági és Pénzügyi Útmutató, 2.1.3 fejezet, 12. oldal

**Külső hivatkozások:**
- MNB Inflációs jelentés: https://www.mnb.hu/

## Frissítési információk / Update Information

**Utolsó frissítés:** 2026-04-01  
**Frissítés oka:** Kezdeti kinyerés a forrás dokumentumból  
**Következő felülvizsgálat:** MNB inflációs előrejelzések frissítésekor