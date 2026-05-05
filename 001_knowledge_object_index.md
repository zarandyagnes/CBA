---
id: xref_001
title: Knowledge Object Cross-Reference Index
title_en: Knowledge Object Cross-Reference Index
source_document: TOP PLUSZ KPÚ.pdf
source_section: All chapters
source_page: 1-97
domain: cross_references
subdomain: index
language: en
status: validated
confidence: high
tags:
  - TOP_PLUSZ
  - cross_reference
  - index
  - navigation
  - knowledge_graph
related_ids:
  - all
---

# Knowledge Object Cross-Reference Index

## Purpose

This index provides a comprehensive map of all knowledge objects in the TOP PLUSZ Knowledge Library and their relationships. It enables:

- **Navigation:** Find related content quickly
- **Dependency tracking:** Understand prerequisite knowledge
- **Retrieval optimization:** Support AI agent queries
- **Knowledge graph construction:** Build semantic relationships
- **Workflow orchestration:** Chain knowledge objects in processes

---

## Index Structure

### Total Knowledge Objects: 28

**By Domain:**
- Core concepts: 1
- Methodology: 8
- Economic analysis: 9
- Financial analysis: 6
- Risk analysis: 1
- Practical examples: 1
- Glossary: 1
- Supporting documents: 1

---

## 1. Core Concepts (01_core_concepts/)

### core_001: Purpose of Evaluation
**File:** `01_core_concepts/001_purpose_of_evaluation.md`  
**Title:** A közgazdasági és pénzügyi értékelés célja  
**Pages:** 6-10

**Depends on:** None (foundational)

**Required by:**
- All methodology objects (meth_001 - meth_008)
- All economic analysis objects (econ_001 - econ_009)
- All financial analysis objects (fin_001 - fin_006)

**Related concepts:**
- Társadalmi hasznosság (Social benefit)
- Ár-érték arány (Value for money)
- Támogatási jogcím (Support eligibility)

**Use cases:**
- Understanding evaluation purpose
- Legal framework reference
- General requirements overview

---

## 2. Methodology (02_methodology/)

### meth_001: Differential Method
**File:** `02_methodology/001_differential_method.md`  
**Title:** Különbözeti módszer (Incremental Method)  
**Pages:** 11

**Depends on:**
- core_001 (evaluation purpose)

**Required by:**
- econ_001 (economic analysis steps)
- fin_001 (financial analysis purpose)
- All CBA calculations

**Related to:**
- meth_002 (without-project scenario)
- meth_003 (price level treatment)

**Key concepts:**
- Projekt esettel vs. projekt nélküli eset
- Incremental cash flows
- Differential analysis

---

### meth_002: Without-Project Scenario
**File:** `02_methodology/002_without_project_scenario.md`  
**Title:** Projekt nélküli eset (Baseline Scenario)  
**Pages:** 11-12

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)

**Required by:**
- econ_001 (economic analysis steps)
- econ_003 (needs assessment)
- fin_001 (financial analysis)

**Related to:**
- meth_003 (price level)
- meth_007 (amortization)

**Key concepts:**
- BAU (Business as Usual)
- Do-Minimum scenario
- Baseline definition

---

### meth_003: Price Level and Inflation
**File:** `02_methodology/003_price_level_and_inflation.md`  
**Title:** Árszint és infláció kezelése  
**Pages:** 12

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)

**Required by:**
- econ_005 (full CBA methodology)
- fin_005 (financial performance indicators)
- All cost/benefit calculations

**Related to:**
- meth_004 (CBA parameters)
- econ_006 (shadow prices)

**Key concepts:**
- Változatlan ár (Constant price)
- Folyó ár (Current price)
- Relatív árváltozás

---

### meth_004: CBA Parameters
**File:** `02_methodology/004_cba_parameters.md`  
**Title:** CBA paraméterek (Discount Rates, GDP, Time Horizon)  
**Pages:** 15-16

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)

**Required by:**
- econ_008 (performance indicators)
- fin_005 (financial performance indicators)
- risk_001 (sensitivity analysis)

**Related to:**
- meth_003 (price level)
- econ_005 (full CBA)

