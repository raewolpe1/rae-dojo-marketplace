---
triggers:
  - "user asks what an effect size means"
  - "user asks about r vs r² or variance explained"
  - "user asks whether an effect is meaningful or significant"
use_when:
  - "translating statistical results into practical meaning"
  - "teaching someone to interpret effect sizes rather than p-values"
  - "converting between effect size metrics (d, r, r², odds ratio)"
fails_when:
  - "you present effect size benchmarks (small/medium/large) as though they are universal rather than context-dependent"
  - "you ignore the practical context that determines whether an effect size matters"
  - "you treat variance explained as the only metric that matters"
related:
  - "evidence-quality-audit.md"
  - "moderator-analysis.md"
  - "intervention-evaluation.md"
---

# Effect Size Literacy

## When to Use
- When someone presents a statistical result and needs help understanding what it means practically.
- When converting between effect size metrics or from significance to magnitude.
- When the distinction between "statistically significant" and "practically meaningful" matters.

## Core Concept
Effect size literacy is Macnamara's foundational skill — the ability to convert a statistical claim into a statement about how much of the real-world variation is explained. The central insight is that statistical significance tells you whether an effect exists (given sample size and variability), but effect size tells you how big it is. A p < .001 can correspond to a trivially small effect in a large sample. A d = 0.80 sounds impressive until you convert it to r² ≈ .14, which means 86% of the variance is unexplained.

The key conversions: Cohen's d (standardised mean difference) translates to r (correlation) via r = d / √(d² + 4). The r translates to r² (variance explained) by squaring. r² is the reality-check metric: it tells you what proportion of the outcome is accounted for by the predictor or intervention. Macnamara's signature move is this conversion — taking a celebrated d or r and translating it to variance explained, then asking: "What explains the rest?"

Benchmarks (Cohen's small = d of 0.20, medium = 0.50, large = 0.80) are widely used but misleading. They were proposed as rough guides, not as universal standards. Whether d = 0.20 is meaningful depends entirely on the context. In medicine, d = 0.20 for a cheap, scalable intervention affecting millions might save thousands of lives. In education, d = 0.20 for an expensive, intensive intervention affecting hundreds might not justify the cost. Context determines significance; the number does not speak for itself.

The variance-explained frame is Macnamara's default because it makes the unexplained visible. Saying "practice explains 26% of variance in games" simultaneously communicates that practice matters substantially and that 74% of the variation comes from other sources. Both halves of the statement are important.

## How to Apply
1. **Always convert to variance explained.** "When presented with d or r, convert to r². This makes visible what the effect explains and — crucially — what it leaves unexplained."
2. **Never accept significance without magnitude.** "'Statistically significant' means 'unlikely to be zero given the sample size.' It does not mean 'large enough to matter.' Always ask: how big?"
3. **Use context to interpret.** "d = 0.30 in a free, scalable, ten-minute online intervention is more practically important than d = 0.30 in an expensive, year-long, face-to-face programme. The same number means different things in different contexts."
4. **Report confidence intervals.** "A point estimate of d = 0.40 with a confidence interval of [0.05, 0.75] means the effect could be nearly zero or moderately large. The width of the interval is part of the answer."

## Examples
**Situation:** A programme manager says: "Our evaluation found a statistically significant effect (p = .03, d = 0.25). This proves the programme works."
**Application:** Macnamara would say: "It proves the programme has an effect that is unlikely to be exactly zero given your sample size. It does not prove the programme 'works' in any practical sense without more context. Let me translate. d = 0.25 converts to approximately r = .12, which is r² ≈ .015. Your programme explains about 1.5% of the variance in the outcome. That means 98.5% of the variation in outcomes is driven by factors other than your programme. Is 1.5% zero? No. Depending on the cost of the programme, the size of the population, and the importance of the outcome, 1.5% could matter. But 'statistically significant' and 'the programme works' are very different claims. The first is a statement about sampling error. The second is a value judgement about whether 1.5% of variance justified at the cost per participant. And note: your confidence interval at p = .03 likely spans from near zero to about d = 0.45 — meaning the true effect could be less than half or nearly double your point estimate. You have evidence of a small, uncertain effect. That is useful information. It is not proof that the programme works."

## Anti-Patterns
**Don't:** Treat Cohen's benchmarks as universal standards.
**Why:** Cohen himself described them as rough guides when no other basis for interpretation existed. In many applied contexts, the relevant comparison is not "small/medium/large" but "worth the cost given the context."

**Don't:** Report only variance explained and ignore what the effect achieves.
**Why:** 1% of variance in a population of millions can affect tens of thousands of lives. Variance explained is necessary context but not the whole story. Both the relative (% variance) and absolute (how many people affected, by how much) interpretations matter.
