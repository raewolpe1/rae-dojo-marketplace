---
triggers:
  - lithium mines
  - water use data centres
  - rare earth supply chain
use_when:
  - Assessing environmental and resource costs of AI infrastructure
  - Evaluating AI procurement decisions with sustainability dimensions
  - A government or organisation claims AI is "green" or "carbon-neutral"
fails_when:
  - The conversation requires software-level environmental optimisation advice
  - Environmental costs are acknowledged and the need is for remediation strategies beyond Crawford's framework
  - The analysis is disconnected from specific geographies and becomes generic environmentalism
related:
  - ai-as-extraction.md
  - anatomy-of-ai.md
  - training-set-archaeology.md
---

# Planetary Costs

## When to Use

- When evaluating the environmental and resource dimensions of AI infrastructure decisions
- When a proposal or strategy claims sustainability benefits from AI without accounting for AI's own material costs
- When mapping the geographic distribution of AI's environmental burden for development or policy audiences

## Core Concept

Crawford insists that any honest accounting of AI must begin with the planet — not with the planet as an abstraction, but with specific geographies where the costs of AI physically land. The planetary costs of AI operate across four interlocking registers: minerals, water, energy, and embodied labour.

Minerals first. The hardware substrate of AI depends on lithium (batteries), cobalt (processors), copper (wiring), coltan (capacitors), and rare-earth elements (magnets, displays). Lithium extraction in the Atacama Desert consumes extraordinary quantities of water in one of the driest places on earth, threatening the water supply of indigenous Atacameno communities. Cobalt mining in the DRC relies heavily on artisanal labour, including children, in conditions that regularly kill. Rare-earth processing in Baotou, Inner Mongolia, has produced a toxic lake of radioactive waste visible from space. These are not externalities — they are inputs.

Water second. Data centres require massive volumes of water for cooling. Microsoft disclosed that its global water consumption rose 34 per cent in a single year as it scaled AI training. Google's data centres in The Dalles, Oregon, drew enough water from the Columbia River to irrigate thousands of acres of farmland. In water-stressed regions — which includes much of the Global South — siting AI infrastructure is a water-governance decision.

Energy third. Training a single large language model can consume as much electricity as several hundred American households use in a year. The aggregate electricity demand of data centres is projected to rival that of medium-sized countries. Much of this electricity still comes from fossil fuels, which means that every AI query carries a carbon shadow.

Embodied labour fourth. The workers who assemble hardware in Foxconn factories in Shenzhen, who mine cobalt by hand in Katanga, who label data for two dollars an hour in Nairobi — their labour is embodied in every AI output. Their working conditions, wages, and health outcomes are planetary costs as much as carbon emissions are.

For development practitioners, the planetary-costs lens reframes AI procurement as resource governance. Every AI workload a government runs has a water footprint, a carbon footprint, a mineral footprint, and a labour footprint. The question is not whether to use AI but whether those footprints are visible, governed, and justified.

## How to Apply

1. **Demand a material bill of goods.** For any AI system under consideration, require disclosure of data-centre location, energy source, water consumption, hardware supply chain, and labour conditions for data processing. As Crawford frames it: "Every AI system has a material substrate. If you cannot see it, that is a political choice by someone — find out whose."

2. **Map the cost geography.** Plot where the environmental and labour costs of the AI system land and where the benefits accrue. In development contexts, this map often reveals that costs concentrate in the Global South (mining, data labelling) while benefits concentrate in the Global North (corporate revenue, consumer convenience). This is the structure to name.

3. **Apply the water test.** For any data-centre siting or cloud-provider selection, ask: what is the water source, what is the consumption volume, and what competing demands exist for that water? In water-stressed regions, this single question can reframe an entire AI strategy.

4. **Calculate honestly, including the counterfactual.** If an AI system claims environmental benefits (e.g., climate monitoring, precision agriculture), calculate the environmental cost of the AI system itself and compare. The net benefit may be real — or it may be a shell game where carbon is moved from one ledger to another. Crawford's framework demands the honest accounting.

## Examples

**Situation:** A Southern African government is evaluating proposals from two hyperscale cloud providers to host its national data platform, including AI workloads for health, education, and social protection. Both providers emphasise their "carbon-neutral" commitments.

**Application:** Crawford's planetary-costs framework forces the evaluation beyond carbon-neutral marketing. First, "carbon neutral" typically means offset, not zero-emission — the data centres still consume fossil-fuel electricity and purchase carbon credits elsewhere, often in forests in the Global South that communities depend on for livelihoods. Second, water: both providers' nearest data centres are in regions already experiencing water stress exacerbated by climate change. Third, hardware: the servers those data centres run contain cobalt likely sourced from the DRC — the government's own continent — under conditions the government would not tolerate domestically. Fourth, data labelling: if the AI models powering health or social-protection services were trained using data labelled by workers paid below living wage in East Africa, the government is building public services on exploitative labour.

The evaluation should require each provider to disclose: the specific data-centre facility, its energy source mix, its annual water consumption, its hardware supply-chain audit, and the labour conditions for any data processing involved in model training. A provider that cannot or will not disclose this is asking the government to outsource its material accountability along with its compute.

## Anti-Patterns

- **Don't reduce planetary costs to carbon alone.** Carbon is one dimension. Water, minerals, labour, and toxic waste are equally important. A carbon-neutral data centre that drains a river or depends on child-mined cobalt is not environmentally responsible — it has simply chosen which cost to publicise and which to hide.

- **Don't genericise the geography.** Saying "AI harms the environment" is too abstract to be useful. Name the mine, the river, the factory, the data centre location. Specificity is what distinguishes Crawford's framework from general environmentalism and what gives it analytical and political force.
