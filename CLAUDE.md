# Claude Agent Instructions

This repository contains structured predictions and analysis for the decade 2026-2036. The content is organized to support both human reading and machine-assisted analysis.

## Purpose

Personal edification and planning. Actionable predictions organized by region and country with inherited context flowing from global → regional → country levels. Each README.md is an **essay-style synthesis** of its underlying data, trends, and analysis.

## Epistemic Status

**This is a scenario exercise, not a forecast.** See [METHODOLOGY.md](METHODOLOGY.md) for explicit assumptions, displacement model, factor weights, and what would change our mind. The confident prose is rhetorical—useful for planning, not a claim to know the future.

## Repository Structure

```
/README.md                          # Root synthesis ("The Fracturing" as essay)
/METHODOLOGY.md                     # Analytical framework, assumptions, model
/CHANGELOG.md                       # Update tracking
/CLAUDE.md                          # This file - agent instructions
/AGENTS.md                          # Points agents to this file
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
| **trends/** | Observable patterns, trajectories in motion | `call-center-collapse.md`, `software-development-automation.md` |
| **analysis/** | Suppositions, predictions, implications | `outlook.md`, `actionable-implications.md` |

### README.md Role

Each README.md is the **substantive essay synthesis** for that level:
- Links to underlying data/, trends/, analysis/ files
- Written in analytical essay format
- Frontmatter with title, type: synthesis, region/country, outlook, growth_outlook (qualitative), confidence, tags, last_updated

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
| | [Vietnam](regions/asia-pacific/vietnam/README.md) | Contested |
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
| **Winner** | Capturing AI transition gains | US, China, Poland, UAE, Saudi Arabia, Australia |
| **Restructured/ing** | Gains but concentrated/unequal | Canada, Argentina |
| **Survivor** | Managing with stability; limited growth | Japan, Singapore, South Korea, Indonesia, Netherlands, Brazil, Spain, Portugal, Israel |
| **Declining** | Structural contraction but social stability | Germany, Switzerland, Russia, Italy, Philippines, Nigeria, Egypt, South Africa, Pakistan |
| **Fracturing** | Economic decline + social instability | UK, France |
| **Contested** | Genuinely uncertain; high variance | Ireland, India, Vietnam, Mexico, Taiwan, Malaysia, Turkey, Thailand |
| **Collapsing** | State failure or near-failure | Iran, Venezuela |

## Key Documents

| Document | Purpose |
|----------|---------|
| [README.md](README.md) | Main thesis essay |
| [METHODOLOGY.md](METHODOLOGY.md) | Explicit assumptions, displacement model, factor weights, scenario structure |
| [UK Example](regions/europe/united-kingdom/README.md) | Fully worked example showing methodology applied to a specific country |

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
- Analytical, measured
- Rhetorical confidence is for clarity, not epistemic certainty
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

1. **Check regional README**: Does the change affect regional dynamics?
2. **Check global README**: Does the change alter the global thesis or reveal a cross-regional pattern?

**Default**: Most country/regional changes do NOT require global updates.

### Data Freshness

Be skeptical of AI-related data more than 12 months old. The field moves fast; stale statistics may mislead.

## Key Metrics

| Metric | Significance |
|--------|--------------|
| Data Centre Capacity (GW) | One factor among several; see methodology |
| GDP Projections | Illustrative ranges, not econometric forecasts |
| Sector Displacement Rates | Vary dramatically; see methodology sector table |
| Energy Costs (relative) | Binding constraint for some archetypes |

---

*Last updated: 2025-12-08*
