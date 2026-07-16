---
triggers:
  - "user asks about stocks and flows"
  - "user asks about accumulation in systems"
  - "user needs to understand bathtub dynamics"
use_when:
  - "the user needs to understand the basic building blocks of system dynamics"
  - "accumulation and depletion processes are central to the analysis"
  - "the distinction between a stock and a flow is being confused"
related:
  - "feedback-loops-balancing-and-reinforcing.md"
  - "systems-thinking-foundations.md"
  - "limits-to-growth-thesis.md"
---

# Stocks and Flows

## When to Use

- When the user needs to understand the fundamental building blocks of system dynamics — stocks (accumulations) and flows (rates of change).
- When confusion between stocks and flows is producing analytical errors.
- When accumulation or depletion dynamics are central to the problem.

## Fails When

- **The system has no significant accumulation dynamics.** Simple input-output processes may not need stocks-and-flows analysis.
- **The user needs advanced modelling.** This file covers the concepts, not simulation techniques.

## Core Concept

Stocks and flows are the foundation of system dynamics. A stock is an accumulation — water in a dam, money in a bank account, skills in a workforce, carbon in the atmosphere, trust in a community. A flow is a rate of change — water flowing in or out, money earned or spent, skills gained or lost. Stocks change only through their flows: the stock of water in a dam increases only when inflow exceeds outflow.

This seems obvious, but the implications are profound and frequently misunderstood. First, stocks create inertia — they change slowly because they accumulate over time. You cannot empty a full dam instantly or fill an empty one quickly. This means that systems with large stocks resist rapid change, and policies that try to change stocks quickly encounter physical limits. Second, stocks decouple flows — a dam allows water use even when rainfall is zero. Stocks provide buffers that smooth out flow variability. Third, the stock-flow distinction reveals common errors: confusing a stock (wealth) with a flow (income); confusing a rate (current emissions) with an accumulation (atmospheric CO2 concentration); or expecting a stock to respond instantly to a change in flow.

For development practitioners, stocks-and-flows thinking reveals why development is slow and why patience is required. The stock of human capital (education, skills, health) accumulates over decades. The stock of institutional capacity builds slowly. The stock of trust between communities and government accumulates through consistent, reliable interaction. Quick-fix programmes that try to change these stocks rapidly are working against the physics of accumulation.

## How to Apply

1. **Identify the key stocks.** What is accumulating or depleting? Human capital, physical infrastructure, natural resources, institutional capacity, social trust?
2. **Map the inflows and outflows.** What increases the stock? What decreases it? What determines the rates?
3. **Assess the stock-flow dynamics.** Is the stock growing or depleting? At what rate? How long before limits are reached?
4. **Design interventions that affect flows sustainably.** Increasing inflows (investment, training) while reducing outflows (brain drain, depreciation) changes the stock over time.

## Examples

**Situation:** South Africa's skills shortage is addressed primarily through training programmes (increasing the inflow of skilled workers), but the shortage persists despite billions spent on training.
**Application:** Stocks-and-flows analysis reveals the problem. The stock of skilled workers is determined by both inflow (training, immigration) and outflow (emigration, retirement, death, career change). If outflow is high — as it is in South Africa due to emigration of skilled professionals — increasing inflow through training may barely maintain the stock, let alone increase it. The analysis also reveals that the stock of skills is not homogeneous: the types of skills produced by training (generic qualifications) may not match the types lost to emigration (experienced professionals with tacit knowledge). The solution requires addressing both sides: increase quality inflows (better training, targeted immigration) and reduce outflows (retention strategies, working conditions).
**Result:** Address both inflows and outflows of the skills stock, not just training volume.

## Anti-Patterns

**Don't:** Confuse a flow with a stock.
**Why:** Current GDP (a flow) tells you the rate of production, not the accumulated wealth (a stock). Current emissions (a flow) tell you the rate of pollution, not the atmospheric concentration (a stock). The distinction matters for policy.

**Don't:** Expect stocks to respond instantly to flow changes.
**Why:** Stocks accumulate slowly. Even large increases in inflows take time to change a stock significantly. Patience and sustained investment are required.
