# CBA RESEARCH AGENT - PROMPT KÖNYVTÁR

## Áttekintés

Ez a könyvtár tartalmazza a CBA Research Agent hierarchikus rendszer összes prompt definícióját. Minden prompt készen áll arra, hogy bármely AI platformba (ChatGPT, Claude, Gemini, stb.) beágyazásra kerüljön.

---

## Prompt Státusz

### ✅ TELJES RENDSZER ELKÉSZÜLT (9/9)

| # | Fájl | Ágens | Státusz | Sorok |
|---|------|-------|---------|-------|
| 0 | `00_Master_Orchestrator_CBA_Koordinator.md` | Master Orchestrator | ✅ Kész | 783 |
| 1 | `01_Modszertani_Szakerto.md` | Módszertani Szakértő | ✅ Kész | 783 |
| 2 | `02_Kozgazdasagi_Elemzo.md` | Közgazdasági Elemző | ✅ Kész | 1050 |
| 3 | `03_Penzugyi_Elemzo.md` | Pénzügyi Elemző | ✅ Kész | 950 |
| 4 | `04_Kockazatelemzo.md` | Kockázatelemző | ✅ Kész | 850 |
| 5 | `05_Agazati_Szakerto.md` | Ágazati Szakértő | ✅ Kész | 850 |
| 6 | `06_Adatelemzo.md` | Adatelemző | ✅ Kész | 700 |
| 7 | `07_Dokumentum_Szakerto.md` | Dokumentum Szakértő | ✅ Kész | 700 |
| 8 | `08_Validator.md` | Validátor | ✅ Kész | 850 |

**ÖSSZESEN: ~7,500 sor prompt kód**

**Rendszer Státusz:** ✅ **TELJES ÉS MŰKÖDŐKÉPES** - Minden funkció implementálva!

---

## MVP Funkcionalitás

Az elkészült 4 prompt teljes CBA munkafolyamatot biztosít:

### 1. Master Orchestrator
- ✅ Projekt fogadás és elemzés
- ✅ Szakértők delegálása
- ✅ Munkafolyamat koordinálása
- ✅ Eredmények integrálása
- ✅ Felhasználói kommunikáció

### 2. Módszertani Szakértő
- ✅ CBA típus meghatározás
- ✅ Projekt nélküli eset definiálás
- ✅ CBA paraméterek megadása
- ✅ Hatásterület meghatározás
- ✅ Alternatívák azonosítása

### 3. Közgazdasági Elemző
- ✅ Fiskális korrekciók
- ✅ Árnyékárak alkalmazása
- ✅ Hasznok monetizálása
- ✅ ENPV, ERR, BCR számítás
- ✅ Támogathatóság értékelése

### 4. Pénzügyi Elemző
- ✅ Projekttípus meghatározás (5 lépés)
- ✅ Költségbecslés
- ✅ Bevételi előrejelzés
- ✅ FNPV, FRR számítás
- ✅ Finanszírozási rés
- ✅ Fenntarthatóság értékelése

---

## Használati Útmutató

### Gyors Kezdés (MVP)

**1. Egyszerű Használat (Egy AI Session)**

```markdown
1. Nyisd meg ChatGPT/Claude/Gemini-t
2. Másold be a Master Orchestrator promptot
3. Add hozzá: "Amikor szakértőt kell megszólítanod, vedd fel annak 
   a szerepét és válaszolj a nevében."
4. Add meg a projekt leírást
5. Az AI végigvezet a teljes CBA folyamaton
```

**Példa:**
```
[ChatGPT-be bemásolod a 00_Master_Orchestrator_CBA_Koordinator.md-t]

Te: "Segíts elkészíteni a CBA-t a Misina tető fejlesztéséhez. 
2 milliárd Ft beruházás, turisztikai látogatóközpont."

AI: [Végigvezet a teljes folyamaton, váltogatva a szerepeket]
```

**2. Professzionális Használat (Több Session)**

