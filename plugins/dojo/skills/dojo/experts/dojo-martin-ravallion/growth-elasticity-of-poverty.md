---
triggers:
  - "user asks how much growth reduces poverty"
  - "user mentions growth elasticity, growth-poverty link"
  - "user is debating whether growth is enough for poverty reduction"
use_when:
  - "the question is about the empirical relationship between growth and poverty reduction"
  - "the user is testing claims about growth's distributional record"
  - "you need to explain why elasticities differ across countries and lines"
fails_when:
  - "the user wants a single global elasticity that applies everywhere"
  - "the data do not support country-specific elasticity estimation"
  - "you treat the average cross-country elasticity as a structural parameter"
related:
  - "pro-poor-growth.md"
  - "growth-incidence-curves.md"
  - "fgt-and-watts-indices.md"
---

# Growth Elasticity of Poverty

## When to Use
- When estimating how much economic growth is likely to reduce poverty in a given country context.
- When critiquing growth-only or distribution-only narratives about poverty reduction.
- When testing whether a particular growth episode was unusually pro-poor or anti-poor.
- When advising on the targets for growth in a poverty-reduction strategy.

## Fails When
- **The audience wants a universal elasticity.** Elasticities vary by country, by line, and by time. Cross-country averages are useful benchmarks; they are not structural parameters.
- **The data do not support country-specific estimation.** Estimating an elasticity requires repeated household surveys over a sustained period. Without the data, only cross-country evidence can be applied.
- **The elasticity is treated as causal.** Cross-country growth elasticities are reduced-form summaries of a relationship between growth and poverty change; they do not by themselves identify the channel.

## Core Concept
The growth elasticity of poverty is the percentage change in a poverty measure (typically the headcount) per one percent change in mean consumption or income. The literature has produced thousands of estimates, with substantial dispersion.

For the headcount on a fixed absolute line, the cross-country average elasticity is in the range of -2 to -3: a 1 per cent rise in mean consumption is associated with a 2-3 per cent reduction in the headcount. For the squared poverty gap, the elasticity is larger in absolute value — distributional sensitivity makes the measure respond more to growth that reaches the poor.

The dispersion around the average is wide. Some growth episodes have produced elasticities of -1 (weak poverty reduction per unit of growth); others have produced elasticities exceeding -5 (strong poverty reduction per unit of growth). The variation is not random. It is systematically related to: the initial level of inequality (high initial inequality dampens the elasticity); the sectoral composition of growth (agriculture-led growth tends to produce higher elasticities than capital-intensive industrial growth); the depth of poverty (the elasticity is smaller when the poor are far below the line); and the line itself (the headcount elasticity falls as the line is lowered, because the very poor are harder to lift across the line).

Initial inequality is the most robustly documented modifier. The standard finding is that countries with low initial Gini coefficients (under 0.40) have growth elasticities of poverty that are roughly twice as large in absolute value as countries with high initial Gini coefficients (above 0.55). The intuition is straightforward: when inequality is high, a percentage rise in mean consumption translates into a smaller absolute gain at the bottom of the distribution, and the poor remain far below the line.

The decomposition of changes in poverty into growth and distributional components — the Datt-Ravallion decomposition — operationalises this. The growth component is the change in poverty that would have occurred if the mean had grown as observed and the distribution had remained constant. The distributional component is the change that would have occurred if the distribution had changed as observed but the mean had remained constant. The decomposition is path-dependent (the order of growth and distribution matters) but a Shapley-decomposition resolves the path-dependence.

Empirically, growth has done most of the work of poverty reduction in most successful poverty-reduction episodes. The distributional component has been smaller, sometimes positive (distribution improved alongside growth, deepening poverty reduction), sometimes negative (distribution worsened alongside growth, dampening poverty reduction). The country cases where distributional change dominated growth in reducing poverty are rare.

The policy implication is not that distribution does not matter but that growth is necessary for sustained poverty reduction. Distribution matters too — both because it amplifies or dampens the poverty-reduction effect of growth and because policies that improve distribution can themselves reduce poverty even without growth. But policies that ignore growth in pursuit of redistribution alone face arithmetic limits.

## How to Apply
1. **Estimate the country-specific elasticity from local data.** Use the repeated cross-sections to compute the elasticity over the most recent decade. Be transparent about the line used and the consumption-measurement methodology.
2. **Compare to cross-country benchmarks.** Is the country's elasticity higher or lower than the cross-country average for countries with similar initial inequality and similar sectoral composition? The comparison is diagnostic.
3. **Decompose past changes in poverty.** Use the Datt-Ravallion decomposition to separate the growth contribution from the distributional contribution. The decomposition reveals where the policy levers have been pulled.
4. **Project the elasticity forward conditionally.** A forward-looking poverty target requires a forecast of mean growth and of distributional change. The elasticity is the lever between them. Make the assumptions explicit.
5. **Test sensitivity.** Repeat the elasticity calculation for different lines, different welfare metrics, and different time windows. The conclusion should be robust; if not, identify what drives the dependence.

## Examples
**Situation:** A country reports that mean consumption grew 3 per cent per year over a decade. The headcount on the national line fell from 25 to 18 per cent. What is the implied elasticity, and is this consistent with cross-country experience?
**Application:** The cumulative growth in mean consumption over the decade is approximately 34 per cent; the cumulative reduction in the headcount is 28 per cent. The implied elasticity is roughly -0.8. This is on the low end of the cross-country distribution, suggesting that either initial inequality was high (dampening the elasticity), the sectoral composition of growth was unfavourable to the poor (capital-intensive rather than agricultural), or the line is set unusually low (so the very poor are far below it).
**Result:** Diagnose which of these factors is at work. The low elasticity is informative — it tells you something about the country's distributional structure, not just about the speed of poverty reduction.

**Situation:** A country has an unusually high growth elasticity of -4. The strategy team is celebrating.
**Application:** Investigate first whether the elasticity is robust to changes in the line and the welfare metric. Some high elasticities reflect a bunching of households just below the line, so that a small income gain crosses many across at once. The high elasticity may not generalise to deeper poverty measures. The squared poverty gap and the Watts index may show smaller percentage reductions.
**Result:** The headline elasticity may understate the difficulty of reducing the depth of poverty among those still far below the line.

## Anti-Patterns
**Don't:** Treat the cross-country average elasticity as a structural parameter.
**Why:** It is a reduced-form summary that varies systematically with initial inequality, sectoral composition, and the level of the line. Applying the average to a country with high initial inequality will over-predict poverty reduction.

**Don't:** Decompose changes in poverty without specifying the line and the welfare metric.
**Why:** The decomposition depends on these. A growth-dominated decomposition for the headcount may be a distribution-dominated decomposition for the squared poverty gap.

**Don't:** Treat a low elasticity as evidence that growth does not matter.
**Why:** A low elasticity tells you that growth is reducing poverty less efficiently than it could. The implication is not that growth is unnecessary; it is that distribution should be addressed alongside growth.
