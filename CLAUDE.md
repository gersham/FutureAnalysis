# Claude Agent Instructions

This repository contains structured predictions and analysis for the decade 2026-2036. The content is organized to support both human reading and machine-assisted analysis.

## Purpose

Personal edification and planning. Actionable predictions organized by region and country with inherited context flowing from global → regional → country levels. Each `index.md` is an **essay-style synthesis** of its underlying data, trends, and analysis.

## Epistemic Status

**This is a scenario exercise, not a forecast.** See [METHODOLOGY.md](METHODOLOGY.md) for explicit assumptions, displacement model, factor weights, and what would change our mind. The confident prose is rhetorical—useful for planning, not a claim to know the future.

## Repository Structure

```
/README.md                          # GitHub landing page (links to site)
/index.md                           # Main thesis essay ("The Fracturing")
/METHODOLOGY.md                     # Analytical framework, assumptions, model
/CHANGELOG.md                       # Update tracking
/CLAUDE.md                          # This file - agent instructions
/AGENTS.md                          # Points agents to this file
/global/
    index.md                        # Global synthesis
    data/                           # Known facts today
    trends/                         # Observable patterns
    analysis/                       # Suppositions and predictions
/regions/{region}/
    index.md                        # Regional essay synthesis
    {country}/
        index.md                    # Country essay synthesis
        data/                       # Country-specific data
        trends/                     # Country-specific trends
        analysis/                   # Country-specific analysis
```

**Live site**: https://gersham.github.io/FutureAnalysis/

## Content Model

### Three Layers

| Layer | Contains | Example Files |
|-------|----------|---------------|
| **data/** | Known facts, current metrics, statistics | `data-center-capacity.md`, `economic-structure.md` |
| **trends/** | Observable patterns, trajectories in motion | `call-center-collapse.md`, `software-development-automation.md` |
| **analysis/** | Suppositions, predictions, implications | `outlook.md`, `actionable-implications.md` |

### index.md Role

Each `index.md` is the **substantive essay synthesis** for that level:
- Links to underlying data/, trends/, analysis/ files
- Written in analytical essay format
- Frontmatter with title, type: synthesis, region/country, outlook, growth_outlook (qualitative), confidence, tags, last_updated

## Countries Covered (38)

| Region | Countries | Outlook |
|--------|-----------|---------|
| **North America** | [United States](regions/north-america/united-states/) | Winner |
| | [Canada](regions/north-america/canada/) | Restructured |
| | [Mexico](regions/north-america/mexico/) | Contested |
| **Europe** | [United Kingdom](regions/europe/united-kingdom/) | Fracturing |
| | [Germany](regions/europe/germany/) | Declining |
| | [France](regions/europe/france/) | Fracturing |
| | [Poland](regions/europe/poland/) | Winner |
| | [Ireland](regions/europe/ireland/) | Contested |
| | [Switzerland](regions/europe/switzerland/) | Declining |
| | [Netherlands](regions/europe/netherlands/) | Survivor |
| | [Russia](regions/europe/russia/) | Declining |
| | [Italy](regions/europe/italy/) | Declining |
| | [Spain](regions/europe/spain/) | Survivor |
| | [Portugal](regions/europe/portugal/) | Survivor |
| | [Turkey](regions/europe/turkey/) | Contested |
| **Asia-Pacific** | [China](regions/asia-pacific/china/) | Winner |
| | [India](regions/asia-pacific/india/) | Contested |
| | [Japan](regions/asia-pacific/japan/) | Survivor |
| | [Taiwan](regions/asia-pacific/taiwan/) | Contested |
| | [Singapore](regions/asia-pacific/singapore/) | Survivor |
| | [Australia](regions/asia-pacific/australia/) | Winner (Contingent) |
| | [South Korea](regions/asia-pacific/south-korea/) | Survivor |
| | [Indonesia](regions/asia-pacific/indonesia/) | Survivor |
| | [Vietnam](regions/asia-pacific/vietnam/) | Contested |
| | [Malaysia](regions/asia-pacific/malaysia/) | Contested |
| | [Philippines](regions/asia-pacific/philippines/) | Declining |
| | [Thailand](regions/asia-pacific/thailand/) | Contested |
| | [Pakistan](regions/asia-pacific/pakistan/) | Declining |
| **Middle East** | [Saudi Arabia](regions/middle-east/saudi-arabia/) | Winner |
| | [UAE](regions/middle-east/uae/) | Winner |
| | [Israel](regions/middle-east/israel/) | Survivor (War-contingent) |
| | [Egypt](regions/middle-east/egypt/) | Declining |
| | [Iran](regions/middle-east/iran/) | Collapsing |
| **Africa** | [Nigeria](regions/africa/nigeria/) | Declining |
| | [South Africa](regions/africa/south-africa/) | Declining |
| **South America** | [Brazil](regions/south-america/brazil/) | Survivor |
| | [Argentina](regions/south-america/argentina/) | Restructuring |
| | [Venezuela](regions/south-america/venezuela/) | Collapsing |

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
| [index.md](index.md) | Main thesis essay |
| [METHODOLOGY.md](METHODOLOGY.md) | Explicit assumptions, displacement model, factor weights, scenario structure |
| [UK Example](regions/europe/united-kingdom/) | Fully worked example showing methodology applied to a specific country |

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
- `index.md` files are substantive essays, not navigation pages
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
4. Update index.md synthesis at affected levels
5. Record change in CHANGELOG.md

## Checkpoint Process

When significant events occur that may validate or invalidate the thesis, run a **checkpoint analysis**:

### 1. Identify the Signal

- What happened? (Be specific: document, statement, event, data release)
- Source quality? (Official document > credible reporting > rumour)
- Date and verification status

### 2. Map to Thesis Claims

For each relevant thesis claim:
- What did we predict?
- What does this signal suggest?
- Alignment: Strong / Moderate / Weak / Contradictory

### 3. Rate the Checkpoint (1-10)

| Dimension | Weight | Question |
|-----------|--------|----------|
| **Directional alignment** | 25% | Does signal move in predicted direction? |
| **Mechanism match** | 25% | Does the *why* match our reasoning, not just the *what*? |
| **Timeline fit** | 15% | Is timing consistent with forecast window? |
| **Specificity** | 20% | How concrete/verified is the signal? |
| **Falsification risk** | 15% | Could this reverse or be walked back? |

**Score interpretation:**
- 8-10: Strong validation—consider upgrading confidence
- 5-7: Partial validation—meaningful signal, watch for confirmation
- 3-4: Weak signal—note but don't adjust
- 1-2: Noise or contradictory—investigate potential invalidation

### 4. Update Repository

**For validating signals:**
- Add to relevant `trends/` file with checkpoint section
- Update `CHANGELOG.md` with checkpoint entry
- Note what would upgrade to full validation
- Note what would invalidate

**For invalidating signals:**
- Document the contradiction
- Assess whether to revise prediction or wait for more data
- If revising: update outlook, confidence, and reasoning
- Record in CHANGELOG.md with "Prediction Status Update"

### 5. Set Tracking Indicators

Define specific signals to watch for:
- **Confirming signals**: What would strengthen the checkpoint?
- **Disconfirming signals**: What would weaken or reverse it?
- **Timeline**: When should we re-evaluate?

### Checkpoint Log

Major checkpoints are recorded in `CHANGELOG.md`. Current checkpoints:

| Date | Event | Rating | Status |
|------|-------|--------|--------|
| 2025-12-10 | US NSS spheres-of-influence language | 7/10 | Partial validation—tracking |

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

*Last updated: 2025-12-10*