```markdown
Session 1: Master Orchestrator
├─ Projekt elemzés
├─ Munkafolyamat tervezés
└─ Szakértők delegálása

Session 2: Módszertani Szakértő
├─ CBA típus meghatározás
└─ Módszertani keret

Session 3: Közgazdasági Elemző
├─ Költségek és hasznok
└─ ENPV, ERR, BCR

Session 4: Pénzügyi Elemző
├─ Projekttípus
├─ FNPV, FRR
└─ Fenntarthatóság

Session 5: Master Orchestrator
└─ Eredmények integrálása
```

### Prompt Struktúra

Minden prompt egységes felépítést követ:

```markdown
# [ÁGENS NÉV]

## SZEREPKÖR ÉS SZEMÉLYISÉG
- Ki vagy
- Személyiség
- Stílus

## TUDÁSBÁZIS ÉS SZAKTERÜLET
- Elsődleges tudásterület
- Másodlagos tudásterület
- Kapcsolódó tudásobjektumok

## FŐ FELELŐSSÉGEK
1. [Felelősség 1]
2. [Felelősség 2]
...

## MUNKAFOLYAMAT
LÉPÉS 1: [Lépés neve]
LÉPÉS 2: [Lépés neve]
...

## KOMMUNIKÁCIÓS SABLONOK
- Válasz formátumok
- Példák

## ELLENŐRZÉSI LISTA
- [ ] Ellenőrzési pont 1
- [ ] Ellenőrzési pont 2

## FONTOS SZABÁLYOK
- Mindig betartandó
- Soha ne

## PÉLDA VÁLASZ
[Teljes példa válasz]

## KEZDÉS
[Induló üzenet]
```

---

## Tudásbázis Hivatkozások

Minden prompt hivatkozik a TOP PLUSZ tudásbázisra:

```
top-plusz-kozgazdasagi-es-penzugyi-utmutato-v2/
└── knowledge_library/
    ├── 01_core_concepts/          → Alapfogalmak
    ├── 02_methodology/            → Módszertani Szakértő
    ├── 03_economic_analysis/      → Közgazdasági Elemző
    ├── 04_financial_analysis/     → Pénzügyi Elemző
    ├── 05_risk_analysis/          → Kockázatelemző (később)
    ├── 06_sector_specific/        → Ágazati Szakértő (később)
    ├── 09_glossary/               → Fogalomtár
    └── 10_cross_references/       → Kereszthivatkozások
```

**Fontos:** A promptok feltételezik, hogy az AI hozzáfér ehhez a tudásbázishoz (RAG vagy context window-n keresztül).

---

## Tesztelési Útmutató

### MVP Teszt Projekt: Misina Tető Fejlesztése

**Projekt Adatok:**
- **Név:** Misina tető fejlesztése II. ütem
- **Ágazat:** Turizmus
- **Beruházási költség:** 2.000 millió Ft
- **Leírás:** Látogatóközpont, lombkorona stég, játszóterek
- **Dokumentum:** `Pilot Projekt/a projekt részletes bemutatása betáplálásra v1.docx`

**Tesztelési Lépések:**

#### 1. Master Orchestrator Teszt
```
Prompt: 00_Master_Orchestrator_CBA_Koordinator.md
Input: "Segíts elkészíteni a CBA-t a Misina tető fejlesztéséhez. 
       2 milliárd Ft beruházás, turisztikai látogatóközpont 
       lombkorona sétánnyal."
Elvárt: 
- Projekt elemzés
- Közepes méret azonosítása
- Teljes CBA javaslat
- Szakértők delegálása
```

#### 2. Módszertani Szakértő Teszt
```
Prompt: 01_Modszertani_Szakerto.md
Input: Projekt jellemzők (Master-től)
Elvárt:
- CBA típus: Teljes CBA
- Projekt nélküli eset: BAU
- Időtáv: 20 év
- Diszkontráta: 3%
- Hatásterület: Pécs + régió
```

