---
triggers:
  - "user asks whether growth has been pro-poor"
  - "user mentions Kakwani-Pernia, Ravallion-Chen, or relative vs absolute pro-poor growth"
  - "user is evaluating a country's distributional record"
use_when:
  - "the question is about how to define and operationalise pro-poor growth"
  - "the user is taking a position that requires a precise definition"
  - "you need to distinguish growth-mediated poverty reduction from inequality-mediated poverty reduction"
fails_when:
  - "the user wants a moral verdict, not an empirical assessment"
  - "the data do not support distributional analysis"
  - "you allow the term to be used loosely without specifying the definition"
related:
  - "growth-incidence-curves.md"
  - "growth-elasticity-of-poverty.md"
  - "fgt-and-watts-indices.md"
---

# Pro-Poor Growth

## When to Use
- When assessing a country's growth episode against a distributional yardstick.
- When testing whether a particular policy episode was pro-poor.
- When advising on country diagnostics that require an explicit distributional position.
- When responding to claims that growth has been pro-poor or anti-poor that may rest on unstated definitions.

## Fails When
- **The audience wants a moral judgment, not an empirical measure.** Pro-poor growth is an empirical concept; it does not by itself tell you whether the growth was just.
- **Distributional data are too thin to support the measurement.** If only the headcount is available, the underlying distributional pattern cannot be characterised.
- **The term is used without specifying the definition.** "Pro-poor growth" means different things to different writers; the ambiguity has produced extensive miscommunication in the literature.

## Core Concept
Two definitions of pro-poor growth dominate the literature. The Ravallion-Chen (or "absolute") definition: growth is pro-poor if the mean income of the poor rises during the growth episode. The Kakwani-Pernia (or "relative") definition: growth is pro-poor only if the incomes of the poor rise faster than the mean.

Both definitions can be operationalised, both have legitimate uses, and they answer different questions. The Ravallion-Chen definition asks: did the poor share in the gains, regardless of whether inequality changed? The Kakwani-Pernia definition asks: did the poor benefit disproportionately, in a way that reduced inequality?

The Ravallion-Chen definition has the empirical advantage that it is satisfied by virtually all growth episodes that produced substantial reduction in absolute poverty. If the growth rate of the mean income of the poor is positive, absolute poverty has fallen (other things equal). The Kakwani-Pernia definition has the rhetorical advantage that it sets a higher bar — it requires that the growth disproportionately benefits the poor.

The choice between them depends on the question. If the question is whether absolute poverty has fallen — the relevant question for most low-income contexts — the Ravallion-Chen definition is what matters. If the question is whether the growth has reduced inequality alongside reducing poverty — relevant for middle-income contexts where social participation matters — the Kakwani-Pernia definition is the more demanding test.

A useful additional concept is the pro-poor growth rate proper: the area under the growth incidence curve below the poverty headcount, divided by the headcount. This is the growth rate of mean income of the poor under the Ravallion-Chen definition, and it can be compared to the overall mean growth rate to test the Kakwani-Pernia condition.

Empirically, growth elasticities of poverty are large and significant. A 1 per cent growth in mean income, on average, reduces the headcount by 2 to 3 per cent. The dispersion around the average reflects the distributional shape of the growth: pro-poor growth episodes deliver higher poverty reduction per unit of mean growth than pro-rich episodes. Initial inequality is a powerful predictor of how pro-poor a given growth episode will be — high initial inequality dampens the poverty-reduction effect of growth, partly because the absolute gain to the poor from a percentage rise in their consumption is small when the level is low.

## How to Apply
1. **Specify the definition.** State whether you are using Ravallion-Chen (absolute) or Kakwani-Pernia (relative). Do not let the term float between definitions.
2. **Compute the growth rate of the mean income of the poor.** Use the area under the GIC below the headcount, divided by the headcount. Compare to the overall mean growth rate.
3. **Report both pro-poor measures.** A growth episode that is pro-poor in absolute terms but not in relative terms is still poverty-reducing. A growth episode that is pro-poor in relative terms is also pro-poor in absolute terms (positive growth at low percentiles above the mean implies positive growth at low percentiles).
4. **Decompose into growth and distribution.** The Datt-Ravallion decomposition separates the change in poverty into a component due to growth (with distribution held constant) and a component due to distributional change (with the mean held constant). The decomposition makes explicit how much of the poverty reduction came from growth and how much from redistribution.
5. **Test sensitivity to the line.** A growth episode that looks pro-poor at one line may look different at another. Repeat the test for the international, national, and weakly relative lines.

## Examples
**Situation:** A country reports a growth episode in which mean consumption rose 5 per cent per year for a decade, the headcount fell from 40 to 18 per cent, and inequality (Gini) rose from 0.42 to 0.46.
**Application:** Growth was pro-poor in the Ravallion-Chen sense — the headcount fell substantially, which implies that mean income of the poor rose. Growth was not pro-poor in the Kakwani-Pernia sense — inequality rose, meaning the rich gained more than the mean and the poor gained less. Both statements are correct; they are answering different questions.
**Result:** Use both definitions to characterise the episode. The country had pro-poor growth in absolute terms; it did not have pro-poor growth in relative terms.

**Situation:** A country reports a growth episode in which mean consumption rose 3 per cent per year, the headcount fell from 25 to 22 per cent, and inequality fell.
**Application:** Growth was pro-poor in both definitions. Growth at the bottom was faster than at the mean, and the absolute level of the mean income of the poor rose. The poverty reduction was modest because the initial level was relatively low, but the distributional shape of growth was favourable.
**Result:** A small reduction in poverty under genuinely pro-poor distributional change. Worth distinguishing from a small reduction under pro-rich distributional change.

## Anti-Patterns
**Don't:** Use "pro-poor growth" without specifying the definition.
**Why:** The term has at least two operational definitions in the literature, and using it loosely allows the reader to insert whichever definition supports the speaker's position. State the definition.

**Don't:** Reject growth as not pro-poor because inequality rose, when absolute poverty fell substantially.
**Why:** Under the Ravallion-Chen definition, growth that reduces absolute poverty is pro-poor by definition. Insisting on the Kakwani-Pernia definition rejects growth episodes that delivered substantial absolute gains to the poor. The terminological choice should be defended on substantive grounds.

**Don't:** Treat the growth elasticity of poverty as a constant.
**Why:** The elasticity varies across countries, time periods, and lines. Initial inequality, the sectoral composition of growth, and the level of the line all affect the elasticity. Cross-country averages are useful for benchmarking; they are not substitutes for country-specific analysis.
