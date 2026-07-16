---
triggers:
  - "user asks about publication bias"
  - "user asks why published research is systematically wrong"
  - "user asks about the file drawer problem"
use_when:
  - "explaining why the published literature overestimates effects"
  - "assessing whether a body of evidence is distorted by selective publication"
  - "interpreting funnel plot asymmetry or trim-and-fill analyses"
fails_when:
  - "you treat all researchers as dishonest"
  - "you ignore that structural incentives, not malice, drive the problem"
  - "you dismiss all published findings as untrustworthy"
related:
  - "evidence-quality-audit.md"
  - "replication-and-credibility.md"
  - "growth-mindset-critique.md"
---

# Researcher and Publication Bias

## When to Use
- When assessing whether a literature or meta-analysis is distorted by selective publication.
- When explaining the structural incentives that inflate published effect sizes.
- When someone cites "the research shows" without asking what research did not get published.

## Core Concept
Publication bias is the systematic tendency for studies with positive, statistically significant results to be published, while studies with null or negative results remain in file drawers. The consequence is that the published literature is not a representative sample of all research conducted — it is a biased sample that overestimates effects.

The mechanism is structural, not conspiratorial. Journals prefer significant results because they are more "interesting." Reviewers recommend rejection of null findings more often. Researchers anticipate this and either do not submit null results, or adjust their analyses until something reaches significance. The result is a published literature where the average effect size is inflated — sometimes substantially.

Researcher bias compounds publication bias. Financial incentives, career incentives, and theoretical commitments create systematic pressure toward positive findings. Macnamara's growth mindset meta-analysis found that authors with a financial incentive tied to the intervention were approximately 2.5 times as likely to report positive effects. This is not an accusation of fraud. Researchers with financial ties may unconsciously choose more favourable designs (waitlist controls rather than active controls), more favourable outcome measures (self-report rather than objective), more favourable analytic strategies (dropping outliers that reduce effects, testing multiple outcomes and reporting the significant one), and more favourable framing (emphasising significant subgroup analyses when the main effect is null).

For M&E practitioners, the practical implication is that "the research supports this intervention" is an incomplete statement. The question is: does the published research represent all the research that was conducted? And do the researchers who produced the positive findings have incentives that could have shaped the results?

## How to Apply
1. **Check for funnel plot asymmetry.** "In a meta-analysis, if the funnel plot shows asymmetry — small studies cluster on the positive side — that is evidence of publication bias. Missing studies from the lower-left suggest null findings were not published."
2. **Ask about the file drawer.** "For every study that found a positive effect, how many studies found nothing and were never published? We cannot know the exact number, but the asymmetry tells us the answer is not zero."
3. **Name the incentive structure.** "Who conducted the studies? Do they have financial, career, or theoretical incentives tied to positive results? Incentives do not prove bias, but they predict it. Check whether incentivised and non-incentivised researchers produce different results."
4. **Apply trim-and-fill cautiously.** "Trim-and-fill is a statistical correction for publication bias, but it assumes a specific model of missingness. It is better than nothing but not a definitive correction."

## Examples
**Situation:** A programme officer says: "We reviewed 15 studies and 12 showed positive effects. The evidence base is strong."
**Application:** Macnamara would say: "Twelve out of fifteen published studies showed positive effects. But we need to ask: how many studies were conducted that we are not seeing? If ten additional studies found null effects and were never published, the true ratio is twelve positive out of twenty-five — a very different picture. Check whether the meta-analysis reports funnel plot asymmetry or trim-and-fill corrections. Then check author incentives: of the twelve positive studies, how many were conducted by researchers with financial ties to the intervention — consulting fees, commercial products, speaker circuits? If the positive results concentrate among incentivised authors, the evidence base is weaker than the count suggests. The file drawer does not announce itself. You have to go looking for it."

## Anti-Patterns
**Don't:** Assume all researchers are deliberately biasing their work.
**Why:** The incentive effects are largely unconscious. Researchers make hundreds of small decisions during a study — design, analysis, reporting — and incentives nudge those decisions in a consistent direction. The structural explanation is more accurate and more charitable than the fraud explanation.

**Don't:** Dismiss all published research because publication bias exists.
**Why:** Publication bias inflates estimates; it does not fabricate them entirely. The appropriate response is calibration — expect published effects to be smaller than reported — not wholesale rejection.
