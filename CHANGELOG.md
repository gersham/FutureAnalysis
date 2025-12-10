---
title: "Changelog"
type: changelog
last_updated: 2025-12-10
---

# Changelog

Track of updates, revisions, and prediction status changes.

---

## 2025-12-10: First Checkpoint — US Strategic Reorientation Signal

### Context
The December 2025 US National Security Strategy introduced explicit spheres-of-influence language. Defense One reported (December 9) on a leaked longer version proposing a "Core 5" (C5) forum of US, China, Russia, India, Japan—excluding Europe from top-tier governance.

### Assessment
**This represents the first external checkpoint partially validating the repository's thesis on European decline and US security umbrella fraying.** The shift from "wavering commitment" to "explicit spheres-of-influence framework" is significant if confirmed.

**Checkpoint Rating**: 7/10 (Partial Validation)

**Confidence**: Low-Moderate. Published NSS language is real; C5 proposal specifically comes from unverified leaked version.

### Framework Evolution: Geopolitical Weight as Distinct Axis

The C5 proposal revealed a blind spot in our methodology: we analyzed countries primarily through economic/AI-displacement lenses, but great power status operates on different criteria (nuclear arsenal, population mass, sphere control, alignment options).

**Key insight**: Economic trajectory and geopolitical weight are partially independent. Russia can be 31st in AI capability while holding the world's largest nuclear arsenal. India can face IT services collapse while being the indispensable swing vote between blocs.

**The C5 structure:**
- **US-Japan**: Western anchor
- **China-Russia**: Eurasian anchor (Russia as junior partner with nukes)
- **India**: The tiebreaker—only major power with genuine bloc choice

### Added
- `global/trends/us-strategic-reorientation.md` — Documents NSS signals and tracking indicators
- `regions/europe/trends/euro-fragmentation-risk.md` — TARGET2 mechanism, ECB dilemma, east-west divide
- European financial stress indicators to `global/data/current-indicators.md`
- **Assumption 4 to METHODOLOGY.md**: Geopolitical weight as distinct axis from economic trajectory

### Changed
- Updated `regions/europe/trends/defence-dependency.md` with December 2025 NSS checkpoint
- Updated Germany README with December 2024 PMI data (42.5) and AfD polling (25-26%)
- Updated France README with verified fiscal data (5.8% deficit, 116% debt, 80-90 bps OAT-Bund spread)
- Linked euro-fragmentation-risk.md from Europe regional README
- **Russia README**: Added dual outlook (Economic: Declining / Geopolitical: Elevated); nuclear factor analysis
- **India README**: Added dual outlook (Economic: Contested / Geopolitical: Elevated); tiebreaker analysis

### Tracking
Watch for confirming/disconfirming signals Q1-Q2 2026:
- C5 or similar forum announced
- NATO burden-sharing demands escalate
- US-Russia bilateral engagement on spheres
- India-US or India-China significant alignment shift
- Or: NSS walked back, NATO reaffirmed

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
