---
id: fin_005
title: Pénzügyi teljesítménymutatók (Financial Performance Indicators)
source_document: TOP PLUSZ KPÚ.pdf
source_section: 4.9 A projekt pénzügyi megtérülése
source_page: 63-64
domain: financial_analysis
subdomain: performance_indicators
language: hu
status: draft
confidence: high
tags:
  - TOP_PLUSZ
  - financial_analysis
  - FNPV
  - FRR
  - performance_indicators
related_ids:
  - fin_001
  - fin_004
  - econ_008
  - method_004
---

# Pénzügyi teljesítménymutatók (Financial Performance Indicators)

## Áttekintés

A pénzügyi megtérülés legfontosabb mutatószámai a projekt pénzügyi életképességét és megtérülését mutatják be a kedvezményezett szempontjából. Ezek alapján dönthető el, hogy a projekt támogatás nélkül megvalósítható-e.

## Kötelezően számítandó mutatók

### 1. FNPV - Pénzügyi nettó jelenérték

**Definíció:**
A projekt várható, különbözetként számolt (diszkontált) beruházási és működési költségeinek, illetve bevételeinek különbözete.

**Képlet:**
```
FNPV = Σ [Xt / (1+i)^t]
       t=0 to n

ahol:
Xt = az adott évre vonatkozó pénzáramlás (bevételek - költségek)
i = pénzügyi diszkontráta
t = aktuális év (0 = beruházás kezdete)
n = referencia időszak vége
```

**Számítási módszer:**

1. **Éves nettó cash flow:**
   ```
   Nettó CF(t) = Bevételek(t) - Költségek(t)
   ```

2. **Diszkontálás:**
   ```
   Diszkontált CF(t) = Nettó CF(t) / (1 + i)^t
   ```

3. **Összegzés:**
   ```
   FNPV = Σ Diszkontált CF(t)
   ```

**Pénzügyi diszkontráta:**
- Projekt-specifikus
- Tükrözi a tőke alternatív költségét
- Jellemzően 3-5% reálérték

### 2. FRR - Pénzügyi belső megtérülési ráta

**Definíció:**
Azt a diszkontrátát fejezi ki, amelynél az FNPV = 0.

**Képlet:**
```
0 = Σ [Xt / (1+FRR)^t]
    t=0 to n

ahol:
FRR = keresett belső megtérülési ráta
```

**Számítási módszer:**

**Iteratív megoldás:**
1. Kezdő érték: i = pénzügyi diszkontráta
2. Számítsd ki FNPV(i)-t
3. Ha FNPV > 0, növeld i-t
4. Ha FNPV < 0, csökkentsd i-t
5. Ismételd, amíg FNPV ≈ 0

**Excel függvény:**
```
=IRR(értéktartomány)
vagy
=MIRR(értéktartomány; finanszírozási_ráta; újrabefektetési_ráta)
```

## Beruházás megtérülése

### FNPV(C) és FRR(C)

**Definíció:**
A beruházási költségeket a nettó bevételekhez viszonyító mutatók.

**Céljuk:**
Azt mérik, hogy a projekt nettó bevétele mennyire tudja visszatermelni támogatás nélküli esetben a befektetett összeget.

**Számítás során NEM kell figyelembe venni:**
- Tartalékot
- Fizetett kamatokat
- Tőkét és jövedelmet érintő adókat
- Egyéb közvetlen adókat

### Támogathatósági kritérium (kohéziós politika)

**Alapszabály:**
```
Ha FNPV(C) < 0 → Projekt részesülhet EU-támogatásban
```

**Kivétel:**
Ha a projekt az állami támogatás szabályai alá esik

**Logika:**
- Negatív FNPV(C): projekt támogatás nélkül nem térül meg
- Pozitív FNPV(C): projekt támogatás nélkül is megvalósítható lenne

### Magas pénzügyi nyereségességű projektek

**Feltétel:**
```
FRR(C) >> pénzügyi diszkontráta
```

**Általános szabály:**
A projektet úgy kezelik, mint amely uniós hozzájárulás nélkül is megvalósítható.

**Kivételek (támogatás indokolt):**

1. **Magas kockázat:**
   - Nagyon innovatív projektek
   - Befektető által vállalt kockázat túl magas
   - Közpénzből nyújtott vissza nem térítendő támogatás nélkül nem megvalósítható

2. **Igazolási kötelezettség:**
   - Be kell mutatni, hogy a beruházás önállóan (saját bevételekből) nem térülne meg
   - Figyelembe véve a kockázatokat

## Gyakorlati alkalmazás

### Példa számítás

**Projekt adatok:**
- Beruházási költség (0. év): 500 M Ft
- Éves működési költség (1-10. év): 30 M Ft/év
- Éves bevétel (1-10. év): 60 M Ft/év
- Pénzügyi diszkontráta: 4%

**1. FNPV számítása:**

```
Éves nettó CF = 60 - 30 = 30 M Ft

FNPV = -500 + Σ [30 / (1,04)^t]
                t=1 to 10

FNPV = -500 + 30 × 8,111 = -256,7 M Ft
```

