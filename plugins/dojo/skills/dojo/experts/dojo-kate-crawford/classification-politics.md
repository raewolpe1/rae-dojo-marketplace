---
triggers:
  - AI classification
  - sorting systems
  - emotion detection bias
use_when:
  - An AI system sorts people into categories with material consequences
  - Evaluating fairness, bias, or accuracy claims in classification systems
  - A welfare, policing, hiring, or identity system uses algorithmic sorting
fails_when:
  - The classification under discussion is genuinely low-stakes and uncontested (e.g., sorting images of geological samples)
  - The user needs a technical fairness-metrics tutorial rather than political analysis
  - The critique is applied without attention to the specific categories and their specific histories
related:
  - training-set-archaeology.md
  - ai-as-extraction.md
  - anatomy-of-ai.md
---

# Classification Politics

## When to Use

- When an AI system classifies people — into risk categories, identity groups, emotional states, or eligibility tiers — and those classifications have material consequences
- When evaluating claims that an AI classification system is "objective," "unbiased," or "fair"
- When a development programme uses algorithmic sorting to allocate resources, target interventions, or verify identity

## Core Concept

Crawford argues that classification is the most politically consequential operation AI performs, and also the most routinely depoliticised. Every AI classification system embeds a theory of the world — a set of assumptions about what categories exist, what they mean, who belongs in them, and what follows from membership. These assumptions are not discovered by the algorithm; they are designed into it by the people who define the categories, assemble the training data, and choose the evaluation metrics.

The politics of classification have deep roots that predate computing entirely. Linnaeus classified humanity into racial hierarchies. Colonial censuses imposed ethnic categories that became the basis for political identity — and, in cases like Rwanda, for genocide. Eugenics classified people by "fitness" for reproduction. Credit scoring classified people by "risk" in ways that encoded racial segregation. Crawford's argument is that contemporary AI classification is not a break from these histories but a continuation of them, carried forward on new infrastructure with new speed and scale.

Three features make AI classification particularly consequential. First, scale: an algorithmic classification system can sort millions of people in seconds, making its errors systemic rather than individual. Second, opacity: the basis for classification is often hidden inside models that neither the classified person nor the deploying institution fully understands. Third, feedback: classification decisions generate data that feeds back into the system, reinforcing the initial categories. A neighbourhood classified as "high risk" receives more policing, which produces more arrests, which confirms the classification. The loop is structural, not accidental.

For development practitioners, classification politics are especially acute. Biometric identity systems classify people as "verified" or "unverified" — with consequences for access to services, social protection, and citizenship. Welfare-targeting algorithms classify households as "poor" or "not poor," "deserving" or "fraudulent." Predictive systems classify communities as "at risk" or "resilient." In each case, the classification is not a technical input to a political process — the classification is the political process. The algorithm does not assist the decision; it makes the decision, at a speed and scale that forecloses human deliberation.

Crawford's central challenge to the AI fairness industry is that improving the accuracy of a classification does not address the politics of the category itself. A more accurate emotion-detection system is still performing emotion detection — a practice with no scientific consensus behind it. A more "fair" recidivism predictor is still predicting recidivism — using a category shaped by the criminal-justice system's own biases. The question is not whether the classification is accurate but whether the classification should exist.

## How to Apply

1. **Interrogate the categories before evaluating the model.** Before asking "Is this classification accurate?" ask "Should this classification exist? Who defined these categories? What theory of the world do they encode?" Crawford's principle: "The most important decision in any AI system is not the algorithm — it is the taxonomy."

2. **Trace the genealogy of the categories.** Every classification scheme has intellectual ancestors. Emotion detection descends from Paul Ekman's universalist affect theory, which is scientifically contested. Risk scoring descends from actuarial practices shaped by racial segregation. Tracing the genealogy reveals what the categories carry forward and what they naturalise.

3. **Map the consequence chain.** Follow the classification from label to action. What happens to someone classified as "high risk"? "Fraudulent"? "Unverified"? The political weight of a classification system lies not in the label itself but in the institutional actions the label triggers. A label with no consequences is a research exercise; a label that determines access to housing, welfare, or freedom is a governing instrument.

4. **Ask who can contest the classification.** A classification system is accountable only if the classified person can see, understand, and challenge the classification. If the basis for classification is opaque, the appeal mechanism is absent, and the institutional incentive is to defend the system, then the classification is functioning as a form of administrative power without democratic accountability. Name that structure.

## Examples

**Situation:** A national social protection agency is deploying an AI system to identify households "most likely to be in extreme poverty" for targeted cash transfers. The system uses mobile-phone metadata, satellite imagery of housing quality, and transaction records to generate a poverty probability score for each household.

**Application:** Crawford's classification-politics lens raises questions that the technical design process is structured to suppress. First, the category: "extreme poverty" is not a natural kind. It is a political-economic construct whose boundaries have been debated for decades. The system does not discover poverty; it imposes a particular definition of poverty and then sorts the population accordingly. Whose definition? Designed by whom? Validated against what ground truth?

Second, the proxies: mobile-phone metadata and housing imagery are proxies for income, but they are also proxies shaped by infrastructure access, cultural practice, and geographic context. A household without a mobile phone is not necessarily poorer than one with a phone — it may be in a region without coverage, or its members may share devices in ways the model does not capture. The proxies encode the infrastructure biases of the data environment.

Third, the feedback loop: households classified as "not in extreme poverty" are excluded from transfers. Their economic situation may deteriorate as a result, but the system has already classified them and moved on. The classification becomes self-fulfilling — not because it was accurate, but because it was consequential.

The critical intervention is not to demand a better algorithm but to demand transparency about the category definition, the proxy assumptions, the exclusion consequences, and the contestation mechanism. If a family classified as "not poor enough" cannot see the basis for that classification and challenge it, the system is exercising power without accountability — and no amount of technical refinement addresses that structural problem.

## Anti-Patterns

- **Don't reduce classification politics to "bias."** Bias implies a correctable deviation from a neutral standard. Crawford's argument is that there is no neutral standard — the categories themselves are political constructions. Calling the problem "bias" accepts the legitimacy of the classification and asks only that it be done more accurately. That is often the wrong question.

- **Don't separate classification from consequence.** Analysing an AI classification system without tracing what happens to the people it classifies is incomplete. The politics are not in the label — they are in the eviction, the benefit denial, the arrest, the border refusal, the service exclusion that the label triggers. Always follow the classification to its institutional endpoint.
