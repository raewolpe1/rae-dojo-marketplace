---
triggers:
  - "user asks about counterfactual causation"
  - "user asks about the counterfactual model"
  - "user asks about 'what would have happened without the programme'"
use_when:
  - "explaining the strengths and limitations of counterfactual approaches to causation"
  - "advising on when counterfactual reasoning is appropriate and when it is insufficient"
  - "clarifying what an RCT's counterfactual actually establishes"
fails_when:
  - "you dismiss counterfactual reasoning as merely hypothetical"
  - "you treat counterfactual dependence as the only legitimate form of causal reasoning"
related:
  - "causal-inference-foundations.md"
  - "causal-pluralism.md"
  - "singular-vs-general-causation.md"
  - "rcts-and-external-validity.md"
---

# Counterfactuals and Causation

## When to Use
- When discussing the counterfactual model of causation that underpins experimental evaluation.
- When someone asks what it means to say a programme "caused" an outcome.
- When clarifying the assumptions behind difference-in-differences, propensity score matching, or other counterfactual methods.

## Fails When
- **You present the counterfactual model as the definition of causation rather than one concept among several.** It is an important and useful concept, but it captures only one aspect of causation.
- **You ignore the epistemic problem: counterfactuals are about what did not happen, which is inherently unobservable.** Every counterfactual claim requires assumptions about what would have occurred in the absence of the intervention — assumptions that can never be directly verified.

## Core Concept
The counterfactual model of causation, formalised by David Lewis and applied to social science through the potential outcomes framework of Rubin and Holland, defines causation as counterfactual dependence: X caused Y if and only if Y would not have occurred (or would have been different) in the absence of X. This is the philosophical foundation of experimental and quasi-experimental evaluation methods.

Cartwright acknowledges the power of this framework. It provides a clear, formal definition of what it means for an intervention to have an effect, and it grounds a family of estimation methods (randomisation, matching, differencing) that can — under their respective assumptions — identify the counterfactual contrast.

However, she identifies several limitations. First, the counterfactual model tells you that X made a difference but not how or why. It identifies difference-making without revealing the causal process. For policy, knowing how is often more useful than knowing that, because how tells you whether the effect will replicate.

Second, the fundamental problem of causal inference — that the counterfactual is unobservable — means that every causal estimate rests on assumptions. In an RCT, the assumption is that randomisation produces comparable groups. In difference-in-differences, the assumption is parallel trends. In propensity score matching, the assumption is selection on observables. These assumptions may or may not hold, and they can never be fully verified. The counterfactual model does not eliminate the need for judgment — it relocates it from the causal claim to the identifying assumptions.

Third, the counterfactual model has difficulty with cases of causal redundancy, where multiple causes are each sufficient. If both A and B are sufficient to produce Y, and both are present, then Y would have occurred without A (because B was present) and without B (because A was present). Neither A nor B is a counterfactual difference-maker, yet both intuitively caused Y. This is not merely a philosophical puzzle — it arises in complex social programmes where multiple factors jointly produce outcomes.

## How to Apply
1. **When using counterfactual methods, be explicit about the identifying assumptions.** State what you are assuming about the counterfactual and assess whether the assumption is plausible in the specific context.
2. **Supplement counterfactual estimation with mechanism analysis.** The counterfactual tells you the size of the effect; the mechanism tells you why it occurred and whether it will occur again.
3. **Recognise that the counterfactual framing shapes what questions are asked.** The counterfactual model naturally leads to "did the programme have an effect?" questions. But policy often needs "how does the programme work?" and "under what conditions will it work?" questions, which require different frameworks.

## Examples
**Situation:** An evaluation of the Expanded Public Works Programme (EPWP) in Gauteng uses propensity score matching to estimate the programme's effect on participants' employment. The evaluators find a statistically significant positive effect on employment during programme participation but no effect after participants exit the programme.
**Application:** Cartwright would first examine the identifying assumption: that selection on observables is sufficient — that there are no unobserved differences between EPWP participants and matched non-participants that affect both programme participation and subsequent employment. In the South African context, this assumption is questionable: motivation, social networks, and spatial proximity to work opportunities are difficult to observe and likely affect both selection into EPWP and employment outcomes. The counterfactual estimate may be biased. More fundamentally, the counterfactual analysis tells you the programme provided temporary employment (which is definitional — participants are employed while on the programme) but not why it failed to generate lasting employment effects. Mechanism analysis would ask: what was the pathway from temporary public works to sustained employment? Was it skills acquisition? Work experience signalling? Network building? If none of these mechanisms operated effectively — because the work was unskilled, employers did not value EPWP experience, and the programme did not build professional networks — then the null post-programme effect is explained. The counterfactual identifies the result; the mechanism explains it.

## Anti-Patterns
**Don't:** Treat the counterfactual as a simple "what would have happened" that can be straightforwardly observed.
**Why:** The counterfactual is inherently hypothetical. Every method for estimating it involves assumptions about unobserved states of the world. The assumptions should be scrutinised, not hidden behind technical confidence.

**Don't:** Abandon counterfactual reasoning because it requires assumptions.
**Why:** All causal reasoning requires assumptions. The virtue of the counterfactual framework is that it makes many of its assumptions explicit and testable. The right response is to use it critically, not to reject it entirely.
