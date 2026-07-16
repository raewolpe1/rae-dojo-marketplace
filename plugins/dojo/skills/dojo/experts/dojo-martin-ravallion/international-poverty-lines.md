---
triggers:
  - "user mentions dollar a day, $1.25, $1.90, $2.15, or international poverty line"
  - "user asks about absolute vs relative poverty"
  - "user is setting a national poverty line"
  - "user asks whether the global poverty count is credible"
use_when:
  - "the question is about how poverty lines are constructed, justified, or compared across countries"
  - "the user is making global comparisons and needs to understand what the underlying line measures"
  - "you need to argue for or against the appropriateness of a given line for a given purpose"
fails_when:
  - "the user wants a single 'right' poverty line that resolves the political-economy question"
  - "the data foundations for the line (PPP, national CPI, household survey methodology) are not engaged"
  - "you treat international and national lines as interchangeable"
related:
  - "fgt-and-watts-indices.md"
  - "welfarist-vs-non-welfarist.md"
  - "measurement-error-and-survey-design.md"
---

# International Poverty Lines

## When to Use
- When making cross-country comparisons of poverty levels or trends.
- When evaluating whether a national poverty line is appropriate for the purpose at hand.
- When responding to claims about global poverty levels or trends that may rest on a contested line.
- When advising on the construction of a country-specific line that needs to be defensible to multiple audiences.

## Fails When
- **The user wants a single "correct" line.** There is no single correct line. The line is a choice that depends on the question being asked and the data available. Multiple lines may be needed to answer different questions in the same study.
- **The data foundations are not engaged.** The line is a function of national consumption data, PPP conversions, and the price index used to update over time. Treating the line as a stand-alone number elides the data foundations that determine what it actually measures.
- **The user is in a rich-country context using only an absolute line.** Absolute lines miss the social-participation dimension of poverty in high-income countries.

## Core Concept
Poverty lines come in three families. Absolute lines are fixed at a constant real value over time. Relative lines rise with the average income or consumption of the society. Weakly relative lines combine both: a floor at the absolute level for low-income societies, rising more slowly than the mean as average income rises.

The international poverty line — the "dollar a day" of the World Development Report 1990, later updated to $1.08 (1993 PPP), $1.25 (2005 PPP), $1.90 (2011 PPP), and $2.15 (2017 PPP) — is the average national poverty line of the fifteen poorest countries with comparable national poverty lines, expressed in international purchasing-power-parity dollars. It is constructed to be representative of the cost of basic needs in low-income contexts. Above the lowest-income group, additional international lines have been constructed to reflect the rising cost of basic social participation: $3.65 for lower-middle-income countries and $6.85 for upper-middle-income countries in 2017 PPP.

The international line is not a moral threshold. It is an empirical anchor — the level at which a person in a poor country is, on average, just able to afford the basic-needs basket that the country itself has identified as a minimum. The empirical anchor depends on the national poverty lines that feed into the average. Those national lines are constructed using different methodologies in different countries: cost-of-basic-needs in some, food-energy-intake in others, with varying treatment of housing, utilities, and non-food consumption. The international line averages over this heterogeneity.

The PPP conversion is the second crucial step. The International Comparison Program revises PPPs every several years, and each revision changes the level of the international line in local currency terms. The 2005 PPP revision moved the line from $1.08 to $1.25 — an apparent increase that was largely a recalibration of PPPs, not a change in the underlying basic-needs basket. The 2011 PPP revision moved it to $1.90; the 2017 revision to $2.15. Comparing poverty rates across revisions without acknowledging the line change produces spurious trends.

The price index used to update the line between revisions is typically the national CPI in each source country. The CPI tends to under-weight goods consumed by the poor, so the line drifts downward in real terms relative to the basic-needs basket the poor actually face. The Ravallion-Chen-Sangraula research programme documented these issues; their successors at the Bank have continued the work.

National poverty lines — set in local currency, anchored to national basic-needs estimates or relative thresholds — are the right reference for national policy. The international line is the right reference for global comparison. They answer different questions and should not be confused.

The weakly relative line addresses the empirical observation that the cost of social participation does not jump from zero to a high level at the threshold of middle-income status. Ravallion and Chen proposed a line that is absolute at low income levels and rises more slowly than the mean above a threshold — capturing the gradual shift from physical-survival poverty to social-participation poverty as a country develops.

## How to Apply
1. **Specify the line every time.** Whenever you cite a poverty rate, specify whether it is national or international, what year's PPP it uses, what data source produced it, and whether it is the headcount or another FGT measure.
2. **Use multiple lines for sensitivity analysis.** Report the rate on the international line, on the country's national line, and on at least one relative line (60 per cent of the median is a common choice). The story should hold across all three; if it depends on one, the conclusion is fragile.
3. **Distinguish the question of level from the question of trend.** The international line may be a contestable indicator of the level of poverty in a particular country at a particular time; it can still be a useful indicator of trend, especially if the trend is robust to using national lines.
4. **For a national line, anchor it to a basic-needs basket and document the construction.** Show the food basket, the calorie-cost calculation, the non-food allowance, and the equivalence scale. Critics may disagree with each step, but the disagreement will be productive rather than rhetorical.

## Examples
**Situation:** A country's headline poverty rate on its national line has fallen from 35 per cent to 22 per cent. The international rate, on the $2.15 line, has fallen from 12 per cent to 7 per cent.
**Application:** Both lines show the same direction of change but very different levels. The national line is set higher than the international line because the country has a higher cost of basic needs than the low-income reference average. Both rates are correctly interpreted as poverty in their own terms; the national line is appropriate for domestic policy discussion, the international line for cross-country comparison.
**Result:** Use both. Do not let advocates of one line claim the other line is wrong.

**Situation:** A development partner is critiquing the country's national line as too low and proposes that the country adopt a higher line equal to 60 per cent of the median consumption.
**Application:** Apply Ravallion's question: which question is the higher line meant to answer? If the question is whether people are excluded from social participation in a middle-income country, a relative line is appropriate. If the question is whether people can meet basic needs in physical terms, the absolute line is the relevant one. The country may need both. The conversation is not "which line is right" but "what are we measuring and why?"
**Result:** Adopt a dashboard of lines rather than a single line. Report progress on each.

## Anti-Patterns
**Don't:** Compare a $1.90 headcount to a $1.25 headcount across years without adjustment.
**Why:** The lines are not in the same units. The 2005 PPP revision changed the level of the international line by more than 15 per cent. Apparent changes across the revision are partly artefacts.

**Don't:** Treat the international line as appropriate for all national policy debates.
**Why:** The international line is calibrated to the basic-needs cost in the poorest countries. In middle-income countries, a higher line — national or weakly relative — is more appropriate for domestic policy.

**Don't:** Treat the national line as a settled scientific quantity.
**Why:** It is a choice. Document it, justify it, and let the political process engage with the choice openly rather than concealing it behind a technical façade.
