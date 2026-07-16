---
triggers:
  - "user asks how to target an anti-poverty programme"
  - "user mentions proxy means test, geographic targeting, or self-targeting"
  - "user is debating universal vs targeted transfers"
use_when:
  - "the question is about who should be eligible for a programme"
  - "you need to assess targeting accuracy and feasibility"
  - "the user is choosing between universal and targeted designs"
fails_when:
  - "administrative capacity and political economy are not engaged"
  - "the user expects a generic answer without country diagnostics"
  - "you treat targeting accuracy as the only criterion"
related:
  - "workfare-and-employment-guarantees.md"
  - "conditional-cash-transfers.md"
  - "evaluating-anti-poverty-programmes.md"
---

# Targeting vs Universalism

## When to Use
- When designing eligibility rules for an anti-poverty programme.
- When critiquing a programme proposal whose targeting design has been understated.
- When advising on the trade-offs between universal coverage and narrow targeting.
- When responding to political-economy challenges to targeting choices.

## Fails When
- **Administrative capacity to deliver the targeting is not analysed.** A proxy-means test that requires regular updating, third-party verification, and appeals processes will perform very differently in a country with strong administrative capacity than in one without.
- **Political economy is not engaged.** Targeting design has political consequences — who is included, who is excluded, who feels themselves a stakeholder in the programme's continuation.
- **Targeting accuracy is treated as the only criterion.** Cost of administration, political sustainability, distortion of behaviour, and stigma are all real considerations.

## Core Concept
Targeting is the use of eligibility rules to direct programme benefits to a sub-population — typically the poor. The case for targeting is that it concentrates resources where they are most welfare-improving and reduces total programme cost for a given anti-poverty impact. The case against targeting is that it requires administrative information that is often unavailable, generates inclusion and exclusion errors, undermines political support, and creates stigma that depresses take-up.

Targeting designs vary widely. Means-tested programmes use household consumption or income to assess eligibility, requiring detailed information. Proxy-means tests use observable household characteristics (housing materials, education of head, assets) to predict consumption, requiring less information but introducing prediction error. Geographic targeting designates areas — districts, neighbourhoods, schools — as eligible based on aggregate poverty rates. Categorical targeting uses observable categories (age, gender of household head, disability) to confer eligibility. Self-targeting uses programme features (the work requirement in workfare, the time cost of attendance) to discourage non-poor take-up. Community-based targeting devolves eligibility decisions to local committees.

Each design has trade-offs in inclusion error (the poor who are excluded), exclusion error (the non-poor who are included), administrative cost, political sustainability, and behavioural distortion. The literature consistently finds that even in middle-income countries with good administrative data, proxy-means tests have inclusion-error and exclusion-error rates in the 20-30 per cent range. In low-capacity contexts, the errors are larger.

The empirical case for fine targeting is weaker than its advocates routinely claim. The theoretical case for narrow targeting assumes that the administrative cost is small, that the political coalition for redistribution is robust, and that the social-protection programme will continue across political cycles. In practice, all three assumptions are commonly violated. Programmes targeted to the very poor lack political constituencies; once funding is squeezed, they are easier to cut. Programmes with broader coverage build wider constituencies and prove more durable.

The empirical case for universalism is not that targeting is undesirable but that the costs of fine targeting are usually larger than the model assumes and the benefits are usually smaller. A combination of geographic targeting (low administrative cost), categorical targeting (workable in low-capacity settings), and self-targeting (where appropriate) often outperforms a sophisticated proxy-means test on net.

The choice depends on context: administrative capacity, the spatial distribution of poverty, the political economy of redistribution, and the specific programme design. A universal old-age pension can target a vulnerable group with very low administrative cost. A geographically targeted school feeding programme can reach poor children without classifying individual households. A workfare programme can self-target through the wage. A consumption-tested cash transfer can reach the very poorest but at high administrative cost and political risk.

## How to Apply
1. **Diagnose the spatial and demographic distribution of poverty.** If the poor are concentrated geographically, geographic targeting captures most of the gain from narrow targeting at much lower cost. If the poor are demographically concentrated (children, elderly, disabled), categorical targeting captures most of the gain.
2. **Assess administrative capacity honestly.** A proxy-means test that performs well in theory will perform much worse if the registry is partial, the validation infrastructure is weak, or the appeals process is unreliable.
3. **Calculate the expected inclusion and exclusion errors for each candidate design.** Use prior studies of targeting performance in similar contexts. Be sceptical of designs whose claimed accuracy depends on conditions that the country does not satisfy.
4. **Engage the political economy.** A programme that creates a broad coalition is more politically durable than one that does not. The poor often lack the political voice to defend a narrowly targeted programme through electoral cycles.
5. **Combine instruments.** Many efficient targeting systems combine geographic targeting (the district), categorical targeting (the demographic group), and self-targeting (programme design). This combination reduces administrative cost and increases political sustainability.

## Examples
**Situation:** A country proposes a consumption-tested cash transfer with a proxy-means test predicting consumption from twenty household characteristics. The PMT is expected to identify the bottom quintile of households for transfer eligibility.
**Application:** The proposed design will, on prior evidence, mis-classify 20-30 per cent of households on each side — some non-poor households will receive the transfer, and some poor households will not. Administrative cost will be substantial — household surveys, registry updates, appeals. The programme's political constituency will be narrow, making it vulnerable to budget cuts. Consider whether a universal child grant (or a geographically targeted programme combined with categorical eligibility for households with young children) would deliver comparable anti-poverty impact at lower administrative cost and higher political durability.
**Result:** The fine-targeting design has costs the proposal has not engaged. A coarser design may dominate on net.

**Situation:** A country's existing universal old-age pension is being critiqued as wasteful because some pensioners are not poor.
**Application:** The "wasteful" universal old-age pension has, in many cases, the lowest administrative cost and the highest political durability of any anti-poverty programme. It captures a demographic group that is largely poor on average, with a simple eligibility rule (age). Replacing it with a means-tested old-age pension would reduce coverage by perhaps 20 per cent, increase administrative cost substantially, and reduce political sustainability. The "waste" is often illusory once the trade-offs are accounted for.
**Result:** Universalism with progressive financing is often preferable to fine targeting for demographically concentrated poverty.

## Anti-Patterns
**Don't:** Adopt a targeting design that requires administrative capacity the country does not have.
**Why:** A sophisticated PMT that performs beautifully on paper will produce coverage that is much closer to random in practice. The choice is not between fine and coarse targeting; it is between coarse targeting that works and fine targeting that fails.

**Don't:** Treat targeting accuracy as the sole criterion.
**Why:** The administrative cost, political sustainability, behavioural distortion, and stigma effects of a targeting design are all real and should be valued explicitly.

**Don't:** Assume that a targeted design will produce more anti-poverty impact than a universal design for the same total cost.
**Why:** Empirical studies frequently find that the saving from narrow targeting is largely offset by the cost of running the targeting system, with the political sustainability gap making the universal design dominate over a medium horizon.
