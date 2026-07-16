---
triggers:
  - "user mentions exponential growth, scaling, or Moore's Law analogues"
  - "user is extrapolating a young technology's curve"
  - "user is discussing limits to growth"
use_when:
  - "the question involves projecting a growing process forward"
  - "the user is treating exponential growth as the default"
  - "you need the physical and biological framework for scaling limits"
fails_when:
  - "the question is genuinely about a system in its early exponential phase"
  - "you become reflexively anti-growth rather than analytically careful"
  - "you treat biological and engineered systems as identical"
related:
  - "innovation-hype-and-failure.md"
  - "material-throughput.md"
  - "numerical-literacy-and-orders-of-magnitude.md"
---

# Growth and Scaling Limits

## When to Use
- When a system's growth is being projected as continuing indefinitely on its current curve.
- When a Moore's-Law analogue is being claimed for a non-semiconductor system.
- When the question is whether physical systems can scale at the rates being assumed.
- When teaching the regularities of growth across biological, engineered, and economic systems.

## Fails When
- **The system is genuinely in early exponential phase.** Some systems do exponential for a while; the question is for how long.
- **You become reflexively anti-growth.** Growth happens, sometimes for decades. The point is to engage the limits, not to deny the growth.
- **You treat biological and engineered systems identically.** Biological growth (S-curves, ecological limits) and engineered scaling (manufacturing, infrastructure) have different governing dynamics.

## Core Concept
Smil's *Growth: From Microorganisms to Megacities* (2019) catalogues the patterns of growth across biological organisms, populations, energy systems, transportation systems, cities, and economies. The central finding is that essentially all real-world growth is bounded; the unbounded exponential is a mathematical fiction. The bounding typically takes the form of an S-curve (logistic growth) or a longer-tailed approach to a plateau, governed by physical, biological, or economic limits.

**The biological pattern.** Individual organisms grow rapidly when young, then plateau (sigmoid growth). Populations expand exponentially when resources are unlimited but reach carrying capacity. The yeast in a wine vat, the bacteria in a Petri dish, the deer on an island — all examples of bounded growth.

**The engineered systems pattern.** Manufactured goods, infrastructure systems, and energy technologies typically follow similar S-curves at the deployment level. Slow start (R&D, demonstration), rapid acceleration (commercial scale-up), maturation (market saturation), plateau or decline (substitution by next technology). The full cycle is typically 50-100 years.

**The economic pattern.** GDP grows but rarely at sustained exponential rates over multiple decades. Mature economies typically grow at 1-3% per year. Catch-up economies can grow at 5-10% per year for 20-40 years. The post-1978 Chinese growth rate (averaging ~8-9% per year for three decades) is essentially without historical precedent at that scale and is now decelerating.

**The Moore's Law trap.** The roughly two-year doubling of integrated-circuit transistor density (Moore's Law) has been an extraordinary regularity from 1965 through approximately 2020, when it has slowed for fundamental physical reasons. Moore's Law is widely invoked as an analogue for other technologies — solar PV costs, battery costs, AI capabilities. Some of these analogies are partially defensible; most are not. Solar PV costs did fall on a Wright's Law curve (cost per unit declining ~25% per doubling of cumulative deployment) but the curve is now bending. Battery costs followed a similar pattern, also bending. AI capabilities are a new and contested case.

**Why bending happens.** Several mechanisms:
1. **Raw materials.** Manufacturing inputs become a higher share of total cost as labour and capital efficiency improve. Material costs ultimately set a floor.
2. **Manufacturing complexity.** As products mature, marginal performance gains become more expensive.
3. **System integration.** Costs of integrating a technology into existing systems (grid, supply chain, regulation) accumulate.
4. **Diminishing returns to scale.** Manufacturing scale benefits saturate.
5. **Market saturation.** New deployment slows as the obvious applications are taken.

**The implications.**

For climate strategy: cost curves are bending. The next decade of solar and battery cost reductions will be slower than the past decade. Strategies that assume continued exponential cost falls will under-deliver.

For AI strategy: whether AI capability scaling continues at its 2020-2025 rate is contested. The strongest skeptical case is that data, compute, and electricity will impose constraints. The strongest optimistic case is that algorithmic and architectural innovation will continue. The honest analysis treats it as an open empirical question.

For development planning: per-capita energy and material consumption in low-income countries can grow rapidly for two to three decades as countries transition from agrarian to urban-industrial structures. After that, growth rates slow. The trajectory is predictable in shape, less so in detail.

For business strategy: any product or service in an exponential phase will eventually saturate. The question for the firm is whether it has the next growth curve identified before the current one bends.

## How to Apply
1. **For any exponential projection, ask how long.** Indefinite exponential is fiction. Bounded exponential has a duration.
2. **Identify the binding constraint.** Materials, manufacturing complexity, integration, market saturation. Different constraints bend the curve at different times.
3. **Look at the analogous historical case.** Solar PV cost curves are well-documented. Use them.
4. **Distinguish quantity from capability.** Quantity scaling (more units, lower cost per unit) has bending mechanisms. Capability scaling (better units, new functions) has different dynamics.
5. **Plan for the bending.** Whether you are a firm, a country, or a programme, build the plan around the curve bending, not around indefinite continuation.

## Examples
**Situation:** An investment thesis projects solar PV module costs falling at 25% per doubling of cumulative installation, sustained through 2040.
**Application:** The curve has demonstrably bent since 2020. Polysilicon and silver costs have set floors. Manufacturing capacity has overshot demand and rebounded. The next decade is unlikely to deliver the same cost gains as the past two. Re-cost the model with a flattened curve.
**Result:** Investment case becomes more honest. May still be defensible at lower returns.

**Situation:** A national strategy projects AI-driven productivity growth contributing 1% per year to GDP for the next two decades.
**Application:** This is a heroic claim. Documented AI productivity gains so far are uneven, concentrated in specific occupations, and partly offset by AI's own energy and infrastructure costs. The historical record on prior general-purpose technologies (electrification, computerisation) shows long lag periods before productivity gains materialise at the aggregate level. The 1%-per-year claim is at the optimistic end of the literature.
**Result:** Strategy includes the claim as one scenario, not the central case.

## Anti-Patterns
**Don't:** Extrapolate any technology curve more than 10-15 years forward without engaging the bending mechanism.
**Why:** Curves bend; the question is when and why, not whether.

**Don't:** Confuse capability scaling with quantity scaling.
**Why:** Moore's Law was a capability curve enabled by a quantity (transistor density). Most other claimed analogues are not the same kind of system.

**Don't:** Become indiscriminately anti-growth.
**Why:** Growth happens. Some countries, sectors, and technologies are genuinely in their exponential phase. The discipline is to engage the duration and the binding constraint.