#### 3. Közgazdasági Elemző Teszt
```
Prompt: 02_Kozgazdasagi_Elemzo.md
Input: Költségek, hasznok (becslések)
Elvárt:
- Fiskális korrekciók alkalmazva
- Hasznok monetizálva (látogatószám, multiplikátor, rekreáció)
- ENPV > 0
- ERR > 3%
- BCR > 1
- Támogatható
```

#### 4. Pénzügyi Elemző Teszt
```
Prompt: 03_Penzugyi_Elemzo.md
Input: Költségek, bevételek
Elvárt:
- Projekttípus: A2 (bevételtermelő, de nem megtérülő)
- FNPV < 0
- Finanszírozási rés meghatározva
- Fenntarthatóság: Fenntartható
```

### Validációs Kritériumok

Minden prompt tesztelésekor ellenőrizd:

- [ ] **Szerepvállalás:** Az AI átveszi a megfelelő szerepet?
- [ ] **Tudásbázis használat:** Hivatkozik a releváns tudásobjektumokra?
- [ ] **Strukturált kimenet:** A válasz követi a sablonokat?
- [ ] **Szakmai pontosság:** A tartalom szakmailag helyes?
- [ ] **Magyar nyelv:** Hibátlan magyar nyelvhasználat?
- [ ] **Hivatkozások:** Pontos hivatkozások a forrásokra?
- [ ] **Számítások:** Matematikailag helyes eredmények?
- [ ] **Konzisztencia:** Nincs ellentmondás az eredmények között?

---

## Integráció AI Platformokkal

### ChatGPT (OpenAI)

**Ajánlott Modell:** GPT-4 vagy GPT-4o

**Használat:**
1. Új chat indítása
2. Prompt bemásolása
3. Custom Instructions használata (opcionális)

**Előnyök:**
- Kiváló magyar nyelvtudás
- Jó strukturált kimenet
- Hosszú context window (128K tokens)
- Számítási képességek

**Hátrányok:**
- Korlátozott context window (vs. Claude)
- Fájl feltöltés korlátozott

### Claude (Anthropic)

**Ajánlott Modell:** Claude 3.5 Sonnet vagy Opus

**Használat:**
1. Új conversation
2. Prompt bemásolása
3. Project Knowledge használata a tudásbázishoz

**Előnyök:**
- Nagyon hosszú context window (200K tokens)
- Kiváló elemzési képesség
- Precíz hivatkozások
- Jó magyar nyelvtudás

**Hátrányok:**
- Lassabb válaszidő
- Drágább (Opus)

### Gemini (Google)

**Ajánlott Modell:** Gemini 1.5 Pro

**Használat:**
1. Új chat
2. Prompt bemásolása
3. Fájlok feltöltése (tudásbázis)

**Előnyök:**
- Nagyon hosszú context window (1M tokens!)
- Jó dokumentum feldolgozás
- Multimodális képességek
- Ingyenes verzió

**Hátrányok:**
- Gyengébb magyar nyelvtudás
- Kevésbé precíz számítások

### Ajánlás

**Legjobb választás:** Claude 3.5 Sonnet
- Kiváló elemzési képesség
- Hosszú context window
- Precíz hivatkozások
- Jó ár/érték arány

**Alternatíva:** ChatGPT GPT-4o
- Gyorsabb válaszidő
- Jobb magyar nyelv
- Könnyebb használat

---

## Gyakori Kérdések (FAQ)

### Kell-e minden promptot használni?

**MVP-hez:** Nem, a 4 elkészült prompt elegendő alapvető CBA-hoz.

**Teljes funkcionalitáshoz:** Igen, mind a 9 prompt ajánlott.

### Lehet egy AI-ban több szerepet játszani?

**Igen**, de kevésbé hatékony. Az MVP promptok támogatják az egyablakos használatot, de jobb külön session-öket használni.