**Key parameters:**
- Közgazdasági diszkontráta: 3%
- Pénzügyi diszkontráta: változó
- Vizsgált időtáv: max 30 év

---

### meth_005: Institutional Framework
**File:** `02_methodology/005_institutional_framework.md`  
**Title:** Intézményi keret (CPR Article 65)  
**Pages:** 13-14

**Depends on:**
- core_001 (evaluation purpose)

**Required by:**
- fin_002 (project types and support)
- fin_004 (project type determination)

**Related to:**
- meth_006 (consolidated approach)
- fin_001 (financial analysis purpose)

**Key concepts:**
- Tulajdonos, üzemeltető, fenntartó
- Közszolgáltatási szerződés
- Jogi monopólium

---

### meth_006: Consolidated Approach
**File:** `02_methodology/006_consolidated_approach.md`  
**Title:** Konszolidált megközelítés  
**Pages:** 14

**Depends on:**
- meth_005 (institutional framework)

**Required by:**
- fin_001 (financial analysis purpose)
- fin_006 (comprehensive financial analysis)

**Related to:**
- meth_001 (differential method)
- fin_005 (financial performance)

**Key concepts:**
- Konszolidált elemzés
- Tulajdonos-üzemeltető kapcsolat
- Pénzmozgások kiszűrése

---

### meth_007: Amortization Treatment
**File:** `02_methodology/007_amortization_treatment.md`  
**Title:** Amortizáció kezelése  
**Pages:** 14

**Depends on:**
- meth_001 (differential method)
- meth_002 (without-project scenario)

**Required by:**
- econ_005 (full CBA methodology)
- fin_006 (comprehensive financial analysis)

**Related to:**
- meth_003 (price level)
- fin_005 (financial performance)

**Key concepts:**
- Amortizáció vs. eszközpótlás
- Felhalmozott amortizáció
- Maradványérték számítás

---

### meth_008: Impact Area and Stakeholders
**File:** `02_methodology/008_impact_area_and_stakeholders.md`  
**Title:** Hatásterület és érintettek  
**Pages:** 12, 14-15

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)

**Required by:**
- econ_003 (needs assessment)
- econ_007 (economic benefits calculation)

**Related to:**
- econ_001 (economic analysis steps)
- example_001 (practical examples)

**Key concepts:**
- Hatásterület meghatározása
- Érintett szereplők
- Elosztási hatások

---

## 3. Economic Analysis (03_economic_analysis/)

### econ_001: Economic Analysis Steps
**File:** `03_economic_analysis/001_economic_analysis_steps.md`  
**Title:** Közgazdasági elemzés lépései  
**Pages:** 17-19

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)
- meth_002 (without-project scenario)

**Required by:**
- econ_002 (project size requirements)
- econ_003 (needs assessment)
- econ_004 (alternative evaluation)

**Related to:**
- All economic analysis objects
- fin_001 (financial analysis purpose)

**Key steps:**
1. Igényfelmérés
2. Változatelemzés
3. Költségek és hasznok számszerűsítése
4. Teljesítménymutatók számítása

---

### econ_002: Project Size and Requirements
**File:** `03_economic_analysis/002_project_size_and_requirements.md`  
**Title:** Projektméret és követelmények  
**Pages:** 19-20

**Depends on:**
- econ_001 (economic analysis steps)

**Required by:**
- econ_003 (needs assessment)
- econ_004 (alternative evaluation)
- econ_005 (full CBA methodology)

**Related to:**
- fin_002 (project types)

**Key thresholds:**
- < 1 M EUR: Egyszerűsített
- 1-10 M EUR: Közepes
- 10-50 M EUR: Részletes
- > 50 M EUR: Teljes körű

---

### econ_003: Needs Assessment Requirements
**File:** `03_economic_analysis/003_needs_assessment_requirements.md`  
**Title:** Igényfelmérés követelményei  
**Pages:** 20-23

**Depends on:**
- econ_001 (economic analysis steps)
- econ_002 (project size requirements)
- meth_008 (impact area and stakeholders)

**Required by:**
- econ_004 (alternative evaluation)
- example_001 (practical examples)

**Related to:**
- meth_002 (without-project scenario)

