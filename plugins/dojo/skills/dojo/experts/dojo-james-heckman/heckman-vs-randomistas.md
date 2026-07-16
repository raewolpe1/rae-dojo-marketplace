---
triggers:
  - "user asks about Heckman's critique of RCTs"
  - "user asks about the econometrics debate on experiments"
  - "user asks about structural versus experimental approaches"
use_when:
  - "explaining Heckman's position in the debate about randomised trials"
  - "advising someone navigating between experimental and structural approaches"
  - "contextualising the 'credibility revolution' debate in economics"
fails_when:
  - "you present Heckman as anti-experiment"
  - "you caricature the randomistas as naive about the limitations of RCTs"
related:
  - "structural-vs-reduced-form.md"
  - "evaluation-methodology-critique.md"
  - "treatment-effects-and-heterogeneity.md"
---

# Heckman vs the Randomistas

## When to Use
- When navigating the debate between experimental and structural approaches to evaluation.
- When explaining what Heckman believes RCTs can and cannot do.
- When advising on evaluation methodology in institutional contexts that privilege one approach.

## Fails When
- **You frame the debate as experiments versus no experiments.** Heckman uses experiments where appropriate. His critique targets the claim that experiments are the only or best source of causal evidence for policy.
- **You miss the core disagreement.** The disagreement is not about whether RCTs produce internally valid estimates (they can) but about whether those estimates are sufficient for policy guidance (Heckman says they are not).

## Core Concept
Heckman's position in the debate with the randomistas (Banerjee, Duflo, and the J-PAL movement) is distinctive because it comes from someone with deep technical authority in econometrics. He is not a qualitative researcher challenging quantitative methods — he is a quantitative methodologist challenging a specific quantitative paradigm.

His critique has several dimensions. First, RCTs answer a limited question. They estimate the average effect of a specific treatment on a specific population under specific conditions. They do not estimate the effect of treatment modifications, alternative targeting, or scaling — the questions policymakers most need answered.

Second, the LATE identified by an RCT (or by IV) applies to a specific subgroup (compliers) that may be unrepresentative of the policy-relevant population. Heckman's work on marginal treatment effects shows that the treatment effect varies across the population and that the average effect for the experimentally identified group may differ substantially from the effect at the margin of programme expansion.

Third, the design-based approach has produced a "con" — what Heckman calls the "con in econometrics" — where clever identification is valued over economic substance. A paper with a credible instrument is publishable regardless of whether it answers an economically important question. This has distorted the research agenda toward questions that are experimentally tractable and away from questions that are policy-important.

Fourth, randomisation is neither necessary nor sufficient for credible causal inference. It is sufficient for estimating the ATE under certain conditions (compliance, no spillovers, no attrition), but it is not necessary — well-specified structural models can produce causal estimates from observational data. And it is not sufficient for policy because internal validity does not imply external validity or policy relevance.

Heckman's constructive alternative is not to abandon experiments but to embed them within structural frameworks. Use experimental variation to identify structural parameters. Combine experimental and observational evidence. Build models that can simulate counterfactual policies. Estimate the distribution of treatment effects, not just the average.

## How to Apply
1. **When commissioning evaluations, specify the policy question before selecting the method.** If the question requires predicting the effects of a novel policy, structural methods are needed alongside or instead of experimental methods.
2. **Combine experimental and structural approaches in evaluation designs.** Use randomised variation to identify key parameters within a structural model that can then address broader policy questions.
3. **Demand heterogeneity analysis from experimental evaluations.** At minimum, require subgroup analysis. Ideally, estimate marginal treatment effects to understand how returns vary across the population.

## Examples
**Situation:** A South African evaluation commissioner receives competing proposals for a youth employment evaluation — one using an RCT and one using a structural labour market model calibrated with survey data. The RCT proposal is for the existing programme; the structural proposal can analyse alternative designs.
**Application:** Heckman would argue for a combined approach. The RCT provides credible identification of the current programme's average effect — useful for accountability but limited for policy design. The structural model can use the RCT's experimental variation to identify key behavioural parameters (reservation wages, search intensity, employer responses to subsidies) and then simulate the effects of programme modifications (different subsidy levels, different eligibility criteria, different durations) that the RCT cannot test. The commissioner should fund both: the RCT for what it does well (internally valid effect estimation) and the structural analysis for what it does well (counterfactual policy prediction). The cost of the structural component is modest relative to the RCT, and the additional policy value is substantial.

## Anti-Patterns
**Don't:** Dismiss Heckman's critique as academic turf warfare.
**Why:** The critique is substantive, not territorial. The limitations of RCTs for policy guidance are real, and the overreliance on experimental methods has real costs — diverting evaluation resources away from the mechanism, heterogeneity, and structural analysis that policy requires.

**Don't:** Accept that methodological rigour equals experimental design.
**Why:** Rigour means appropriate methods for the question at hand. An experiment that answers the wrong question with perfect internal validity is less rigorous, in a meaningful sense, than a structural analysis that answers the right question with well-tested assumptions.
