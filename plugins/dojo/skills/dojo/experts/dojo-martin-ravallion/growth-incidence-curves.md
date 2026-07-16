---
triggers:
  - "user asks about pro-poor growth measurement"
  - "user mentions growth incidence curve, GIC, or distributional change"
  - "user wants to visualise how growth was distributed across the income distribution"
  - "user is decomposing change in poverty"
use_when:
  - "the question is whether growth raised the incomes of the poor more or less than the average"
  - "you need to characterise the shape of distributional change, not just summary statistics"
  - "the answer should be visual and quantitative simultaneously"
fails_when:
  - "panel data on the same households across time is not available — you have only cross-sections"
  - "the time period is so short that distributional change is dominated by noise"
  - "you confuse anonymous incidence (the percentile-by-percentile comparison) with the gains to the specific people who started poor"
related:
  - "pro-poor-growth.md"
  - "growth-elasticity-of-poverty.md"
  - "fgt-and-watts-indices.md"
---

# Growth Incidence Curves

## When to Use
- When you have repeated cross-sections of household data and want to characterise how growth was distributed across the income distribution.
- When testing whether growth was pro-poor in the Ravallion-Chen sense (growth in the mean of the poor) or the Kakwani-Pernia sense (growth at the bottom faster than the mean).
- When communicating distributional change visually to a non-technical audience — the GIC is one of the most accessible distributional diagnostics.
- When decomposing change in poverty into growth and redistribution components.

## Fails When
- **You only have cross-section data, not panel data, and need to know about the specific households who were poor.** The GIC is anonymous — it compares percentiles across time, not the same people across time. The household at the 20th percentile in 2010 may not be the household at the 20th percentile in 2020. For panel-based analysis, you need a different curve.
- **The two surveys are not strictly comparable.** If recall periods, sampling frames, or consumption modules differ between the two cross-sections, the GIC will show changes that reflect survey design as much as real distributional change.
- **The time interval is too short.** Over one or two years, the GIC is dominated by measurement noise. Five years is usually a minimum for credible distributional analysis.

## Core Concept
The growth incidence curve, introduced by Ravallion and Chen in 2003, plots the annualised growth rate of consumption (or income) at each percentile of the distribution, from the poorest to the richest. The x-axis is the percentile; the y-axis is the growth rate. A horizontal line represents distribution-neutral growth — every percentile growing at the same rate. An upward-sloping curve represents growth that favoured the rich; a downward-sloping curve represents growth that favoured the poor.

The GIC is anonymous in the sense that the percentile in time t is not the same household as the percentile in time t+1. It compares two distributions; it does not track individual households through the distribution. For tracking the same households, a non-anonymous incidence curve based on panel data is needed.

The growth rate at the mean of the GIC equals the growth rate of mean income, by construction. The mean of the growth rates below the poverty line (or below any chosen percentile) is the growth rate of the mean income of the poor — the Ravallion-Chen measure of pro-poor growth.

The GIC gives a complete picture of anonymous distributional change. From it, you can read off whether the poor gained absolutely (positive growth at low percentiles), whether they gained relative to the mean (growth at low percentiles above the mean growth rate), and where in the distribution the gains were concentrated. The curve's shape carries information that summary statistics conceal.

Growth incidence curves can be constructed for sub-populations (rural vs urban, by region, by demographic group) to test whether distributional gains were uniform or concentrated. They can also be constructed using welfare metrics other than consumption — assets, wages, multidimensional indices — though each substitution embeds additional assumptions.

The "pro-poor growth rate" is the growth rate of mean income of the poor, defined as the area under the GIC below the poverty headcount, divided by the headcount. It is a single number summarising the GIC for the segment that matters for poverty reduction.

## How to Apply
1. **Plot the GIC for the full distribution.** Use the two repeated cross-sections to compute the growth rate at each percentile. Smooth lightly to remove sampling noise without obscuring the shape.
2. **Compare to the mean growth rate.** Draw a horizontal line at the growth rate of the mean. The GIC above the line indicates pro-rich growth at that percentile; below the line indicates pro-poor growth.
3. **Compute the pro-poor growth rate.** Take the average of the growth rates below the poverty headcount. Compare to the overall mean growth rate. Use the Ravallion-Chen test for whether the difference is statistically significant.
4. **Decompose by sub-group.** Plot GICs separately for rural and urban populations, for major regions, and for demographic groups of policy interest. Where the curves diverge, you have identified the geography and demography of distributional change.
5. **Combine with poverty decomposition.** Use the GIC alongside the Datt-Ravallion growth-redistribution decomposition to separate the contribution of growth in the mean from the contribution of distributional change to the change in poverty.

## Examples
**Situation:** A country experienced mean consumption growth of 4 per cent per year over a decade. The headcount fell from 30 to 18 per cent. Was the growth pro-poor?
**Application:** Plot the GIC. If growth at the bottom 20 percentiles averaged 5 per cent, growth was pro-poor in both the Ravallion-Chen and the Kakwani-Pernia sense. If growth at the bottom averaged 3 per cent (below the mean) but was still positive, the growth was pro-poor in the Ravallion-Chen sense (poverty fell because the poor's incomes rose) but not in the Kakwani-Pernia sense (the rich gained more). If growth at the bottom was 1 per cent, the headcount might still have fallen because some households crossed the line, but the underlying distributional pattern would be much less favourable to the poor than the headline numbers suggest.
**Result:** The GIC distinguishes these three cases. A headline poverty reduction does not, by itself, distinguish a story of broad-based gains from a story of a thin layer crossing the line.

**Situation:** Two countries had the same mean growth rate but very different poverty reduction rates over the same period.
**Application:** Plot the GICs for both. The country with stronger poverty reduction will have a downward-sloping GIC (growth concentrated at the bottom); the country with weaker poverty reduction will have a flat or upward-sloping GIC. The difference in initial inequality and in the sectoral pattern of growth (agriculture vs export manufacturing) typically explains the difference in GIC shape.
**Result:** The mean growth rate is the same. The distributional shape is what made the difference.

## Anti-Patterns
**Don't:** Treat the anonymous GIC as a description of what happened to specific people.
**Why:** Households move through the distribution. The percentile-20 household in time t may be the percentile-40 household in time t+1, or may have dropped out of the survey entirely. The anonymous GIC describes distributional change in the population; the non-anonymous GIC describes individual mobility.

**Don't:** Compare GICs across countries without comparing the underlying surveys.
**Why:** Different consumption modules, recall periods, and equivalence scales produce GICs that are not strictly comparable. The shape of the curve is partly an artefact of survey design.

**Don't:** Smooth the GIC so heavily that the actual shape is lost.
**Why:** Over-smoothing produces a curve that looks clean but no longer reflects the data. Light smoothing to remove obvious sampling noise is appropriate; aggressive smoothing is data fabrication.