**Értelmezés:**
- FNPV(C) = -256,7 M Ft < 0
- Projekt támogatás nélkül nem térül meg
- EU-támogatásra jogosult

**2. FRR számítása:**

```
0 = -500 + Σ [30 / (1+FRR)^t]
            t=1 to 10

FRR ≈ -2,5%
```

**Értelmezés:**
- Negatív FRR: projekt veszteséges
- Támogatás szükséges a megvalósításhoz

### Példa: Magas megtérülésű projekt

**Projekt adatok:**
- Beruházási költség: 200 M Ft
- Éves nettó CF: 40 M Ft (10 év)
- Pénzügyi diszkontráta: 4%

**Számítás:**
```
FNPV = -200 + 40 × 8,111 = 124,4 M Ft
FRR ≈ 15,1%
```

**Értékelés:**
- FNPV(C) > 0: projekt támogatás nélkül is megtérül
- FRR >> 4%: magas pénzügyi nyereségességű
- Általános szabály szerint: nem támogatható

**Kivétel indoklása szükséges:**
- Pl. magas technológiai kockázat
- Piaci bizonytalanság
- Stratégiai jelentőség

## FNPV vs. ENPV

### Különbségek

| Szempont | FNPV | ENPV |
|----------|------|------|
| Nézőpont | Kedvezményezett | Társadalom |
| Árak | Piaci árak | Árnyékárak |
| ÁFA | Benne van (ha nem visszaigényelhető) | Nincs benne |
| Externáliák | Nincsenek | Benne vannak |
| Diszkontráta | Pénzügyi (3-5%) | Társadalmi (3%) |
| Támogatások | Bevételként | Nem szerepelnek |

### Kapcsolat

**Tipikus eset:**
```
FNPV < 0 (projekt nem térül meg pénzügyileg)
ENPV > 0 (projekt társadalmilag hasznos)
→ Támogatás indokolt
```

**Ideális projekt:**
```
FNPV < 0 (támogatásra szorul)
ENPV >> 0 (nagy társadalmi haszon)
→ Erős támogatási indok
```

## Döntési szabályok

### Egyedi projekt értékelése

**Kohéziós politika (nem állami támogatás):**
```
Ha FNPV(C) < 0 → Támogatható
Ha FNPV(C) > 0 → Általában nem támogatható (kivéve indokolt esetben)
```

**Állami támogatás:**
- Specifikus szabályok szerint
- FNPV(C) nem feltétlenül döntő

### Több projekt rangsorolása

**Korlátozott költségvetés esetén:**

1. **Szűrés:**
   - Csak FNPV(C) < 0 projektek (kohéziós politika)
   - Vagy állami támogatási szabályok szerint

2. **Rangsorolás:**
   - ENPV szerint (társadalmi hasznosság)
   - Vagy ERR szerint
   - Vagy BCR szerint

3. **Kiválasztás:**
   - Legnagyobb társadalmi hasznú projektek
   - Költségvetési korlát figyelembevételével

## Érzékenységvizsgálat

### Kötelező elemek

**FNPV érzékenysége:**
- Beruházási költség ±20%
- Működési költség ±20%
- Bevételek ±20%
- Pénzügyi diszkontráta változása

**FRR érzékenysége:**
- Kulcs paraméterek változása
- Forgatókönyvek (pesszimista, bázis, optimista)

### Kritikus értékek

**Switching values:**
Azon paraméter értékek, amelyeknél:
- FNPV(C) = 0
- FRR = pénzügyi diszkontráta

**Példa:**
"A bevételek hány %-os csökkenése mellett válik a projekt pénzügyileg nem fenntarthatóvá?"

## Kapcsolódó fogalmak

- **Nettó jelenérték (NPV):** Diszkontált cash flow-k összege
- **Belső megtérülési ráta (IRR):** Diszkontráta, ahol NPV = 0
- **Pénzügyi diszkontráta:** Tőke alternatív költsége
- **Nettó bevétel:** Bevételek - működési költségek
- **Beruházás megtérülése:** FNPV(C), FRR(C)

## Minőségi megjegyzések

⚠️ **Kritikus pontok:**
- FNPV(C) < 0 általában szükséges a támogathatósághoz (kohéziós politika)
- Magas FRR(C) esetén támogatás indoklása szükséges
- FNPV és ENPV különbözősége fontos
- Érzékenységvizsgálat kötelező

⚠️ **Gyakori hibák:**
- FNPV és ENPV összekeverése
- Pénzügyi és társadalmi diszkontráta helytelen használata
- ÁFA kezelése (pénzügyi vs. közgazdasági elemzés)
- Támogatások kezelése (bevétel vs. finanszírozás)

⚠️ **Validációs igény:**
- Számítások helyességének ellenőrzése
- Diszkontráta megfelelőségének vizsgálata
- Érzékenységvizsgálat eredményeinek értékelése
- Támogathatósági kritériumok teljesülése

## Hivatkozások

- Pénzügyi elemzés célja → fin_001
- Projekttípusok → fin_004
- Közgazdasági teljesítménymutatók → econ_008
- CBA paraméterek → method_004
- Pénzügyi fenntarthatóság → fin_007