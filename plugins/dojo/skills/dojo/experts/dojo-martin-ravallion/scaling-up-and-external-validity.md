---
triggers:
  - "user mentions external validity, scaling up, generalisation of RCTs"
  - "user asks whether an impact-evaluation result will hold at scale"
  - "user is debating RCTs vs natural experiments"
use_when:
  - "the question is about whether a study's results will travel to a different population, scale, or context"
  - "the user is critiquing or defending the RCT movement"
  - "you need to argue that internal validity is not sufficient for policy"
fails_when:
  - "the policy decision is genuinely about the population that was studied"
  - "the audience wants a moral judgment rather than empirical assessment"
  - "you dismiss internal validity as worthless"
related:
  - "evaluating-anti-poverty-programmes.md"
  - "measurement-error-and-survey-design.md"
  - "pro-poor-growth.md"
---

# Scaling Up and External Validity

## When to Use
- When advising on whether to extrapolate an impact-evaluation result to a policy decision at scale.
- When critiquing a study that overclaims based on internal validity alone.
- When designing an evaluation that will inform scale-up decisions.
- When responding to claims that RCTs have settled a policy question.

## Fails When
- **The policy decision is to continue the specific programme that was evaluated for the population that was studied.** Internal validity may then be sufficient.
- **The audience wants a polemic against RCTs rather than empirical assessment.** The methodological tradition has produced real gains in internal validity; the critique is of its limits, not its existence.
- **You dismiss internal validity as worthless.** Internal validity is a precondition for external validity; an internally invalid study has no external validity to extrapolate.

## Core Concept
Internal validity and external validity are different properties. Internal validity asks: is the experimental estimate of the treatment effect unbiased for the population that was studied? External validity asks: is the estimate informative about the effect of the same intervention on a different population in a different context delivered through different institutions?

An impact evaluation with high internal validity may have low external validity. The randomised experiment that produced the estimate may have been conducted in a specific district with a specific implementing partner under specific conditions that do not generalise. The estimated treatment effect is unbiased for the experimental population; it is not unbiased for the population that will receive the policy.

The randomised-controlled-trial movement in development economics has emphasised internal validity. Cleaner experiments, more robust standard errors, better-identified effects. These are real gains. The cost has been the relative under-emphasis of external validity. The literature has many internally valid estimates and fewer externally valid policy lessons.

Scaling involves three transitions, each affecting external validity.

First, the population transition. The experimental sample is selected, often by an NGO or research team that chose the implementing context. The scaled-up programme will reach a population that includes the experimental sample as a special case but extends to populations the implementing partner would not have selected. The non-selected populations may have different baselines, different responsiveness to the treatment, and different supply-side environments. The average treatment effect from the experiment is not the average treatment effect at scale.

Second, the implementer transition. The experimental implementer is often an NGO with high administrative capacity. The scaled-up implementer is usually a government ministry with different incentives, different administrative capacity, and different relationships to the target population. The implementer transition typically reduces effectiveness, sometimes dramatically. Banerjee, Banerji, Berry, Duflo, et al. (2017) document the gap between NGO-implemented and government-implemented versions of the same education intervention.

Third, the equilibrium transition. The experiment estimates effects holding general equilibrium constant. At scale, the programme changes the equilibrium — labour-market prices, school capacity, credit availability, supplier behaviour. The general-equilibrium effects can amplify or dampen the partial-equilibrium estimate, sometimes substantially. Microcredit programmes that raised borrowers' incomes in small pilots have produced much smaller effects at scale partly because of equilibrium effects on the local credit market.

The literature has methodologies to address external validity, but they are under-used. Natural experiments that exploit policy variation across regions or time provide evidence at scales relevant to policy. Structural estimation calibrates models that can be used to simulate counterfactuals at different scales. Site-selection randomisation extends external validity by selecting implementation contexts at random rather than by convenience. Comparison of pilot effects to scaled-up effects in the same setting provides direct evidence on the scaling gap. None of these is a substitute for the internally clean RCT; all are complements to it.

The defensible position is: internal validity is necessary but not sufficient. Policy decisions require external validity, which requires methodologies that go beyond the RCT. The RCT is a tool; it is not the only tool, and its results require interpretation in light of the scaling transitions.

## How to Apply
1. **Distinguish internal from external validity claims.** When a study claims an effect, ask whether the claim is about the experimental population or about the policy-relevant population.
2. **Identify the scaling transitions.** Will the population, implementer, and equilibrium be the same at scale as in the experiment? Where they differ, the estimated effect requires adjustment.
3. **Use complementary methodologies.** Natural experiments, structural estimation, site-selection randomisation, and direct comparison of pilot and scaled effects can address external validity that the RCT alone cannot.
4. **Plan for scale-up evaluation.** If a programme is scaled, design the rollout to allow learning during the scale-up. Phased rollouts, regional variation, and staggered implementation provide identification opportunities the original pilot did not.
5. **Be transparent about confidence at scale.** The scaled-up effect is a different parameter than the experimental ATE. State the assumptions required to extrapolate; assess robustness.

## Examples
**Situation:** A microcredit RCT finds a small positive effect on borrower income. The country is considering nationwide scale-up of the microcredit model.
**Application:** The experimental effect is for the population the implementing MFI selected, in the districts the MFI chose, with the credit terms the MFI offered, holding the credit market constant. At scale, the MFI will reach new populations (with different baselines), the government may regulate the credit market differently, and the local credit market will adjust to the increased supply of formal credit. The experimental effect is unlikely to survive scaling intact. The scale-up plan should incorporate evidence on at-scale microcredit from other contexts, structural modelling of credit-market equilibrium, and a phased rollout that generates evidence at the policy-relevant scale.
**Result:** The experimental result is informative but does not by itself justify nationwide scale-up.

**Situation:** A randomised evaluation of a conditional cash transfer in three districts finds large positive effects on school enrolment. The team proposes national scale-up.
**Application:** The districts were selected by the implementing NGO; they may have had stronger schools, better-supplied teachers, and more responsive local government than the average district nationally. At scale, the supply-side capacity will be the binding constraint in many districts; the conditions will be applied to a population whose schools cannot absorb the additional demand. The headline enrolment effect is unlikely to scale. The strategy should include supply-side investment, phased rollout to detect scaling gaps, and ongoing monitoring of the supply-demand match.
**Result:** The experimental result is the upper bound. The scaled-up effect will be smaller; design for the supply-side constraints that the experiment did not face.

## Anti-Patterns
**Don't:** Treat internal validity as a settled question for policy.
**Why:** Internal validity tells you about the experimental population; policy is about the scaled population. The two are different.

**Don't:** Dismiss methodologies that compromise internal validity in pursuit of external validity.
**Why:** Natural experiments, structural estimation, and quasi-experimental approaches sacrifice internal-validity precision for external-validity reach. For most policy questions, the latter is the binding constraint.

**Don't:** Treat the RCT literature as having settled the case for a policy.
**Why:** The literature has settled the experimental population's response to the experimental version of the intervention. The scaled-up version, the scaled-up population, and the scaled-up equilibrium are different parameters.
