---
id: meth_007
title: Amortizáció kezelése / Amortization Treatment
source_document: TOP PLUSZ KPÚ.pdf
source_section: 2.1.6 Amortizáció kezelése
source_page: 14
domain: methodology
subdomain: financial_analysis
language: hu
status: validated
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - amortization
  - depreciation
  - cash_flow
  - asset_replacement
  - financial_analysis
related_ids:
  - meth_001
  - meth_004
  - meth_006
  - fin_001
---

# Amortizáció kezelése / Amortization Treatment

## Forrás / Source

**Dokumentum:** TOP PLUSZ Közgazdasági és Pénzügyi Útmutató  
**Fejezet:** 2.1.6 Amortizáció kezelése  
**Oldal:** 14

## Áttekintés / Overview

Az amortizáció (értékcsökkenés) kezelése kritikus kérdés a pénzügyi megtérülési számításokban. A dokumentum tisztázza, hogy az amortizáció hogyan jelenik meg (vagy nem jelenik meg) a diszkontált cash-flow alapú elemzésekben, és hogyan kapcsolódik az eszközpótlási költségekhez.

---

## Alapelv / Basic Principle

### Amortizáció és cash-flow elemzés

> "Az amortizációs költség a diszkontált pénzáram (cash-flow) alapú pénzügyi megtérülési számításoknak közvetlenül nem része, mivel az amortizációs költség nem jelent közvetlen készpénzkiadást."

**Kulcs megállapítás:**
- Amortizáció = számviteli költség
- Amortizáció ≠ készpénzkiadás
- Cash-flow elemzésben: csak tényleges pénzmozgások számítanak

### Számviteli szabályok irrelevanciája

> "A megtérülés számításának szempontjából közömbös, hogy az amortizáció elszámolására vonatkozólag milyen számviteli szabályok, módszerek vannak."

---

## Amortizáció közvetett szerepe / Indirect Role of Amortization

### Fejlesztések finanszírozása

> "A fejlesztéseknek azonban számvitelileg a saját forrásokat tekintve általában a nyereség, illetve a felhalmozott amortizáció a forrása."

**Finanszírozási logika:**
```
Működési bevételek
    ↓
Fedezik: működési költségeket + amortizációt
    ↓
Nyereség + Felhalmozott amortizáció
    ↓
Forrás a fejlesztésekhez
```

---

## Eszközpótlás és amortizáció kapcsolata / Asset Replacement and Amortization

### Közvetett figyelembevétel

> "Ezt a tényt közvetetten a megtérülési számítás is figyelembe veszi, hiszen a folyamatos, adott szolgáltatási színvonalat biztosító működéshez szükséges beruházási pótlások/felújítások (gépek, berendezések cseréje) beépítésre kerülnek a megtérülési számítás alapját képező pénzáramba."

### Logikai kapcsolat

**Feltételezés:**
> "Ez feltételezi, hogy olyan díjak kerülnek meghatározásra, amelyek az amortizációs költségként nyilvántartott költségeket – vagy legalább azok egy részét – is magukban foglalják"

**Eredmény:**
> "így az évek során felhalmozódik annyi szabad forrás amortizációs ágon, amennyi a vizsgált időszak alatt – és azon túl is – fedezetet biztosít a beruházási jellegű eszközpótlásokra."

---

## Gyakorlati alkalmazás / Practical Application

### Cash-flow elemzésben

**NEM szerepel:**
- ❌ Amortizációs költség (mint költségtétel)
- ❌ Számviteli értékcsökkenés

**SZEREPEL:**
- ✅ Tényleges beruházási költségek (kezdeti)
- ✅ Eszközpótlási költségek (jövőbeli)
- ✅ Működési költségek (tényleges kiadások)
- ✅ Bevételek (tényleges beáramlások)

### Eszközpótlás tervezése

