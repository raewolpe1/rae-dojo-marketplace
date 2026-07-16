---
triggers:
  - "user is evaluating or designing an evaluation of an anti-poverty programme"
  - "user mentions impact evaluation, treatment effect, counterfactual"
  - "user is critiquing an evaluation report"
use_when:
  - "the question is about how to evaluate a programme's effect on poverty credibly"
  - "the user is choosing among evaluation designs"
  - "you need to assess whether an evaluation's claim is supported by its design"
fails_when:
  - "the user wants a verdict without engaging the design"
  - "the data do not support the claimed identification strategy"
  - "you mistake methodological rigour for substantive importance"
related:
  - "scaling-up-and-external-validity.md"
  - "measurement-error-and-survey-design.md"
  - "targeting-vs-universalism.md"
---

# Evaluating Anti-Poverty Programmes

## When to Use
- When designing an evaluation of an anti-poverty programme.
- When critiquing an impact evaluation that claims a particular effect.
- When advising on whether the evaluation's evidence supports the proposed scale-up or termination.
- When responding to claims that a programme has been proved to work or proved to fail.

## Fails When
- **The data do not support the claimed identification strategy.** Difference-in-differences requires parallel pre-trends; regression discontinuity requires a sharp cut-off; instrumental variables require a credible exclusion restriction. Without these, the design fails on its own terms.
- **The user wants a methodological verdict rather than substantive engagement.** A clean evaluation of an irrelevant question is less useful than a less-clean evaluation of a relevant one.
- **You confuse rigour with importance.** A perfectly executed evaluation of a marginal policy decision is less valuable than a less perfect evaluation of a consequential one.

## Core Concept
Evaluating an anti-poverty programme requires answering one core question: what would have happened in the absence of the programme? Every evaluation design is an answer to this counterfactual question, and the credibility of the evaluation rests on how well its design constructs the counterfactual.

The main designs are familiar. Randomised controlled trials construct the counterfactual through random assignment to treatment and control. Difference-in-differences constructs the counterfactual by assuming that the treatment and control groups would have followed parallel trends in the absence of treatment. Regression discontinuity constructs the counterfactual at the eligibility cut-off by comparing those just above and just below. Instrumental variables constructs the counterfactual by exploiting variation in treatment uptake that is independent of the outcome. Matching constructs the counterfactual by pairing treated units to similar untreated units. Each design has assumptions; the credibility of the evaluation depends on whether those assumptions hold in the specific context.

The empirical reality is that most anti-poverty programmes are evaluated by less than ideal designs because random assignment is politically infeasible, regression-discontinuity cut-offs are blurry, instruments are weak, and matching covers heterogeneity poorly. The literature has tools to assess these challenges and to bound the resulting bias; the tools are under-used.

Beyond identification, four substantive considerations distinguish a credible evaluation from a less credible one.

First, intent-to-treat vs treatment-on-treated. The intent-to-treat estimate captures the effect on all eligible people, including those who did not take up the programme. The treatment-on-the-treated estimate captures the effect on those who actually participated. Both are policy-relevant — ITT is the relevant parameter for policy decisions about offering the programme to a population; ToT is the relevant parameter for understanding the mechanism. Reporting only one is incomplete.

Second, spillovers. The control group may benefit from the programme through general-equilibrium effects, social spillovers, or contamination by treated peers. If the spillover is positive, the estimated effect understates the true treatment effect; if it is negative, the estimated effect overstates it. The evaluation should engage spillovers directly.

Third, heterogeneity. The average treatment effect averages across heterogeneous responses. The effect on the poorest may differ from the effect on the near-poor. The effect in some regions may differ from the effect in others. Reporting heterogeneity is essential for policy design — it tells the policy-maker which sub-populations the programme works for.

Fourth, the welfare interpretation. A programme that raises consumption by 10 per cent for the poor is not the same as a programme that raises consumption by 10 per cent for everyone. The welfare interpretation depends on the distribution of effects and on the welfare weights placed on different parts of the distribution. Distributionally weighted effects can be more informative than the simple ATE.

The Ravallion position is that internal validity is a necessary but not sufficient condition for evaluation usefulness. The most credibly identified estimate may be uninformative for the policy decision it is intended to inform. The evaluator's job is to produce an estimate that is both credibly identified and policy-relevant; one without the other is not enough.

## How to Apply
1. **Specify the counterfactual.** What would have happened in the absence of the programme? The design must construct this counterfactual; the credibility of the evaluation rests on it.
2. **Assess the design's assumptions.** Random assignment is verifiable; parallel pre-trends require a long pre-period; instruments require an exclusion restriction. Test the assumptions in the specific context.
3. **Report ITT and ToT.** Both are policy-relevant. The ITT effect for scaling decisions; the ToT effect for understanding the mechanism.
4. **Engage spillovers.** General-equilibrium and social spillovers can dominate partial-equilibrium estimates. Design the evaluation to detect them where possible.
5. **Report heterogeneity.** The average effect is rarely the policy-relevant effect. Heterogeneity reveals which sub-populations benefit and which do not.
6. **Translate to welfare.** A consumption effect is informative; a poverty effect is more directly policy-relevant. Distributionally weighted welfare measures can capture what the ATE misses.

## Examples
**Situation:** An evaluation finds an 11-point average treatment effect on a programme-targeted outcome. The evaluators recommend scale-up.
**Application:** Investigate four things. First, internal validity — is the design's identification strategy credible in this context? Second, the ITT vs ToT distinction — what fraction of the eligible population was treated, and what is the policy-relevant parameter? Third, heterogeneity — is the average effect a useful summary or a misleading one? Fourth, external validity — will the experimental population, implementer, and equilibrium be the same at scale? The 11-point average is the start of the assessment, not its conclusion.
**Result:** The recommendation requires substantive scrutiny across all four dimensions before policy commitment.

**Situation:** An evaluation reports a null effect of an anti-poverty programme on consumption.
**Application:** Diagnose the null. Is it a true zero, suggesting the programme does not work? Is it a power problem, suggesting the sample is too small to detect a modest effect? Is it a measurement problem, suggesting the consumption measure is too noisy? Is it a timing problem, suggesting the effect takes longer to materialise than the follow-up window? Each diagnosis has different policy implications.
**Result:** A null is informative but only when the source of the null is understood.

## Anti-Patterns
**Don't:** Treat a methodologically clean evaluation as sufficient evidence for scale-up.
**Why:** Internal validity does not imply external validity. The clean estimate may not be informative about the scaled policy decision.

**Don't:** Treat the ATE as the answer to every policy question.
**Why:** Heterogeneity, spillovers, and welfare weights all modify the policy interpretation of the ATE. Reporting only the ATE conceals the more substantive analytics.

**Don't:** Reject a less-clean evaluation in favour of a clean evaluation that is uninformative.
**Why:** A less-precise estimate of the policy-relevant parameter is more useful than a precise estimate of a different parameter.
