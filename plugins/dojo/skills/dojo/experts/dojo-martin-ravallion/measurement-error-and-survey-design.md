---
triggers:
  - "user mentions recall period, diary, household survey, consumption module"
  - "user asks about national accounts vs survey discrepancies"
  - "user is critiquing survey-based poverty estimates"
use_when:
  - "the question is about how survey design affects poverty estimates"
  - "the user is reconciling household-survey aggregates with national accounts"
  - "you need to explain why apparently small design choices have large effects"
fails_when:
  - "the user wants a single clean adjustment that resolves all measurement error"
  - "the survey documentation is too thin to identify the design choices"
  - "you treat measurement error as a niche technical concern"
related:
  - "living-standards-measurement-study.md"
  - "international-poverty-lines.md"
  - "fgt-and-watts-indices.md"
---

# Measurement Error and Survey Design

## When to Use
- When evaluating the credibility of a poverty estimate against alternative survey designs.
- When advising on choices in household survey methodology.
- When reconciling household survey aggregates with national accounts.
- When critiquing a cross-country or cross-time comparison that may depend on un-noted methodological differences.

## Fails When
- **The survey documentation is too thin to identify the design choices.** When the methodology is not transparent, the resulting estimates cannot be properly diagnosed.
- **The audience wants a clean adjustment that resolves all measurement error.** No such adjustment exists. Measurement error is structural and can only be managed, not eliminated.
- **The user treats measurement error as a niche technical concern.** It is a substantive analytical issue that often dominates apparent differences across time or countries.

## Core Concept
Household surveys measure consumption with error, and the error is large, systematic, and consequential. Recall periods matter — a 7-day recall and a 30-day recall produce systematically different consumption aggregates, with longer recalls typically producing lower aggregates because of recall failure. Diaries and recall instruments produce different aggregates; diaries tend to produce higher aggregates with diary fatigue effects in later weeks. Equivalence scales (per capita, per adult equivalent, OECD scale) shift the implied distribution and the poverty line. The unit of observation (household vs individual) affects what is measured and how it is interpreted.

The Tanzania-Malawi consumption module experiments, conducted by LSMS-ISA in the 2010s, demonstrated how large the design effects can be. The same households reported very different consumption levels when measured with different module designs. Poverty estimates moved by 10-20 per cent depending on the module — within-country, within-month, within-household. The methodological choice that produced one estimate was not less rigorous than the one that produced another; they were different choices producing different numbers.

National accounts and household survey aggregates diverge widely and the divergence has grown. The growth rate of mean consumption from household surveys is typically lower than the growth rate of private consumption from national accounts, sometimes by half. The gap reflects under-coverage of the rich in surveys (who decline interviews or under-report consumption), under-reporting of high-income consumption (luxuries, services), and conceptual differences (the NAS includes consumption by the government, by non-profits, and by foreign residents in ways the survey does not).

The reconciliation choice has substantive implications. If the analysis uses the survey mean (and survey distribution) for poverty analysis, the estimates are internally consistent but understate growth in mean consumption that the NAS captures. If the analysis uses the NAS mean (and the survey distribution rescaled to match), the implied poverty estimates assume the rich are under-reporting and the poor are correctly reporting — which is the empirical pattern but is not always defensible. Both choices are second-best; the right answer is to report both and discuss the implications.

Recall periods affect food consumption massively in low-income contexts. A 7-day recall for food is the international standard but understates infrequently purchased items (meat, alcohol, ceremonial purchases) and overstates frequently purchased items relative to long-term averages. A 14-day recall captures more but increases respondent fatigue. A diary captures the most accurate within-week consumption but extrapolates poorly to weeks not covered. Each instrument has trade-offs.

Equivalence scales embed assumptions about household economies of scale and about the relative consumption needs of adults and children. Per capita treats every member equally; the OECD scale treats the first adult as 1, additional adults as 0.7, children as 0.5. The OECD scale produces lower poverty rates in larger households than per-capita; per-capita over-states the consumption of children relative to their needs. Neither is right; they answer different questions.

Cross-country comparisons of poverty rates are particularly vulnerable to measurement-error issues. Different countries use different consumption modules, different recall periods, different equivalence scales, and different price indices. The headline rates are presented as comparable; they are not. Cross-country trends are more robust than cross-country levels because within-country methodology tends to be more stable than across-country methodology.

## How to Apply
1. **Document the methodology.** When citing a poverty estimate, document the recall period, the equivalence scale, the data source, and the line. Without this documentation, the estimate is uninterpretable.
2. **Report sensitivity to alternative design choices.** Show how the headline estimate changes if you use per-adult-equivalent instead of per-capita, or a 14-day recall instead of a 7-day recall. Robustness across plausible alternatives supports confidence; sensitivity reveals fragility.
3. **Reconcile survey and NAS aggregates explicitly.** Show the gap. Discuss whether the analysis uses the survey mean (with its conservatism on growth) or the NAS mean (with its assumptions about under-reporting). Defend the choice.
4. **Recognise that cross-country comparisons require harmonisation.** International poverty estimates use a single line in PPP, but the underlying country surveys vary in methodology. Harmonisation is the right principle, but it is partial.
5. **Treat measurement error as a substantive issue.** Decisions that rest on small differences between two estimates may be artefacts of measurement-error differences.

## Examples
**Situation:** A country's poverty rate fell by 3 percentage points between two surveys. The previous survey used a 30-day recall for food; the new survey uses a 7-day recall.
**Application:** The methodological change confounds the trend. The 7-day recall typically reports higher food consumption than the 30-day recall, so the methodology change alone would reduce the measured poverty rate. The 3-percentage-point decline may reflect the methodology change in whole or in part. A bridge analysis comparing the two methodologies on a sub-sample is needed before the trend can be interpreted.
**Result:** The trend is not interpretable without addressing the methodological change.

**Situation:** A country's household survey shows mean consumption growth of 2 per cent per year; the national accounts show private consumption growth of 4 per cent per year. The strategy team is using the survey mean for poverty analysis.
**Application:** The 2 per cent NAS-survey gap is large and growing. If the strategy uses only the survey mean, poverty reduction projections based on growth will be biased downward — the rich are under-reporting in the survey, and the NAS captures their growth. If the strategy uses the NAS mean rescaled to the survey distribution, the projections assume the rich are under-reporting (often plausible) and the poor are correctly reporting (also often plausible). Report both projections; discuss which scenario the strategy is robust to.
**Result:** The NAS-survey reconciliation is a substantive choice; do not let it be hidden in technical footnotes.

## Anti-Patterns
**Don't:** Compare poverty estimates across surveys without checking the methodology.
**Why:** The methodological differences can dominate the substantive differences. The headline numbers are not comparable until the methodology has been harmonised.

**Don't:** Suppress the NAS-survey discrepancy.
**Why:** It is a structural feature of the data and the analysis must engage it. Suppressing it produces apparent precision that the data do not support.

**Don't:** Treat the equivalence scale as a technicality.
**Why:** It changes the implied poverty rate by a large fraction in countries with large families. Document the choice and report sensitivity.