**Key elements:**
- Jelenlegi helyzet bemutatása
- Problémák azonosítása
- Fejlesztési szükséglet megalapozása

---

### econ_004: Alternative Evaluation Methods
**File:** `03_economic_analysis/004_alternative_evaluation_methods.md`  
**Title:** Alternatív értékelési módszerek (CEA, LCA, MCA)  
**Pages:** 27-31

**Depends on:**
- econ_001 (economic analysis steps)
- econ_003 (needs assessment)

**Required by:**
- example_001 (practical examples - MCA)

**Related to:**
- econ_005 (full CBA methodology)
- econ_008 (performance indicators)

**Methods:**
- CEA: Cost-Effectiveness Analysis
- LCA: Least-Cost Analysis
- MCA: Multi-Criteria Analysis

---

### econ_005: Full CBA Methodology
**File:** `03_economic_analysis/005_full_cba_methodology.md`  
**Title:** Teljes CBA módszertan (Fiskális korrekciók)  
**Pages:** 32-33

**Depends on:**
- econ_001 (economic analysis steps)
- econ_002 (project size requirements)
- meth_003 (price level)
- meth_007 (amortization)

**Required by:**
- econ_006 (shadow prices)
- econ_007 (economic benefits)
- econ_008 (performance indicators)

**Related to:**
- fin_005 (financial performance)

**Key concepts:**
- ÁFA korrekció (mindig kötelező)
- Támogatások kezelése
- Fiskális korrekciók

---

### econ_006: Shadow Prices
**File:** `03_economic_analysis/006_shadow_prices.md`  
**Title:** Árnyékárak és konverziós faktorok  
**Pages:** 33-35

**Depends on:**
- econ_005 (full CBA methodology)
- meth_003 (price level)

**Required by:**
- econ_007 (economic benefits calculation)
- econ_008 (performance indicators)

**Related to:**
- meth_004 (CBA parameters)

**Key conversion factors:**
- Munkaerő: Piaci bér × (1 - α × Munkanélküliségi ráta)
- Energia: Változó
- Föld: Változó
- CO₂: Változó

---

### econ_007: Economic Benefits Calculation
**File:** `03_economic_analysis/007_economic_benefits_calculation.md`  
**Title:** Közgazdasági hasznok számítása  
**Pages:** 35-36

**Depends on:**
- econ_005 (full CBA methodology)
- econ_006 (shadow prices)
- meth_008 (impact area and stakeholders)

**Required by:**
- econ_008 (performance indicators)

**Related to:**
- fin_006 (revenue estimation)

**Benefit categories:**
- Közvetlen hasznok
- Közvetett hasznok
- Externáliák

---

### econ_008: Performance Indicators
**File:** `03_economic_analysis/008_performance_indicators.md`  
**Title:** Teljesítménymutatók (ENPV, ERR, BCR)  
**Pages:** 36-37

**Depends on:**
- econ_005 (full CBA methodology)
- econ_006 (shadow prices)
- econ_007 (economic benefits)
- meth_004 (CBA parameters)

**Required by:**
- risk_001 (sensitivity analysis)

**Related to:**
- fin_005 (financial performance indicators)

**Key indicators:**
- ENPV = Σ[Xt/(1+0.03)^t]
- ERR: ahol ENPV = 0
- BCR = PV(Hasznok) / PV(Költségek)

**Támogathatósági kritériumok:**
- ENPV > 0
- ERR > 3%
- BCR > 1

---

### econ_009: Sector-Specific Guidance
**File:** `03_economic_analysis/009_sector_specific_guidance.md`  
**Title:** Ágazat-specifikus útmutatók  
**Pages:** 38-55

**Depends on:**
- econ_001 - econ_008 (all economic analysis)

**Required by:**
- example_001 (practical examples)

**Related to:**
- All methodology and economic analysis objects

**Sectors covered:**
1. Közlekedés (Transport)
2. Környezetvédelem (Environment)
3. Egészségügy (Health)
4. Hulladékgazdálkodás (Waste)
5. Energetika (Energy)
6. Turizmus (Tourism)
7. Egyéb ágazatok (Other)

---

## 4. Financial Analysis (04_financial_analysis/)

