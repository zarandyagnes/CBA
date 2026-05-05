---
id: fin_003
title: Pénzügyi elemzés illesztése a projekt mérföldköveihez (Financial Analysis Alignment with Milestones)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 4.2 Pénzügyi elemzés illesztése a projekt mérföldköveihez
source_page: 56-57
domain: financial_analysis
subdomain: project_milestones
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - financial_analysis
  - milestones
  - reporting
  - monitoring
related_ids:
  - fin_001
  - fin_002
  - method_001
---

# Pénzügyi elemzés illesztése a projekt mérföldköveihez

## Áttekintés

A pénzügyi elemzés különböző mélységben és időpontokban készül el a projekt életciklusa során. A dokumentum bemutatja, hogy mikor és milyen részletességgel kell a pénzügyi elemzést elkészíteni és frissíteni.

## Elemzési szintek

### Egyszerűsített pénzügyi elemzés

**Tartalom:**
- Beruházási költségek bemutatása és indoklása
- Működési költségek bemutatása és indoklása
- Működési bevételek bemutatása és indoklása
- Projekt fenntarthatóságának bizonyítása

**Időzítés:**
- **Támogatási kérelem beadásakor:** Minden projektre kötelező

**Frissítés:**
- **Projekt előkészítési fázis végén:** Ha a műszaki tartalom módosítása miatt az értékek változnak

### Részletes pénzügyi elemzés

**Tartalom:**
- Teljes pénzügyi elemzés
- Pénzügyi teljesítménymutatók (FNPV, FRR)
- Támogatási összeg meghatározása
- Részletes pénzügyi fenntarthatóság

**Időzítés:**
- **Projekt előkészítési fázis végéig:** Amennyiben szükséges

**Szükségességi kritériumok:**
- Nettó bevételtermelő projektek
- Állami támogatási szabályok alá eső projektek
- Finanszírozási hiány ráta számítása szükséges

## Monitoring és nyomon követés

### IH (Irányító Hatóság) nyomon követése

**Alapja:**
- Releváns jogszabályok
- Útmutatók

**Nyomon követett adatok:**
- Pénzügyi adatok változása
- Bevételek keletkezése
- Nettó bevétel
- Működési eredmény (állami támogatás esetén)

### Záró kifizetési kérelem

**Kedvezményezett kötelezettségei:**

Ha a projekt megvalósítása során bevétel keletkezett:

1. **Adatszolgáltatás:**
   - Bevétel
   - Nettó bevétel
   - Működési eredmény (állami támogatás esetén)

2. **Módosított pénzügyi elemzés:**
   - Ha az adatok módosulása módosítja a pénzügyi elemzést
   - Módosított pénzügyi elemzés csatolása kötelező

**Jogszabályi háttér:**
256/2021 (V. 18) Korm. rendelet 288. § (3) bekezdése

### Záró projekt fenntartási jelentés

**Tartalom:**

1. **Tény beruházási költségek:**
   - Tényleges megvalósult költségek

2. **Működési költségek:**
   - Tény adatok
   - Vagy pontosabb becsléssel megállapított értékek

3. **Bevételek:**
   - Tény adatok
   - Vagy pontosabb becsléssel megállapított értékek

## Ingatlanértékesítés kezelése

**Speciális szabályok:**
- Ingatlanok értékesítéséből származó bevétel kezelését a 4.8 fejezet tartalmazza
- Külön figyelmet igényel a támogatás számítása során

## Visszafizetési kötelezettség

### Támogatási összeg csökkenése

**Feltétel:**
Tény adatokkal újraszámolva a támogatási összeg csökkent

**Következmény:**
```
Kedvezményezett köteles a különbözetet visszafizetni
```

### Jogosulatlan igénybevétel

**Feltétel:**
Kimutatható, hogy a kedvezményezett jogosulatlanul vette igénybe a támogatást

**Következmény:**
```
Visszafizetés kamatokkal együtt
```

### Jogszerű eltérés

**Feltétel:**
Nem jogszerűtlen esetekben (pl. piaci változások, előre nem látható körülmények)

