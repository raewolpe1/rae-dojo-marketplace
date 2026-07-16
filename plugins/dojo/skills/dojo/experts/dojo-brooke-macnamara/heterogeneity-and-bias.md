---
triggers:
  - "user asks about heterogeneity in meta-analysis"
  - "user asks about the Yeager/Tipton counter-position"
  - "user asks about blanket verdicts vs moderated findings"
use_when:
  - "interpreting heterogeneous meta-analytic results"
  - "navigating the tension between average effects and moderated effects"
  - "deciding whether to report an overall effect or explore moderators"
fails_when:
  - "you dismiss the Yeager/Tipton position as mere defence of a pet theory"
  - "you treat heterogeneity as a nuisance to be explained away rather than a finding"
  - "you ignore the risk that moderator searching capitalises on chance"
related:
  - "growth-mindset-critique.md"
  - "moderator-analysis.md"
  - "evidence-quality-audit.md"
---

# Heterogeneity and Bias

## When to Use
- When interpreting a meta-analysis with high heterogeneity (high I²).
- When deciding whether to report average effects or moderated effects.
- When engaging the methodological debate between blanket verdicts and heterogeneity-attuned approaches.

## Core Concept
Heterogeneity — variation in effect sizes across studies — is not noise. It is a finding. When I² is above 75%, the average effect size is misleading because it summarises a distribution with enormous spread. The studies are not estimating the same underlying effect; they are estimating different effects that vary by context, population, implementation, and study quality.

Macnamara's approach is to report the average alongside moderator analyses that explain the heterogeneity. The quality gradient is the first moderator: does study quality predict effect size? The incentive gradient is the second: do author incentives predict effect size? Domain-specific moderators come third: population, implementation fidelity, outcome type, control condition.

The Yeager/Tipton counter-position represents a fundamentally different philosophy of meta-analysis. Where Macnamara tends toward a verdict — "the average effect is small and driven by bias" — Yeager and Tipton argue that the right approach is to ask where the effect is stronger and where it is weaker. They contend that averaging across heterogeneous contexts obscures the real finding, which is that interventions work for specific populations under specific conditions. Their commentary on the Macnamara and Burgoyne growth mindset meta-analysis directly contests the all-or-nothing framing.

Both positions have genuine merit. Macnamara is right that quality and incentive effects must be reported and that they substantially reduce confidence in the average effect. Yeager is right that blanket verdicts can obscure real, moderated effects in specific populations. The tension between them mirrors a deeper methodological debate: should meta-analysis provide verdicts or maps? Macnamara tends toward verdicts; Yeager tends toward maps. The most informative approach provides both.

The risk of the heterogeneity-focused approach is that it becomes a method for salvaging positive findings. If you search enough subgroups, you will find one where the effect is positive — even if the true effect is null everywhere. Preregistration of moderator analyses addresses this risk but is rare in practice.

## How to Apply
1. **Report the I² and interpret it.** "I² above 75% means the average effect is a poor summary. The studies are not estimating the same thing. Explore why."
2. **Test the quality gradient first.** "Before exploring substantive moderators, test whether quality explains the heterogeneity. If it does, the true effect is closer to what the best studies show."
3. **Engage the Yeager/Tipton position fairly.** "The heterogeneity-attuned approach is legitimate. Present it as a genuine alternative, not as a motivated defence."
4. **Guard against moderator fishing.** "If moderator analyses are post-hoc, acknowledge the risk of capitalising on chance. Preregistered moderator hypotheses carry more weight."

## Examples
**Situation:** You are reviewing a meta-analysis of a development intervention that reports I² = 89% and an average effect of d = 0.28. The authors present the 0.28 as the main finding.
**Application:** Macnamara would say: "An I² of 89% means the average of 0.28 is nearly meaningless as a summary. The studies are estimating wildly different things. The 0.28 could be an average of effects ranging from -0.20 to +0.80. Before interpreting the average, I would want to know: Does study quality moderate the effect? Do author affiliations moderate it? Does implementation fidelity moderate it? Does the population moderate it? If higher-quality studies show d = 0.10 and lower-quality studies show d = 0.50, the honest estimate is closer to 0.10. If the intervention works well in certain contexts (say, urban settings with trained implementers) and not at all in others (rural settings with untrained implementers), that is a far more useful finding than 'average d = 0.28.' The Yeager approach would say: stop trying to deliver a verdict and map where the effect is strong and where it is weak. That is good advice if the moderator analyses are preregistered. If they are post-hoc, treat them as hypotheses for future testing, not as established findings."

## Anti-Patterns
**Don't:** Dismiss the Yeager/Tipton position as motivated reasoning.
**Why:** The heterogeneity-attuned approach is a legitimate methodological framework used across disciplines. It is not a defence mechanism for growth mindset specifically. Engage it on its merits.

**Don't:** Present moderator analyses as conclusive when they are post-hoc.
**Why:** Searching for subgroups where effects appear capitalises on chance. Preregistered moderators carry evidential weight. Post-hoc moderators generate hypotheses. The distinction matters.
