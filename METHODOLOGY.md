# Methodology

This repository organizes predictions and analysis for 2026-2036 using a structured approach that separates known facts from observations from suppositions.

---

## Epistemic Status

**This is a scenario exercise, not a forecast.** It stakes out a clear, internally consistent scenario and follows implications through countries and sectors. The prose is intentionally confident to sharpen thinking; treat it as a planning premise, not a claim of certainty.

**What this is for**: Thinking through implications, identifying exposure, stress-testing assumptions.

**What this is not**: A prediction market, an investment recommendation, or a claim to know the future.

---

## Core Assumptions

This analysis proceeds from several foundational assumptions. **If you disagree with these, the downstream conclusions don't follow.**

### Assumption 1: AI Displacement Rate (Scenario Premise)

This work adopts a clear premise to drive the scenario: **net job displacement of ~5% of the workforce per year, compounding, from 2026 through 2036.**

- Compounding math: 1 − 0.95^10 ≈ 40% cumulative; 1 − 0.95^11 ≈ 43% cumulative.
- Interpretation: By the mid‑2030s, on the order of half of today’s roles are displaced or fundamentally transformed in this scenario.

We treat 5%/year as a scenario lever, not a consensus estimate. The point is to examine downstream implications if displacement runs at this pace.

**Sector heterogeneity**: The global average masks dramatic variation. The figures below are directional, expressed relative to the 5% net scenario baseline.

| Sector | Expected Net Displacement/Year | Rationale |
|--------|-------------------------------|-----------|
| Legal services | Higher than baseline | Research, drafting, review highly automatable |
| Software development | Higher than baseline | See [software automation trend](global/trends/software-development-automation.md) |
| Financial back/middle office | Higher than baseline | Pure information processing |
| Call centers / BPO | Much higher than baseline | Near‑total elimination; see [call center collapse](global/trends/call-center-collapse.md) |
| Administrative / clerical | Around baseline to higher | Broad automation of routine tasks |
| Retail / hospitality | Lower than baseline | Physical presence still valued; robotics later |
| Healthcare delivery | Lower than baseline | Physical skills; regulatory protection |
| Trades / construction | Lower early, higher late | Robotics Wave 2; later in timeline |
| Agriculture | Lower than baseline | Already automated; continued pressure |

Countries/regions weighted toward high-displacement sectors (UK financial services, Indian IT, Philippine BPO) face steeper curves than those weighted toward physical work.

**What this scenario simplifies** (acknowledged limitations):
- General equilibrium effects (wage adjustment, capital deepening)
- New job/sector creation from AI-enabled activities
- Hours-per-worker adjustment (underemployment vs unemployment)
- Policy responses (UBI, retraining, work-sharing)
- Deliberate adoption slowdowns in some jurisdictions

**Historical comparison**: Peak industrial‑revolution displacement is typically estimated at ~1–2% annual structural adjustment. This scenario assumes a step‑change to ~5% net, sustained for a decade. Aggressive, but analytically useful.

### Assumption 2: Energy/Compute as Key Factor (Not Master Variable)

Data centre capacity is treated as **one important factor in a bundle**, not the sole determinant. Rather than pretending to a level of precision the judgment does not have, we use relative importance labels:

| Factor | Relative Importance | Rationale |
|--------|---------------------|-----------|
| Compute access (local + cloud) | High | Can rent capacity; latency matters for some workloads |
| Energy cost/reliability | High | Ongoing operational constraint |
| Regulatory environment | High | Determines deployment friction |
| Capital markets | Medium | Funds buildout and adoption |
| Talent base | Medium | Engineers, researchers, operators |
| Cultural adoption disposition | Medium | Willingness to deploy and accept |

**Important caveats**:
- Compute is more mobile than oil—firms can rent capacity cross-border
- Model efficiency improves ~10x per few years; GW today ≠ GW in 2030
- DC buildout is fast if policy allows (1→4 GW is years, not decades)
- The US advantage is real but not as deterministic as the text sometimes implies

**Factor emphasis varies by country archetype**:

| Archetype | Examples | Most Binding Factors | Role of Data Centres |
|-----------|----------|---------------------|----------------------|
| **Hegemon** | US, China | Energy, political stability, talent | High |
| **Mid-sized developed** | UK, Germany, Canada, Australia | Regulation, energy price, ability to tap US compute | Medium |
| **Small open economy** | Singapore, Ireland, Switzerland | Geopolitics, niche positioning, openness | Medium‑Low |
| **Emerging market** | India, Indonesia, Vietnam | Capital markets, infrastructure, talent pipeline | Medium‑High |
| **Resource-rich** | Saudi Arabia, UAE, Australia | Energy cost, capital, regulatory simplicity | Very High |

The original 25/20/20/15/10/10 weights were always a heuristic; in practice, binding constraints differ by country type. Synthesis should not over‑weight any single factor (e.g., compute) relative to this bundle.

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

### Assumption 4: Geopolitical Weight as Distinct Axis (Added December 2025)

**Claim**: Economic trajectory and geopolitical standing are partially independent axes. A country can be economically declining while retaining or even gaining geopolitical weight.

**The C5 Test**: The December 2025 US NSS reportedly proposes a "Core 5" (US, China, Russia, India, Japan) based on:
- Nuclear arsenal
- Population mass (>100M)
- Geographic sphere control
- Great power legitimacy

This is orthogonal to our economic/AI-displacement analysis. Russia ranks 31st in AI capability but holds the world's largest nuclear arsenal. India faces IT services collapse but is the only major power with genuine bloc choice.

**Framework implication**: Country assessments should now consider two dimensions:

