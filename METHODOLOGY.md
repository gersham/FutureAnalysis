# Methodology

This repository organizes predictions and analysis for 2026-2036 using a structured approach that separates known facts from observations from suppositions.

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

## Core Assumptions

This analysis proceeds from several foundational assumptions:

### AI Displacement Rate
- **Assumption**: ~5% of existing jobs automated per year through 2035
- **Basis**: Extrapolation from current LLM capabilities and deployment trajectories
- **Implication**: ~50% of current employment displaced by 2035
- **Concentration**: White-collar, professional, administrative, entry-level, part-time

### Energy as Constraint
- **Assumption**: Data center capacity is a binding constraint on AI economic power
- **Basis**: Current infrastructure investment patterns, power requirements for training and inference
- **Implication**: Nations with cheap, abundant energy capture disproportionate gains

### Two Waves
- **Wave 1 (2025-2030)**: Cognitive/administrative automation via LLMs
- **Wave 2 (2030-2035)**: Physical automation via humanoid robotics
- **Implication**: Traditional retraining pathway (white-collar → blue-collar) closes

### Regulatory Inefficacy
- **Assumption**: Regulation cannot prevent AI deployment, only shift where gains are captured
- **Basis**: Global competition dynamics; technology deployed by competitors regardless
- **Implication**: Heavy regulation = forfeited advantage, not protection

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

## Outlook Categories

Countries are classified by trajectory:

| Category | Definition | Characteristics |
|----------|------------|-----------------|
| **Winner** | Capturing AI transition gains | Growing GDP, expanding infrastructure, competitive positioning |
| **Restructured** | Gains captured but concentrated | Growth exists but benefits flow to specific actors; inequality widens |
| **Survivor** | Managing decline with stability | Economic contraction but social cohesion maintained |
| **Declining** | Structural contraction | Persistent negative growth, institutional strain |
| **Fracturing** | Decline + instability | Economic contraction combined with civil unrest risk |

## Updating

When new information emerges:

1. **Data**: Add to relevant `data/` folder with source and date
2. **Trends**: Update or add to `trends/` folder; note trajectory changes
3. **Analysis**: Revise predictions in `analysis/` folder; update confidence if warranted
4. **Synthesis**: Update README.md to reflect new understanding
5. **Changelog**: Record what changed and why in CHANGELOG.md

## Source Material

Initial content extracted from "The Fracturing: Western Civilisation and the Coming Decade of Transformation, 2025-2035" (December 2025).

The source essay is available at `/sources/the-fracturing-2025-2035.md` and will be removed once extraction is complete.

---

*Last updated: 2025-12-07*
