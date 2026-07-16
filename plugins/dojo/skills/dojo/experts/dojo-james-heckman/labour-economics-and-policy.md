---
triggers:
  - "user asks about labour economics"
  - "user asks about wage determination"
  - "user asks about labour market policy"
use_when:
  - "applying Heckman's labour economics frameworks to policy questions"
  - "advising on active labour market programmes"
  - "analysing wage structures, employment, and human capital returns"
fails_when:
  - "you discuss labour markets without attention to selection and heterogeneity"
  - "you treat labour market outcomes as determined solely by supply-side factors"
related:
  - "selection-bias-foundations.md"
  - "education-returns-and-inequality.md"
  - "human-capital-and-capabilities.md"
  - "heckman-applied-to-southern-africa.md"
---

# Labour Economics and Policy

## When to Use
- When analysing labour market outcomes through Heckman's analytical lens.
- When advising on active labour market programme design and evaluation.
- When discussing wage determination, employment, and the role of human capital in labour markets.

## Fails When
- **You ignore selection into employment, occupation, and sector.** Labour market outcomes are shaped by selection at every stage — who works, in what sector, at what wage. Ignoring selection produces biased estimates of returns and programme effects.
- **You treat labour supply and demand as separate problems.** Heckman's framework integrates worker decisions (human capital investment, labour supply, job search) with employer decisions (hiring, wage-setting, screening) in an equilibrium framework.

## Core Concept
Heckman's labour economics integrates human capital theory, selection models, and structural econometrics to analyse labour market outcomes. His foundational insight — that observed wages and employment reflect selection processes — applies throughout labour market analysis.

Wage equations estimated on employed workers are biased by selection into employment. Returns to education estimated without accounting for ability selection overstate the causal return to schooling. Programme effects estimated without modelling participation decisions confound programme effects with selection effects. These are not exotic problems — they are the default condition of labour market data.

Heckman's approach to active labour market policy is characterised by several distinctive positions. First, programme effects are heterogeneous. A job training programme benefits some participants substantially, others modestly, and some not at all. Average effects are misleading for targeting and design decisions. Second, general equilibrium effects matter. A training programme that places 1,000 graduates in jobs may displace 500 workers who would otherwise have filled those positions. The net employment effect is smaller than the gross effect, and the displaced workers bear a cost not captured in the evaluation. Third, programme design should be informed by structural models of labour market behaviour, not just experimental estimates of existing programme effects.

For developing countries with structural unemployment — where job seekers substantially outnumber available positions — Heckman's framework implies that supply-side interventions (training, skills development) have limited effectiveness unless they are accompanied by demand-side conditions (job creation, investment, economic growth) that create the positions for trained workers to fill.

## How to Apply
1. **When evaluating labour market programmes, model selection into participation and employment.** Account for who participates and who finds employment, using appropriate corrections.
2. **Consider general equilibrium effects when assessing programme scalability.** Small-scale trial effects may overstate the impact at scale if displacement effects are significant.
3. **Integrate supply-side and demand-side analysis.** Skills development programmes are unlikely to reduce unemployment if the binding constraint is insufficient labour demand.

## Examples
**Situation:** South Africa's Youth Employment Service (YES) programme subsidises one-year work placements for youth. An evaluation compares employment outcomes for YES participants versus non-participants twelve months after the placement ends.
**Application:** Heckman would identify multiple analytical challenges. First, selection: YES participants are selected by employers, who screen for characteristics (attitude, reliability, proximity) that also predict employment outcomes. The evaluation must model this employer selection process to avoid conflating programme effects with selection effects. Second, heterogeneity: the average effect masks variation by participant characteristics, employer type, and local labour market conditions. Some participants gain valuable experience and connections; others learn little transferable. The policy-relevant question is which placements generate lasting returns. Third, displacement: if YES participants fill positions that would otherwise have gone to non-subsidised applicants, the net employment creation is lower than the gross placements. In South Africa's tight labour market, where approximately six million people are unemployed, displacement may be substantial for entry-level positions in areas with surplus applicants. Fourth, general equilibrium: if YES depresses entry-level wages by increasing the supply of experienced young workers, the programme's benefits to participants come partly at the cost of non-participants. The evaluation should estimate all four dimensions, not just the average difference in employment rates.

## Anti-Patterns
**Don't:** Evaluate labour market programmes solely on employment outcomes.
**Why:** Employment is a binary indicator that misses quality of employment, wage levels, job stability, skill acquisition, and career progression. A programme that moves participants into precarious low-wage employment is less valuable than one that builds lasting human capital, even if both show similar employment effects at twelve months.

**Don't:** Ignore the demand side of the labour market when evaluating supply-side programmes.
**Why:** Training workers for jobs that do not exist is waste. The return to skills development depends on whether the labour market will absorb the trained workers, which is a demand-side question.
