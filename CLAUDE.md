---
title: "Claude Agent Instructions"
type: agent-instructions
last_updated: 2025-12-08
---

# Claude Agent Instructions

This repository contains structured predictions and analysis for the decade 2026-2036, derived from "The Fracturing" essay. The content is organized to support both human reading and machine-assisted analysis.

## Purpose

Personal edification and planning. Actionable predictions organized by region and country with inherited context flowing from global → regional → country levels. Each README.md is an **essay-style synthesis** of its underlying data, trends, and analysis.

## Repository Structure

```
/README.md                          # Root synthesis ("The Fracturing" as essay)
/METHODOLOGY.md                     # Analytical framework and assumptions
/CHANGELOG.md                       # Update tracking
/CLAUDE.md                          # This file - agent instructions
/global/
    README.md                       # Global synthesis
    data/                           # Known facts today
    trends/                         # Observable patterns
    analysis/                       # Suppositions and predictions
/regions/{region}/
    README.md                       # Regional essay synthesis
    {country}/
        README.md                   # Country essay synthesis
        data/                       # Country-specific data
        trends/                     # Country-specific trends
        analysis/                   # Country-specific analysis
```

## Content Model

### Three Layers

| Layer | Contains | Example Files |
|-------|----------|---------------|
| **data/** | Known facts, current metrics, statistics | `data-center-capacity.md`, `economic-structure.md` |
| **trends/** | Observable patterns, trajectories in motion | `manufacturing-decline.md`, `political-realignment.md` |
| **analysis/** | Suppositions, predictions, implications | `outlook.md`, `actionable-implications.md` |

### README.md Role

Each README.md is the **substantive essay synthesis** for that level:
- Links to underlying data/, trends/, analysis/ files
- Written in analytical essay format matching source material tone
- Frontmatter with title, outlook, GDP projection, tags, etc.

## Frontmatter Standard

All markdown files include YAML frontmatter:

```yaml
---
title: "Document Title"
type: data | trend | analysis | synthesis
country: country-name (if applicable)
region: region-name (if applicable)
outlook: Winner | Restructured | Survivor | Declining | Fracturing | Contested
gdp_projection: "+X% to +Y% annually" or "-X% to -Y% annually"
confidence: High | Moderate | Low
tags: [relevant, tags, here]
last_updated: YYYY-MM-DD
---
```

## Countries Covered (38)

| Region | Countries | Outlook |
|--------|-----------|---------|
| **North America** | [United States](regions/north-america/united-states/README.md) | Winner |
| | [Canada](regions/north-america/canada/README.md) | Restructured |
| | [Mexico](regions/north-america/mexico/README.md) | Contested |
| **Europe** | [United Kingdom](regions/europe/united-kingdom/README.md) | Fracturing |
| | [Germany](regions/europe/germany/README.md) | Declining |
| | [France](regions/europe/france/README.md) | Fracturing |
| | [Poland](regions/europe/poland/README.md) | Winner |
| | [Ireland](regions/europe/ireland/README.md) | Contested |
| | [Switzerland](regions/europe/switzerland/README.md) | Declining |
| | [Netherlands](regions/europe/netherlands/README.md) | Survivor |
| | [Russia](regions/europe/russia/README.md) | Declining |
| | [Italy](regions/europe/italy/README.md) | Declining |
| | [Spain](regions/europe/spain/README.md) | Survivor |
| | [Portugal](regions/europe/portugal/README.md) | Survivor |
| | [Turkey](regions/europe/turkey/README.md) | Contested |
| **Asia-Pacific** | [China](regions/asia-pacific/china/README.md) | Winner |
| | [India](regions/asia-pacific/india/README.md) | Contested |
| | [Japan](regions/asia-pacific/japan/README.md) | Survivor |
| | [Taiwan](regions/asia-pacific/taiwan/README.md) | Contested |
| | [Singapore](regions/asia-pacific/singapore/README.md) | Survivor |
| | [Australia](regions/asia-pacific/australia/README.md) | Winner (Contingent) |
| | [South Korea](regions/asia-pacific/south-korea/README.md) | Survivor |
| | [Indonesia](regions/asia-pacific/indonesia/README.md) | Survivor |
| | [Vietnam](regions/asia-pacific/vietnam/README.md) | Winner |
| | [Malaysia](regions/asia-pacific/malaysia/README.md) | Contested |
| | [Philippines](regions/asia-pacific/philippines/README.md) | Declining |
| | [Thailand](regions/asia-pacific/thailand/README.md) | Contested |
| | [Pakistan](regions/asia-pacific/pakistan/README.md) | Declining |
| **Middle East** | [Saudi Arabia](regions/middle-east/saudi-arabia/README.md) | Winner |
| | [UAE](regions/middle-east/uae/README.md) | Winner |
| | [Israel](regions/middle-east/israel/README.md) | Survivor (War-contingent) |
| | [Egypt](regions/middle-east/egypt/README.md) | Declining |
| | [Iran](regions/middle-east/iran/README.md) | Collapsing |
| **Africa** | [Nigeria](regions/africa/nigeria/README.md) | Declining |
| | [South Africa](regions/africa/south-africa/README.md) | Declining |
| **South America** | [Brazil](regions/south-america/brazil/README.md) | Survivor |
| | [Argentina](regions/south-america/argentina/README.md) | Restructuring |
| | [Venezuela](regions/south-america/venezuela/README.md) | Collapsing |

## Outlook Categories

| Category | Definition | Example |
|----------|------------|---------|
| **Winner** | Capturing AI transition gains | US, China, Poland, UAE, Saudi Arabia, Vietnam |
| **Restructured/ing** | Gains but concentrated/unequal | Canada, Argentina |
| **Survivor** | Managing with stability; limited growth | Japan, Singapore, South Korea, Indonesia, Netherlands, Brazil, Spain, Portugal, Israel |
| **Declining** | Structural contraction but social stability | Germany, Switzerland, Russia, Italy, Philippines, Nigeria, Egypt, South Africa, Pakistan |
| **Fracturing** | Economic decline + social instability | UK, France |
| **Contested** | Genuinely uncertain; high variance | Ireland, India, Mexico, Taiwan, Malaysia, Turkey, Thailand |
| **Collapsing** | State failure or near-failure | Iran, Venezuela |

## Prediction Format

### Timeframes
- **Near Term**: 2026-2028
- **Mid Term**: 2029-2032
- **Late Term**: 2033-2036

### Criteria
- Include falsifiable criteria with specific thresholds
- Example: "Manufacturing employment -10% from 2025" not "manufacturing declines"

### Confidence
- Note only when notably high or low
- Default assumption is moderate confidence

## Content Guidelines

### Tone
- Analytical, measured, matching source essay's style
- No sensationalism; present probabilities and reasoning
- Direct and clear

### Essay Format
- README.md files are substantive essays, not navigation pages
- Each paragraph links to relevant underlying files
- Synthesis flows: data → trends → analysis → implications

### Inheritance
- Global trends affect all regions/countries
- Regional dynamics affect countries within that region
- Country pages link back to inherited context

## Updating Content

1. Add evidence to appropriate `data/` folder
2. Update relevant `trends/` if patterns shift
3. Revise `analysis/` predictions as warranted
4. Update README.md synthesis at affected levels
5. Record change in CHANGELOG.md

### Bubble-Up Rule

**Changes must propagate upward when relevant.** After modifying country-level content:

1. **Check regional README**: Does the change affect regional dynamics or require mention in the regional synthesis?
2. **Check global README**: Does the change represent a pattern that applies beyond this region, or alter the global thesis?

Examples:
- A new country trend file (e.g., `trends/defence-dependency.md`) → update regional README to reference it
- A regional dynamic with global implications (e.g., a structural trap pattern appearing in multiple regions) → consider adding to global trends
- A country outlook change (e.g., "Declining" → "Fracturing") → update regional README table and potentially global summary

**Default**: Most country/regional changes do NOT require global updates. The global README captures macro-level dynamics; regional/country content elaborates. Only bubble up when the change alters the global thesis or reveals a cross-regional pattern.

## Key Metrics

| Metric | Significance |
|--------|--------------|
| Data Centre Capacity (GW) | Proxy for AI economic power |
| GDP Projections | Annual growth/contraction rates |
| AI Adoption Rates | Organisational and citizen-level |
| Financial Services Exposure | Vulnerability to automation |
| Energy Costs (relative) | Infrastructure competitiveness |

## Source Material

The root README.md contains the full synthesis derived from "The Fracturing" (2025). The original essay has been decomposed into the data/, trends/, and analysis/ structure throughout the repository.

---

*Last updated: 2025-12-08*
