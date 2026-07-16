---
triggers:
  - "user asks about inequality of opportunity vs inequality of outcome"
  - "user mentions Roemer, Bourguignon, Ferreira on opportunity"
  - "user wants a normatively defensible measure of inequality"
use_when:
  - "the question requires distinguishing inequality due to circumstance from inequality due to effort"
  - "the user is debating whether inequality is the right policy target"
  - "you need to construct a normatively grounded inequality measure"
fails_when:
  - "the data do not include circumstances at the household level"
  - "the user wants moral judgment rather than measurement"
  - "you treat inequality of opportunity as a substitute for inequality of outcome"
related:
  - "growth-elasticity-of-poverty.md"
  - "welfarist-vs-non-welfarist.md"
  - "fgt-and-watts-indices.md"
---

# Inequality of Opportunity

## When to Use
- When constructing a normatively grounded measure of inequality.
- When advising on whether to target inequality in policy and which measure to use.
- When comparing countries on distributive justice grounds.
- When responding to claims that inequality of outcome is the right policy target.

## Fails When
- **The data lack circumstance information.** The Roemer-Bourguignon-Ferreira framework requires household-level data on circumstances (parental education, region of birth, race, gender). Without these, the framework cannot be operationalised.
- **The audience wants moral verdicts.** The framework provides a measurement structure for inequality of opportunity; it does not substitute for the normative judgment about how much inequality is acceptable.
- **You treat the inequality-of-opportunity measure as a substitute for the headline Gini.** They answer different questions and both have policy uses.

## Core Concept
Inequality of opportunity, as developed by John Roemer, François Bourguignon, and Francisco Ferreira, distinguishes inequality reflecting differences in circumstances that people did not choose — race, gender, parental education, region of birth, ethnicity — from inequality reflecting differences in effort and choice. The framework holds that inequality of opportunity (the part driven by circumstance) is normatively distinct from inequality of outcome (the total), and that policy concerns about distributive justice should focus on inequality of opportunity.

The empirical implementation typically proceeds in two stages. First, identify the circumstances — observable characteristics that are exogenous to individual choice — and the outcome (income, consumption, wealth, or a multidimensional measure). Second, decompose the total inequality of the outcome into the part that is explained by circumstances (inequality of opportunity) and the part that remains unexplained (effort, luck, choice).

The decomposition can be implemented parametrically (regressing the outcome on circumstances and reporting the variance explained) or non-parametrically (partitioning the sample by circumstance combinations and computing the between-group share of total inequality). Each approach has limitations: the parametric approach assumes a functional form; the non-parametric approach faces the dimensionality challenge of fine partitioning.

Empirically, the share of total inequality attributable to circumstances varies widely across countries. In Latin America, the share is often above 30 per cent — circumstances at birth account for a large fraction of subsequent inequality. In Northern Europe, the share is smaller but still substantial. Cross-country rankings on inequality of opportunity differ markedly from rankings on inequality of outcome — some countries with moderate Ginis have high inequality of opportunity because the moderate Gini reflects circumstance-driven inequality with little effort-driven variation; others with high Ginis have lower inequality of opportunity because the high Gini reflects effort-driven dispersion within circumstance groups.

The normative significance is straightforward. Inequality driven by circumstances that people did not choose is, in most ethical frameworks, more concerning than inequality driven by effort and choice. Policy that targets equalisation of opportunity — through education, early-childhood investment, anti-discrimination enforcement, regional development — addresses the morally more significant component of inequality. Policy that targets equalisation of outcome through redistribution addresses inequality more broadly but does less to remove the underlying circumstance-driven disparities.

The framework has limitations. The distinction between circumstance and effort is theoretical and at the margin is hard to draw. Parental education affects a child's opportunities, but a child's effort to study is itself partly shaped by parental investment; the line between circumstance and effort is fuzzy. Race and gender are clear circumstances; preferences for risk and time discount may be partly shaped by upbringing in ways the framework cannot cleanly attribute.

The framework also produces a lower bound on inequality of opportunity, because unobserved circumstances are by construction excluded. The measured share is a function of which circumstances are observed in the data; richer data reveals more inequality of opportunity. A claim that a country has low inequality of opportunity is partly a claim that the data are thin.

## How to Apply
1. **Define the outcome.** Income, consumption, wealth, or a multidimensional measure. The choice affects the framework's results.
2. **Identify the circumstances.** Parental education, parental occupation, region of birth, race, ethnicity, gender. Be transparent about which circumstances are observed and which are not.
3. **Decompose inequality.** Use the parametric or non-parametric approach. Report the share of total inequality attributable to observed circumstances. Acknowledge that this is a lower bound on inequality of opportunity.
4. **Compare to inequality of outcome.** Report both measures. A country with low inequality of opportunity but high inequality of outcome has equalised circumstances but produced large effort-and-luck-driven dispersion; a country with high inequality of opportunity but moderate inequality of outcome has unequal circumstances that the system has not yet translated into outcome dispersion.
5. **Identify policy levers.** Equalising opportunity through early childhood investment, education, and anti-discrimination has different implications than equalising outcome through redistribution. Both can be valuable; the framework helps clarify which.

## Examples
**Situation:** Two countries have similar Gini coefficients (0.45). The first has 35 per cent of inequality attributable to observable circumstances; the second has 15 per cent.
**Application:** The two countries have the same outcome inequality but very different normative profiles. The first has substantial inequality of opportunity — circumstances at birth account for a large fraction of subsequent inequality. The second has substantial inequality of outcome but most of it is not explained by observable circumstances. Policy implications differ. The first country needs to equalise opportunity — early childhood investment, anti-discrimination, regional development. The second country may need redistribution to equalise outcome or may need to investigate the unobserved circumstances driving the unexplained inequality.
**Result:** The same Gini conceals very different normative profiles. Use both measures.

**Situation:** A country reports a 20 per cent inequality-of-opportunity share. A development partner argues this shows the country has achieved equal opportunity.
**Application:** The 20 per cent is a lower bound. Unobserved circumstances (parental wealth, schooling quality, network access) are excluded. A richer dataset would likely reveal a higher share. The claim of achieved equal opportunity is over-strong given the data limitations.
**Result:** Treat the measure as a lower bound. Investigate unobserved circumstances before concluding that opportunity has been equalised.

## Anti-Patterns
**Don't:** Treat the inequality-of-opportunity share as a high-precision estimate.
**Why:** It is a lower bound dependent on the observed circumstances. Different countries observe different circumstances, making cross-country comparison sensitive to data coverage.

**Don't:** Substitute inequality of opportunity for inequality of outcome.
**Why:** They answer different questions. Inequality of outcome captures realised dispersion; inequality of opportunity captures the circumstance-driven share. Both are policy-relevant.

**Don't:** Conflate the empirical framework with the normative claim that effort-driven inequality is acceptable.
**Why:** The empirical framework distinguishes circumstance from effort; whether effort-driven inequality is normatively acceptable is a separate ethical question.