### fin_001: Financial Analysis Purpose
**File:** `04_financial_analysis/001_financial_analysis_purpose.md`  
**Title:** Pénzügyi elemzés célja  
**Pages:** 56-57

**Depends on:**
- core_001 (evaluation purpose)
- meth_001 (differential method)
- meth_005 (institutional framework)
- meth_006 (consolidated approach)

**Required by:**
- fin_002 (project types)
- fin_003 (financial milestones)
- fin_004 (project type determination)

**Related to:**
- econ_001 (economic analysis steps)

**Key purposes:**
- Pénzügyi fenntarthatóság
- Támogatási jogcím meghatározása
- Bevételtermelő képesség értékelése

---

### fin_002: Project Types and Support
**File:** `04_financial_analysis/002_project_types_and_support.md`  
**Title:** Projekttípusok és támogatási sémák  
**Pages:** 57-58

**Depends on:**
- fin_001 (financial analysis purpose)
- meth_005 (institutional framework)

**Required by:**
- fin_004 (project type determination)
- fin_006 (comprehensive financial analysis)

**Related to:**
- econ_002 (project size)

**Project types:**
- A1: Nem állami támogatás + PF max
- A2: Nem állami támogatás + finanszírozási rés
- B1: Állami támogatás + PF max
- B2: Állami támogatás + nettó bevétel levonás
- C: Vegyes projekt

---

### fin_003: Financial Analysis Milestones
**File:** `04_financial_analysis/003_financial_analysis_milestones.md`  
**Title:** Pénzügyi elemzés mérföldkövei  
**Pages:** 58-59

**Depends on:**
- fin_001 (financial analysis purpose)
- fin_002 (project types)

**Required by:**
- fin_004 (project type determination)
- fin_005 (financial performance)
- fin_006 (comprehensive financial analysis)

**Related to:**
- econ_001 (economic analysis steps)

**Key milestones:**
1. Projekttípus meghatározása
2. Költségek és bevételek becslése
3. Teljesítménymutatók számítása
4. Támogatás számítása
5. Pénzügyi fenntarthatóság értékelése

---

### fin_004: Project Type Determination
**File:** `04_financial_analysis/004_project_type_determination.md`  
**Title:** Projekttípus meghatározása (5 lépéses folyamat)  
**Pages:** 57-58

**Depends on:**
- fin_001 (financial analysis purpose)
- fin_002 (project types)
- fin_003 (financial milestones)
- meth_005 (institutional framework)

**Required by:**
- fin_005 (financial performance)
- fin_006 (comprehensive financial analysis)

**Related to:**
- econ_002 (project size)

**5-step process:**
1. Állami támogatás meghatározása
2. Támogatási séma kiválasztása
3. Paraméterek meghatározása
4. Nettó bevétel meghatározása
5. Számítási módszer kiválasztása

---

### fin_005: Financial Performance Indicators
**File:** `04_financial_analysis/005_financial_performance_indicators.md`  
**Title:** Pénzügyi teljesítménymutatók (FNPV, FRR)  
**Pages:** 59-60

**Depends on:**
- fin_001 (financial analysis purpose)
- fin_004 (project type determination)
- meth_003 (price level)
- meth_004 (CBA parameters)

**Required by:**
- fin_006 (comprehensive financial analysis)
- risk_001 (sensitivity analysis)

**Related to:**
- econ_008 (economic performance indicators)

**Key indicators:**
- FNPV = Σ[Xt/(1+i)^t]
- FRR: ahol FNPV = 0

**Támogathatósági kritérium (kohéziós politika):**
- FNPV(C) < 0

---

### fin_006: Comprehensive Financial Analysis
**File:** `04_financial_analysis/006_financial_analysis_comprehensive.md`  
**Title:** Átfogó pénzügyi elemzés  
**Pages:** 60-68

**Depends on:**
- All previous financial analysis objects (fin_001 - fin_005)
- meth_006 (consolidated approach)
- meth_007 (amortization)

**Required by:**
- risk_001 (sensitivity analysis)

**Related to:**
- econ_007 (economic benefits)

**Key components:**
- Maradványérték számítás
- Bevételbecslés
- Támogatás számítás
- Pénzügyi fenntarthatóság
- Excel sablon használata

