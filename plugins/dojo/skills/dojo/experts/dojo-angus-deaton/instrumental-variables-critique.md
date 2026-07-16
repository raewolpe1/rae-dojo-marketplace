---
triggers:
  - "user is using instrumental variables for identification"
  - "user is debating causal-identification strategies"
use_when:
  - "the methodology of IV is at issue"
related:
  - "critique-of-rcts-deaton.md"
  - "development-economics-method.md"
---

# Instrumental Variables Critique

## When to Use
- When IV-based causal claims are being made.
- When evaluating an econometric paper.
- When discussing the methodological revolution in applied economics.

## Fails When
- **All IV work is dismissed.** Some IV applications are credible; the critique is about over-confidence in the methodology.

## Core Concept

The instrumental-variables (IV) approach has been central to applied economics for decades. Deaton's *Instruments, Randomization, and Learning about Development* (JEL 2010) and earlier work develops a sustained critique of how IV is often used:

**The IV strategy in theory.** When a regressor is endogenous (correlated with the error term), OLS produces biased estimates. An instrument — a variable that affects the regressor but not the outcome through any other channel — can be used to identify the causal effect. The famous papers (AJR colonial origins, Card-Krueger, Angrist's Vietnam draft) made the strategy central to the discipline.

**The validity conditions are demanding.** A valid instrument must (a) be correlated with the regressor of interest, (b) affect the outcome only through the regressor (exclusion restriction), (c) not be correlated with omitted variables that affect the outcome. The conditions are typically untestable; the analyst's argument has to be evaluated.

**Many published IV studies have problems.** Weak instruments (low correlation with the regressor) produce large standard errors and small-sample biases. Implausible exclusion restrictions are common. The instrument is often correlated with omitted factors. The published literature is biased toward instruments that produced significant results, regardless of their methodological merit.

**The estimated effect may not be what you want.** IV identifies the local average treatment effect (LATE) for the "compliers" — those whose treatment status is affected by the instrument. This is generally not the average treatment effect for the whole population. Policy claims based on LATEs often slide into ATE claims that aren't supported.

**External validity is severe.** Even if the IV is internally valid for the population studied, the LATE for the compliers may not transfer to other populations or settings. The same critique applies to IV as to RCTs.

**The "natural experiment" rhetoric overstates.** Many IV strategies are presented as "natural experiments" using historical events, geographic features, or policy changes as instruments. The rhetoric implies that the analysis approximates an RCT. In practice, the validity is usually contested and the design rarely as clean as the rhetoric suggests.

**The colonial-origins case.** AJR's settler-mortality-as-instrument-for-institutions paper is one of the most influential IV applications. Glaeser et al. and others have argued that settler mortality is correlated with human-capital differences, not just institutional differences, undermining the exclusion restriction. The debate is unresolved; Deaton's view is that the AJR work makes a contribution but the strong claims have to be qualified.

**The proper use of IV.** When the exclusion restriction is plausibly satisfied, when the first stage is strong, when the LATE-vs-ATE issue is acknowledged, when the external validity is not overclaimed — IV can be a valuable tool. The discipline's problem is the gap between proper use and common practice.

## How to Apply

1. **Evaluate the validity conditions explicitly** for any IV claim.
2. **Distinguish LATE from ATE** in policy applications.
3. **Be sceptical of "natural experiment" rhetoric** without scrutiny of the design.
4. **Use IV as one tool** rather than treating it as the gold standard.

## Examples

**Situation:** A study uses rainfall variation as an instrument for income to estimate the causal effect of income on schooling decisions in a developing country.

**Application:** The Deaton lens: rainfall affects income but probably also affects other variables (health, agricultural-decision urgency, migration) that may directly affect schooling. The exclusion restriction is questionable. The estimated effect is the LATE for households whose income is responsive to rainfall — a specific subset. Policy claims about general income-effects on schooling would over-generalise. The study is informative but the claims should be calibrated.

**Result:** A more rigorous engagement with the IV evidence.

## Anti-Patterns

**Don't:** Dismiss all IV work.
**Why:** Within scope, the methodology can be valuable.

**Don't:** Treat the validity conditions as testable in practice.
**Why:** Usually the analyst's argument is the only evidence; evaluate the argument.
