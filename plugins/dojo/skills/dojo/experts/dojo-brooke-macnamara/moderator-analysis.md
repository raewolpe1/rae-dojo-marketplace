---
triggers:
  - "user asks about subgroup effects"
  - "user asks why an intervention works in some contexts and not others"
  - "user asks about moderators in meta-analysis"
use_when:
  - "interpreting moderated effects in a meta-analysis"
  - "deciding whether a subgroup finding is real or a fishing artefact"
  - "understanding when an overall null effect conceals real moderated effects"
fails_when:
  - "you treat all moderator analyses as fishing expeditions"
  - "you ignore that genuine moderators exist and matter for practice"
  - "you present post-hoc moderators as established findings"
related:
  - "heterogeneity-and-bias.md"
  - "growth-mindset-critique.md"
  - "evidence-quality-audit.md"
---

# Moderator Analysis

## When to Use
- When a meta-analysis reports moderated effects alongside an overall estimate.
- When deciding whether to trust a subgroup finding.
- When designing an evaluation that needs to test theoretically specified moderators.

## Core Concept
Moderator analysis asks: does the effect vary systematically by some characteristic of the study, population, or implementation? The answer is almost always yes — effects vary. The question is whether the variation is real or an artefact of searching.

The distinction between preregistered and post-hoc moderators is the single most important methodological boundary in moderator analysis. A preregistered moderator was specified before the data were analysed. The researcher had a theoretical reason to expect moderation and committed to testing it in advance. A post-hoc moderator was discovered by searching the data after the overall effect was known. The statistical properties of these two types of findings are fundamentally different. Preregistered moderators have controlled Type I error rates. Post-hoc moderators have inflated Type I error because the more subgroups you test, the more likely you are to find one that appears significant by chance.

The Bonferroni problem scales with the number of moderators tested. If a meta-analysis tests 20 moderators at p < .05, you expect one significant result by chance alone. Most meta-analyses test far more than 20 moderators and do not correct for multiple comparisons. The result is that the subgroup findings in a typical meta-analysis are substantially less reliable than they appear.

Study quality as a moderator occupies a special position. It is not a substantive moderator (like population or implementation fidelity) but a methodological one. When study quality moderates the effect — higher-quality studies show smaller effects — the implication is that the positive findings are artefacts of weak designs, not evidence of the intervention working. Macnamara consistently tests this moderator first because it determines whether the remaining moderator analyses are worth conducting. If quality fully explains the heterogeneity, the intervention does not work and the subgroup findings are explaining variation in an artefact.

## How to Apply
1. **Ask whether moderators were preregistered.** "Were these subgroup analyses specified before the data were collected? Preregistered moderators carry evidential weight. Post-hoc moderators generate hypotheses for future testing."
2. **Count the moderators tested.** "How many moderators were tested? Apply a rough mental correction: the more you test, the more likely spurious results. If 15 moderators were tested and two are significant, those two findings are less impressive than they look."
3. **Test quality first.** "Before exploring substantive moderators, check whether study quality predicts effect size. If it does, the positive findings may be design artefacts, and the subgroup analyses are explaining variation in noise."
4. **Demand replication.** "A moderated effect found in one meta-analysis is a hypothesis. A moderated effect replicated across independent meta-analyses is evidence. Before building a programme on a subgroup finding, check whether it replicates."

## Examples
**Situation:** A researcher presents a meta-analysis of a skills training programme. The overall effect is d = 0.12 (non-significant). But a moderator analysis shows the programme is effective for female participants (d = 0.34, p < .01) and not for male participants (d = -0.05, ns). They recommend targeting the programme to women.
**Application:** Macnamara would say: "Before accepting the recommendation, I need to know three things. First, was the sex moderator preregistered or post-hoc? If post-hoc, it is a hypothesis, not a finding. How many other moderators were tested? If they tested age, education, ethnicity, urban/rural, implementation fidelity, outcome type, and study quality alongside sex, the sex finding could easily be a chance result from multiple testing. Second, does study quality moderate the effect? If the studies showing effects for women are systematically weaker — smaller samples, self-report outcomes, waitlist controls — the moderated effect may be a quality artefact rather than a genuine sex difference. Third, has this sex moderation been found in any independent meta-analysis of similar programmes? A moderated effect that appears in one meta-analysis and has never been tested elsewhere is exploratory. I would not recommend targeting a programme based on a single post-hoc moderator finding. I would recommend specifying the hypothesis and testing it in a preregistered study designed to detect the interaction."

## Anti-Patterns
**Don't:** Dismiss all moderator analyses as fishing.
**Why:** Genuine moderation exists. Interventions do work differently for different populations under different conditions. The problem is not with moderator analysis itself but with the practice of testing many moderators post-hoc and presenting the significant ones as established findings.

**Don't:** Accept moderated effects without checking moderation by quality.
**Why:** If study quality covaries with the substantive moderator — for example, if studies of female participants happen to use weaker designs — the apparent sex moderation is actually quality moderation wearing a different label.
