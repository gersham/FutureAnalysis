# Methodology

This repository organizes predictions and analysis for 2026-2036 using a structured approach that separates known facts from observations from suppositions.

---

## Epistemic Status

**This is a scenario exercise, not a forecast.** The document stakes out a coherent, internally consistent view of how AI-driven transformation might unfold. It is deliberately pointed rather than hedged, because hedged scenarios are less useful for planning.

However:
- The confident prose is **rhetorical**, not epistemic certainty
- GDP projections are **illustrative ranges**, not econometric forecasts
- Country classifications are **central cases** with significant variance around them
- Decade-long projections are inherently fragile; treat as directional, not precise

**What this is for**: Thinking through implications, identifying exposure, stress-testing assumptions.

**What this is not**: A prediction market, an investment recommendation, or a claim to know the future.

---

## Core Assumptions

This analysis proceeds from several foundational assumptions. **If you disagree with these, the downstream conclusions don't follow.**

### Assumption 1: AI Displacement Rate

| Element | Claim | Basis | Uncertainty |
|---------|-------|-------|-------------|
| **Task automation rate** | ~40-60% of current tasks automatable by 2035 | Current LLM/robotics capability trajectories | Moderate |
| **Job elimination rate** | ~5% of roles eliminated annually | Tasks ≠ jobs; assumes partial absorption | **High** |
| **Net displacement by 2035** | ~30-50% of current workforce affected | Cumulative effect minus re-deployment | **High** |

**The explicit model**:

```
Gross task automation: ~5-7% of all work tasks per year
× Tasks-to-jobs conversion: ~0.6-0.8 (many tasks automated ≠ job eliminated)
× (1 - Re-deployment rate): ~0.5-0.7 (fraction NOT absorbed into new/modified roles)
= Net job displacement: ~2-4% of workforce per year
```

**Compounding math**: We use a compounding model where each year's displacement is from the *current* workforce. At 3% net annual displacement:
- Year 1: 100 → 97 (3% displaced)
- Year 5: 100 → 86 (1 - 0.97⁵)
- Year 10: 100 → 74 (1 - 0.97¹⁰ = 26% cumulative)

At 4% net annual: 1 - 0.96¹⁰ = 34% cumulative displacement.

The **25-40% range** corresponds to net annual rates of 2.8-5%, which maps to the model outputs above.

**Sector heterogeneity**: The global average masks dramatic variation:

| Sector | Expected Net Displacement/Year | Rationale |
|--------|-------------------------------|-----------|
| Legal services | 8-12% | Research, drafting, review highly automatable |
| Software development | 6-10% | See [software automation trend](global/trends/software-development-automation.md) |
| Financial back/middle office | 6-10% | Pure information processing |
| Call centers / BPO | 15-25% | Near-total elimination; see [call center collapse](global/trends/call-center-collapse.md) |
| Administrative / clerical | 5-8% | Broad automation of routine tasks |
| Retail / hospitality | 2-4% | Physical presence still valued; robotics later |
| Healthcare delivery | 1-3% | Physical skills; regulatory protection |
| Trades / construction | 1-2% | Robotics Wave 2; later in timeline |
| Agriculture | 2-4% | Already highly automated; continued pressure |

Countries/regions weighted toward high-displacement sectors (UK financial services, Indian IT, Philippine BPO) face steeper curves than those weighted toward physical work.

**What this model ignores** (acknowledged limitations):
- General equilibrium effects (wage adjustment, capital deepening)
- New job/sector creation from AI-enabled activities
- Hours-per-worker adjustment (underemployment vs unemployment)
- Policy responses (UBI, retraining, work-sharing)
- Deliberate adoption slowdowns in some jurisdictions

The 5%/year headline figure is a **gross task automation rate** that gets partially offset by job restructuring and re-deployment. Net effects are lower but still historically unprecedented.

**Historical comparison**: Peak industrial-revolution displacement was ~1-2% annual structural unemployment adjustment. We're assuming 2-4x that rate, sustained for a decade. This is aggressive but not impossible given the generality of cognitive automation. The closest modern analogue is perhaps the collapse of manufacturing employment in the US/UK from 1980-2010—but that was spread over 30 years, not 10.

### Assumption 2: Energy/Compute as Key Factor (Not Master Variable)

Data centre capacity is treated as **one important factor in a bundle**, not the sole determinant:

