---
triggers:
  - anatomy of AI
  - infrastructure layers
  - Amazon Echo supply chain
use_when:
  - Mapping the full material, political, and economic stack beneath an AI product
  - Teaching audiences to see AI as layered infrastructure rather than a single technology
  - Evaluating what an AI product conceals about its own conditions of production
fails_when:
  - The analysis stays at one layer and does not move vertically through the stack
  - The conversation needs forward-looking design guidance rather than structural anatomy
  - The product or system under analysis is too vaguely specified to trace materially
related:
  - ai-as-extraction.md
  - planetary-costs.md
  - classification-politics.md
---

# Anatomy of an AI System

## When to Use

- When an audience needs to see the full material and political infrastructure beneath a specific AI product or service
- When evaluating an AI deployment by mapping every layer of its supply chain, from mineral extraction to user interface
- When a conversation treats an AI product as self-contained and needs the wider system made visible

## Core Concept

In 2018, Kate Crawford and Vladan Joler produced "Anatomy of an AI System," a large-scale research-art map tracing the full lifecycle of a single Amazon Echo. The work follows the device from the mines where its minerals are extracted, through the smelters and fabrication plants where its components are manufactured, to the data centres where its voice-recognition models are trained, to the homes where it listens, and finally to the electronic-waste dumps where it is discarded. The result is a visualisation of AI not as a product but as an infrastructure — a layered system of material extraction, human labour, data capture, and capital accumulation.

The anatomy reveals three simultaneous extraction processes. First, extraction of resources from the earth: lithium, cobalt, copper, tin, tungsten, gold, and rare earths, sourced from mines across multiple continents under conditions that range from industrial to artisanal to exploitative. Second, extraction of human labour: assembly workers in Shenzhen, data labellers in East Africa and Southeast Asia, content moderators in Manila, logistics workers in Amazon warehouses. Third, extraction of data from users: every voice command, every query, every silence feeds back into training pipelines that improve the product and generate value for the company, not the user.

What makes the anatomy methodology powerful for development practitioners is its insistence on completeness. Most evaluations of AI systems operate at a single layer — the algorithm, the interface, the business model. Crawford and Joler's method demands vertical integration: from geological substrate to atmospheric carbon, from labour relations to data governance, from mineral trade routes to regulatory frameworks. When a development agency proposes an AI-enabled service, the anatomy method asks: can you draw the full map? If not, which layers are you choosing not to see, and why?

The anatomy also reveals temporal dimensions. The minerals in a single device were formed over millions of years. The device itself has a functional life of a few years. The electronic waste it produces will persist for centuries. AI is a system that compresses geological time into consumer time and then extends the consequences across future generations. For development contexts — where intergenerational equity is a stated goal — this temporal structure matters.

## How to Apply

1. **Draw the full stack.** For any AI system under evaluation, map at least five layers: mineral inputs, hardware manufacturing, data infrastructure (centres, energy, water), data labour (collection, labelling, moderation), and the application layer (interface, classification, output). Crawford and Joler's method insists: "If you cannot map it, you cannot govern it."

2. **Identify what each layer conceals.** Each layer of the stack is designed to be invisible to the layers above it. The user does not see the data centre; the data centre does not see the mine; the mine does not see the electronic-waste dump. Identify these designed invisibilities and name them.

3. **Trace the value flow.** At each layer, ask: who captures the value generated here, and who bears the cost? The anatomy reveals that value flows upward and inward (toward the platform company) while costs flow downward and outward (toward peripheral communities). Map this flow concretely.

4. **Apply to a specific product or proposal.** The anatomy method works best when applied to something concrete — a specific AI product, a specific procurement decision, a specific programme design. Generality weakens it. Name the device, the provider, the data centre, the supply chain.

## Examples

**Situation:** A development agency is designing an AI-powered agricultural advisory service for smallholder farmers in East Africa. The service will use satellite imagery, weather data, and farmer-reported data to provide planting and harvest recommendations via a mobile app.

**Application:** Applying Crawford and Joler's anatomy method, the full infrastructure map reveals layers the programme design does not address. At the mineral layer: the smartphones farmers use contain cobalt likely mined in neighbouring DRC, creating a dependency chain within the same region. At the hardware layer: the satellites providing imagery were manufactured and launched by a small number of companies with their own supply-chain issues. At the data-infrastructure layer: the machine-learning models run on cloud servers consuming water and electricity in facilities thousands of kilometres from the farmers they serve. At the data-labour layer: if training data required manual labelling of satellite images or crop classifications, who did that work, under what conditions, and at what pay?

At the application layer, the recommendations the system produces encode particular agricultural theories — which crops, which methods, which markets. These are not neutral; they reflect the priorities of whoever designed the training pipeline. And at the waste layer: what happens to the smartphones when they break? East Africa already receives disproportionate volumes of electronic waste from the Global North; a programme that distributes devices without planning for end-of-life management adds to that burden.

The anatomy does not necessarily argue against the programme. It argues for completeness — for seeing and governing the full stack rather than evaluating only the application layer where the benefits are visible.

## Anti-Patterns

- **Don't stop at one layer.** The anatomy method's entire value lies in vertical integration — tracing the full stack from mineral to interface to waste. An analysis that examines only the algorithm, or only the environmental cost, or only the labour conditions, misses the structural insight: these layers are connected, and the connections are what produce and distribute power.

- **Don't treat the anatomy as an argument against all AI.** Crawford and Joler's work is not a rejection of technology. It is a demand for visibility. The anatomy method asks for honest accounting, not abstinence. An AI system whose full anatomy is visible, governed, and justified is different from one whose anatomy is hidden — and the difference is political, not technical.