**Módszer:**
1. Azonosítsa az eszközöket és élettartamukat
2. Tervezze meg a pótlási időpontokat
3. Becsülje meg a pótlási költségeket
4. Építse be a cash-flow előrejelzésbe (tényleges kiadásként)

**Példa:**
```
Év 0: Beruházás (gép beszerzése): -100 M Ft
Év 1-10: Működési költségek: -10 M Ft/év
Év 10: Gép pótlása: -100 M Ft (újabb gép)
Év 11-20: Működési költségek: -10 M Ft/év
```

**Megjegyzés:** Az amortizáció (pl. 10 M Ft/év) NEM jelenik meg a cash-flow-ban.

---

## Díjképzés és amortizáció / Pricing and Amortization

### Díjak meghatározása

**Követelmény:**
> "olyan díjak kerülnek meghatározásra, amelyek az amortizációs költségként nyilvántartott költségeket – vagy legalább azok egy részét – is magukban foglalják"

**Díjstruktúra:**
```
Díj = Működési költségek + Amortizáció + Nyereség
```

**Cél:**
- Fedezze a működési költségeket
- Fedezze az amortizációt (eszközpótlás forrása)
- Biztosítson észszerű nyereséget

### Felhalmozódás mechanizmusa

**Folyamat:**
1. Díjbevételek beérkeznek
2. Működési költségek kifizetése
3. Amortizáció elszámolása (számvitelileg)
4. Felhalmozott amortizáció = forrás
5. Eszközpótlás finanszírozása a felhalmozott amortizációból

---

## Példa: Amortizáció vs. Cash-flow / Example: Amortization vs. Cash-flow

### Számviteli megközelítés (eredménykimutatás):

| Év | Bevétel | Működési ktg | Amortizáció | Eredmény |
|----|---------|--------------|-------------|----------|
| 1 | 50 | -20 | -10 | 20 |
| 2 | 50 | -20 | -10 | 20 |
| ... | ... | ... | ... | ... |
| 10 | 50 | -20 | -10 | 20 |

**Felhalmozott amortizáció 10 év alatt:** 10 × 10 = 100 M Ft

### Cash-flow megközelítés (CBA):

| Év | Bevétel | Működési ktg | Beruházás | Nettó CF |
|----|---------|--------------|-----------|----------|
| 0 | 0 | 0 | -100 | -100 |
| 1 | 50 | -20 | 0 | 30 |
| 2 | 50 | -20 | 0 | 30 |
| ... | ... | ... | ... | ... |
| 10 | 50 | -20 | -100 | -70 |
| 11 | 50 | -20 | 0 | 30 |

**Megjegyzés:** 
- Amortizáció NEM szerepel a cash-flow-ban
- Eszközpótlás (100 M Ft) SZEREPEL a 10. évben
- A felhalmozott amortizáció (100 M Ft) fedezi az eszközpótlást

---

## Kapcsolat más módszertani elemekkel / Relationship to Other Elements

### Különbözeti módszer (meth_001)

Az eszközpótlási költségeket is a különbözeti módszer szerint kell kezelni:
- Projekt nélküli esetben is lenne eszközpótlás? → Csak a különbözet számít

### Konszolidált megközelítés (meth_006)

Bérleti/vagyonkezelési szerződésekben:
> "például az üzemeltető többek közt az értékcsökkenés értékét is megfizeti a bérleti díjban, amelyet a tulajdonos a megfelelő időpontban az eszközök pótlására fordít"

### Vizsgált időtáv (meth_004)

Az eszközpótlások tervezése függ a vizsgált időtávtól:
- Rövid időtáv: kevesebb pótlás
- Hosszú időtáv: több pótlási ciklus

---

## Ellenőrzési lista / Checklist

### Cash-flow előkészítés:

- [ ] Amortizációs költség NINCS benne a cash-flow-ban
- [ ] Kezdeti beruházási költségek szerepelnek
- [ ] Eszközök élettartama azonosítva
- [ ] Pótlási időpontok megtervezve
- [ ] Pótlási költségek becsülve
- [ ] Pótlási költségek beépítve a cash-flow-ba (tényleges kiadásként)