| Factor | Weight | Rationale |
|--------|--------|-----------|
| Compute access (local + cloud) | 25% | Can rent capacity; latency matters for some workloads |
| Energy cost/reliability | 20% | Ongoing operational constraint |
| Regulatory environment | 20% | Determines deployment friction |
| Capital markets | 15% | Funds buildout and adoption |
| Talent base | 10% | Engineers, researchers, operators |
| Cultural adoption disposition | 10% | Willingness to deploy and accept |

**Important caveats**:
- Compute is more mobile than oil—firms can rent capacity cross-border
- Model efficiency improves ~10x per few years; GW today ≠ GW in 2030
- DC buildout is fast if policy allows (1→4 GW is years, not decades)
- The US advantage is real but not as deterministic as the text sometimes implies

**Factor weights vary by country archetype**:

| Archetype | Examples | Most Binding Factors | DC Weight |
|-----------|----------|---------------------|-----------|
| **Hegemon** | US, China | Energy, political stability, talent | 30% |
| **Mid-sized developed** | UK, Germany, Canada, Australia | Regulation, energy price, ability to tap US compute | 20% |
| **Small open economy** | Singapore, Ireland, Switzerland | Geopolitics, niche positioning, openness | 15% |
| **Emerging market** | India, Indonesia, Vietnam | Capital markets, infrastructure, talent pipeline | 25% |
| **Resource-rich** | Saudi Arabia, UAE, Australia | Energy cost, capital, regulatory simplicity | 35% |

The 25/20/20/15/10/10 global weights are a heuristic; in practice, binding constraints differ by country type.

**Interaction effects**: These factors are not additively independent:
- Regulation × Capital markets: Can we finance DC given NIMBY + ESG constraints?
- Energy × DC: Cheap power without buildout permits is wasted
- Talent × Adoption: High-skill workers accelerate deployment; low adoption wastes talent
- Regulatory environment × Cultural adoption: Regulations that match cultural disposition stick; those that don't get arbitraged

### Assumption 3: Two Automation Waves

| Wave | Timing | Target | Current Status |
|------|--------|--------|----------------|
| **Wave 1**: Cognitive | 2023-2030 | White-collar, administrative, professional | Underway; accelerating |
| **Wave 2**: Physical | 2028-2035 | Manufacturing, logistics, service work | Pilots; 3-5 years from scale |

**Key implication**: The traditional safety valve—retraining displaced white-collar workers for blue-collar work—closes as Wave 2 arrives. This is the mechanism behind the "no escape" thesis.

**Uncertainty**: Wave 2 timing is the most speculative element. Robotics deployment could be:
- Faster than projected (aggressive Chinese/Tesla scaling)
- Slower (engineering challenges, regulation, union resistance)
- Different in character (augmentation rather than replacement)

### Assumption 4: Regulatory Inefficacy

**Claim**: Regulation cannot prevent AI deployment globally; it only shifts where gains are captured.

**Mechanism**:
- AI is deployed by US/China regardless of EU/UK/Canada rules
- Regulated firms compete against unregulated AI-enabled competitors
- "Human in the loop" requirements add cost without preventing capability deployment
- Net effect: compliance burden without protection

**Counterarguments acknowledged**:
- Regulation can slow domestic deployment, buying adjustment time
- Consumer protection, liability frameworks do provide real value
- EU may eventually adapt (carve-outs, arbitrage, grey markets)
- "Regulatory suicide" is rhetorical; reality is messier

---

## Scenario Structure

### Country Classifications

Countries are classified into **central case scenarios** with explicit upside/downside variants:

| Category | Central Case | Upside | Downside |
|----------|--------------|--------|----------|
| **Winner** | Capturing AI gains; 4-7% growth | Even faster adoption; 6-8% | Trade war; regulatory reversal |
| **Restructured** | Growth but concentrated; 2-4% | Broader distribution; 3-5% | Capture by narrow interests; 1-2% |
| **Survivor** | Managed decline; 0-2% | Unexpected adaptation; 2-3% | Stagnation; -1 to 1% |
| **Contested** | Uncertain; -1 to +4% | Structural reform works; +3-5% | Reform fails; -2 to 0% |
| **Declining** | Structural contraction; -1 to -3% | Adaptation surprises; 0-1% | Acceleration; -3 to -5% |
| **Fracturing** | Decline + instability; -2 to -5% | Institutional resilience; -1 to -2% | Serious unrest; -4 to -7% |

