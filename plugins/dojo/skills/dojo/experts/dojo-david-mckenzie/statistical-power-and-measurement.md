---
triggers:
  - "user is designing an evaluation or M&E framework"
  - "user reports that an evaluation found no effect"
  - "user cites a null result as evidence a programme doesn't work"
use_when:
  - "the question is whether a study could have detected what it was looking for"
  - "the question is how to measure microenterprise outcomes"
fails_when:
  - "the question is qualitative evaluation design (route to Patton)"
related:
  - "adjudicating-an-initiative.md"
  - "evidence-base-business-training.md"
---

# Statistical Power and the Measurement of Microenterprise Outcomes

## When to Use
- Designing an impact evaluation or an M&E framework with attribution ambitions.
- Reading any null result in the MSME literature.
- When profits, sales, or employment are to be measured in small firms.

## Fails When
- **The evaluation is developmental or utilisation-focused** — route to Patton. This file is about detecting effects.

## Core Concept

**The central methodological fact of this literature: most of it could not have found what it was looking for.**

Almost all of the first wave of randomised trials of business training **lacked the power to detect a 25% increase in profits**. Confidence intervals are typically wide, most of them including the possibility that training increased profits and sales by 25% — while also including zero. A study of that construction cannot distinguish "useless" from "excellent". Its null is not a finding.

This has three consequences.

**First, a hierarchy of readings.** "We found no effect" and "we could not have found an effect" are different statements. Before reading any null, check the minimum detectable effect. If it is not reported, assume the study was underpowered — most were.

**Second, an asymmetry in how nulls are used.** People who dislike a programme cite the nulls as refutation. People who like it cite the interval's upper bound. Both are misreading. The correct reading is that the study is uninformative.

**Third, a design implication.** Underpowered evaluations are worse than no evaluation, because they produce a spurious finding that is then cited. If you cannot afford a powered evaluation, do not run an underpowered one — run a well-designed pilot with process monitoring and be honest that you have not measured impact.

**The measurement problem is separate and equally serious.** Microenterprise profits are genuinely hard to measure: no records, recall error, seasonality, deliberate misreporting, and the conceptual difficulty of separating firm from household. Many evaluations measure noise and then estimate a treatment effect on the noise. McKenzie has worked directly on this — including proof-of-concept trials of technologies like RFID to measure microenterprise turnover objectively rather than by recall.

**Attrition compounds it.** Many evaluations experience problems with survey attrition; small firms close, move, and refuse. Differential attrition between arms destroys the identification.

**The current guidance.** McKenzie (2025), "Designing and Analysing Powerful Experiments: Practical Tips for Applied Researchers", *Fiscal Studies* 46(3): 305–322 — the current practical reference. Related: Cilliers, Elashmawy & McKenzie (2024), "Using Post-Double Selection Lasso in Field Experiments", World Bank PRWP 10931.

## How to Apply

1. **Ask for the minimum detectable effect** before reading any result. If absent, assume underpowered.
2. **Power on the outcome you care about**, not the one that is easy to measure. Practices are easy and move a little; profits are hard and move less.
3. **Budget for sample size before curriculum.** An evaluation of 300 firms measuring profits will tell you nothing regardless of how good the programme is.
4. **Measure practices as well as profits.** Practices are the first stage. If practices did not move, profits cannot have, and you have learned where the failure is.
5. **Plan for attrition** at the design stage, with tracking budget and a differential-attrition analysis.
6. **Consider objective measurement** where recall is hopeless — transaction records, mobile money data, physical counts.
7. **Refuse the underpowered evaluation.** It will produce a citable number that is wrong.

## Examples

**Situation:** DEDAT proposes to evaluate an enterprise support pilot with 250 treated and 250 control firms, measuring profit change at 12 months.

**Application:** That design cannot detect anything short of a very large effect on profits, and 12 months is inside the window McKenzie & Woodruff identified as too short. It will almost certainly return a null, and that null will be cited for a decade as evidence the programme doesn't work. Options: (a) power up — several thousand firms, which is probably unaffordable; (b) change the primary outcome to business practices, which move detectably at this sample size and tell you whether the first stage worked; (c) drop the impact claim, run process evaluation, and be explicit that impact was not measured.

**Result:** Either a study that can find something, or an honest admission that it cannot — rather than a false null in the record.

## Anti-Patterns

**Don't:** Read a null from a small study as evidence of no effect.
**Why:** Most of these studies could not have detected a 25% profit increase.

**Don't:** Run an underpowered impact evaluation because the budget requires an evaluation line.
**Why:** It is worse than nothing. It manufactures a wrong number that enters the literature.

**Don't:** Measure only profits.
**Why:** Practices are the first stage and are measurable. Without them, a null tells you nothing about *why*.

**Don't:** Ignore attrition.
**Why:** Differential attrition between arms destroys the randomisation you paid for.
