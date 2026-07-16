---
triggers:
  - "user asks about AI labour or data workers"
  - "user asks about data annotation, content moderation, or RLHF"
  - "user encounters AI deployment in African or Global South contexts"
use_when:
  - "making visible the invisible labour that produces AI systems — data annotation, content moderation, RLHF"
  - "documenting the conditions under which AI labour is performed in the Global South"
  - "connecting AI deployment in development contexts to the labour exploitation behind the systems"
fails_when:
  - "you present the workers as helpless victims rather than as agents navigating structural constraints"
  - "you reduce the labour analysis to a single company or country"
  - "you treat the labour pipeline as a temporary stage rather than a permanent feature of AI production"
related:
  - "empire-of-ai.md"
  - "ai-resource-extraction.md"
  - "openai-case-study.md"
---

# AI Labour Pipeline

## When to Use
- When AI capabilities are being discussed without reference to the human labour that produces them — and the labour needs to be made visible.
- When AI is being deployed in African or Global South contexts and the irony needs to be named: the systems being deployed are built on the labour of workers in the same regions.
- When Hao's investigative reporting on data workers in Kenya, the Philippines, and Venezuela provides the evidence base.
- **Non-negotiable for any African AI engagement** — Hao's labour-pipeline reporting is grounded in the African data-worker story.

## Core Concept
The AI labour pipeline is the system through which human labour — data annotation, content moderation, RLHF feedback — is extracted from workers in the Global South to produce AI systems consumed in the Global North. This pipeline is the central mechanism of the AI empire: it converts cheap human labour into expensive AI capability, capturing the value differential as profit for the AI companies and their investors.

The pipeline operates through outsourcing. The AI labs (OpenAI, Google, Meta, Anthropic) contract with business process outsourcing (BPO) companies (Sama, Scale AI, Appen, Remotasks) who hire workers in Kenya, the Philippines, Venezuela, India, and elsewhere. The workers — often educated, multilingual, and technically competent — are classified as independent contractors, paid between $1.50 and $3.50 per hour, denied benefits, and employed on precarious short-term contracts. The outsourcing layer absorbs liability: the AI lab can claim it does not employ the workers; the BPO company can claim it merely follows the AI lab's instructions.

The work itself is often traumatic. Content moderators review violent, sexual, and hateful content to train safety classifiers. RLHF workers evaluate model outputs for harmfulness — which means reading the harmful outputs. Data annotators label images, text, and audio for hours under intense productivity targets. The psychological toll is documented and significant; the mental health support is minimal or absent.

Hao's MIT Technology Review reporting documented the specific case of Sama's workers in Nairobi who trained ChatGPT's safety systems — workers paid approximately $2 per hour to read and classify descriptions of sexual abuse, violence, and self-harm. The reporting contributed to Sama's decision to exit the AI content-moderation business — but the work was simply transferred to other outsourcing companies. The pipeline is structural, not contingent on any single company.

## How to Apply
1. **Make the labour visible.** "When an AI system is being adopted or evaluated, ask: who did the training labour? Where? Under what conditions? At what wages? The answers are rarely available — which is itself evidence of the invisibility by design."
2. **Trace the supply chain.** "From the user interface, trace backward: model → training data → annotation → workers → outsourcing company → AI lab. Each link in the chain distances the AI lab from the labour conditions while concentrating the value at the top."
3. **Connect to the local context.** "If you are working in Kenya, the Philippines, or any country with a significant BPO sector, your local workforce may already be part of the AI supply chain. The workers who annotate data for global AI systems live in the same communities that development programmes serve."
4. **Demand supply-chain transparency.** "When procuring AI services, require disclosure: where is the training labour performed? By whom? Under what conditions? At what wages? If the vendor cannot or will not disclose, the invisibility is functioning as designed."

## Examples
**Situation:** A development organisation in East Africa is adopting an AI-powered platform for beneficiary registration and case management. The platform is marketed as "AI-driven" and promises to reduce administrative costs by 40%.
**Application:** "The platform's AI component was trained using human labour — data annotation, entity recognition labelling, and RLHF feedback. Some of that labour was almost certainly performed in East Africa: Nairobi is a major hub for AI data work. The workers who trained the model may live in the same communities the platform will serve. They were likely paid $2–3 per hour, classified as contractors, and employed on precarious terms. The organisation is now adopting a product built on this labour to serve these same communities — a product priced to cover compute costs and investor returns but not to reflect the full cost of the labour that produced it. This is not a reason to reject the platform — the 40% cost reduction is real and may allow the organisation to serve more people. But it is a reason to ask questions: what labour practices does the platform vendor require of its training-data suppliers? What wages? What working conditions? What mental-health support for content moderators? If the vendor cannot answer — or will not — the organisation is participating in a supply chain whose labour practices it cannot verify. At minimum, include supply-chain labour standards in the procurement criteria."

## Anti-Patterns
**Don't:** Present the workers as helpless.
**Why:** The data workers are often educated, multilingual, and technically skilled. They navigate the AI labour market with agency — choosing among employers, negotiating conditions, organising collectively where possible. The structural analysis should not deny individual agency.

**Don't:** Treat the labour pipeline as temporary.
**Why:** The industry narrative suggests that human labelling will be automated away. The evidence suggests otherwise: as models become more capable, the labelling requirements increase (more complex evaluation, more nuanced content moderation, more sophisticated RLHF). The pipeline is a permanent feature, not a transitional stage.
