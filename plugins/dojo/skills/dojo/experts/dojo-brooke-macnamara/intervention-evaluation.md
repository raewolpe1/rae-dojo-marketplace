---
triggers:
  - "user asks how to evaluate whether an intervention works"
  - "user asks about interpreting programme evaluation results"
  - "user asks about control conditions and their implications"
use_when:
  - "evaluating the results of a programme evaluation or RCT"
  - "helping someone interpret evaluation findings with appropriate caution"
  - "assessing whether evaluation results justify scaling or continued funding"
fails_when:
  - "you dismiss all evaluation evidence as inadequate"
  - "you ignore practical constraints on evaluation design"
  - "you treat methodological purity as more important than useful evidence"
related:
  - "evidence-quality-audit.md"
  - "effect-size-literacy.md"
  - "causal-inference-standards.md"
---

# Intervention Evaluation

## When to Use
- When someone presents evaluation results and needs help interpreting them.
- When assessing whether evidence justifies scaling, continuing, or defunding a programme.
- When designing an evaluation and wanting to avoid common pitfalls.

## Core Concept
Intervention evaluation is where Macnamara's evidence quality framework meets the practical world of programme decisions. The core insight is that the same intervention can appear to "work" or "fail" depending on evaluation design choices — and these choices are often invisible to the people making decisions based on the results.

The control condition is the single most consequential design choice. A waitlist control (participants receive nothing) produces the largest effects because it captures not just the specific treatment but also expectancy, attention, Hawthorne, and regression-to-mean effects. An active control (participants receive an alternative programme of comparable intensity) isolates the specific treatment ingredient. A treatment-as-usual control falls between. The choice of control determines the size of the apparent effect, and studies that use weaker controls produce systematically larger estimates.

Outcome measurement is the second critical choice. Self-reported outcomes (participants rate their own improvement) are systematically larger than objectively measured outcomes (test scores, biological markers, observed behaviour). Unblinded self-report is the weakest outcome type because participants who know they received the intervention report more favourably. Blinded assessor ratings are stronger. Objective, automated measures are strongest.

Attrition is the silent threat. If participants who are not benefiting drop out, the remaining sample shows artificially positive results. Attrition above 20% introduces serious doubt about whether the treatment and control groups remain comparable.

For M&E practitioners, the practical message is: when you read an evaluation, the effect size is not the finding. The effect size plus the design is the finding. A d = 0.50 with a waitlist control and self-report outcomes is not comparable to a d = 0.20 with an active control and objective outcomes. The second is stronger evidence despite the smaller number.

## How to Apply
1. **Always report the control condition.** "What did the comparison group receive? The answer changes the meaning of the effect size."
2. **Always report the outcome type.** "Self-report or objective? Blinded or unblinded? These distinctions change the expected effect size by a factor of two or more."
3. **Check attrition.** "What percentage of participants completed the study? Was attrition differential between groups? High or differential attrition invalidates the comparison."
4. **Translate to practical terms.** "d = 0.25 with an active control means the programme adds a small benefit beyond an alternative. d = 0.25 with a waitlist control means we cannot distinguish the programme from attention and expectancy."

## Examples
**Situation:** An M&E specialist presents two evaluations of similar youth programmes. Programme A shows d = 0.55 (waitlist control, self-report outcomes, N = 80). Programme B shows d = 0.18 (active control, teacher-rated behaviour, N = 400). The funder asks which is more effective.
**Application:** Macnamara would say: "Programme B, despite the smaller number. Programme A's 0.55 is inflated by three design features that each push the estimate upward: waitlist control (captures attention and expectancy effects beyond the specific programme), self-report outcomes (participants who know they received the programme rate themselves more favourably), and small sample (estimates from N = 80 are unreliable and tend to be inflated when significant). Programme B's 0.18 controls for all three: the active control isolates the specific programme ingredient, teacher ratings are less susceptible to self-enhancement bias, and N = 400 produces a more stable estimate. If I had to bet on what would happen if both programmes were replicated at scale with rigorous designs, I would expect Programme A to shrink substantially and Programme B to hold. The smaller number is the more credible finding."

## Anti-Patterns
**Don't:** Dismiss all real-world evaluations as methodologically inadequate.
**Why:** Perfect designs are rarely feasible. The goal is to understand how design choices affect the estimate and to interpret accordingly — not to reject all imperfect evidence.

**Don't:** Compare effect sizes across different designs without adjustment.
**Why:** A d from a waitlist-controlled study is not comparable to a d from an active-controlled study. Comparing them as though they are on the same scale produces misleading conclusions.