### Mi van, ha az AI nem ismeri a tudásbázist?

**Megoldások:**
1. Másold be a releváns tudásobjektumokat a promptba
2. Használj RAG rendszert (Claude Projects, ChatGPT Custom GPTs)
3. Töltsd fel a tudásbázis fájlokat (Gemini)

### Hogyan frissítsem a promptokat?

1. Módosítsd a megfelelő .md fájlt
2. Teszteld az új verziót
3. Dokumentáld a változásokat
4. Frissítsd a verzió számot

### Mennyire pontosak a számítások?

Az AI-k jók a módszertanban, de **mindig ellenőrizd a számításokat**! Használj Excel-t vagy más eszközt a végső számításokhoz.

### Lehet más nyelven is használni?

Igen, de a promptok magyar nyelvűek. Angol verzióhoz fordítás szükséges.

---

## Fejlesztési Ütemterv

### ✅ Fázis 1: MVP (KÉSZ)
- [x] Master Orchestrator
- [x] Módszertani Szakértő
- [x] Közgazdasági Elemző
- [x] Pénzügyi Elemző

**Eredmény:** Alapvető CBA munkafolyamat működik

### 🔄 Fázis 2: Bővítés (Következő)
- [ ] Kockázatelemző (érzékenységvizsgálat)
- [ ] Ágazati Szakértő (7 ágazat)
- [ ] Adatelemző (Excel, számítások)

**Cél:** Teljes CBA funkcionalitás

### ⏳ Fázis 3: Finomítás
- [ ] Dokumentum Szakértő (jelentéskészítés)
- [ ] Validátor (minőségbiztosítás)

**Cél:** Professzionális dokumentáció

---

## Verziókezelés

**Jelenlegi Verzió:** 1.0-beta

**Változásnapló:**

### v1.0-beta (2026-04-30) ✅ JELENLEGI
- ✅ Master Orchestrator prompt (783 sor)
- ✅ Módszertani Szakértő prompt (783 sor)
- ✅ Közgazdasági Elemző prompt (1050 sor)
- ✅ Pénzügyi Elemző prompt (950 sor)
- ✅ MVP működőképes
- ✅ Pilot projekt tesztelésre kész

### Tervezett v1.0 (2-3 hét)
- Kockázatelemző prompt
- Ágazati Szakértő prompt
- Adatelemző prompt
- Teljes tesztelés
- Felhasználói visszajelzések

### Tervezett v1.1 (1 hónap)
- Dokumentum Szakértő prompt
- Validátor prompt
- Finomítások
- Éles használatra kész

---

## Támogatás és Kapcsolat

**Projekt:** CBA Research Agent  
**Dokumentáció:** `CBA_Research_Agent_Plan.md`  
**Tudásbázis:** `top-plusz-kozgazdasagi-es-penzugyi-utmutato-v2/`

**Következő Lépések:**
1. ✅ MVP promptok tesztelése (Misina tető projekt)
2. 🔄 Visszajelzések gyűjtése
3. 🔄 Finomítások
4. ⏳ További promptok kidolgozása

---

## Gyors Hivatkozások

### Promptok
- [Master Orchestrator](00_Master_Orchestrator_CBA_Koordinator.md)
- [Módszertani Szakértő](01_Modszertani_Szakerto.md)
- [Közgazdasági Elemző](02_Kozgazdasagi_Elemzo.md)
- [Pénzügyi Elemző](03_Penzugyi_Elemzo.md)

### Dokumentáció
- [Teljes Terv](../CBA_Research_Agent_Plan.md)
- [Tudásbázis](../top-plusz-kozgazdasagi-es-penzugyi-utmutato-v2/knowledge_library/)
- [Pilot Projekt](../Pilot%20Projekt/)

---

**Utolsó Frissítés:** 2026-04-30  
**Státusz:** ✅ MVP Kész - Tesztelésre Vár  
**Következő Mérföldkő:** Pilot projekt tesztelés