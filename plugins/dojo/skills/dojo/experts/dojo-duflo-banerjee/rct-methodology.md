---
triggers:
  - "user is designing an impact evaluation"
  - "user asks how RCTs work in development"
  - "user is debating whether to use experimental methods"
use_when:
  - "the question is about establishing causal effects of specific interventions"
  - "you need to explain RCT design principles"
fails_when:
  - "the question is about structural-historical-institutional dynamics rather than specific interventions"
  - "the intervention cannot ethically or practically be randomised"
related:
  - "external-validity-and-scaling.md"
  - "policy-trial-iteration.md"
  - "micro-empirical-policy.md"
---

# RCT Methodology

## When to Use
- When designing the evaluation of a specific intervention with measurable outcomes and a clear treatment-control comparison.
- When establishing credible causal effects rather than correlations.
- When the question is "what does this intervention do" rather than "how do systems transform".

## Fails When
- **The intervention cannot be randomly assigned** for ethical, political, or practical reasons.
- **The unit of randomisation does not match the unit of effect** (randomising individuals when effects are network-level produces biased estimates).
- **The question is structural** — what industrial policy a country should pursue is not an RCT question.

## Core Concept

A randomised controlled trial in development economics assigns a treatment (an intervention) randomly to a subset of eligible units (individuals, households, villages, schools, clinics, firms) and compares outcomes against the untreated control. Random assignment ensures that treatment and control groups are statistically equivalent at baseline; any subsequent difference in outcomes is attributable to the treatment.

The core methodological insight is that random assignment solves the selection problem that bedevils observational studies. When a programme is rolled out to those who self-select, those who are reached by administrators, or those whose local conditions make implementation easier, the participants differ from non-participants in ways that confound any simple comparison. Random assignment makes the groups comparable.

Several design considerations matter. The unit of randomisation should match the level at which the intervention operates and the effect plausibly occurs — village-level for community-wide interventions, individual-level for personally administered ones. Sample size must be large enough to detect the minimum effect of policy interest; this requires explicit power calculations. The outcomes measured should be specified in advance (pre-registered) to prevent fishing through the data for significant results. Implementation must be monitored to ensure treatment fidelity. Spillovers from treatment to control must be considered and either prevented or measured.

RCTs answer specific questions well: what is the average effect of this intervention on this outcome in this population? They do not answer: would the intervention work elsewhere (external validity), what is the mechanism (theory), what would happen at scale, what alternative policies might do better.

## How to Apply

1. **Define the question precisely** — intervention, population, outcomes, time horizon.
2. **Decide the unit of randomisation** — individual, household, village, school, district — based on where the intervention operates.
3. **Calculate sample size** for the minimum effect of policy interest.
4. **Pre-register the analysis plan** — primary and secondary outcomes, sub-group analyses, multiple-comparison corrections.
5. **Implement with fidelity monitoring** — verify the treatment was delivered as designed.
6. **Analyse and report honestly** — including null findings and the limits of external validity.

## Examples

**Situation:** Evaluating whether free distribution of insecticide-treated bed nets reaches more people than subsidised distribution.

**Application:** Randomise villages between free and subsidised distribution. Measure ownership, use, and malaria incidence at 6 and 12 months. The RCT-derived finding — free distribution dramatically outperforms subsidised — has shaped global malaria policy.

**Result:** A specific policy question with a specific answer that has saved millions of lives.

## Anti-Patterns

**Don't:** Pretend RCT findings answer questions they don't address.
**Why:** A finding about village-level effects does not tell us about scale effects, distributional effects, or political-economy feasibility.

**Don't:** Skip pre-registration.
**Why:** Post-hoc selection of outcomes inflates false positives. Pre-registration is the methodological discipline that makes findings credible.
