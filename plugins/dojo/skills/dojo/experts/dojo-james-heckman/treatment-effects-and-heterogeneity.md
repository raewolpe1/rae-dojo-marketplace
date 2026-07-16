---
triggers:
  - "user asks about treatment effect heterogeneity"
  - "user asks about marginal treatment effects"
  - "user asks about LATE or local average treatment effect"
use_when:
  - "explaining why average treatment effects mask important variation"
  - "advising on how to think about who benefits from a programme"
  - "discussing the MTE framework and its policy implications"
fails_when:
  - "you present treatment effects as a single number rather than a distribution"
  - "you ignore that different estimation methods identify different parameters"
related:
  - "selection-bias-foundations.md"
  - "structural-vs-reduced-form.md"
  - "evaluation-methodology-critique.md"
---

# Treatment Effects and Heterogeneity

## When to Use
- When an evaluation presents an average treatment effect without exploring who benefits and who does not.
- When discussing what different estimators (ATE, ATT, LATE, MTE) actually identify.
- When advising on programme expansion or targeting decisions.

## Fails When
- **You accept an average treatment effect as sufficient for policy.** The average may be positive while many individuals experience zero or negative effects. Policy requires distributional information.
- **You conflate different treatment effect parameters.** ATE, ATT, LATE, and MTE answer different questions and are identified by different methods. Treating them as interchangeable is a common and costly error.

## Core Concept
Heckman's work on treatment effects, developed over decades with collaborators including Vytlautas, Urzua, and others, emphasises that individuals are heterogeneous in their responses to treatment. A job training programme does not have "an effect" — it has a distribution of effects that varies across individuals based on their characteristics, circumstances, and responses.

The average treatment effect (ATE) is the mean of this distribution across the population. The average treatment effect on the treated (ATT) is the mean among those who actually participate. The local average treatment effect (LATE), identified by instrumental variables, is the mean effect for "compliers" — those whose participation was changed by the instrument. The marginal treatment effect (MTE) is the effect for the person at the margin of participation — the individual who is just indifferent between participating and not.

These are different parameters that answer different questions. ATE answers: what is the expected effect if we assigned someone from the population at random? ATT answers: what was the effect on those who chose to participate? LATE answers: what was the effect on those whose participation was induced by a specific change in incentives? MTE answers: what is the return to expanding the programme by one additional person?

For policy, the MTE is often the most relevant parameter. If you are considering expanding a programme, you want to know the effect on the next person who would be included — not the average effect on existing participants or the population average. Heckman shows that if people self-select based on their expected gains, then the marginal participant typically has a lower return than the average participant. This means that average effects overstate the return to expansion, sometimes dramatically.

## How to Apply
1. **Always ask: which treatment effect parameter is being estimated?** When reading evaluation findings, determine whether the estimate is ATE, ATT, LATE, or something else, and assess whether that parameter is relevant to the policy question.
2. **When advising on programme expansion, estimate or approximate the MTE.** The average effect on current participants is not the relevant parameter. The effect on the marginal entrant is.
3. **Examine heterogeneity by observable subgroups.** Even if MTE estimation is not feasible, treatment effect heterogeneity by gender, education, age, location, and baseline characteristics provides policy-relevant information about who benefits.

## Examples
**Situation:** An RCT of a youth entrepreneurship programme in Johannesburg finds an average treatment effect of a 15% increase in earnings. The Department of Small Business Development proposes scaling the programme nationally.
**Application:** Heckman would ask: who are the compliers in this RCT? If the programme was oversubscribed and the RCT randomised access among applicants, the estimated effect is the ATT among applicants — people who already demonstrated interest in entrepreneurship. The national population includes many youth with no entrepreneurial inclination. The ATE for the national population would likely be much lower. Furthermore, if national scaling means less selective recruitment, the marginal participant has lower expected returns than the average trial participant. The 15% earnings increase is a parameter for a specific subpopulation under specific conditions, not a forecast for a national programme. The scaling decision requires estimating how the return changes as the programme moves from selected to unselected populations.

## Anti-Patterns
**Don't:** Use LATE estimates to make general claims about programme effects.
**Why:** LATE identifies the effect for compliers induced by the specific instrument. This subpopulation may be unrepresentative. Generalising from LATE to ATE requires additional assumptions.

**Don't:** Ignore the relationship between selection and heterogeneity.
**Why:** If people select into programmes based on their expected gains, then ATT exceeds ATE (positive selection on gains) or ATT is less than ATE (negative selection). Understanding this relationship is essential for predicting effects under different targeting rules.
