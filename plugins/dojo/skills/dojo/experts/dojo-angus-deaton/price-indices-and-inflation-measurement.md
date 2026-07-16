---
triggers:
  - "user is debating CPI or inflation measurement"
  - "user is asking about the cost of living"
use_when:
  - "price measurement is at issue"
related:
  - "measuring-poverty-and-welfare.md"
  - "trust-in-numbers.md"
---

# Price Indices and Inflation Measurement

## When to Use
- When inflation rates are being analysed.
- When real-income comparisons across time or places are at issue.
- When discussing cost-of-living adjustments.

## Fails When
- **The technical detail is bypassed.** Price-index choices substantially shape what real-income measures mean.

## Core Concept

A major thread of Deaton's career has been the methodology of price-index construction and the implications for welfare measurement. The key concepts:

**The price index converts nominal to real.** Without it, comparing income across time or places is meaningless. The construction of the index involves multiple choices that affect the result.

**Laspeyres vs Paasche.** A Laspeyres index uses base-period quantities as weights; a Paasche uses current-period. Both have problems — Laspeyres overweights goods whose prices rise (substitution bias); Paasche overweights goods whose prices fall. Fisher and Tornqvist indices average them.

**The substitution bias.** When prices change, consumers substitute away from goods that became more expensive. Failing to capture this overstates the cost-of-living increase. Most published CPIs have some substitution bias.

**The quality-change problem.** When goods change quality (cars get safer; phones get better), part of the price change is paying for the quality improvement. Adjusting for this is methodologically demanding; different adjustments produce different results.

**The new-goods problem.** When new goods are introduced (smartphones in 2007, generative AI in 2023), the price-index construction has to incorporate them. Different methods produce different inflation estimates.

**PPP conversions across countries.** International real-income comparison requires converting local prices to common units. ICP methodology involves sampling goods, weighting them, and constructing exchange rates. Changes in ICP methodology have substantially changed estimated cross-country real-income gaps over time.

**Cost-of-living indices vs consumer price indices.** A CPI tracks the price of a fixed basket; a COLI tracks the cost of maintaining a given utility level. They differ. CPIs are typically the published indicator but cost-of-living concepts are what welfare analysis usually wants.

**Different baskets for different groups.** Average consumption baskets differ from poor consumption baskets, which differ from rural baskets, which differ from urban baskets. Publishing only one CPI obscures variation in inflation experienced by different groups.

**The bias debate.** The Boskin Commission (US, 1996) argued that CPI overstated inflation by ~1% per year due to substitution, quality-change, and new-goods issues. Estimates of bias have been substantially debated. The implication: real-income growth has been higher than published statistics show — by some accounts substantially.

**For South Africa:** Stats SA produces several CPI series — headline, core, by income quintile. The differences across these are informative. The food-CPI inflation often differs substantially from headline. Geographic differences are substantial. Methodology has updated periodically. The interpretation of real-income data requires engagement with these details.

## How to Apply

1. **Engage methodology** when using inflation data.
2. **Use multiple CPI measures** where available — overall, group-specific, regional.
3. **Be cautious about long-run real-income comparisons**; methodology changes accumulate.
4. **Recognise the bias debates** as substantive, not technical.

## Examples

**Situation:** South African real-wage trends over the post-1994 period.

**Application:** The Deaton lens: real-wage calculation requires deflating nominal wages by an appropriate price index. The standard CPI is one choice but the inflation experienced by workers (food, transport, housing as larger shares of their budget) differs from headline CPI in some periods. Using a workers' or low-income CPI produces different real-wage trends. The interpretation should engage these alternatives, not assume the headline CPI is the right deflator.

**Result:** A real-wage analysis that engages the measurement details rather than glossing them.

## Anti-Patterns

**Don't:** Use a single CPI without considering whether it's appropriate to the question.
**Why:** Different questions need different deflators.

**Don't:** Treat CPI methodology as settled.
**Why:** Real ongoing debate about bias and method matters for interpretation.