**Következmény:**
```
Visszafizetés kamat nélkül
```

**Jogszabályi háttér:**
256/2021. (V. 18.) Korm. rendelet 418., 419. §

## Gyakorlati alkalmazás

### Projekt életciklus és pénzügyi elemzés

```
1. Támogatási kérelem beadása
   ↓
   [Egyszerűsített pénzügyi elemzés - KÖTELEZŐ]
   ↓
2. Projekt előkészítési fázis vége
   ↓
   [Frissítés, ha műszaki tartalom változott]
   [Részletes pénzügyi elemzés, ha szükséges]
   ↓
3. Projekt megvalósítás
   ↓
   [IH monitoring]
   ↓
4. Záró kifizetési kérelem
   ↓
   [Adatszolgáltatás bevételekről]
   [Módosított pénzügyi elemzés, ha szükséges]
   ↓
5. Záró projekt fenntartási jelentés
   ↓
   [Tény adatok bemutatása]
   [Visszafizetés, ha szükséges]
```

### Döntési fa: Részletes pénzügyi elemzés szükségessége

```
Kérdés: Keletkezik-e bevétel vagy költségmegtakarítás?
│
├─ NEM → Egyszerűsített elemzés elegendő
│        + Fenntarthatóság bemutatása
│        + PF szerinti max. támogatási arány
│
└─ IGEN → Kérdés: Állami támogatás?
           │
           ├─ NEM → Finanszírozási hiány ráta számítás
           │        + Részletes pénzügyi elemzés
           │
           └─ IGEN → Működési eredmény figyelembevétele
                     + Részletes pénzügyi elemzés
                     + Állami támogatási szabályok szerint
```

## Adatfrissítés és validáció

### Frissítési kötelezettség

**Trigger események:**
- Műszaki tartalom módosítása
- Költségek változása
- Bevételek változása
- Működési paraméterek változása

**Frissítés mértéke:**
- Csak a változott elemek
- Vagy teljes újraszámítás (ha jelentős változás)

### Validációs pontok

**Konzisztencia ellenőrzés:**
- [ ] Beruházási költségek összhangban a műszaki tervekkel
- [ ] Működési költségek reálisak
- [ ] Bevételek megalapozottak
- [ ] Fenntarthatóság biztosított

**Dokumentációs követelmények:**
- [ ] Minden feltételezés dokumentált
- [ ] Számítások átláthatóak
- [ ] Változások indokoltak
- [ ] Források megjelöltek

## Kapcsolódó fogalmak

- **Egyszerűsített pénzügyi elemzés:** Alapvető költség-bevétel bemutatás
- **Részletes pénzügyi elemzés:** Teljes körű elemzés teljesítménymutatókkal
- **Tény adatok:** Tényleges megvalósult értékek
- **Nettó bevétel:** Bevételek - működési költségek
- **Működési eredmény:** Állami támogatási szabályok szerinti eredmény

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- Az egyszerűsített elemzés minden projektre kötelező már a kérelem beadásakor
- A részletes elemzés szükségessége a projekt típusától függ
- Tény adatok alapján visszafizetési kötelezettség keletkezhet
- Jogszerűtlen igénybevétel esetén kamatfizetési kötelezettség

⚠️ **Gyakori hibák:**
- Frissítés elmulasztása műszaki tartalom változásakor
- Bevételek keletkezésének nem jelentése
- Tény adatok pontatlan bemutatása
- Visszafizetési kötelezettség nem teljesítése

⚠️ **Validációs igény:**
- IH monitoring során folyamatos ellenőrzés
- Záró kifizetési kérelemnél részletes vizsgálat
- Fenntartási jelentésnél tény adatok validálása

## Hivatkozások

- 256/2021 (V. 18) Korm. rendelet 288. § (3), 418., 419. §
- Pénzügyi elemzés célja → fin_001
- Projekttípusok → fin_002
- Ingatlanértékesítés → fin_008
- Pénzügyi fenntarthatóság → fin_007