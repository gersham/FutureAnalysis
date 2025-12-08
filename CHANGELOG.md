---
title: "Changelog"
type: changelog
last_updated: 2025-12-08
---

# Changelog

Track of updates, revisions, and prediction status changes.

---

## 2025-12-08: Complete Repository Restructuring

### Changed
- Converted all README.md files from table-based format to essay-style syntheses
- Each country README now reads as analytical essay linking to data/trends/analysis
- Added YAML frontmatter to all new files with title, type, tags, dates

### Added
- Complete data/, trends/, analysis/ structure for all 14 countries:
  - **North America**: United States, Canada
  - **Europe**: United Kingdom, Germany, France, Poland, Ireland, Switzerland
  - **Asia-Pacific**: China, Japan, Singapore, Australia

- Country data files created:
  - data-center-capacity.md, economic-structure.md, energy-crisis.md
  - public-sector-exposure.md, nuclear-energy.md, resource-endowment.md
  - financial-services-exposure.md, stability-record.md, etc.

- Country trend files created:
  - manufacturing-decline.md, political-realignment.md, services-collapse.md
  - demographic-fractures.md, legitimacy-fracture.md, state-capital-fusion.md
  - private-banking-decline.md, technocratic-adaptation.md, etc.

- Country analysis files created:
  - outlook.md (predictions by period with falsifiable criteria)
  - actionable-implications.md (strategic considerations)

### Updated
- Regional README.md files now essay-style syntheses
- CLAUDE.md updated with frontmatter standard and content model documentation
- Root README.md unchanged (already contains full essay)

---

## 2025-12-08: Scenario + Synthesis Standardization Pass

### Changed
- Adopted 5%/year net displacement as explicit scenario premise across Methodology and synthesis docs (no numeric GDP projections).
- Replaced numeric GDP projections with qualitative growth outlooks (High/Moderate/Low/Negative/Uncertain) across country/region pages.
- Rebalanced emphasis away from compute/energy as sole drivers; reinforced factor bundle (compute, energy, regulation, capital, talent, culture).
- Tone pass for neutrality (e.g., removed "regulatory suicide" phrasing).

### Fixed
- Datacenter capacity discrepancies: standardized on canonical values in `global/data/data-center-capacity.md` (e.g., US 2030 = 132 GW). Updated references in trends/analysis/country data.
- Frontmatter: added `type: synthesis`, `growth_outlook`, and standardized keys on key synthesis pages (global, US, UK, Germany, France, Poland, Canada, Australia, and others).
- Broken/fragile links reduced by pointing to canonical data files instead of duplicating numbers.

### Notes
- Some remaining country pages already followed the standard; others were updated in this pass to align with qualitative outlooks and frontmatter.

## 2025-12-07: Initial Repository Creation

### Added
- Repository structure with global, regional, and country levels
- Root README.md with "The Fracturing" essay as global synthesis
- METHODOLOGY.md documenting analytical framework
- CLAUDE.md with agent instructions
- Global data/, trends/, analysis/ structure

### Content Extracted from Source Essay
- Global trends: AI displacement, robotics wave, energy/data centers, cultural adoption, financial services disruption, legitimacy crisis
- 14 country profiles created
- 3 regional syntheses: North America, Europe, Asia-Pacific

### Initial Predictions
All predictions dated 2025-12-07, status: active

---

## Format for Future Entries

```markdown
## YYYY-MM-DD: Brief Description

### Added
- New data/trends/analysis files

### Changed
- Updated predictions with reasoning

### Prediction Status Updates
- [Country/Prediction]: Status changed from X to Y
  - Reason: [Evidence or reasoning]
```

---

*Maintained as part of prediction tracking system.*
