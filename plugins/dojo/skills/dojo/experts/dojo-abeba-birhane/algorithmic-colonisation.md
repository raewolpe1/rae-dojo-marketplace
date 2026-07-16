---
triggers:
  - "AI deployment in Africa or the Global South"
  - "data extraction from low-income countries"
  - "Western technology exported without local accountability"
use_when:
  - "Evaluating whether an AI deployment in the Global South reproduces colonial extraction patterns"
  - "Designing data governance or AI policy for African institutions"
  - "Challenging 'AI for development' narratives that centre foreign technology providers"
fails_when:
  - "The discussion is about AI systems deployed within and for Western contexts with no Global South dimension"
  - "The question is purely about technical model architecture with no deployment or governance component"
  - "The user needs a neutral survey of AI development perspectives rather than a critical structural analysis"
related:
  - dataset-audits.md
  - forgotten-margins.md
  - hate-scaling.md
---

# Algorithmic Colonisation

## When to Use

- When an AI system developed in the West is being deployed in African or Global South contexts and you need to evaluate the structural dynamics of that deployment — not just whether it "works" but who it works for.
- When advising on data governance, AI policy, or digital sovereignty for African institutions and the analysis must start from African realities rather than adapting Western frameworks.
- When challenging "AI for development" or "technology for inclusion" narratives that position Global South populations as recipients of benevolent innovation rather than agents of their own technological futures.

## Core Concept

Algorithmic colonisation describes the structural reproduction of colonial dynamics through AI systems. It operates through a double movement: Western AI systems are exported into Global South contexts — often under "development," "inclusion," or "leapfrogging" narratives — while data, labour, and value are extracted back into Western training pipelines, corporate datasets, and profit structures.

This is not a metaphor applied loosely. The parallels are structural and specific. Colonial extraction operated through asymmetric flows of raw materials outward and finished goods inward, creating dependency rather than development. Algorithmic colonisation operates through asymmetric flows of raw data outward (scraped from African users, annotated by African workers at exploitative wages) and finished AI products inward (deployed on African populations without meaningful consent, accountability, or local governance).

Three mechanisms are central. First, **data extraction**: African users' data — biometric, behavioural, linguistic — feeds into models owned and controlled by foreign corporations. The value accrues elsewhere. Second, **epistemic displacement**: AI systems import Western categories, taxonomies, and assumptions, displacing local knowledge systems and governance traditions. A credit scoring algorithm trained on US financial behaviour encodes a specific theory of creditworthiness that may be incoherent in an East African informal economy. Third, **dependency creation**: when AI systems become infrastructure — for identity verification, welfare distribution, agricultural advice — communities become dependent on systems they do not control, cannot audit, and cannot maintain.

For development practitioners, the framework reframes the evaluation question. The relevant question is not "does this AI system improve outcomes?" but "does this deployment create or reduce structural dependency, and whose interests does the data pipeline ultimately serve?" Development programmes that embed foreign AI infrastructure without building domestic technical capacity and governance authority are not development — they are the digital extension of structural adjustment.

## How to Apply

1. **Map the data flow before evaluating the deployment.** "Trace the full circuit: where does user data go after collection? Who owns the derived models? Can local institutions access, audit, or modify the system? If data flows out and products flow in with no local control over either, you are looking at an extractive structure, regardless of the stated development intention."

2. **Test for dependency creation, not just immediate impact.** "Ask what happens if the vendor withdraws, raises prices, or pivots their business model. If the community or government has no fallback because domestic alternatives were displaced or never developed, the deployment has created dependency. Impact evaluation must include structural resilience, not just short-term outcome metrics."

3. **Evaluate consent under conditions of inequality.** "When the AI system is the only pathway to a basic service — banking, welfare, healthcare — 'consent' to data collection is structurally coerced. Meaningful consent requires genuine alternatives. If there are none, the consent framework is decorative and the deployment is extractive regardless of how many consent forms were signed."

4. **Insist on domestic audit capacity.** "External audits conducted by European or American consultancies against European or American benchmarks reproduce the epistemic asymmetry. Build the audit capacity domestically: train local computer scientists in adversarial evaluation, fund local institutions to develop context-specific evaluation criteria, ensure that the people assessing the system understand the communities it affects."

## Examples

**Situation**: A European fintech company deploys an AI-driven credit scoring system across three West African countries. The system analyses mobile phone usage patterns, social media activity, and transaction histories to assess creditworthiness for microloans. The company's pitch to development donors emphasises "financial inclusion for the underbanked."

**Application**: The algorithmic colonisation framework reframes this deployment. The mobile phone and social media data of millions of West African users feeds into proprietary models owned by a European company — data extraction. The credit scoring algorithm encodes assumptions about creditworthiness derived from Western financial systems — assumptions that may systematically disadvantage informal economies, communal financial arrangements, and seasonal agricultural income patterns — epistemic displacement. If the system becomes the primary gateway to microcredit and domestic banking institutions atrophy or fail to develop their own scoring capacity, dependency is created. The development evaluation should ask not "does the system extend credit to previously excluded populations?" but "does the credit system create structural dependency on foreign infrastructure, and what happens to these populations' financial access when the company's incentives change?" A genuinely developmental credit scoring system would be owned by West African institutions, trained on data that remains under their governance, and auditable by domestic regulators with the technical capacity to evaluate it.

## Anti-Patterns

**Don't** treat algorithmic colonisation as a loose analogy for "AI might not work well in Africa."
**Why**: The colonial framework is structural, not attitudinal. It describes specific mechanisms — data extraction, epistemic displacement, dependency creation — that operate regardless of the intentions of the deployers. Weakening it to "cultural insensitivity" or "poor localisation" strips the analysis of its explanatory power and makes the problem appear solvable by better UX rather than structural change.

**Don't** assume that African-led AI development is automatically exempt from critique.
**Why**: The framework analyses structural dynamics, not national origin. An African company that replicates extractive data practices, displaces local knowledge systems, or creates dependency in rural communities is subject to the same critique. The relevant question is the structure of the data pipeline and governance architecture, not the passport of the CEO.
