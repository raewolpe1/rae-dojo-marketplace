---
triggers:
  - "user asks about singular causation"
  - "user asks about general causal claims"
  - "user asks about whether a specific event caused an outcome"
use_when:
  - "explaining the difference between 'this programme caused this effect here' and 'this type of programme causes this type of effect'"
  - "clarifying what an evaluation result actually establishes"
  - "advising on attribution in a specific case versus generalisation across cases"
fails_when:
  - "you conflate singular and general causal claims as if they require the same evidence"
  - "you assume that general causal knowledge straightforwardly applies to individual cases"
related:
  - "causal-inference-foundations.md"
  - "counterfactuals-and-causation.md"
  - "causal-pluralism.md"
---

# Singular vs General Causation

## When to Use
- When distinguishing between claims about a specific programme implementation and claims about programme types.
- When someone infers from a general finding that a specific programme must have caused (or failed to cause) an effect.
- When discussing attribution in evaluation — did this programme cause this change?

## Fails When
- **You assume that knowing general causal relationships is sufficient for attributing outcomes in specific cases.** General knowledge tells you what tends to happen; singular causation tells you what happened here. The two require different evidence and different reasoning.
- **You treat all evaluation questions as questions about general causation.** Many evaluation questions are singular — did this specific intervention cause this specific outcome in this specific context? — and they cannot be answered by appeal to general findings alone.

## Core Concept
Cartwright draws on a distinction fundamental to philosophy of causation: the difference between singular and general causal claims. A singular causal claim asserts that a specific event or intervention caused a specific outcome in a specific instance — this cash transfer programme caused this household's income to increase. A general causal claim asserts that a type of cause tends to produce a type of effect — cash transfers increase household income.

The relationship between singular and general causation is not straightforward. A true general claim does not entail that every instance conforms. Cash transfers generally increase income, but this particular transfer to this particular household may not have, because of contextual factors that block the mechanism. Conversely, a singular causal success does not establish a general pattern — this transfer worked for this household, but the circumstances may be atypical.

For evaluation, this distinction matters in several ways. An RCT establishes a general claim: on average, across the study population, the treatment had an effect. It does not establish that the treatment caused the effect for any particular individual. The average treatment effect is consistent with the treatment having large positive effects for some participants, no effect for others, and negative effects for still others. Moving from the average to the particular requires additional reasoning about heterogeneity and mechanisms.

For policy, the distinction matters because policy decisions are often about specific contexts — will this programme work here? — which is closer to a singular claim than a general one. The general finding that the programme type works tells you something relevant, but it does not tell you what will happen in this particular implementation, with this particular population, in this particular institutional environment.

## How to Apply
1. **Clarify whether the evaluation question is singular or general.** Is the question "does this type of programme work?" (general) or "did this specific programme work in this context?" (singular)? The answer determines the type of evidence needed.
2. **Do not infer singular causation directly from general claims.** Even if microfinance generally reduces poverty, you cannot conclude that this microfinance programme reduced poverty for this community without examining the specific implementation and context.
3. **Use general causal knowledge as one input to singular causal reasoning.** General knowledge establishes that the mechanism can operate. Singular causal reasoning then assesses whether the mechanism did operate in the specific case, given the specific conditions.

## Examples
**Situation:** A provincial government in Mpumalanga implements a community-based violence prevention programme modelled on Cure Violence. A national evaluation of Cure Violence-type programmes in South Africa finds no statistically significant average effect. The provincial government asks: should we conclude our programme failed?
**Application:** Cartwright would argue that the general finding (no average effect across all sites) does not establish a singular conclusion about Mpumalanga. The average may conceal heterogeneity — the programme may have worked in some sites and failed in others. Whether it worked in Mpumalanga is a singular causal question that requires examining the Mpumalanga implementation specifically: were the violence interrupters well-connected to the communities? Were the transmission mechanisms (interrupting conflicts, changing norms, connecting individuals to services) operating in this site? A null average effect is consistent with the Mpumalanga programme having succeeded, if other sites pulled the average down. The provincial government should assess the singular case on its own evidence, using the general finding as context but not as a verdict.

## Anti-Patterns
**Don't:** Treat average treatment effects as applying uniformly to all participants or all contexts.
**Why:** The average is a summary statistic that may describe no actual individual's experience. Heterogeneity is the norm in social programmes, and the distribution of effects matters at least as much as the mean.

**Don't:** Dismiss the relevance of general causal knowledge for singular cases.
**Why:** General knowledge is relevant — it tells you what can happen and what mechanisms might operate. The error is treating it as sufficient, not treating it as irrelevant. Singular causal reasoning uses general knowledge as input alongside case-specific evidence.
