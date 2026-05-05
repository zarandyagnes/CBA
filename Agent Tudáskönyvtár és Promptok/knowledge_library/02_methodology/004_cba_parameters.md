---
id: meth_004
title: Költség-haszon elemzés paraméterei / Cost-Benefit Analysis Parameters
source_document: TOP PLUSZ KPÚ.pdf
source_section: 2.2 Költség-haszon elemzés paraméterei
source_page: 15-16
domain: methodology
subdomain: cba_parameters
language: hu
status: validated
confidence: high
tags:
  - TOP_PLUSZ
  - CBA
  - discount_rate
  - GDP_forecast
  - time_horizon
  - exchange_rate
  - inflation
related_ids:
  - meth_001
  - meth_002
  - meth_003
  - meth_006
  - meth_007
---

# Költség-haszon elemzés paraméterei / Cost-Benefit Analysis Parameters

## Forrás / Source

**Dokumentum:** TOP PLUSZ Közgazdasági és Pénzügyi Útmutató  
**Fejezet:** 2.2 Költség-haszon elemzés paraméterei  
**Oldal:** 15-16

## 1. Árfolyam / Exchange Rate

### Szabály / Rule

**Explicit követelmény:**
> "Az elemzés adatait rögzített árszinten, forintban kell megadni."

**Euróban történő megadás esetén:**
> "Amennyiben bizonyos adatokat euróban is szükséges megadni, akkor az átszámításhoz a mindenkor érvényes, hivatalos technikai árfolyam alkalmazandó."

### Alkalmazás / Application
- **Elsődleges pénznem:** Forint (HUF)
- **Árszint:** Rögzített (konstans árak)
- **EUR átszámítás:** Hivatalos technikai árfolyam
- **Árfolyam forrás:** Aktuális, hivatalos technikai árfolyam

---

## 2. Infláció / Inflation

### Szabály / Rule

**Általános elv:**
> "A projektelemzés során általában változatlan áron (inflációval kiigazított, a kiinduló évhez rögzített ár) kell számolni."

**Speciális eset - Relatív árváltozások:**
> "Azonban a pénzügyi áramok elemzése során, ha az elemzés változatlan árakon történik, és az inflációs előrejelzések alapján a relatív árak változása jelentős, akkor a relatív árak korrekciója szükséges."

### Adatforrás / Data Source
- **Forrás:** Magyar Nemzeti Bank (MNB)
- **Dokumentum:** Inflációs jelentés
- **Frissítés:** Rendszeresen közzétett

---

## 3. GDP előrejelzés / GDP Forecast

### Szabály / Rule

**Forrás és módszertan:**
> "A táblázatban megadott hosszútávú GDP előrejelzést a tanulmány írásakor rendelkezésre álló rövidtávú GDP előrejelzések, illetve az EU Reference Scenario 2020 prognózisa alapján állítottuk elő."

**Rugalmasság:**
> "Amennyiben aktuálisabb előrejelzések elérhetők, akkor az adatforrás lehivatkozásával a táblázatban javasolttól eltérő értékek is elfogadottak."

### GDP növekedési ráták / GDP Growth Rates

| Időszak | GDP növekedés |
|---------|---------------|
| 2025 | 2,4% |
| 2026 | 4,2% |
| 2027 | 3,3% |
| 2028-2030 | 3,0% |
| 2031-2035 | 2,1% |
| 2036-2040 | 1,7% |
| 2041-2045 | 1,5% |
| 2046- | 1,5% |

### Adatforrások / Data Sources

**Rövid távú (2025-2027):**
- Forrás: MNB
- Link: https://www.mnb.hu/letoltes/ir-infografika-2025-03.pdf

**Közép távú (2028-2030):**
- Forrás: IMF
- Link: https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/OEMDC/HUN

**Hosszú távú:**
- Forrás: EU Reference Scenario 2020
- Link: https://ec.europa.eu/energy/data-analysis/energy-modelling/eu-reference-scenario-2020_en

---

## 4. Vizsgált időtáv / Analysis Time Horizon

### Alapelv / Basic Principle

