---
id: kb_readme_001
title: TOP PLUSZ KPÚ Knowledge Library
version: 1.0.0
created: 2026-04-01
language: hu
status: in_development
---

# TOP PLUSZ Közgazdasági és Pénzügyi Útmutató - Knowledge Library

## Áttekintés / Overview

Ez a tudásbázis a TOP Plusz operatív program közgazdasági és pénzügyi elemzési módszertani útmutatójának strukturált, újrafelhasználható tudáselemekre bontott változata.

This knowledge library is a structured, reusable transformation of the TOP Plusz operational program's economic and financial analysis methodology guidance.

## Célok / Objectives

1. **Forrás hűség** - Preserve source accuracy
2. **Gépi feldolgozhatóság** - Enable AI/agent processing
3. **Moduláris felépítés** - Modular, reusable content
4. **Nyomon követhetőség** - Full traceability to source
5. **Egyértelmű jelölések** - Clear ambiguity marking

## Könyvtárstruktúra / Directory Structure

### 01_core_concepts/
Alapfogalmak, definíciók, alapelvek
- Core concepts, definitions, principles
- Differential method, baseline scenarios
- Key terminology and frameworks

### 02_methodology/
Módszertani alapok és közös követelmények
- Common methodological requirements
- Parameters and assumptions
- Analytical frameworks

### 03_economic_analysis/
Közgazdasági elemzés módszertana
- Economic analysis steps and requirements
- CBA, CEA, LCA, MCA methodologies
- Economic cost and benefit estimation
- Performance indicators

### 04_financial_analysis/
Pénzügyi elemzés módszertana
- Financial analysis requirements
- Cost estimation (investment, operating)
- Revenue projections
- Financial sustainability
- Support amount calculation

### 05_risk_analysis/
Kockázat- és érzékenységelemzés
- Sensitivity analysis
- Risk identification and assessment
- Risk management strategies

### 06_sector_specific/
Ágazat-specifikus útmutatók
- Transport
- Environmental management
- Healthcare
- Waste management
- Energy efficiency
- Renewable energy
- Tourism

### 07_processes/
Folyamatok és döntési fák
- Process flows
- Decision trees
- Milestone integration
- Project lifecycle alignment

### 08_templates/
Sablonok és eszközök
- Excel template documentation
- Calculation frameworks
- Checklists

### 09_glossary/
Fogalomtár és terminológia
- Hungarian-English terminology
- Controlled vocabulary
- Concept relationships
- Aliases and synonyms

### 10_examples/
Példák és esettanulmányok
- Good practice examples
- Case studies by sector
- Alternative analysis examples

## Metaadat Séma / Metadata Schema

Minden tudáselem tartalmazza:
Every knowledge object contains:

```yaml
id: <unique_identifier>
title: <descriptive_title>
source_document: TOP PLUSZ KPÚ
source_section: <section_reference>
source_page: <page_number>
domain: <primary_domain>
subdomain: <specific_area>
language: hu
status: draft|validated|needs_review
confidence: high|medium|low
tags:
  - TOP_PLUSZ
  - <domain_tags>
related_ids:
  - <linked_knowledge_objects>
```

## Használati Útmutató / Usage Guide

### Emberi felhasználók számára / For Human Users
- Navigálj a domain könyvtárak között
- Használd a kereszthivatkozásokat
- Ellenőrizd a forrás referenciákat

### AI ágensek számára / For AI Agents
- Parse YAML front matter for metadata
- Follow related_ids for context
- Check confidence levels for reliability
- Use tags for retrieval filtering

## Státusz Jelölések / Status Markers

- ✅ **Validated**: Ellenőrzött, megbízható
- 🔄 **Draft**: Vázlat, fejlesztés alatt
- ⚠️ **Needs Review**: Felülvizsgálat szükséges
- ❓ **Ambiguous**: Értelmezést igényel
- 🔗 **Cross-reference**: Kapcsolódó tartalom

## Verziókezelés / Version Control

- **v1.0.0** - Initial knowledge library structure
- Minden változás dokumentált
- Forrás nyomon követhetőség megőrzött

## Kapcsolat / Contact

Ez a tudásbázis a TOP Plusz program hivatalos útmutatójának feldolgozása.
Hivatalos forrás: TOP PLUSZ KPÚ (2025. június)

---

**Utolsó frissítés / Last Updated**: 2026-04-01
**Dokumentum állapot / Document Status**: In Development