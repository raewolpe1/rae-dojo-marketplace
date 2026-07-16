---
triggers:
  - "user mentions LSMS, household surveys, or consumption modules"
  - "user is designing a national survey for poverty analysis"
  - "user asks how to measure household consumption credibly"
  - "user is debating diary vs recall, or modular vs comprehensive surveys"
use_when:
  - "the question is about the empirical infrastructure for poverty analysis"
  - "you need to justify a particular survey design choice"
  - "the user is critiquing or designing a household consumption module"
fails_when:
  - "the user wants a one-size-fits-all survey instrument"
  - "you ignore the country's existing statistical infrastructure"
  - "you treat survey design as a technical detail divorced from the analytical question"
related:
  - "measurement-error-and-survey-design.md"
  - "international-poverty-lines.md"
  - "fgt-and-watts-indices.md"
---

# Living Standards Measurement Study

## When to Use
- When designing or revising a national household survey programme.
- When evaluating whether existing survey infrastructure can support a particular analytical question.
- When advising statistical offices on consumption-module design, recall periods, or rotation of modules.
- When defending the choice of household survey over administrative data for poverty analysis.

## Fails When
- **The country's statistical office lacks the capacity to field the recommended design.** Technical superiority of a design is irrelevant if the implementing agency cannot deliver it. Design must respect institutional reality.
- **Comparability with existing national time series is sacrificed for design improvements.** A better instrument that breaks the time series imposes large costs on every user of the historical data. Improvements must be evaluated against the value of comparability.
- **The user treats survey design as separable from analytical question.** The right survey design depends on which questions the analysis is meant to answer.

## Core Concept
The Living Standards Measurement Study was launched by the World Bank in 1980 to develop multi-topic household surveys capable of supporting integrated analysis of welfare, poverty, and policy in developing countries. Before LSMS, household surveys in most developing countries were single-purpose: a labour-force survey, a budget survey, an agricultural survey, none speaking to each other. The LSMS innovation was to put consumption, income, employment, education, health, and demographics in a single integrated instrument so that the analyst could examine the joint distribution of welfare and its determinants in the same households.

The design principles that emerged from LSMS experience are by now standard in developing-country household survey practice. Consumption is measured comprehensively across food and non-food items, with appropriate recall periods (typically a 7-day recall for food, longer for non-food). Some items use a diary; others use a structured recall. The household is the unit of consumption measurement; individual-level information is collected for employment, education, health, and time use. Sampling is stratified, typically by region and rural-urban status, with adequate sample size to support sub-national poverty estimation. The questionnaire is designed to be administered in a single visit (or a short series), trading off depth of detail against respondent fatigue.

The integrated design supports four classes of analysis that single-purpose surveys cannot. First, joint distribution of welfare and characteristics — what fraction of female-headed households are poor, what is the poverty rate among households with no formal education, where do the poor live. Second, behavioural analysis — how do households respond to price changes, how does education affect earnings, how does household composition affect consumption. Third, programme evaluation — household-level identification of programme participants and comparison of welfare outcomes between participants and non-participants. Fourth, decomposition analysis — separating the contribution of growth, distributional change, and demographic change to changes in poverty over time.

The trade-offs in LSMS design are real and persistent. A comprehensive consumption module produces higher and more accurate consumption aggregates but is more burdensome on respondents and enumerators. A simplified module reduces respondent burden but produces consumption aggregates with more measurement error and possible understatement. A 7-day food recall is the standard but is sensitive to seasonality and may miss occasional purchases. A diary is more accurate but more expensive and exhibits diary fatigue.

The post-2000 generation of LSMS instruments — LSMS-Integrated Surveys on Agriculture (LSMS-ISA), Integrated Household Surveys (IHS), and successors — has experimented with consumption module design, with results that affect poverty estimates substantially. The Tanzania-Malawi consumption module experiments showed that consumption estimates can move by 20 per cent or more depending on module design, with corresponding effects on poverty estimates. Survey design is not a technical detail; it is a methodological choice with substantive implications.

## How to Apply
1. **Design the survey to answer the analytical questions.** Begin with the questions: what poverty estimates are needed, at what level of disaggregation, what behavioural relationships are to be estimated, what programmes are to be evaluated. Work backwards to the module design.
2. **Use a multi-topic integrated instrument unless there is a compelling reason not to.** Single-purpose surveys force the analyst to merge data from different households at different times, with the loss of joint-distribution analysis that LSMS was designed to support.
3. **Preserve comparability where possible.** Changes to consumption modules between rounds should be motivated, documented, and ideally accompanied by a bridge survey that allows the new and old estimates to be reconciled.
4. **Adopt the consumption-module design that is appropriate to the country's empirical reality.** A 7-day food recall works in most settings; a 14-day recall is sometimes needed in highly seasonal contexts; a diary is sometimes needed for items with very low purchase frequency. The choice should be empirical, not generic.
5. **Plan for sub-national disaggregation.** Sample size must be adequate to support the poverty estimates that policy will use. National rural-urban breakdowns are usually feasible; provincial or district estimates often require larger samples or small-area estimation methods.

## Examples
**Situation:** A country's statistical office is redesigning its household budget survey, which has been run every five years on the same instrument since 1995. The proposed redesign moves from a 30-day recall for non-food items to a 7-day diary, with corresponding methodological adjustments.
**Application:** The proposed change will improve the accuracy of non-food consumption measurement, but it will break comparability with the historical time series. Recommend that the office conduct a bridge survey using both instruments simultaneously on a sub-sample, producing the adjustment factor needed to splice the time series. Otherwise, every poverty trend statement using the historical data will be confounded by the change in methodology.
**Result:** Improvement of the instrument is justified, but the cost of breaking the series is real and should be addressed with a bridge survey.

**Situation:** A development partner is pressing the country to add modules on subjective well-being, time use, and gender-based violence to the next survey round. The questionnaire is already long.
**Application:** Each additional module has substantive value. The constraint is respondent burden — a survey that takes too long produces lower-quality data on all modules, not only the added ones. Recommend a rotation design: keep the consumption and labour modules constant across all waves; rotate the additional modules across waves so that each is fielded in at least one wave per five-year cycle. This gives the data on the rotated modules while protecting the quality of the core consumption measurement.
**Result:** Add the modules through rotation, not by extending the core questionnaire.

## Anti-Patterns
**Don't:** Treat the consumption module as a settled instrument that needs no further attention.
**Why:** Consumption module design is a substantive choice with substantive consequences. Periodic review and experimentation, with appropriate bridge protocols, is part of responsible statistical practice.

**Don't:** Replace household-survey-based poverty estimation with administrative data.
**Why:** Administrative data systems track programme participation, formal employment, and registered transactions; they do not measure household consumption or the welfare of those outside the formal sector. The poor are systematically under-represented in administrative data.

**Don't:** Use household surveys for purposes the sample size does not support.
**Why:** A survey designed for national poverty estimation cannot, without modification, support district-level poverty estimation. Forcing the data to produce estimates the sample cannot credibly bear produces apparent precision that is in fact noise.