**Definíció:**
> "A vizsgált időtáv (elemzési időszak vagy referencia-időszak) azon évek száma, amelyek tekintetében a költség-haszon elemzés előrejelzéseket tartalmaz."

**Szabály:**
> "A vizsgált időtávra alkalmazandó szabály – amennyiben a pályázati felhívás nem határozza meg kötelezően -, hogy a vizsgált időtáv meg kell, hogy feleljen a projekt gazdaságilag hasznos időtávjának."

### Követelmények / Requirements

1. **Gazdaságilag hasznos időtáv:**
   - Meg kell felelnie a projekt gazdaságilag hasznos időtávjának
   - Elégségesen hosszú az összes jelentős költség és hatás figyelembevételéhez

2. **Gazdaságilag hasznos időtáv definíciója:**
   > "A közgazdaságilag hasznos időtávot úgy lehet definiálni, mint azt a becsült időtartamot, amíg a projekt várhatóan hasznos marad (pl. képes termékek/szolgáltatások előállítására) a projektgazda számára."

3. **Eltérés a fizikai élettartamtól:**
   > "A közgazdaságilag hasznos időtáv eltérhet a fizikai élettartamtól (pl. egy technológia elavulttá válhat a fizikai élettartamának vége előtt)."

### Speciális esetek / Special Cases

**Különböző élettartamú eszközök:**
> "Ha egy projekt különböző hasznos élettartamú eszközöket tartalmaz, az eszközök értékével arányosan megállapított, átlagos élettartam alkalmazása javasolt."

**Nagyon hosszú időtáv (>50 év):**
> "Ugyanakkor a nagyon hosszú (50 évnél hosszabb) időtávon hasznos projektek esetén javasolt rövidebb időtávot megállapítani, annak érdekében, hogy a jövőbeli közgazdasági pénzáramok nagyobb megbízhatósággal előjelezhetők legyenek."

**Pályázati felhívás által meghatározott:**
> "A Pályázati Felhívás kötelezően meghatározhatja a vizsgált időtávot, amit a kedvezményezettnek követnie kell."

### Maradványérték / Residual Value

**Általános eset:**
> "Amikor a vizsgált időtáv megegyezik a projekt gazdaságilag hasznos időtartamával, a maradvány érték általában zéró."

**Speciális eset:**
> "Azonban, ha a vizsgált időtáv végén néhány eszköz még gazdaságilag hasznos, vagy a piacon értékesíthető, a maradványértékkel kapcsolatos hasznot/bevételt szükséges lehet figyelembe venni."

---

## 5. Elemzés kezdő éve / Analysis Starting Year

### Szabály / Rule

**Kezdő év meghatározása:**
> "A referencia-időszak kezdő évének (ami a rögzített árszínvonal éve is) a beruházás első évét kell tekinteni."

**Korábbi költségek kezelése:**
> "Ha az elemzés kezdő éve előtt is felmerültek elszámolható vagy nem elszámolható beruházási költségek, akkor azokat – a fogyasztói árindexen alapuló, átlagos inflációs ráta segítségével – át kell számolni a kezdő év rögzített árszínvonalára és a referencia-időszak első évében kell őket szerepeltetni."

### Alkalmazás / Application

1. **Kezdő év = Beruházás első éve**
2. **Árszínvonal = Kezdő év árszínvonala**
3. **Korábbi költségek:** Inflációval kiigazítva a kezdő évre
4. **Elhelyezés:** Referencia-időszak első évében

---

## 6. Pénzügyi diszkontráta / Financial Discount Rate

### Definíció / Definition

> "A pénzügyi diszkontráta a tőke aktuális költségét fejezi ki egy adott gazdaságban/szektorban, ezért úgy lehet rá tekinteni, mint (minimum) elvárt piaci megtérülésre."

### Alkalmazás / Application

**Elfogadható gyakorlat:**
> "Elfogadható gyakorlat az állami támogatásoknál alkalmazott ráta alkalmazása, amely a támogatás nyújtásakor alkalmazandó leszámítolási kamatlábat, illetve diszkont-kamatlábat jelenti."

