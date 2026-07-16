---
triggers:
  - "user asks about RCTs and generalisability"
  - "user asks about external validity"
  - "user asks about transporting results across contexts"
use_when:
  - "explaining why RCT results do not automatically generalise"
  - "advising on whether evidence from one context applies to another"
  - "critiquing the assumption that internal validity is sufficient for policy guidance"
fails_when:
  - "you dismiss RCTs entirely rather than identifying their specific limitations"
  - "you treat external validity as a minor technical problem rather than a fundamental logical challenge"
related:
  - "causal-inference-foundations.md"
  - "mechanisms-and-capacities.md"
  - "effectiveness-vs-efficacy.md"
  - "cartwright-vs-randomistas.md"
---

# RCTs and External Validity

## When to Use
- When assessing whether evidence from a trial in one context can inform policy in another.
- When someone claims that an RCT result establishes that a programme "works."
- When designing an evaluation and deciding how much weight to give to existing experimental evidence from other settings.

## Fails When
- **You treat the external validity problem as merely a call for more RCTs in more contexts.** The problem is logical, not just empirical. Even a hundred RCTs do not solve the external validity problem if you cannot articulate the mechanism and support conditions.
- **You dismiss external validity concerns by saying "some evidence is better than no evidence."** Misleading evidence can be worse than no evidence if it produces confident but wrong policy decisions.

## Core Concept
Cartwright's critique of the privileged status of RCTs centres on the distinction between internal and external validity. Internal validity asks: did the programme cause the observed effect in this study? External validity asks: will the programme cause a similar effect in a different population, context, or implementation?

An RCT with perfect internal validity establishes that, in the study population, under the study conditions, with the study implementation, the programme produced the observed effect. This is a valuable piece of knowledge. But the policy question is almost never "will this programme work in the exact conditions of the trial?" It is "will this programme work here — in our context, with our population, with our implementation capacity?"

The inference from "it worked there" to "it will work here" is not automatic. It requires additional premises: that the causal mechanism that produced the effect in the trial context will also operate in the policy context, and that the support conditions necessary for the mechanism to operate are present in the policy context. These premises cannot be established by the RCT itself. They require mechanism analysis, context assessment, and local knowledge.

Cartwright is precise about this: she does not argue that RCTs are useless or that internal validity does not matter. She argues that internal validity is not sufficient for policy guidance and that the additional evidence required for external validity — evidence about mechanisms and support conditions — is systematically neglected in the "what works" paradigm.

The practical implication is that evidence synthesis for policy should not be organised solely around the strength of internal validity (as evidence hierarchies do). It should also assess the relevance of existing evidence to the policy context, which requires understanding why programmes work, not just whether they worked somewhere.

## How to Apply
1. **When citing RCT evidence for a policy decision, explicitly state the inference chain.** The chain runs: the programme worked in context A → the mechanism that produced the effect was M → mechanism M requires support conditions S₁, S₂, S₃ → support conditions S₁, S₂, S₃ are present in context B → therefore, the programme is likely to work in context B. Each link requires evidence.
2. **Assess the similarity of contexts on causally relevant dimensions.** Not all differences between contexts matter. The relevant differences are those that affect the causal mechanism and its support conditions. Surface-level similarities (both are developing countries) may conceal deep differences in mechanisms.
3. **Commission mechanism studies alongside impact evaluations.** If you want evidence that travels, you need to understand why a programme works, not just that it works. Process evaluations and theory-based evaluations provide this understanding.

## Examples
**Situation:** The South African Department of Social Development is considering a youth employment programme modelled on an RCT-validated programme from Kenya. The Kenyan trial showed significant employment gains among urban youth who received vocational training combined with a cash stipend.
**Application:** Cartwright would identify the inference chain. The Kenyan programme worked because: (a) training provided skills that local employers demanded; (b) the stipend reduced liquidity constraints that prevented youth from investing in training; (c) local labour markets had unfilled vacancies in the sectors trained for. Each of these is a support condition. In South Africa, the binding constraint on youth employment is not primarily a skills mismatch — it is structural unemployment driven by insufficient labour demand, spatial disconnection between townships and job centres, and employer signalling through networks and credentials. The mechanism that worked in Kenya — skill-building meeting employer demand — may not operate in a context where employer demand is the binding constraint. The RCT evidence from Kenya is internally valid but its external validity for South Africa depends on whether these support conditions hold. They likely do not.

## Anti-Patterns
**Don't:** Respond to external validity concerns by saying "we just need to replicate the trial in South Africa."
**Why:** A replication trial answers the question for South Africa but does not solve the external validity problem for the next context. Understanding the mechanism allows prediction across contexts; replication provides only context-specific estimates.

**Don't:** Rank evidence solely by internal validity when making policy decisions.
**Why:** An RCT from an irrelevant context provides weaker policy guidance than a well-designed observational study from the policy context, because relevance — not just rigour — determines the value of evidence for a specific decision.
