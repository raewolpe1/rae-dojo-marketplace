---
triggers:
  - "user asks about Heckman's critique of evaluation methods"
  - "user asks about problems with programme evaluation"
  - "user asks about what evaluations get wrong"
use_when:
  - "critiquing evaluation designs that focus narrowly on average effects"
  - "advising on more rigorous and policy-relevant evaluation approaches"
  - "explaining the limitations of current evaluation practice from Heckman's perspective"
fails_when:
  - "you present the critique as anti-evaluation"
  - "you ignore that Heckman himself has conducted extensive programme evaluations"
related:
  - "heckman-vs-randomistas.md"
  - "structural-vs-reduced-form.md"
  - "treatment-effects-and-heterogeneity.md"
  - "selection-bias-foundations.md"
---

# Evaluation Methodology Critique

## When to Use
- When reviewing evaluation designs for methodological adequacy.
- When advising on what evaluation methods can and cannot answer.
- When someone assumes that a well-designed evaluation automatically produces policy-relevant evidence.

## Fails When
- **You treat the critique as a rejection of empirical evaluation.** Heckman's critique is internal — he wants better evaluation, not less evaluation.
- **You focus on technical critiques while ignoring the deeper point about what questions evaluation should answer.** The fundamental issue is that most evaluations answer a narrow question (did this programme have an average effect?) when policy requires answers to broader questions (who benefits? through what mechanism? what happens at scale?).

## Core Concept
Heckman's critique of evaluation methodology targets several systematic weaknesses in current practice.

First, the focus on average treatment effects obscures the distribution of effects. Most evaluations report a single number — the ATE or ATT — without exploring who benefits, who does not, and who is harmed. For policy, the distribution matters more than the mean. A programme with a positive ATE may have strong effects on a subgroup and no effect on the majority, which has very different policy implications than a programme with a moderate effect on everyone.

Second, evaluations rarely connect reduced-form estimates to the economic parameters needed for policy design. Knowing that a job training programme increases employment by eight percentage points tells you something about the current programme. It does not tell you what would happen if you changed the training duration, the curriculum, the targeting criteria, or the scale. Policy design requires structural parameters — elasticities, behavioural responses, skill production functions — that reduced-form evaluations do not estimate.

Third, evaluations typically ignore general equilibrium effects. A small-scale trial does not affect market conditions. But a scaled programme that trains 100,000 workers may depress wages in the occupations trained for, may crowd out private training, and may shift employer behaviour. These effects are absent from trial estimates but present in scaled programmes.

Fourth, the time horizon of most evaluations is too short. Human capital programmes have effects that compound over decades. Measuring a training programme's effect at six months captures the immediate employment response but misses the long-term career trajectory. The Perry Preschool evidence showed that the most important effects emerged twenty to thirty years after the programme ended.

Fifth, the evaluation industry creates perverse incentives. The pressure to show "impact" leads to evaluating programmes where effects are easiest to detect (small, targeted interventions) rather than programmes where the policy stakes are highest (large, systemic reforms). The tail of evaluation wags the dog of programme design.

## How to Apply
1. **Require heterogeneity analysis in all evaluations.** Mandate subgroup analysis by key dimensions (gender, education, baseline characteristics, location) and explore treatment effect distributions, not just averages.
2. **Commission structural analysis alongside reduced-form evaluation.** Include components that estimate the behavioural parameters needed for programme redesign and scaling decisions.
3. **Extend evaluation time horizons.** For human capital programmes, plan for follow-up data collection years or decades after programme completion.

## Examples
**Situation:** An evaluation of South Africa's Jobs Fund finds that funded projects created an average of 50 jobs per project at a cost of R100,000 per job. The evaluation is presented as evidence of the Fund's effectiveness.
**Application:** Heckman would identify several gaps. First, are these 50 jobs net of displacement — did the funded projects create new employment or simply shift employment from unfunded competitors? A general equilibrium analysis is needed. Second, who got the jobs? If the "average of 50 jobs" comes from a few highly successful projects and many that created few or no jobs, the distribution matters more than the average for allocating future funding. Third, are the jobs sustained? Cost per job at project completion does not capture whether jobs persist after funding ends. Fourth, what are the structural parameters? What characteristics of projects predict success? What industry, location, firm size, and training model features are associated with higher returns? These parameters are needed for targeting future funding. The headline number — 50 jobs at R100,000 each — is an average that answers the narrowest possible question and provides almost no guidance for improving the Fund.

## Anti-Patterns
**Don't:** Treat evaluation critique as a reason to avoid evaluation.
**Why:** The solution to inadequate evaluation is better evaluation, not less. Heckman's critiques identify specific improvements (heterogeneity analysis, structural components, longer horizons, general equilibrium) that would make evaluation more useful.

**Don't:** Accept that the primary purpose of evaluation is accountability.
**Why:** Accountability is one function, but the primary purpose of evaluation should be learning — understanding what works, for whom, through what mechanism, and at what scale. Accountability-driven evaluation that produces a "pass/fail" verdict without generating learning has minimal policy value.
