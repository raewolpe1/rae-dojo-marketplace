---
triggers:
  - "user asks about returns to education"
  - "user asks about education and inequality"
  - "user asks about the skill premium"
use_when:
  - "analysing the causal return to schooling after accounting for selection"
  - "explaining how education quality mediates returns to years of schooling"
  - "advising on education policy in contexts of high inequality"
fails_when:
  - "you estimate returns to education without addressing ability bias and selection"
  - "you treat the Mincerian return as a causal parameter without qualification"
related:
  - "selection-bias-foundations.md"
  - "human-capital-and-capabilities.md"
  - "skill-formation-technology.md"
  - "heckman-applied-to-southern-africa.md"
---

# Education Returns and Inequality

## When to Use
- When estimating or interpreting returns to education in developing country contexts.
- When explaining how selection bias affects estimates of schooling returns.
- When analysing the relationship between education quality, quantity, and earnings inequality.

## Fails When
- **You treat the OLS Mincerian return as a causal estimate.** The standard wage regression of log earnings on years of schooling confounds the causal return to education with ability selection, family background, and school quality. Heckman's work shows that the naive estimate overstates the causal return for most populations.
- **You ignore the distinction between years of schooling and skills acquired.** In contexts where school quality varies dramatically — as in South Africa — an additional year of schooling may produce very different skill gains depending on the school. Returns to schooling are really returns to skills, and years of schooling is a noisy proxy for skills actually acquired.

## Core Concept
Heckman's contribution to understanding education returns operates at several levels. First, he demonstrated that the standard Mincerian wage equation — which regresses log earnings on years of schooling and experience — produces biased estimates of the causal return to education. The bias arises from selection: individuals who choose more schooling differ systematically from those who choose less, in ways (ability, motivation, family resources) that independently affect earnings. The OLS estimate captures both the causal effect of schooling and the selection premium, and cannot distinguish between them.

Second, Heckman showed that returns to education are heterogeneous. Different individuals face different returns, and individuals sort into education levels partly based on their comparative advantage. Someone who attends university does so partly because their return to university education is high relative to their return to entering the labour market with a matric. This sorting on comparative advantage means that the average return for those who attend university differs from the return that non-attenders would have received had they attended — the distinction between ATT and ATE is critical.

Third, Heckman's work connects education returns to inequality through the technology of skill formation. Inequality in educational outcomes begins before school entry, with gaps in cognitive and non-cognitive development that reflect family investment differences. Schools can either compress or amplify these pre-existing gaps depending on their quality. In countries with highly unequal school systems, education can reproduce inequality rather than reduce it — more years of low-quality schooling may generate minimal skill gains and minimal earnings returns.

For policy, this means that expanding access to education without addressing quality is insufficient. The return to an additional year in a dysfunctional school may be close to zero, while the return to an additional year in a well-functioning school may be substantial. Aggregate estimates of returns to schooling that average across these contexts are misleading for policy.

## How to Apply
1. **When estimating returns to education, use methods that address selection.** IV approaches (using policy changes, distance to schools, or cohort exposure as instruments), control function methods, or structural models that explicitly model the education choice.
2. **Decompose returns by school quality and type.** Aggregate returns mask enormous variation. In South Africa, distinguish between returns to formerly Model C schooling and returns to township or rural schooling.
3. **Measure skills directly rather than relying solely on years of schooling.** Literacy and numeracy assessments, cognitive test scores, and non-cognitive skill measures provide more informative human capital indicators than credential counts.

## Examples
**Situation:** A South African policy research institute estimates Mincerian returns to education and finds that each additional year of schooling raises earnings by approximately 15 per cent. They use this to argue for expanding secondary school access in rural KwaZulu-Natal.
**Application:** Heckman would challenge this analysis on multiple grounds. First, the 15 per cent estimate is biased upward by ability selection — individuals who complete more schooling are systematically different in ability and family background. Using IV approaches (such as changes in compulsory schooling laws or school construction programmes as instruments), the causal return is likely 8–10 per cent, possibly lower. Second, the average return masks heterogeneity by school quality. In well-resourced former Model C schools, an additional year may generate genuine skill gains and corresponding earnings returns. In under-resourced rural schools — with high teacher absenteeism, limited materials, and large class sizes — an additional year may produce minimal skill acquisition and correspondingly low returns. Third, the policy implication is not simply "expand access" but "expand access to quality schooling." Building more classrooms in rural KZN without addressing teacher quality, instructional materials, and school management may increase years of schooling without increasing skills or earnings. The research institute should estimate returns separately by school quintile, measure learning outcomes directly, and frame the policy question as one of quality-adjusted access rather than access alone.

## Anti-Patterns
**Don't:** Cite aggregate returns to education as if they apply uniformly across the population.
**Why:** Returns vary by ability, school quality, field of study, labour market conditions, and individual comparative advantage. An aggregate estimate is an average of very different experiences.

**Don't:** Assume that expanding education will automatically reduce inequality.
**Why:** If school quality is unequal and the wealthy access better schools, expanding education can reproduce or even amplify inequality. The distribution of education quality matters as much as the distribution of education quantity.
