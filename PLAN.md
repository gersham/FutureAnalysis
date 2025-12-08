# FutureAnalysis Repository Plan

**Purpose**: Personal repository for tracking actionable predictions 2026-2036, organized by region and country. Plain markdown, GitHub-hosted.

**Audience**: Personal edification and planning. May share.

**Tone**: Analytical, matching the source essay.

---

## 1. Repository Structure

```
/
├── README.md                        # Global synthesis
├── METHODOLOGY.md                   # Analytical framework
├── CHANGELOG.md                     # Track updates over time
│
├── global/
│   ├── README.md                    # Global overview + links to trends
│   ├── data/                        # Evidence files (added over time)
│   └── trends/
│       ├── ai-displacement.md
│       ├── robotics-wave.md
│       ├── energy-and-data-centers.md
│       ├── cultural-adoption.md
│       ├── financial-services-disruption.md
│       └── legitimacy-crisis.md
│
├── regions/
│   ├── north-america/
│   │   ├── README.md                # Regional synthesis
│   │   ├── data/                    # Regional evidence
│   │   ├── united-states/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   └── canada/
│   │       ├── README.md
│   │       └── data/
│   │
│   ├── europe/                      # Includes EU discussion (EU integrated, not separate)
│   │   ├── README.md
│   │   ├── data/
│   │   ├── united-kingdom/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   ├── germany/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   ├── france/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   ├── ireland/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   ├── switzerland/
│   │   │   ├── README.md
│   │   │   └── data/
│   │   └── poland/
│   │       ├── README.md
│   │       └── data/
│   │
│   └── asia-pacific/
│       ├── README.md
│       ├── data/
│       ├── china/
│       │   ├── README.md
│       │   └── data/
│       ├── japan/
│       │   ├── README.md
│       │   └── data/
│       ├── singapore/
│       │   ├── README.md
│       │   └── data/
│       └── australia/
│           ├── README.md
│           └── data/
│
└── sources/
    └── the-fracturing-2025-2035.md  # Original essay (remove later)
```

## Key Decisions

- **14 countries** (from essay): US, Canada, UK, Germany, France, Ireland, Switzerland, Poland, China, Japan, Singapore, Australia
- **EU integrated** into Europe regional README (not separate page)
- **Evidence** goes in data/ folders at each level
- **No timeline view** for now
- **Predictions phased**: Near (2026-2028), Mid (2029-2032), Late (2033-2036)
- **Confidence**: Mention only when notably high or low; assume moderate otherwise
- **Falsifiable criteria**: Include specific thresholds where possible

---

## 2. README.md as Synthesis at Each Level

Each README.md is the **substantive analysis** for that level, not just navigation. Content flows down and synthesizes up.

### Hierarchy

```
/README.md                          # GLOBAL synthesis: the whole picture
├── /global/trends/ai-displacement.md   # Deep dive on specific trend
├── /regions/north-america/README.md    # REGIONAL synthesis: North America's trajectory
│   └── /regions/north-america/canada/README.md  # COUNTRY synthesis: Canada's trajectory
```

### Root README.md (Global Synthesis)

The big picture: what's happening to the world 2026-2036.

```markdown
# The Future: 2026-2036

A synthesis of global trajectories for the coming decade.

## The Shape of What's Coming

[High-level synthesis of the transformation underway - AI displacement,
energy as power, legitimacy crisis, winners/losers framework]

## Global Trends

- [AI Displacement](global/trends/ai-displacement.md) - 5% of jobs annually
- [Robotics Wave](global/trends/robotics-wave.md) - Physical automation after 2030
- [Energy & Data Centers](global/trends/energy-and-data-centers.md) - The new oil
- [Cultural Adoption](global/trends/cultural-adoption.md) - Who embraces, who resists
- [Financial Services Disruption](global/trends/financial-services-disruption.md)
- [Legitimacy Crisis](global/trends/legitimacy-crisis.md)

## Regional Trajectories

- [North America](regions/north-america/README.md) - Divergent paths
- [Europe](regions/europe/README.md) - Regulatory suicide and fracture
- [Asia-Pacific](regions/asia-pacific/README.md) - The adoption advantage

## The Winners and Losers

| Outlook | Countries |
|---------|-----------|
| **Winners** | [US](regions/north-america/united-states/README.md), [China](regions/asia-pacific/china/README.md), [Australia](regions/asia-pacific/australia/README.md), [Poland](regions/europe/poland/README.md) |
| **Restructured** | [Canada](regions/north-america/canada/README.md) |
| **Survivors** | [Singapore](regions/asia-pacific/singapore/README.md), [Japan](regions/asia-pacific/japan/README.md) |
| **Declining** | [Germany](regions/europe/germany/README.md), [Switzerland](regions/europe/switzerland/README.md), [Ireland](regions/europe/ireland/README.md) |
| **Fracturing** | [UK](regions/europe/united-kingdom/README.md), [France](regions/europe/france/README.md) |

---
*Last updated: YYYY-MM-DD | [Methodology](METHODOLOGY.md) | [Changelog](CHANGELOG.md)*
```

