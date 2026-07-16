---
triggers:
  - "user mentions numbers without units, or uses adjectives where numbers are needed"
  - "user is comparing claims of different magnitudes without the magnitudes"
  - "user wants a quick reality check on a quantitative claim"
use_when:
  - "the question requires arithmetic and the conversation has not done it"
  - "the user is being sold a claim that hides behind percentages"
  - "you need to teach the methodological foundation that Smil's entire body of work rests on"
fails_when:
  - "the question is genuinely qualitative or normative"
  - "you become pedantic about precision when the order of magnitude is the substantive issue"
  - "you let numerical correctness substitute for engagement with the meaning"
related:
  - "critique-of-techno-optimism.md"
  - "the-decarbonisation-paradox.md"
  - "growth-and-scaling-limits.md"
---

# Numerical Literacy and Orders of Magnitude

## When to Use
- When a claim is being made without units, or with units that are not understood by the audience.
- When percentage changes are being cited without absolute bases.
- When a quick reality check is needed on a quantitative claim.
- When teaching the methodological foundation of Smil's body of work.

## Fails When
- **The question is genuinely qualitative.** Some questions are about meaning, not quantity. Forcing them into numerical terms is a category error.
- **You demand spurious precision.** When the order of magnitude is the substantive issue, demanding three significant figures is missing the point.
- **You let numerical correctness substitute for engagement with the meaning.** Numbers are necessary but not sufficient; they have to be interpreted.

## Core Concept
Numerical literacy is the discipline of knowing the basic magnitudes of the systems you are deciding on. It is Smil's methodological foundation and the most under-developed skill among senior decision-makers in policy, consulting, and journalism. Without it, every conversation about energy, materials, food, transport, climate, or development is an exchange of adjectives.

**Some baseline numbers every educated person discussing energy should know:**

Global primary energy: ~620 EJ (exajoules) per year, or about 200,000 TWh (terawatt-hours) equivalent.

Global electricity generation: ~30,000 TWh per year (so electricity is about 15% of total final energy use).

Fossil fuels share of primary energy: about 80%.

Global CO₂ emissions from energy: ~37 GtCO₂ per year.

Global cement production: ~4 Gt per year.
Global steel production: ~1.9 Gt per year.
Global ammonia production: ~180 Mt per year.
Global plastics production: ~400 Mt per year.

Population: ~8.1 billion (2024).

Global GDP: ~$110 trillion.

Per-capita primary energy: ranges from ~5 GJ/year (low-income countries) to ~300 GJ/year (high-end of rich countries).

**Some baseline ratios:**

Solar PV power density: 5-10 W/m² average over the year (temperate).
Wind onshore power density: 1-2 W/m² of affected land.
Fossil-fuel plant power density: 100s to 1000s of W/m².

Solar PV capacity factor: 15-20% (temperate), up to 25% (desert).
Onshore wind capacity factor: 25-40%.
Offshore wind capacity factor: 35-50%.
Nuclear capacity factor: 85-95%.

Energy density of jet fuel: ~43 MJ/kg.
Energy density of Li-ion battery cell: ~0.5 MJ/kg (best cells).

Without these reference points, you cannot tell whether a claim is reasonable, ambitious, or absurd. With them, you can do a useful sanity check on most energy and materials claims in under a minute.

**The order-of-magnitude check.** When a claim arrives, ask:
1. What is the magnitude (the order of ten)?
2. What is the historical baseline?
3. What is the implied rate?
4. Does the rate have a precedent?

A claim that something will grow by 10× over a decade is plausible for a young industry. A claim that something will grow by 100× over a decade requires very specific conditions and usually fails. A claim that something will grow by 1000× over a decade is essentially never true.

Conversely, a claim that something will shrink by 50% over a decade is uncommon historically and requires either deliberate policy contraction or catastrophic external event. A claim that it will shrink by 90% over a decade has essentially no precedent in established industries.

**The percentage-without-base trap.** "Renewables grew by 40% last year" is meaningless without knowing the base. From 1% to 1.4% is trivial in absolute terms; from 30% to 42% is substantial. The base must always accompany the rate.

**The capacity-vs-output trap.** Capacity is what's installed. Output is what's delivered. Capacity factor connects them. 1 GW of solar capacity ≠ 1 GW continuous power; it averages roughly 0.2 GW over the year in temperate climates. The two are routinely confused in popular reporting.

**The forecast-extrapolation trap.** Current rates of change rarely sustain indefinitely. Cost curves bend. Demand growth slows. Substitution effects emerge. A forecast that linearly extrapolates the past five years for thirty years is usually wrong, often by a lot.

## How to Apply
1. **Force the units.** Every claim about energy or materials must have units. "More renewables" is not a claim. "200 GW of new solar in 2024" is.
2. **Force the base.** Every percentage must have a base. "40% growth" is not a claim. "From 100 to 140 of X" is.
3. **Force the time horizon.** "Going to scale" is not a claim. "By 2035" is.
4. **Do the implied-rate calculation.** What annual rate of change does the claim require? Does it have historical precedent?
5. **Compare to a known reference.** Is the proposed thing larger or smaller than France's electricity consumption? Larger or smaller than China's cement production?
6. **Be willing to be wrong.** Numerical-literacy checks are calibration, not prophecy. Some things do exceed historical rates. The point is to engage the question, not to predict.

## Examples
**Situation:** A pitch deck claims "we will scale to 1 gigawatt by 2030".
**Application:** 1 GW of what? Solar PV deployment at 1 GW is a substantial project (about 1,000 hectares of land for the panels). 1 GW of battery storage is a major facility (a few hundred MWh to a few GWh of storage depending on duration). 1 GW of green hydrogen electrolyser is a multi-billion-dollar project. Force the specificity.
**Result:** Vague claim becomes a specific engineering project that can be assessed.

**Situation:** A national government announces a target of "reducing emissions by 45% by 2030".
**Application:** From what base year? Production-based or consumption-based emissions? Including imports? Including land-use change? What does the implied annual reduction rate (typically 6-8% per year) compare to historical national reductions (the fastest sustained voluntary national reduction in history is roughly 5% per year, achieved by the UK over a decade in special circumstances)?
**Result:** Target is contextualised and the implementation pathway becomes the substantive conversation.

## Anti-Patterns
**Don't:** Accept percentages without bases.
**Why:** They are nearly always misleading. Percentage of small is small. Percentage of large is large.

**Don't:** Confuse capacity with output.
**Why:** A renewable system's capacity factor matters as much as its installed capacity. Both must be cited.

**Don't:** Demand spurious precision when the question is about order of magnitude.
**Why:** Knowing whether a thing is closer to 10⁶ or 10⁹ is what matters. The third significant figure is often not the question.
