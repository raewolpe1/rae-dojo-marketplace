---
triggers:
  - "user asks whether a study shows causation"
  - "user asks about correlation vs causation"
  - "user asks about causal claims in programme evaluation"
use_when:
  - "assessing whether a study design supports causal conclusions"
  - "evaluating whether an intervention caused an observed outcome"
  - "distinguishing correlational from experimental evidence"
fails_when:
  - "you dismiss all non-experimental evidence as worthless"
  - "you treat RCTs as the only valid design without acknowledging their limitations"
  - "you confuse statistical significance with causal demonstration"
related:
  - "evidence-quality-audit.md"
  - "intervention-evaluation.md"
  - "moderator-analysis.md"
---

# Causal Inference Standards

## When to Use
- When someone claims an intervention caused an outcome and you need to evaluate the claim.
- When assessing whether study designs support the causal conclusions drawn from them.
- When navigating the hierarchy of evidence from correlational to experimental.

## Core Concept
Causal inference is the central challenge of empirical research, and the standards for establishing causation are more demanding than most practitioners realise. The core requirement is ruling out alternative explanations. A study demonstrates causation to the extent that it eliminates plausible confounds — and the number of plausible confounds in social and behavioural research is large.

The hierarchy runs from weakest to strongest. Cross-sectional correlations are the weakest: mindset correlates with achievement, but the direction of causation is unknown and third variables (socioeconomic status, prior ability, school quality) could explain both. Longitudinal studies improve on this by establishing temporal ordering, but temporal precedence is necessary for causation, not sufficient — a third variable could cause both the predictor and the outcome with different time lags. Quasi-experimental designs (pre-post with comparison group, regression discontinuity, difference-in-differences) improve further by creating comparison conditions, but the groups may differ on unmeasured variables. Randomised controlled trials are the strongest single-study design because randomisation, in expectation, balances all confounds — measured and unmeasured — across conditions.

But RCTs have their own threats. Non-compliance (participants not following the protocol), attrition (participants dropping out differentially), contamination (control participants receiving elements of the treatment), and demand characteristics (participants behaving differently because they know they are being studied) all undermine the causal inference even in randomised designs. A badly executed RCT can provide weaker causal evidence than a well-executed quasi-experiment.

For meta-analysis, the causal inference question becomes: do the constituent studies, collectively, support a causal claim? If most studies are correlational, the meta-analytic average is a correlational estimate, no matter how precisely estimated. Aggregating weak designs does not produce strong inference. The quality of the causal claim depends on the quality of the weakest link in the chain, not the number of studies.

## How to Apply
1. **Ask what was controlled.** "What alternative explanations does this design rule out? What alternatives remain? The causal claim is only as strong as the alternatives it eliminates."
2. **Distinguish statistical from causal evidence.** "Statistical significance tells you the association is unlikely due to chance. It tells you nothing about whether the association is causal. These are different questions requiring different evidence."
3. **Check the RCT execution.** "Randomisation is necessary but not sufficient. Was the randomisation compromised? Was attrition differential? Did contamination occur? An RCT with 30% attrition provides weaker evidence than the label 'RCT' suggests."
4. **Evaluate the meta-analytic claim.** "A meta-analysis of correlational studies produces a precise correlational estimate, not a causal one. Check what proportion of constituent studies used experimental designs."

## Examples
**Situation:** A colleague presents a cross-sectional survey showing that participants in a youth programme report higher self-efficacy than non-participants. They conclude: "The programme increases self-efficacy."
**Application:** Macnamara would say: "This design cannot support a causal claim. The participants were not randomly assigned — they self-selected or were selected into the programme. People who join voluntary programmes differ from those who do not on motivation, family support, prior functioning, and many other variables. Any of these differences could explain the self-efficacy gap. To make a causal claim, you would need at minimum a pre-post design with a comparison group, and ideally random assignment. What you have is an association. It is consistent with the programme working, but it is also consistent with selection effects, maturation, and a dozen other explanations. I would not use the word 'increases' — I would say 'participants report higher self-efficacy, but the design does not allow us to determine whether the programme caused this difference.'"

## Anti-Patterns
**Don't:** Treat RCTs as the only valid source of causal evidence.
**Why:** Well-designed quasi-experiments, natural experiments, and regression discontinuity designs can provide compelling causal evidence. The question is not "is this an RCT?" but "does this design adequately rule out alternative explanations?"

**Don't:** Accept causal language from correlational designs because the sample is large.
**Why:** Large samples increase statistical precision, not causal validity. A correlation based on N = 100,000 is a very precise correlation — it is not evidence of causation. Sample size addresses sampling error; design addresses confounding. They are independent problems.
