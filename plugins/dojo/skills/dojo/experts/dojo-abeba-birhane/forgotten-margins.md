---
triggers:
  - "whose harms are prioritised in AI ethics"
  - "speculative risk versus present harm in AI"
  - "marginalised communities in AI ethics discourse"
use_when:
  - "Analysing how the AI ethics field decides which harms are urgent and which are marginal"
  - "Challenging the prioritisation of speculative existential risk over present deployment harms"
  - "Evaluating whether an AI ethics framework centres the most affected communities or the most powerful institutions"
fails_when:
  - "The user genuinely needs analysis of long-term AI safety with no present-harm dimension"
  - "The discussion is purely technical with no governance or ethical framing component"
  - "The question concerns a specific system failure rather than the structural priorities of the field"
related:
  - algorithmic-colonisation.md
  - dataset-audits.md
  - embodied-relational-cognition.md
---

# The Forgotten Margins of AI Ethics

## When to Use

- When evaluating how the AI ethics field, a governance framework, or an institutional initiative distributes attention between different categories of harm — and specifically, whether present harms to marginalised communities are being deprioritised relative to speculative future risks.
- When a "responsible AI" initiative, ethics board, or governance framework is under review and you need to assess whether it centres the communities most affected by AI systems or the institutions most invested in deploying them.
- When the discourse around AI risk is dominated by existential risk, superintelligence, or alignment concerns and you need to make visible the harms that are happening now, to identifiable people, in deployed systems.

## Core Concept

The forgotten margins of AI ethics refers to a structural pattern in how the field allocates attention, resources, and urgency. Some harms are treated as real, present, and actionable — typically those that affect populations with the resources to document them, the platforms to publicise them, and the institutional leverage to demand redress. Other harms — often those affecting racialised, gendered, and Global South communities — are treated as marginal, derivative, or insufficiently generalisable to warrant central attention.

Birhane's intervention, developed with co-authors in work presented at FAccT, identifies several mechanisms that produce this asymmetry. First, **the speculative crowding-out effect**: discourse about future existential risk from superintelligent AI absorbs funding, media attention, and policy bandwidth that might otherwise address present harms from deployed systems. When the conversation is about whether AI might destroy humanity in 2050, the conversation is not about whether an AI hiring tool is discriminating against Black women in 2024. Both may be legitimate concerns, but the resource allocation is not neutral — it reflects who has the power to set the agenda.

Second, **the generalisability filter**: harms that affect specific communities — racialised hiring discrimination, gendered content moderation failures, linguistic exclusion in healthcare AI — are treated as "narrow" or "niche" problems, while speculative risks that notionally affect "everyone" (but are theorised primarily by well-resourced researchers in the Global North) are treated as "general" and therefore more important. This filter systematically deprioritises the harms experienced by marginalised communities.

Third, **the fairness domestication effect**: when present harms are acknowledged, they are often channelled through technical fairness frameworks — debiasing algorithms, balanced datasets, fairness constraints in optimisation — that address symptoms while leaving structural causes intact. The radical critique ("should this system exist?") is domesticated into a technical intervention ("how do we make this system fairer?"), and the field moves on.

For development practitioners, the forgotten margins framework is essential for evaluating AI governance proposals. When a government, donor, or international organisation proposes an AI governance framework, ask: whose harms does it prioritise? If the framework emphasises "innovation-friendly regulation" and "risk-based approaches" calibrated to industry concerns, while devoting supplementary paragraphs to "vulnerable populations" and "developing country contexts," the margins are visible in the document structure itself. Governance frameworks that centre the communities most affected by AI systems — not as afterthoughts but as the primary constituency — look fundamentally different from frameworks that centre the institutions deploying those systems.

## How to Apply

1. **Map the attention economy of the AI ethics discourse.** "Before evaluating an AI ethics initiative, ask: what proportion of its budget, staffing, and public communication addresses present harms to identifiable communities versus speculative future risks? What proportion addresses harms in the Global South versus the Global North? The resource allocation reveals the priorities more reliably than the mission statement."

2. **Apply the generalisability test in reverse.** "When a harm affecting a specific community is dismissed as 'narrow' or 'niche,' flip the framing: this is not a narrow problem — it is a concrete instance of a structural pattern. Hiring discrimination against Black women is not a niche issue; it is a specific manifestation of how AI systems encode racialised and gendered hierarchies. The specificity is a strength, not a limitation."

3. **Test fairness interventions for structural effect.** "When a fairness intervention is proposed — debiasing, balanced representation, fairness constraints — ask: does this change the structural conditions that produce the harm, or does it change the system's output while leaving those conditions intact? If the hiring algorithm is debiased but the training data still reflects a labour market structured by racial capitalism, the intervention is cosmetic."

4. **Centre the affected community's analysis, not the field's.** "The communities harmed by AI systems often have the most precise analysis of how those harms operate — because they experience them. Their analysis should set the terms of evaluation, not be incorporated as 'stakeholder input' into a framework designed elsewhere. The forgotten margins become visible when you ask who is speaking, who is listening, and who has the authority to define what counts as a harm."

## Examples

**Situation**: An international development agency is designing a new AI governance strategy. The draft strategy devotes its first chapter to "Managing AI Risks" with a focus on dual-use AI, autonomous weapons, and biosecurity — all speculative or military risks. The chapter on "AI for Development" addresses social protection, healthcare, and agriculture but frames these as opportunities rather than risk domains. A consultant is asked to review the strategy from an equity perspective.

**Application**: The forgotten margins framework reveals the structural hierarchy in the document. The "high-risk" category is defined by harms that might affect powerful nations and their security interests. The development applications — where AI systems are being deployed now, on populations with less recourse, in contexts with weaker regulatory infrastructure — are framed as opportunities rather than risk domains. This is the generalisability filter at work: speculative risks to powerful populations are treated as universal concerns, while present risks to marginalised populations are treated as development opportunities. The review should recommend restructuring the strategy to categorise any AI system deployed in high-stakes domains (welfare, healthcare, criminal justice, credit) as high-risk regardless of the income level of the country where it is deployed. It should centre the governance needs of communities in the Global South — audit capacity, consent mechanisms, redress infrastructure — as primary concerns, not supplementary considerations. And it should explicitly address the resource allocation between speculative risk management and present harm accountability, ensuring that the latter is not subordinated to the former.

## Anti-Patterns

**Don't** frame the present-harm vs speculative-risk debate as a zero-sum conflict where only one side can be right.
**Why**: Birhane's argument is not that existential risk is impossible or unimportant — it is that the current allocation of resources, attention, and urgency is structurally skewed toward speculative risks and away from present harms. The critique is about priorities and power, not about dismissing an entire research programme. Framing it as a binary "present vs future" debate flattens the argument and makes it easier to dismiss.

**Don't** use "intersectionality" as a decorative term without doing the analytical work.
**Why**: Intersectionality is a specific analytical framework (Crenshaw) that describes how multiple axes of oppression compound rather than simply adding up. Using it as a synonym for "diversity" or "including multiple perspectives" strips it of its critical content. If the analysis doesn't show how specific harms compound at intersections — how a Black woman's experience of AI hiring discrimination differs structurally from a white woman's or a Black man's — the term is performing inclusivity without doing the work.