### Region README.md (Regional Synthesis)

What's happening to this region as a whole.

```markdown
# Europe: 2026-2036

> Regulatory suicide, energy crisis, and the fracturing of the postwar order.

## Regional Trajectory

[Synthesis of Europe's path - the EU AI Act burden, energy costs,
loss of competitiveness, divergent outcomes by country]

## Inherited Global Context

This region is shaped by:
- [AI Displacement](../../global/trends/ai-displacement.md) - Hitting professional services hard
- [Financial Services Disruption](../../global/trends/financial-services-disruption.md) - London, Zurich, Dublin vulnerable
- [Legitimacy Crisis](../../global/trends/legitimacy-crisis.md) - Compounding existing fractures

## Key Regional Dynamics

[Europe-specific factors: EU regulation, energy dependence, demographic pressures,
political fragmentation]

## Countries

| Country | Outlook | GDP Projection |
|---------|---------|----------------|
| [United Kingdom](united-kingdom/README.md) | Fracturing | -3 to -6% |
| [Germany](germany/README.md) | Declining | -2 to -4% |
| [France](france/README.md) | Fracturing | -2 to -4% |
| [Poland](poland/README.md) | Winner | +3 to +4% |
| [Ireland](ireland/README.md) | Declining | -1 to +2% |
| [Switzerland](switzerland/README.md) | Declining | -1 to -2% |

---
*Last updated: YYYY-MM-DD*
```

### Country README.md (Country Synthesis)

The complete picture for one country.

```markdown
# Canada: 2026-2036

> **Outlook**: Restructured
> **GDP Projection**: +2 to +4% annually (gains concentrated)

## Trajectory

[Full synthesis of Canada's path - the state-capital fusion model,
resource development, institutional ownership, who wins and who loses]

## Inherited Context

- [Global Trends](../../../global/README.md)
- [North America Regional Dynamics](../README.md)

## Key Factors

### Advantages
- Hydroelectric power, natural gas, critical minerals
- Resource extraction infrastructure buildout ($116B pipeline)
- Small population relative to resources

### Vulnerabilities
- Services economy in Toronto/Vancouver exposed to AI displacement
- State de-risking model concentrates gains with institutional investors
- UAE investment agreement ($50B under ISDS protection)

## Metrics

| Metric | 2025 | 2030 | 2035 |
|--------|------|------|------|
| Data Center Capacity | 1.2 GW | 3-5 GW | TBD |

## Predictions

### 2026-2028: Infrastructure Buildout
- LNG export capacity reaches first milestones
- SMR projects advance
- Resource extraction expands

### 2029-2032: Ownership Consolidation
- Institutional investors capture infrastructure returns
- Services sector contraction in major cities
- Regional inequality widens

### 2033-2036: The New Normal
- Resource economy dominant
- Rentier dynamics entrenched

## Risks
- Regulatory shift toward EU model
- Political backlash against foreign ownership
- Commodity price collapse

## What This Means

[Actionable implications - what should someone do with this information]

---
*Last updated: YYYY-MM-DD*
```

### Trend Pages (Deep Dives)

Individual trend files provide detail that README.md synthesis references.

```markdown
# AI Displacement Wave

> **Timeframe**: 2025-2035
> **Rate**: ~5% of jobs automated per year
> **Cumulative**: ~50% of current employment displaced by 2035

## The Pattern Break

[Why this is different from previous automation waves]

## Who Gets Displaced

- White-collar, professional, administrative roles
- Junior and entry-level positions
- Part-time work
- Disproportionately: women, younger workers

## Timeline

| Period | Development |
|--------|-------------|
| 2025-2027 | Acceleration in knowledge work |
| 2027-2030 | First wave peaks |
| 2030-2035 | Second wave (robotics) begins |

## Regional Variations

- **US**: Frontier firms capture gains, median workers bypassed
- **Europe**: Regulatory burden slows adoption but doesn't prevent displacement
- **Asia**: Fastest adoption, cultural acceptance

## Countries Most Affected

- [UK](../../regions/europe/united-kingdom/README.md) - Services economy fully exposed
- [Singapore](../../regions/asia-pacific/singapore/README.md) - Financial hub vulnerable
- [Canada](../../regions/north-america/canada/README.md) - Toronto/Vancouver services hit

---
*Last updated: YYYY-MM-DD*
```

---

## 3. Implementation Phases

