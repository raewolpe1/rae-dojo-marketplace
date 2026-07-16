---
triggers:
  - "user asks about selection bias"
  - "user asks about the Heckman correction"
  - "user asks about sample selection"
use_when:
  - "explaining selection bias and its consequences for causal inference"
  - "advising on how to address selection in evaluation designs"
  - "introducing Heckman's foundational contribution to econometrics"
fails_when:
  - "you treat selection bias as a purely technical problem divorced from economic behaviour"
  - "you present the Heckman correction as the only solution to selection"
related:
  - "treatment-effects-and-heterogeneity.md"
  - "structural-vs-reduced-form.md"
  - "evaluation-methodology-critique.md"
---

# Selection Bias Foundations

## When to Use
- When explaining why naive comparisons between programme participants and non-participants are misleading.
- When advising on how to address selection in evaluation designs.
- When someone assumes that controlling for observable characteristics eliminates bias.

## Fails When
- **You treat selection as merely a statistical problem.** Selection is an economic problem — people make choices based on expectations, constraints, and private information. Modelling selection means modelling choice.
- **You present randomisation as the only solution to selection bias.** Heckman's work shows that structural modelling, instrumental variables, and control function approaches can address selection when randomisation is infeasible.

## Core Concept
Heckman's 1979 paper on sample selection bias is among the most cited in economics. The problem it addresses is fundamental: when the sample we observe is not randomly drawn from the population, estimates based on that sample are biased.

The canonical example is wage estimation. We observe wages only for people who work. But the decision to work is not random — it depends on potential wages, household circumstances, and preferences. If we estimate the wage equation using only working individuals, we systematically over- or under-estimate population wages because the sample is selected on a variable correlated with the outcome.

The two-step correction models the selection process explicitly: first estimate a model of selection (who enters the sample), then correct the outcome equation for the predicted probability of selection. The inverse Mills ratio — derived from the selection equation — captures the statistical effect of the truncated sample and allows recovery of unbiased estimates.

But Heckman's contribution goes beyond the correction technique. The deeper insight is that selection is pervasive in social science data and must be modelled, not ignored. Programme participation is selective. School enrolment is selective. Migration is selective. Labour force participation is selective. Every observational comparison between groups that were formed through individual choice is contaminated by selection, and the direction and magnitude of the bias depend on the economics of that choice.

For evaluation, this means that the fundamental challenge is not finding a clever identification strategy but understanding the selection process. Who participates and why? What unobserved factors drive participation that also affect outcomes? Once the selection process is understood, appropriate corrections can be applied — whether through exclusion restrictions, control functions, matching on the propensity score, or structural modelling.

## How to Apply
1. **Before estimating any programme effect, model the selection process.** Identify the factors that determine who participates. Distinguish factors that affect participation from factors that affect outcomes.
2. **Look for exclusion restrictions.** Variables that strongly predict programme participation but do not directly affect outcomes enable identification of the selection-corrected treatment effect.
3. **When randomisation is unavailable, use structural approaches.** The Heckman correction, control function methods, and structural models of programme choice can address selection when experimental designs are infeasible.

## Examples
**Situation:** An evaluation of a National Student Financial Aid Scheme (NSFAS) programme in South Africa compares graduation rates of funded students with unfunded students and finds that funded students graduate at higher rates.
**Application:** Heckman would identify severe selection bias. NSFAS recipients are selected through an application process that requires initiative, information access, and meeting academic thresholds. Students who successfully apply differ from non-applicants in motivation, academic preparation, family support, and access to information — all of which independently affect graduation. The naive comparison conflates the effect of funding with the effect of the characteristics that predicted receiving funding. A Heckman-style correction would model the NSFAS selection process (application, eligibility, academic threshold) and use variables that predict NSFAS receipt but do not directly affect graduation (e.g., distance from the NSFAS office, local information campaigns, specific eligibility cut-offs) to identify the funding effect net of selection.

## Anti-Patterns
**Don't:** Assume that matching on observables eliminates selection bias.
**Why:** Matching addresses selection on observables but not selection on unobservables. If unobserved factors (motivation, ability, social networks) drive both participation and outcomes, matching produces biased estimates.

**Don't:** Treat selection bias as an exotic problem affecting only certain studies.
**Why:** Selection bias is the default condition of observational data. Any comparison between self-selected groups is affected. The question is not whether selection bias exists but how large it is and in what direction.
