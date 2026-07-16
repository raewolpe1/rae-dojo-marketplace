---
triggers:
  - "user asks about regression to the mean"
  - "user describes extreme results followed by less extreme results"
  - "user attributes improvement or decline to an intervention when it may be statistical"
use_when:
  - "an extreme performance — good or bad — is being attributed to causes when it may simply be reverting to the average"
  - "pre-post comparisons may be confounded by regression to the mean"
  - "someone is confusing statistical regression with causal explanation"
fails_when:
  - "you apply regression to the mean to dismiss genuine causal effects"
  - "you explain the statistics but not the psychological trap"
  - "you fail to distinguish regression to the mean from mean reversion in time series"
related:
  - "base-rate-neglect.md"
  - "cognitive-biases.md"
  - "kahneman-applied-to-practice.md"
---

# Regression to the Mean

## When to Use
- When extreme performance is followed by less extreme performance and this change is being attributed to a cause.
- When pre-post comparisons may be confounded by natural statistical regression.
- When someone is drawing causal conclusions from what may be a purely statistical phenomenon.

## Core Concept
Regression to the mean is a statistical inevitability that people persistently misinterpret as a causal phenomenon. Whenever a variable is measured on two occasions and the measurements are imperfectly correlated, extreme values on the first occasion will tend to be less extreme on the second — not because anything caused the change, but because extreme scores are partly due to luck, and luck does not persist.

Kahneman's illuminating example came from his experience teaching flight instructors. Instructors reported that when they praised a cadet for an exceptionally smooth landing, the next landing was usually worse; when they criticised a cadet for a rough landing, the next landing was usually better. They concluded that criticism works and praise backfires. But the correct explanation is regression to the mean: an exceptionally smooth landing is partly skill and partly luck. On the next attempt, the luck component is unlikely to repeat, so the performance moves toward the average — regardless of whether the instructor praised, criticised, or said nothing. The instructors were constructing a causal story (praise causes deterioration, criticism causes improvement) for what was a purely statistical phenomenon.

This has profound implications for programme evaluation. If you select the worst-performing schools for an intervention and then measure their performance again, they will improve even if the intervention does nothing — because they were selected for being extreme, and extreme performance regresses to the mean. If you select the best-performing health clinics for a study visit and then compare them to baseline, they may look worse the second time — not because anything went wrong, but because their initial extreme performance included a luck component.

The psychological trap is that regression to the mean is invisible. The causal story — the intervention worked, the training made a difference, the new manager turned things around — is always more available and more compelling than the statistical explanation. System 1 generates causal narratives automatically; it does not generate statistical explanations spontaneously.

## How to Apply
1. **Ask whether selection was based on extreme scores.** If participants were selected because they were at the top or bottom of a distribution, expect regression to the mean regardless of any intervention.
2. **Use control groups.** The only reliable way to distinguish genuine intervention effects from regression to the mean is to compare with a control group that was equally extreme at baseline but did not receive the intervention.
3. **Be suspicious of pre-post designs.** Before-and-after comparisons without controls are particularly vulnerable to regression to the mean, especially when participants were selected for extreme values.
4. **Teach the concept with examples.** Regression to the mean is counterintuitive. The flight instructor example and similar stories make the statistical logic accessible.

## Examples
**Situation:** A provincial education department selected the 50 worst-performing schools for an intensive support programme. After one year, test scores improved by 15%. The department is celebrating the programme's success.
**Application:** Kahneman would say: "Before celebrating, you need to consider regression to the mean. You selected schools because they were at the bottom of the performance distribution. But being at the bottom is partly about systemic issues and partly about luck — a particularly weak cohort, a key teacher on leave, disrupted exam conditions. On the next measurement, the luck component will tend not to repeat, so scores will improve even if the support programme did nothing. How much of the 15% improvement is genuine impact and how much is regression? Without a control group — 50 similarly low-performing schools that did not receive the programme — you cannot answer this question. My suspicion is that a meaningful portion of the improvement is statistical regression, not programme impact. This does not mean the programme had no effect. It means you cannot know, from this design, how large the effect was. The department's confident celebration is premature — they are attributing to their intervention an improvement that may be partly or wholly statistical."

## Anti-Patterns
**Don't:** Use regression to the mean to dismiss all improvement.
**Why:** Regression to the mean does not eliminate genuine effects — it obscures them. The point is not that interventions never work, but that without proper controls, you cannot determine how much of an observed change is real and how much is statistical artefact.

**Don't:** Confuse regression to the mean with a claim that everything averages out.
**Why:** Regression to the mean is about imperfect correlation between measurements, not about a mystical tendency toward mediocrity. A genuinely excellent school can be genuinely excellent — but its most extreme performance in any single year includes a luck component that is unlikely to repeat.