| Dimension | Measures | Example |
|-----------|----------|---------|
| **Economic trajectory** | AI exposure, growth outlook, sector displacement | Germany: Declining |
| **Geopolitical weight** | Nuclear status, population, sphere control, alignment options | Germany: Diminishing |

A country can be:
- Economically declining + geopolitically rising (Russia post-C5 recognition)
- Economically strong + geopolitically diminishing (Germany, EU broadly)
- Both aligned (US, China)
- High variance on both (India)

**Countries with elevated geopolitical weight regardless of economics:**
- **Russia**: Nuclear arsenal (5,580 warheads), UNSC seat, sphere in Central Asia/Caucasus, China partnership
- **India**: Population (1.4B), nuclear capability, genuine bloc choice, Indian Ocean control
- **Japan**: US alliance anchor, Pacific geography, industrial base, latent nuclear capability

**Countries with diminished geopolitical weight despite economic strength:**
- **Germany**: No nukes, no unified European command, energy dependence, sphere-less
- **EU**: No unified actor, no coherent military, no nuclear policy, 27 competing voices
- **UK**: Post-Brexit, post-empire, nuclear but small, no sphere

### Assumption 5: Regulatory Redistributive Effect

**Claim**: Regulation cannot prevent global AI deployment; it primarily shifts where gains and costs are captured.

**Mechanism**:
- AI is deployed by US/China regardless of EU/UK/Canada rules
- Regulated firms compete against unregulated AI-enabled competitors
- "Human in the loop" requirements add cost without preventing capability deployment
- Net effect: compliance burden without protection

**Counterarguments acknowledged**:
- Regulation can slow domestic deployment, buying adjustment time
- Consumer protection, liability frameworks do provide real value
- EU may eventually adapt (carve-outs, arbitrage, grey markets)
- Outcomes vary; implementation details matter

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

### Outcome Schema by Category (Heuristic)

To keep the prose honest, each category maps to a rough band of macro outcomes in this 5%‑displacement scenario. These are **scenario heuristics**, not forecasts.

| Category | GDP Band (10y avg) | Unemployment Band | Typical Legitimacy Trajectory |
|----------|--------------------|-------------------|-------------------------------|
| **Winner** | ~3–6% annual growth | Generally low to moderate (3–8%) | Institutions broadly trusted; distributional conflict but system stable |
| **Restructured** | ~2–4% growth, gains concentrated | Moderate (5–10%); pockets of high underemployment | Legitimacy contested around who captures gains; system holds |
| **Survivor** | ~0–3% growth; “muddle through” | Moderate to high (6–12%) but stable | Legitimacy erodes slowly; discontent without systemic break |
| **Contested** | ~‑1 to +4% (high variance) | Variable; can swing quickly | Legitimacy path genuinely uncertain; reform or breakdown both plausible |
| **Declining** | ~‑1 to +2% (trend down) | High (10–20%+) or disguised via informality | Trust in institutions falls; resignation > revolt, but unrest risk elevated |
| **Fracturing** | ~‑2 to ‑5% with shocks | High, regional or youth unemployment extreme | Legitimacy crisis; episodic serious unrest, secessionist or extra‑system movements |
| **Collapsing** | ~‑3 to ‑7% or unmeasurable | Labour metrics cease to be meaningful | State authority fails or fragments; parallel power centres emerge |

Country pages should be read as placing each nation somewhere inside these bands for the 2026‑2036 period, not as precise point estimates.

### Growth Outlook Interpretation

Country profiles use **qualitative growth outlooks** (High / Moderate / Low / Negative / Uneven) rather than numeric GDP projections. These reflect relative positioning within the scenario’s factor model and sector exposure rather than econometric forecasts.

---

## Analytical Framework

### The Three Layers

| Layer | Question | Contents |
|-------|----------|----------|
| **Data** | What do we know today? | Current metrics, statistics, documented facts |
| **Trends** | What patterns are in motion? | Observable trajectories, emerging dynamics |
| **Analysis** | What do we suppose will happen? | Predictions, scenarios, risk assessments |

Each geographic level (global, regional, country) maintains these three layers. The `index.md` at each level synthesizes them into a coherent narrative.

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
Predictions include specific criteria where possible (capacity targets, adoption milestones, sector employment shifts, event triggers). Where GDP is referenced, use it to validate category direction rather than to forecast exact magnitudes.

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
4. **Synthesis**: Update index.md to reflect new understanding
5. **Changelog**: Record what changed and why in CHANGELOG.md

---

## Source Material

Initial content extracted from "The Fracturing: Western Civilisation and the Coming Decade of Transformation, 2025-2035" (December 2025).

---

*Last updated: 2025-12-08*

---

## From Sector Exposure to Growth Outlook (Bridge)

This bridge maps sectoral exposure in the 5% net displacement scenario to a qualitative growth outlook.

- High Exposure: Large shares in financial/professional/administrative/BPO; minimal offsetting sectors; weak adoption capacity → Growth outlook: Negative; risk of instability elevated if legitimacy is low.
- Mixed Exposure: Services exposure but with offsetting strengths (manufacturing, resources, strong adoption, capital) → Growth outlook: Low to Moderate; uneven distribution likely.
- Low Exposure or Strong Offsets: Resources, energy abundance, or leadership in AI ownership/compute; high adoption capacity → Growth outlook: Moderate to High.

Modifiers:
- Factor bundle (compute, energy, regulation, capital, talent, culture) can shift outlook up/down a notch.
- Wave 2 (robotics) timing raises late‑period exposure for trades/manufacturing.
