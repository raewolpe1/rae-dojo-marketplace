---
triggers:
  - "user asks about causal mechanisms"
  - "user asks about capacities in Cartwright's sense"
  - "user asks about how or why something works"
use_when:
  - "explaining the distinction between knowing that something works and knowing why"
  - "advising on mechanism-based evaluation design"
  - "arguing for process evaluation alongside impact evaluation"
fails_when:
  - "you reduce mechanisms to storytelling or narrative accounts"
  - "you treat capacities as guaranteed outcomes rather than context-dependent potentials"
related:
  - "causal-inference-foundations.md"
  - "ceteris-paribus-laws.md"
  - "rcts-and-external-validity.md"
  - "theory-and-evidence.md"
---

# Mechanisms and Capacities

## When to Use
- When someone asks why a programme works, not just whether it works.
- When assessing whether a causal finding will generalise to a new context.
- When designing evaluations that need to produce policy-useful knowledge about how change happens.

## Fails When
- **You treat mechanism identification as an optional add-on to impact estimation.** For policy purposes, mechanism knowledge is often more valuable than effect estimates, because it enables prediction across contexts.
- **You confuse a programme's theory of change with its actual mechanism.** A theory of change is a hypothesis about the mechanism. The actual mechanism may differ from the theory, and discovering the difference is precisely the point of mechanism analysis.

## Core Concept
Cartwright draws a fundamental distinction between two types of causal knowledge. Knowing-that is knowledge that a cause produced an effect: the programme increased income, the drug lowered blood pressure. Knowing-why is knowledge of the process through which the cause produced the effect: the programme increased income because it provided access to credit that enabled investment in productive assets; the drug lowered blood pressure because it inhibited the angiotensin-converting enzyme.

Knowing-why is more valuable for policy than knowing-that, because it reveals the conditions under which the causal relationship will and will not hold. If you know that a microfinance programme increased income, you know it can work somewhere. If you know that it increased income because it relaxed credit constraints that prevented productive investment, you know it will work in contexts where credit constraints are the binding barrier and where investment opportunities exist — and that it will not work where the binding barrier is something else (market access, skills, demand).

This is Cartwright's concept of capacity. To say that aspirin has the capacity to relieve headaches is not to say that aspirin always relieves headaches. It is to say that aspirin, by virtue of its chemical properties, can relieve headaches when the relevant conditions are met (the headache is caused by a mechanism that aspirin's action addresses, the dose is sufficient, there are no counteracting factors). A capacity is a stable dispositional property — it can be exercised or blocked depending on circumstances.

Applied to social programmes: a conditional cash transfer has the capacity to increase school attendance. Whether it exercises that capacity depends on support conditions — whether schools are accessible, whether the conditionality is enforced, whether the amount is sufficient to change behaviour, whether attendance is not already near-universal. The capacity claim is more modest than the regularity claim ("CCTs increase attendance") but more accurate and more useful for policy.

## How to Apply
1. **When an impact evaluation finds an effect, ask through what mechanism.** The effect estimate tells you the result; the mechanism tells you why, and therefore where the result will replicate.
2. **When an impact evaluation finds no effect, ask whether the mechanism was blocked.** A null result does not mean the programme lacks the capacity to produce the effect. It may mean that support conditions were absent. Identifying which conditions were missing is more useful than concluding "the programme doesn't work."
3. **Design evaluations to test mechanisms, not just estimate effects.** Include process evaluation, intermediate outcome measurement, and theory-testing components that can identify the causal pathway, not just the endpoint.

## Examples
**Situation:** An evaluation of a community health worker (CHW) programme in rural KwaZulu-Natal finds significant improvements in child immunisation rates in the first year but the effect disappears in year two. The funder concludes the programme "stopped working."
**Application:** Cartwright would reject the conclusion that the programme stopped working. The programme has the capacity to improve immunisation — year one demonstrated this. The question is what changed between year one and year two that blocked the mechanism. Investigation might reveal that year one CHWs were highly motivated volunteers with strong community ties, while year two saw staff turnover and replacement with less embedded workers. Or that initial gains came from reaching easily accessible households, while remaining unimmunised children faced structural barriers (distance, documentation, maternal depression) that CHW visits alone could not overcome. The mechanism — CHWs providing information and reducing transaction costs for immunisation — operated when support conditions held (motivated workers, accessible households, functional clinics) and failed when those conditions eroded. The policy response is to restore the support conditions, not to abandon the programme.

## Anti-Patterns
**Don't:** Treat mechanism analysis as qualitative hand-waving that adds colour to quantitative findings.
**Why:** Mechanism identification is a rigorous analytical task. It involves specifying the causal pathway, identifying the conditions under which each link in the pathway operates, and testing whether those conditions hold. It is not storytelling — it is the analysis that makes causal findings useful for prediction.

**Don't:** Assume that a programme's stated theory of change accurately describes its actual mechanism.
**Why:** Theories of change are hypotheses, and they are often wrong or incomplete. The actual mechanism by which a programme produces its effects may be quite different from what the designers intended. Discovering the actual mechanism is one of the most valuable outputs of evaluation.