### GDP Projection Interpretation

The GDP ranges in country profiles are **illustrative**, not econometric:

- They represent "think about this range" rather than "our model outputs this"
- They assume the core displacement scenario plays out roughly as described
- They do NOT account for:
  - Black swan events (war, pandemic, financial crisis)
  - Major policy shifts (unexpected liberalization or autarky)
  - Technological discontinuities (AGI, fusion, etc.)

**Sanity check**: If US runs +5-7% while Germany runs -2 to -4% for a decade, that implies:
- US GDP roughly doubles; Germany GDP falls ~20-30%
- Per capita gap widens from ~1.4x to ~2.5-3x
- Capital flows massively toward US
- Euro under severe pressure

This is historically extreme but not impossible (cf. Japan vs US 1990-2010). The ranges are at the aggressive end of plausible.

---

## Analytical Framework

### The Three Layers

| Layer | Question | Contents |
|-------|----------|----------|
| **Data** | What do we know today? | Current metrics, statistics, documented facts |
| **Trends** | What patterns are in motion? | Observable trajectories, emerging dynamics |
| **Analysis** | What do we suppose will happen? | Predictions, scenarios, risk assessments |

Each geographic level (global, regional, country) maintains these three layers. The README.md at each level synthesizes them into a coherent narrative.

### Inheritance

Context flows downward:
- Global data/trends/analysis affect all regions
- Regional context shapes all countries within it
- Country-specific factors modify inherited context

When reading a country profile, the full picture requires understanding:
1. Global trends (AI displacement, energy, etc.)
2. Regional dynamics (regulatory environment, economic bloc effects)
3. Country-specific factors (resources, demographics, institutions)

---

## Prediction Format

### Timeframes
- **Near term**: 2026-2028
- **Mid term**: 2029-2032
- **Late term**: 2033-2036

### Confidence Levels
- Only noted when notably **high** or **low**
- Absence of confidence note = moderate confidence
- High confidence: strong data support, clear trajectory, few confounding variables
- Low confidence: limited data, multiple plausible scenarios, high uncertainty

### Falsifiability
Predictions include specific criteria where possible:
- GDP thresholds (e.g., "contracts 3%+ for 2 consecutive quarters")
- Capacity targets (e.g., "data center capacity exceeds 5 GW")
- Event triggers (e.g., "major civil unrest in 3+ cities")

---

## Adaptation Channels (Acknowledged)

The text sometimes underplays adaptation. Key channels that could invalidate scenarios:

### For "Declining" economies:
- Currency devaluation restoring competitiveness
- Radical regulatory liberalization
- Unexpected resource discoveries
- Constitutional/political reform
- Mass immigration policy changes

### For "Winner" economies:
- Regulatory capture or reversal
- Trade war escalation
- Internal political instability
- Technology export controls biting harder than expected

### For "Fracturing" scenarios:
- Institutional resilience exceeding expectations
- Effective redistribution policies
- Social cohesion stronger than demographics suggest
- Emigration as safety valve

---

## What Would Change Our Mind

Specific indicators that would cause major reassessment:

| Signal | Implication |
|--------|-------------|
| AI capability plateau (no major advances 2025-2027) | Slow displacement scenario; Europe less disadvantaged |
| Robotics deployment faster than expected (100k+ units by 2027) | Wave 2 arrives early; acceleration of physical displacement |
| Major EU regulatory loosening | Europe more competitive than projected |
| US political instability | American advantage less secure |
| China-Taiwan conflict | Everything changes; all projections void |
| Breakthrough in model efficiency (100x in 2 years) | DC capacity less binding; smaller nations can compete |
| Effective UBI deployment at scale | Displacement ≠ crisis; social adaptation possible |

---

## Updating

When new information emerges:

1. **Data**: Add to relevant `data/` folder with source and date
2. **Trends**: Update or add to `trends/` folder; note trajectory changes
3. **Analysis**: Revise predictions in `analysis/` folder; update confidence if warranted
4. **Synthesis**: Update README.md to reflect new understanding
5. **Changelog**: Record what changed and why in CHANGELOG.md

---

## Source Material

Initial content extracted from "The Fracturing: Western Civilisation and the Coming Decade of Transformation, 2025-2035" (December 2025).

---

*Last updated: 2025-12-08*