---

## 5. Risk Analysis (05_risk_analysis/)

### risk_001: Sensitivity and Risk Analysis
**File:** `05_risk_analysis/001_sensitivity_and_risk_analysis.md`  
**Title:** Érzékenység- és kockázatelemzés  
**Pages:** 69-76

**Depends on:**
- econ_008 (economic performance indicators)
- fin_005 (financial performance indicators)
- meth_004 (CBA parameters)

**Required by:**
- None (final analysis step)

**Related to:**
- All economic and financial analysis objects

**Key components:**
- Érzékenységvizsgálat
- Kritikus változók azonosítása
- Váltási értékek
- Forgatókönyv-elemzés
- Kvalitatív kockázatelemzés
- Kockázati mátrix (5×5)
- Kockázatkezelési stratégiák
- Klímakockázatok integrálása

---

## 6. Practical Examples (06_practical_examples/)

### example_001: Bicycle Path and Stormwater Examples
**File:** `06_practical_examples/001_bicycle_path_and_stormwater_examples.md`  
**Title:** Gyakorlati példák - Kerékpárút és csapadékvíz  
**Pages:** 77-80

**Depends on:**
- econ_003 (needs assessment)
- econ_004 (alternative evaluation - MCA)
- econ_009 (sector-specific guidance)

**Required by:**
- None (illustrative examples)

**Related to:**
- All methodology and economic analysis objects

**Examples:**
1. Kerékpárút építés (stratégiai illeszkedés)
2. Csapadékvíz elvezetés (MCA alkalmazás)

---

## 7. Glossary (09_glossary/)

### glossary_001: Core Terminology
**File:** `09_glossary/001_core_terminology.md`  
**Title:** Alapfogalmak - Core Terminology  
**Pages:** Various

**Depends on:**
- All knowledge objects (terms extracted from all)

**Required by:**
- All knowledge objects (terminology reference)

**Related to:**
- All domains

**Content:**
- 105+ bilingual terms (Hungarian-English)
- 20 thematic categories (A-T)
- Source references for all terms
- Formulas and definitions

---

## 8. Supporting Documents

### Document Analysis
**File:** `00_DOCUMENT_ANALYSIS.md`  
**Title:** TOP PLUSZ KPÚ Document Analysis  
**Pages:** 1-97

**Depends on:**
- None (source document analysis)

**Required by:**
- All knowledge objects (source reference)

**Content:**
- Document structure
- Table of contents
- Chapter summaries
- Extraction strategy

---

## Dependency Graph

### Level 0 (Foundation)
- core_001: Purpose of Evaluation
- 00_DOCUMENT_ANALYSIS.md

### Level 1 (Core Methodology)
- meth_001: Differential Method
- meth_002: Without-Project Scenario
- meth_003: Price Level and Inflation
- meth_004: CBA Parameters
- meth_005: Institutional Framework
- meth_008: Impact Area and Stakeholders

### Level 2 (Advanced Methodology)
- meth_006: Consolidated Approach
- meth_007: Amortization Treatment

### Level 3 (Economic Analysis Foundation)
- econ_001: Economic Analysis Steps
- econ_002: Project Size and Requirements
- fin_001: Financial Analysis Purpose

### Level 4 (Detailed Analysis)
- econ_003: Needs Assessment
- econ_004: Alternative Evaluation
- fin_002: Project Types
- fin_003: Financial Milestones

### Level 5 (Technical Analysis)
- econ_005: Full CBA Methodology
- fin_004: Project Type Determination

### Level 6 (Calculations)
- econ_006: Shadow Prices
- econ_007: Economic Benefits
- fin_005: Financial Performance

### Level 7 (Performance & Synthesis)
- econ_008: Performance Indicators
- fin_006: Comprehensive Financial Analysis

### Level 8 (Risk & Validation)
- risk_001: Sensitivity and Risk Analysis

### Level 9 (Sector-Specific & Examples)
- econ_009: Sector-Specific Guidance
- example_001: Practical Examples

### Cross-Cutting (All Levels)
- glossary_001: Core Terminology

---

## Usage Patterns