**Forrás:**
- **Közzétevő:** TVI (Támogatásokat Vizsgáló Iroda)
- **Link:** https://tvi.kormany.hu/referencia-rata
- **Frissítés:** Rendszeresen közzétett

**Rögzítés időpontja:**
> "A pénzügyi diszkontrátát a támogatás beadásának időpontjának aktuális értékén kell megállapítani és a későbbi időpontokban elvégzett pénzügyi értékeléseknek is ezt a pénzügyi diszkontrátát kell alkalmaznia."

---

## 7. Közgazdasági diszkontráta / Economic Discount Rate

### Definíció / Definition

> "A társadalmi diszkontráta a társadalom egésze számára az erőforrások hosszú távú alternatív költségét jelenti, más szavakkal kifejezve az egyik projektre fordított források más lehetséges projektek megvalósulása elől veszik el a lehetőséget."

### Szabály / Rule

**2021-2027 periódus:**
> "A 2021-2027-es periódusban Magyarországon az EU támogatásoknál a 3%-os reál diszkontráta alkalmazandó."

**Alkalmazás:**
- **Ráta:** 3% (reál)
- **Típus:** Társadalmi/közgazdasági diszkontráta
- **Időszak:** 2021-2027 EU programozási periódus
- **Kötelező:** Igen, minden EU támogatott projektnél

---

## Összefoglaló táblázat / Summary Table

| Paraméter | Érték/Forrás | Megjegyzés |
|-----------|--------------|------------|
| **Pénznem** | HUF (forint) | Rögzített árszinten |
| **EUR átszámítás** | Hivatalos technikai árfolyam | Szükség esetén |
| **Infláció** | MNB Inflációs jelentés | Változatlan áras elemzés |
| **GDP növekedés** | Lásd táblázat | Aktuálisabb adat elfogadható |
| **Időtáv** | Gazdaságilag hasznos élettartam | Max. 50 év javasolt |
| **Kezdő év** | Beruházás első éve | Árszínvonal bázisa |
| **Pénzügyi diszkontráta** | TVI referencia ráta | Pályázás időpontjában |
| **Közgazdasági diszkontráta** | 3% (reál) | 2021-2027 periódus |

## Értelmezési kérdések / Interpretation Issues

### Tisztázott:
- ✅ Közgazdasági diszkontráta: 3% reál
- ✅ Pénzügyi diszkontráta: TVI referencia ráta
- ✅ GDP előrejelzés táblázat megadva
- ✅ Időtáv: gazdaságilag hasznos élettartam
- ✅ Kezdő év: beruházás első éve

### Nyitott kérdések:
- ⚠️ **"Jelentős" relatív árváltozás küszöbe:** Nem definiált pontosan
- ⚠️ **Technikai árfolyam forrása:** Konkrét hivatkozás hiányzik
- ⚠️ **50 évnél hosszabb projektek időtáv meghatározása:** Konkrét módszertan hiányzik

## Kapcsolódó szabályok / Related Rules

- **Árszint kezelés:** meth_003
- **Különbözeti módszer:** meth_001
- **Projekt nélküli eset:** meth_002
- **Pénzügyi elemzés:** fin_001 (tbd)
- **Közgazdasági elemzés:** econ_001 (tbd)

## Hivatkozások / References

**Forrás dokumentum:**
- TOP PLUSZ Közgazdasági és Pénzügyi Útmutató, 2.2 fejezet, 15-16. oldal

**Külső hivatkozások:**
- MNB Inflációs jelentés: https://www.mnb.hu/letoltes/ir-infografika-2025-03.pdf
- IMF GDP előrejelzés: https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/OEMDC/HUN
- EU Reference Scenario: https://ec.europa.eu/energy/data-analysis/energy-modelling/eu-reference-scenario-2020_en
- TVI referencia ráta: https://tvi.kormany.hu/referencia-rata

## Frissítési információk / Update Information

**Utolsó frissítés:** 2026-04-01  
**Frissítés oka:** Kezdeti kinyerés a forrás dokumentumból  
**Következő felülvizsgálat:** GDP előrejelzések és diszkontrák frissítésekor