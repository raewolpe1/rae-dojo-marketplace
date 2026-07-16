---
triggers:
  - "user asks about structural econometrics"
  - "user asks about reduced form versus structural approaches"
  - "user asks about whether RCTs can answer policy design questions"
use_when:
  - "explaining the debate between structural and reduced-form approaches"
  - "advising on when structural models are necessary for policy analysis"
  - "critiquing the limitations of design-based causal inference"
fails_when:
  - "you dismiss reduced-form methods as useless"
  - "you present structural models as infallible or assumption-free"
related:
  - "selection-bias-foundations.md"
  - "treatment-effects-and-heterogeneity.md"
  - "heckman-vs-randomistas.md"
---

# Structural vs Reduced Form

## When to Use
- When a policy question requires predicting the effects of a programme that has never been tried.
- When discussing whether experimental evidence is sufficient for policy design.
- When advising on evaluation approaches for complex policy decisions.

## Fails When
- **You present the structural approach as universally superior.** Structural models require assumptions that may be wrong. The advantage is that the assumptions are explicit and testable; the risk is that they may be misspecified.
- **You ignore the complementarity between approaches.** Reduced-form estimates can validate structural model predictions; structural models can extend reduced-form findings to new counterfactuals. The best work uses both.

## Core Concept
Heckman draws a fundamental distinction between reduced-form and structural approaches to empirical economics. Reduced-form methods — RCTs, instrumental variables, difference-in-differences, regression discontinuity — estimate the causal effect of a specific treatment under specific conditions without specifying the economic model that generates the data. Structural methods specify an economic model of behaviour (preferences, technology, constraints, information) and estimate the model's parameters, which can then be used to simulate the effects of counterfactual policies.

The reduced-form approach has dominated empirical economics since the "credibility revolution" of the 1990s and 2000s. Its strength is transparency: the identifying assumptions are clearly stated, and the estimates have clear causal interpretations. Its limitation is narrowness: a reduced-form estimate tells you the effect of a specific, implemented policy but cannot tell you the effect of a modified policy, a different targeting rule, or a novel programme design.

Heckman argues that for most policy questions, structural models are necessary. If the question is "should we expand the existing programme by 20%?", the answer depends on the marginal treatment effect, which requires modelling how the programme's returns vary across the population — a structural question. If the question is "should we redesign the programme with a different subsidy structure?", the answer requires predicting behaviour under conditions that have never been observed — which only a structural model can do. If the question involves general equilibrium — "what happens to wages if we train a million workers?" — the answer requires a model of the labour market, not just a treatment effect estimate.

The structural approach is not assumption-free. It requires specifying functional forms, distributional assumptions, and equilibrium conditions. But Heckman argues that these assumptions are explicit and can be tested, whereas reduced-form methods also rely on assumptions (parallel trends, exclusion restrictions, selection on observables) that are often untested and untestable.

## How to Apply
1. **Match the method to the policy question.** If the question is about an existing programme's effect, reduced-form methods may suffice. If the question involves novel policies, scaling, targeting, or general equilibrium, structural approaches are needed.
2. **Use reduced-form estimates to validate structural models.** Estimate both. If the structural model's predictions align with reduced-form estimates for cases where both apply, confidence in the structural model increases.
3. **When commissioning evaluations for policy design, require structural components.** Programme evaluations that only estimate average effects under current conditions do not provide the information needed to redesign, retarget, or scale the programme.

## Examples
**Situation:** The South African National Treasury is designing a youth employment tax incentive. Several RCTs of wage subsidy programmes exist from other countries. Treasury asks: can we use these results to predict the effect of our proposed incentive design?
**Application:** Heckman would argue that the RCT results cannot directly answer this question because South Africa's proposed design differs from the evaluated programmes in subsidy amount, duration, targeting criteria, and labour market context. The RCTs tell you that specific subsidy designs worked in specific contexts. Predicting the effect of South Africa's design requires a structural model of firm hiring decisions that captures how firms respond to changes in the cost of labour, how the subsidy interacts with existing labour regulations, how workers respond to the employment opportunity, and how the programme affects equilibrium wages. The structural model can be disciplined by the international RCT evidence (using it to calibrate parameters) while extending the analysis to the untried South African design. Without the structural model, Treasury is guessing — using an average from different programmes in different countries as a proxy for the effect of a different programme in South Africa.

## Anti-Patterns
**Don't:** Treat reduced-form and structural approaches as competing paradigms where one must be chosen.
**Why:** They are complementary. Reduced-form methods provide credible estimates of specific effects. Structural models extend those findings to policy-relevant counterfactuals. The best empirical work integrates both.

**Don't:** Dismiss structural models because they require assumptions.
**Why:** All empirical methods require assumptions. The advantage of structural models is that their assumptions are explicit, derived from economic theory, and testable against data. The assumptions behind reduced-form methods are often equally strong but less transparent.