### For Project Preparation
**Sequence:**
1. core_001 → meth_001 → meth_002
2. econ_001 → econ_002 → econ_003
3. econ_004 (if needed)
4. econ_005 → econ_006 → econ_007 → econ_008
5. fin_001 → fin_002 → fin_003 → fin_004
6. fin_005 → fin_006
7. risk_001

### For Economic Analysis Only
**Sequence:**
1. core_001 → meth_001 → meth_002 → meth_003 → meth_004
2. econ_001 → econ_002 → econ_003
3. econ_005 → econ_006 → econ_007 → econ_008
4. risk_001 (sensitivity only)

### For Financial Analysis Only
**Sequence:**
1. core_001 → meth_001 → meth_005 → meth_006
2. fin_001 → fin_002 → fin_003 → fin_004
3. fin_005 → fin_006
4. risk_001 (sensitivity only)

### For Alternative Evaluation
**Sequence:**
1. core_001 → meth_001 → meth_002
2. econ_001 → econ_002 → econ_003
3. econ_004 (CEA, LCA, or MCA)
4. example_001 (for MCA example)

### For Sector-Specific Guidance
**Sequence:**
1. core_001 → meth_001 → meth_002
2. econ_001 → econ_002
3. econ_009 (sector-specific)
4. example_001 (if applicable)

---

## AI Agent Retrieval Patterns

### Query: "How to calculate ENPV?"
**Retrieve:**
1. econ_008 (performance indicators - primary)
2. meth_004 (CBA parameters - discount rate)
3. econ_005 (full CBA methodology - fiscal corrections)
4. econ_006 (shadow prices - if needed)
5. glossary_001 (ENPV definition)

### Query: "What is the project type determination process?"
**Retrieve:**
1. fin_004 (project type determination - primary)
2. fin_002 (project types and support)
3. meth_005 (institutional framework)
4. glossary_001 (project type definitions)

### Query: "How to perform sensitivity analysis?"
**Retrieve:**
1. risk_001 (sensitivity and risk analysis - primary)
2. econ_008 (performance indicators - ENPV, ERR, BCR)
3. fin_005 (financial performance - FNPV, FRR)
4. meth_004 (CBA parameters)
5. glossary_001 (sensitivity terms)

### Query: "What are shadow prices and how to use them?"
**Retrieve:**
1. econ_006 (shadow prices - primary)
2. econ_005 (full CBA methodology - context)
3. meth_003 (price level treatment)
4. glossary_001 (shadow price definition)

### Query: "How to assess financial sustainability?"
**Retrieve:**
1. fin_006 (comprehensive financial analysis - primary)
2. fin_005 (financial performance indicators)
3. meth_006 (consolidated approach)
4. meth_007 (amortization treatment)
5. glossary_001 (financial sustainability)

---

## Validation Checklist

### Metadata Completeness
- ✅ All 28 knowledge objects have complete YAML front matter
- ✅ All have source document references
- ✅ All have page numbers
- ✅ All have domain/subdomain classification
- ✅ All have status and confidence levels

### Traceability
- ✅ Every knowledge object links to source pages
- ✅ Dependencies are documented
- ✅ Related objects are cross-referenced
- ✅ Glossary terms are source-referenced

### Completeness
- ✅ All 6 main chapters covered
- ✅ All methodology requirements documented
- ✅ All economic analysis steps covered
- ✅ All financial analysis components included
- ✅ Risk analysis fully documented
- ✅ Practical examples provided
- ✅ 105+ glossary terms documented

---

## Statistics

**Total Knowledge Objects:** 28
**Total Glossary Terms:** 105+
**Total Pages Covered:** 97
**Total Lines of Content:** ~11,200
**Cross-References:** 200+
**Dependency Levels:** 9

**Coverage by Chapter:**
- Chapter 1: 100% (1 object)
- Chapter 2: 100% (8 objects)
- Chapter 3: 100% (9 objects)
- Chapter 4: 100% (6 objects)
- Chapter 5: 100% (1 object)
- Chapter 6: 100% (1 object)

---

**Prepared by:** Bob (AI Knowledge Engineer)  
**Date:** 2026-04-01  
**Version:** 1.0  
**Status:** Complete