### Phase 1: Create Directory Structure

- [ ] Create all directories
- [ ] Create placeholder README.md in each
- [ ] Write root README.md with navigation
- [ ] Write METHODOLOGY.md
- [ ] Initialize CHANGELOG.md

### Phase 2: Extract Global Trends from Essay

- [ ] **AI Displacement Wave** (Part I)
  - 5% job automation per year
  - 50% displacement by 2035
  - Affected sectors: white-collar, administrative, professional, entry-level
  - Disproportionate impact on women, younger workers, part-time

- [ ] **Robotics Wave** (Part I)
  - Timeline: pilots now → scale 2027-2028 → mainstream 2030+
  - Battery: 2hr now → 6hr by 2030 → 8hr by 2035+
  - Sectors: automotive → logistics → warehousing → service
  - Market size: $30-80B by 2035

- [ ] **Energy & Data Centers** (Part II)
  - Capacity table (8 countries/regions)
  - Pipeline projections to 2030
  - Energy cost differentials

- [ ] **Cultural Adoption** (Part III)
  - Asian advantage (China 58%, India 92%)
  - American paradox (25% adoption, frontier dominance)
  - European regulatory burden

- [ ] **Financial Services Disruption** (Part IV)
  - AI automation of knowledge work
  - Alternative finance (stablecoins, DeFi)
  - Vulnerable hubs list

- [ ] **Legitimacy Crisis** (Part V)
  - Trust deficits
  - Preconditions for unrest

### Phase 3: Extract Country Data from Essay

**Winners:**
- [ ] United States (53.7 GW, 5-7% GDP)
- [ ] China (32 GW, 4-6% GDP)
- [ ] Australia (1.3 GW, 3-5% GDP)
- [ ] Poland (3-4% GDP)

**Restructured:**
- [ ] Canada (1.2 GW, 2-4% GDP, concentrated gains)

**Survivors:**
- [ ] Singapore (~1 GW, 2-4% GDP)
- [ ] Japan (1.5 GW, 1-2% GDP)

**Declining:**
- [ ] Germany (0.8 GW, -2 to -4% GDP)
- [ ] Switzerland (-1 to -2% GDP)
- [ ] Ireland (-1 to +2% GDP, high variance)

**Fracturing:**
- [ ] France (-2 to -4% GDP)
- [ ] United Kingdom (~1 GW, -3 to -6% GDP)

### Phase 4: Structure Predictions

- [ ] Convert projections to year-specific predictions
- [ ] Add confidence ratings with reasoning
- [ ] Add actionable implications
- [ ] Cross-link to relevant global trends

### Phase 5: Regional Context

- [ ] Write North America regional overview
- [ ] Write Europe regional overview
- [ ] Write Asia-Pacific regional overview
- [ ] Add regional trends where applicable

---

## 4. Data to Extract from Essay

### Data Center Capacity Table

| Country/Region | 2025 (GW) | 2030 Est. (GW) | Assessment |
|----------------|-----------|----------------|------------|
| United States | 53.7 | 81+ | Dominant |
| China | ~32 | 50+ | Major Power |
| European Union | 11.9 | ~35 | Trailing |
| Japan | 1.5 | 3-4 | Constrained |
| Australia | 1.3 | 4-5 | Rising |
| United Kingdom | ~1.0 | 2-3 | Inadequate |
| Germany | ~0.8 | 1.5-2 | Energy Crisis |
| Canada | ~1.2 | 3-5 | Policy Dependent |

### AI Adoption Rates

| Country/Region | Org Adoption | Citizen Optimism |
|----------------|--------------|------------------|
| India | 92% | High |
| China | 58% | 2x US |
| Malaysia | - | 68% |
| Indonesia | - | 69% |
| United States | 25% | ~40-50% |
| Japan | 51% | 46% |
| Western avg | - | 40-50% |

### Robotics Timeline

| Year | Milestone |
|------|-----------|
| 2025 | Hundreds deployed in pilots (BMW, Amazon) |
| 2027-2028 | Cross from pilots to large-scale deployment |
| 2030 | 6hr battery life, automotive/logistics mainstream |
| 2035 | $30-80B market, service sector expansion |

---

## 5. Prediction Categories

1. **Economy**: GDP, employment, industry shifts
2. **Technology**: AI adoption, robotics, data centers
3. **Energy**: Power capacity, costs, infrastructure
4. **Politics**: Elections, policy, instability
5. **Finance**: Financial services, crypto, capital flows
6. **Social**: Civil unrest, legitimacy, migration

---

## 6. Next Steps

1. ✅ Plan complete
2. Approve plan
3. Create directory structure and placeholder files
4. Extract and write global trends
5. Extract and write country profiles
6. Add cross-links and navigation