### Díjképzés ellenőrzése:

- [ ] Díjak fedezik a működési költségeket
- [ ] Díjak fedezik az amortizációt (legalább részben)
- [ ] Díjak biztosítanak észszerű nyereséget
- [ ] Felhalmozott amortizáció elegendő az eszközpótláshoz

### Konzisztencia ellenőrzés:

- [ ] Eszközpótlási költségek konzisztensek az eszközök élettartamával
- [ ] Díjbevételek elegendőek a hosszú távú fenntarthatósághoz
- [ ] Projekt nélküli esetben is figyelembe vett eszközpótlás (ha releváns)

---

## Gyakori hibák / Common Mistakes

### ❌ HELYTELEN:
1. Amortizációt költségként szerepeltetni a cash-flow-ban
2. Eszközpótlást NEM szerepeltetni a cash-flow-ban
3. Díjakat úgy meghatározni, hogy NEM fedezik az amortizációt
4. Felhalmozott amortizációt figyelmen kívül hagyni a finanszírozásban

### ✅ HELYES:
1. Amortizációt NEM szerepeltetni a cash-flow-ban
2. Eszközpótlást tényleges kiadásként szerepeltetni
3. Díjakat úgy meghatározni, hogy fedezik az amortizációt
4. Felhalmozott amortizációt figyelembe venni az eszközpótlás finanszírozásában

---

## Értelmezési kérdések / Interpretation Issues

### Tisztázott:
- ✅ Amortizáció NEM része a cash-flow elemzésnek
- ✅ Eszközpótlás RÉSZE a cash-flow elemzésnek
- ✅ Díjaknak fedezniük kell az amortizációt
- ✅ Felhalmozott amortizáció forrás az eszközpótláshoz

### Nyitott kérdések:
- ⚠️ **"Legalább azok egy részét" - mennyi?** Nincs konkrét küszöbérték megadva
- ⚠️ **Eszközpótlás becslési módszertana:** Részletes útmutatás hiányzik
- ⚠️ **Díjképzési módszertan:** Konkrét számítási módszer nincs részletezve

---

## Kapcsolódó szabályok / Related Rules

- **Különbözeti módszer:** meth_001
- **Vizsgált időtáv:** meth_004
- **Konszolidált megközelítés:** meth_006
- **Pénzügyi elemzés:** fin_001 (tbd)

---

## Hivatkozások / References

**Forrás dokumentum:**
- TOP PLUSZ Közgazdasági és Pénzügyi Útmutató, 2.1.6 fejezet, 14. oldal

---

## Gyakorlati tanácsok / Practical Advice

### Eszközpótlás tervezése:

1. **Eszközlista készítése:**
   - Listázza ki az összes eszközt
   - Határozza meg az élettartamokat
   - Becsülje meg a pótlási költségeket

2. **Pótlási ütemterv:**
   - Tervezze meg a pótlási időpontokat
   - Figyelje a technológiai elavulást
   - Vegye figyelembe a jogszabályi változásokat

3. **Finanszírozás biztosítása:**
   - Ellenőrizze, hogy a díjak fedezik-e az amortizációt
   - Számítsa ki a felhalmozott amortizációt
   - Győződjön meg róla, hogy elegendő forrás lesz

### Dokumentálás:

- Készítsen eszközlistát élettartamokkal
- Dokumentálja a pótlási ütemtervet
- Mutassa be a díjképzési logikát
- Igazolja, hogy a díjak fedezik az amortizációt

---

## Frissítési információk / Update Information

**Utolsó frissítés:** 2026-04-01  
**Frissítés oka:** Kezdeti kinyerés a forrás dokumentumból  
**Következő felülvizsgálat:** Számviteli szabályok vagy CBA módszertan változása esetén