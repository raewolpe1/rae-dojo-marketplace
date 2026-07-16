---
triggers:
  - "user asks which poverty measure to use"
  - "user mentions FGT, Foster-Greer-Thorbecke, Watts, or headcount"
  - "user is critiquing a study that reports only the headcount"
  - "user wants distributionally sensitive poverty measurement"
use_when:
  - "the question is about how to summarise the depth or severity of poverty, not only its incidence"
  - "you need to argue that the headcount alone is inadequate"
  - "you need to compare poverty across distributions where the headcount may move in the opposite direction to the welfare of the poor"
fails_when:
  - "the audience needs a single simple headline number with no further engagement"
  - "the data do not support distributional analysis below the line"
  - "you treat the FGT family as a substitute for thinking about the line itself"
related:
  - "international-poverty-lines.md"
  - "growth-incidence-curves.md"
  - "measurement-error-and-survey-design.md"
---

# FGT and Watts Indices

## When to Use
- When designing the indicator set for a poverty monitoring system and needing measures sensitive to the depth and severity of poverty among those below the line.
- When critiquing an analysis that reports only the headcount ratio and may be masking a deepening of poverty.
- When evaluating an anti-poverty programme whose effect should appear as a change in the gap or severity even if the line is not crossed.
- When constructing pro-poor growth measures that require additive decomposability.

## Fails When
- **The data do not support reliable measurement below the line.** Survey instruments designed to identify whether households fall above or below a line may not measure consumption among the poorest with the precision needed for FGT(2) or the Watts index. Use the measure that the data can credibly support.
- **The audience needs a single number for media or political communication.** The headcount is the most accessible number to non-specialist audiences. The distributional measures should accompany it in serious analysis but not necessarily lead a press release.
- **You treat the measure as a substitute for thinking about the line.** A perfect distributional measure with the wrong line is still answering the wrong question. The line is the more fundamental choice.

## Core Concept
The Foster-Greer-Thorbecke (FGT) class of poverty measures, introduced in 1984, indexes a family of measures by a parameter α that controls sensitivity to the distribution of welfare among the poor. The general form is the average over the population of (gap/line)^α for those below the line, with zero contribution from those above.

When α = 0, the FGT measure is the headcount ratio — the share of the population below the line. It is insensitive to the depth of poverty among those below the line; a transfer from a person just below the line to a destitute person leaves it unchanged. It is also insensitive to the welfare of those who fall further below the line during a downturn, as long as they were already poor.

When α = 1, the FGT measure is the poverty gap — the average shortfall of the poor from the line, expressed as a proportion of the line, with the proportion measured across the entire population (so the poverty gap times the headcount-relevant population gives the total absolute shortfall). The poverty gap captures the depth of poverty: how far below the line the poor are, on average.

When α = 2, the FGT measure is the squared poverty gap, often called the severity of poverty. It gives extra weight to those farther below the line — a transfer from a household at 90 per cent of the line to a household at 30 per cent of the line raises FGT(2). It is transfer-sensitive in the sense that downward transfers among the poor increase it.

The Watts index has the same transfer-sensitivity property as FGT(2) and additional axiomatic appeal: it is the only poverty index that satisfies all the standard distributional axioms (focus, monotonicity, transfer, transfer sensitivity) and is sub-group decomposable in a clean way. It is defined as the average of the logarithm of the ratio of the line to the welfare metric, for those below the line. It is the Atkinson-Sen-Foster preferred measure when distributional sensitivity matters.

All three measures (poverty gap, squared poverty gap, Watts) are additively decomposable: total poverty is a population-weighted average of poverty within mutually exclusive population sub-groups. This is the property that makes them useful for spatial decomposition (urban vs rural, by district, by region), for demographic decomposition (by gender of household head, by ethnicity), and for growth-distribution decomposition (the Datt-Ravallion decomposition).

## How to Apply
1. **Always report at least two FGT measures.** The headcount alone tells you the incidence; the poverty gap tells you the depth; the squared poverty gap tells you the severity. Report at least the headcount and the gap; ideally all three plus Watts.
2. **Use the gap and Watts for cross-time comparisons.** When you are testing whether a programme reduced poverty, the gap is the more informative target — it captures effects on those below the line who do not cross it. The squared gap and Watts capture effects concentrated among the poorest.
3. **Decompose by sub-group.** Use the decomposability of the gap, the squared gap, and Watts to show where poverty is most severe, where it is changing fastest, and where the policy response should be concentrated.
4. **Test robustness.** Check whether the qualitative conclusion (poverty fell substantially) is robust across all three FGT measures and the Watts index. If the headcount fell but the gap did not, the policy is reaching households just below the line but not the poorest.

## Examples
**Situation:** A poverty assessment shows the headcount falling from 24 per cent to 18 per cent over five years. The analyst concludes that poverty has fallen substantially.
**Application:** Look at the poverty gap. If it fell from 6 per cent to 4 per cent in tandem with the headcount, the conclusion is supported. If it fell only marginally — say from 6 per cent to 5.5 per cent — then households just above the line have crossed it but the poorest have not improved. If the squared poverty gap is flat or rising, the poorest are doing worse even though the headcount has fallen.
**Result:** The analysis that reports only the headcount could be telling a story of broad-based gains or of a thin layer crossing the line while the depths remain. The FGT family lets you distinguish those cases.

**Situation:** An impact evaluation of a cash transfer programme reports no statistically significant effect on the headcount in the treatment villages.
**Application:** Look at the poverty gap and the squared gap. If the cash transfer raised the consumption of the poor without lifting many above the line, the headcount will be flat but the gap and the squared gap will have fallen. The headcount is the wrong indicator for a programme whose mechanism is income supplementation to the poor.
**Result:** The headcount-only analysis missed the programme's effect entirely. Reporting the gap and the squared gap reveals what the programme actually did.

## Anti-Patterns
**Don't:** Report only the headcount and treat it as the full picture.
**Why:** A reduction in the headcount can mask any pattern of welfare change below the line — including a deepening of poverty among those who remain poor. The headcount answers a narrower question than the analysis usually claims.

**Don't:** Use FGT(2) when the underlying consumption measurement is too noisy to support it.
**Why:** FGT(2) gives substantial weight to households reported at very low welfare levels, where measurement error is typically largest. If the bottom of the distribution is poorly measured, FGT(2) will be dominated by the measurement error. Use the poverty gap, which is less sensitive to measurement at the extreme.

**Don't:** Treat the Watts index as a niche academic measure.
**Why:** It is the cleanest distributionally sensitive measure on welfare-theoretic grounds and has every property the literature considers desirable. The reason it is less used in practice is convention, not analytical inferiority. Use it.
