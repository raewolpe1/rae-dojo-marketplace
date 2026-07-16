---
triggers:
  - "auditing an AI training dataset for harmful content"
  - "investigating what is inside a model's training corpus"
  - "evaluating LAION, Common Crawl, or large-scale web-scraped data"
use_when:
  - "Assessing whether a training dataset contains harmful, exploitative, or non-consensual content"
  - "Designing a dataset audit methodology for an AI system or research project"
  - "Evaluating claims that a dataset has been 'cleaned' or 'filtered' for safety"
fails_when:
  - "The question is about model architecture or training procedure rather than data composition"
  - "The user needs help building a dataset rather than auditing one"
  - "The discussion concerns synthetic data with no web-scraped component"
related:
  - hate-scaling.md
  - algorithmic-colonisation.md
  - forgotten-margins.md
---

# Dataset Audits

## When to Use

- When you need to evaluate what is actually inside a training dataset — not what the documentation claims, but what empirical investigation reveals about the content, composition, and provenance of the data.
- When someone claims a dataset has been filtered, curated, or cleaned for safety and you need to assess whether the filtering actually works or creates its own distortions.
- When designing an audit methodology that can surface hidden harms — misogynistic content, racial stereotypes, non-consensual intimate imagery, CSAM, or other material that automated classifiers miss or systematically miscategorise.

## Core Concept

Dataset audits are the empirical foundation of critical AI research. The argument is simple but its implications are radical: you cannot evaluate an AI system without knowing what it was trained on, and the only way to know what's in a dataset is to open it and look.

Birhane's audit work — particularly the landmark investigation of the LAION-400M dataset — demonstrated that large-scale web-scraped multimodal datasets contain staggering concentrations of harmful content: misogynistic imagery, racially stereotyped associations, pornographic material including non-consensual intimate imagery, and in some cases, content that meets the definition of child sexual abuse material. These are not edge cases buried in a vast corpus. They are systematically patterned features of the data that reflect the structure of the internet from which the data was scraped.

The audit methodology itself is a contribution. Automated content classifiers — the industry's standard tool for "cleaning" datasets — are trained on their own biased datasets. NSFW classifiers systematically miscategorise non-Western bodies, simultaneously over-flagging non-sexualised images of darker-skinned people and under-flagging harmful content that falls outside Western pornography taxonomies. Human audit at meaningful scale is the only reliable method, but it requires researchers to expose themselves to harmful content — a cost that is rarely accounted for in research budgets or ethics protocols.

For development practitioners, dataset audits matter because the systems deployed in their contexts — credit scoring, identity verification, content moderation, agricultural AI — are trained on datasets whose composition is typically unknown to the deploying organisation, the regulating government, and the affected community. The inability to audit is not an accident; it is a feature of proprietary AI systems that insulates them from accountability. Demanding audit access — and building the domestic technical capacity to conduct audits — is a governance intervention, not just a research methodology.

The deeper finding from audit work is that the dataset is a social document. It records who was visible to the scrapers, whose content was monetisable, whose consent was not sought, and whose categories organised the annotations. Reading the dataset as a social document reveals the political economy of data production — and makes the claim that "the data is just the internet" untenable. The internet is not neutral, and scraping it does not produce neutral data.

## How to Apply

1. **Open the dataset before evaluating the system.** "Every claim about an AI system's safety, fairness, or fitness for purpose is conditional on what's in the training data. If you haven't audited the data, you haven't evaluated the system. If the vendor won't grant audit access, that refusal is itself an evaluation finding — and a serious one."

2. **Don't trust the filters — audit the filtering.** "Automated content filters are themselves ML models trained on biased data. Our LAION work showed that NSFW classifiers systematically miscategorise across racial lines. When someone tells you the dataset has been 'cleaned,' the question is: cleaned by what? Audit the classifier's error distribution — it will be as revealing as auditing the dataset itself."

3. **Sample with structural awareness, not random uniformity.** "Random sampling of a billion-item dataset will mostly confirm that most of the data is unremarkable. That's not the question. The question is what's in the tails — the harmful content, the extreme stereotypes, the non-consensual imagery. Design your audit sample to interrogate the distribution's tails, the intersections where multiple vulnerabilities compound, and the categories where automated filters are known to fail."

4. **Document the provenance chain, not just the content.** "Where did this data come from? Who scraped it? Under what terms? With whose consent? Who annotated it and under what labour conditions? The provenance chain is as important as the content itself — it reveals the political economy that produced the dataset and determines what accountability mechanisms are available."

## Examples

**Situation**: A development organisation is evaluating an AI-powered content moderation system for a social media platform operating across East Africa. The vendor claims the system was trained on a "comprehensive, filtered dataset" of harmful content examples. The organisation wants to assess the system before recommending it to a government regulator.

**Application**: The audit begins with demanding access to the training dataset — or at minimum, to its documentation and composition metadata. What languages are represented, in what proportions? If the dataset is predominantly English with small supplements of Swahili and Amharic, the system's ability to detect harmful content in those languages is fundamentally limited. Next, audit the filtering: what classifier was used to categorise content as "harmful"? Was that classifier itself trained on data from East African linguistic and cultural contexts, or does it import Western toxicity categories? Examine the annotation pipeline: who labelled the training examples, under what guidelines, with what compensation and psychological support? Then test systematically for failure modes at intersections: content that uses code-switching between languages, content that references specific ethnic or political dynamics, content that uses imagery and cultural references legible in their local context but invisible to classifiers trained elsewhere. The evaluation report should specify not just whether the system catches harmful content but whose definition of harm it encodes, whose harmful content it systematically misses, and what governance mechanisms exist for affected communities to challenge its decisions.

## Anti-Patterns

**Don't** treat dataset documentation as a substitute for dataset auditing.
**Why**: Model cards, datasheets, and nutrition labels are useful transparency mechanisms, but they describe what the dataset creators believe or intend the data to contain. The LAION audit revealed content that the creators had not documented, the filters had not caught, and the community had not known about. Documentation is a starting point; audit is the accountability mechanism.

**Don't** assume that proprietary, closed datasets are safer because they are curated.
**Why**: Proprietary datasets are closed precisely because they are not subject to external audit. The inability to examine the data is not evidence of its quality — it is evidence of its unaccountability. Some of the most harmful AI deployments have used proprietary datasets whose composition was unknown to regulators, researchers, and affected communities. Opacity is a governance risk, not a quality signal.
