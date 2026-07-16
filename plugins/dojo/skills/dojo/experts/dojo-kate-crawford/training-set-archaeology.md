---
triggers:
  - training data audit
  - ImageNet politics
  - dataset composition
use_when:
  - Auditing what is inside a training dataset and what its composition implies
  - Evaluating claims about data representativeness or data quality
  - A programme or product depends on a training corpus whose provenance is unclear
fails_when:
  - The conversation requires data-engineering advice on building better datasets rather than political analysis
  - The dataset under discussion is well-documented and the user needs implementation guidance
  - The archaeological metaphor is stretched beyond its analytical usefulness
related:
  - classification-politics.md
  - ai-as-extraction.md
  - planetary-costs.md
---

# Training-Set Archaeology

## When to Use

- When evaluating what is inside a training dataset — its sources, its categories, its labour of assembly, its embedded assumptions
- When a claim about AI performance depends on training data whose provenance, composition, or labour conditions are opaque
- When helping an audience understand that data is never raw — it is always cooked, by someone, for some purpose

## Core Concept

In "Excavating AI" (2019), Crawford and artist Trevor Paglen performed an archaeological dig into the training sets that underpin modern AI — most prominently ImageNet, the benchmark dataset that has shaped a generation of computer-vision research. What they found beneath the surface of these datasets was not neutral data but a sedimented record of cultural assumptions, historical prejudices, and political choices.

ImageNet, for example, derived its category labels from WordNet, a lexical database built by Princeton psychologists. The "person" categories in ImageNet included labels such as "alcoholic," "kleptomaniac," "drug addict," "failure," "loser," and racial slurs. These were not obscure edge cases — they were categories against which real photographs of real people were classified, often without those people's knowledge or consent. The images themselves were scraped from the internet, meaning they carried the biases of online image culture: whose photos are uploaded, whose faces are searchable, whose bodies are available for computational sorting.

Crawford's archaeological method treats training sets not as technical resources but as cultural artefacts — products of specific historical moments, specific institutions, specific labour practices, and specific theories of the world. Like any archaeological site, a training set reveals the values and assumptions of its makers when you dig carefully enough. The labels tell you what the makers thought the world contained. The images tell you whose bodies were available for capture. The gaps tell you who was invisible. The labour conditions tell you whose work was valued and whose was discounted.

For development practitioners, training-set archaeology is directly operational. Every AI system deployed in a development context depends on training data. If that data was assembled from Global North internet culture, it will encode Global North assumptions about what faces look like, what names mean, what "normal" housing looks like, what constitutes poverty or wealth. Deploying such a model in a Southern African or South Asian context is not a technical transfer — it is a cultural imposition carried on data infrastructure. The model does not adapt to local context; it imposes the context of its training data onto local populations.

The labour dimension is equally important. The people who label training data — who draw bounding boxes around faces, who tag images with emotion categories, who transcribe audio — are overwhelmingly located in the Global South, paid per-task rates that often fall below minimum wage, and exposed to traumatic content without adequate psychological support. Their labour is essential to AI but is systematically made invisible. Crawford's archaeology insists on making it visible: who labelled this data, under what conditions, for what pay, and with what consequences for their well-being?

## How to Apply

1. **Demand provenance documentation.** For any AI system, ask: what data was it trained on? Where did that data come from? Who assembled it? Who labelled it? Under what conditions? What categories were used? If the vendor or developer cannot answer these questions, that opacity is itself a finding. Crawford's principle: "If you do not know what is in the training data, you do not know what the model has learned."

2. **Examine the categories archaeologically.** Look at the labels used in the training set and trace their intellectual genealogy. Who defined "emotion"? Who defined "risk"? Who defined "quality"? Every label carries a history — and that history shapes what the model produces. A model trained on ImageNet's person categories has learned a theory of personhood that includes "failure" and "loser" as types of people.

3. **Audit for geographic and cultural fit.** If a model was trained primarily on data from one cultural context and deployed in another, the gap between training distribution and deployment context is a source of systematic error — not a bug but a structural feature. For development contexts, ask: does this training data represent the population it will classify? If not, what are the consequences of the mismatch?

4. **Make the labour visible.** For any labelled dataset, identify the labelling workforce. Where are they located? What are they paid? What content are they exposed to? What protections do they have? Crawford insists that data labour is real labour and must be evaluated by the same standards applied to any other form of work in a development programme's supply chain.

## Examples

**Situation:** A health ministry is procuring an AI-powered diagnostic imaging system to support radiologists in rural clinics. The vendor claims the system was "trained on millions of medical images" and achieves "specialist-level accuracy."

**Application:** Crawford's training-set archaeology prompts a series of questions the procurement process is unlikely to ask on its own. First, provenance: where were those millions of medical images sourced? If primarily from hospitals in the United States, Europe, or East Asia, the training distribution reflects the demographics, disease prevalence, and imaging equipment of those settings. Skin conditions present differently across skin tones; disease prevalence varies by geography; imaging equipment in rural African clinics differs from that in American teaching hospitals. The model's "specialist-level accuracy" was measured against a test set drawn from the same distribution as the training data — not from the deployment context.

Second, categories: what diagnostic categories does the model use? Were they defined by the clinical conventions of the data-source countries? Do they map onto the disease burden and clinical priorities of the procuring country? A model trained to detect conditions common in ageing Global North populations may be poorly calibrated for the infectious-disease and nutritional-deficiency patterns prevalent in a different demographic context.

Third, labour: who annotated the medical images? Were they qualified radiologists or lower-cost labellers? Were the annotations reviewed for quality? Medical data labelling requires clinical expertise — if the training labels were produced by non-specialists, the model's learned representations may encode labelling errors as medical knowledge.

The intervention is not to reject the system but to require the vendor to open the training set to archaeological scrutiny: provenance documentation, category definitions, demographic composition, labelling workforce credentials and conditions, and validation against the specific deployment population. A system that cannot survive this scrutiny is not ready for clinical deployment.

## Anti-Patterns

- **Don't treat "more data" as the solution.** The problems Crawford identifies in training sets are not problems of scale — they are problems of composition, category design, and labour conditions. A larger dataset assembled under the same conditions reproduces the same problems at greater scale. The fix is not volume but governance.

- **Don't separate the data from the labour that produced it.** Treating a training set as a technical artefact while ignoring the conditions under which it was labelled is analytically incomplete and ethically untenable. The data and the labour are inseparable — the label is the product of the labeller's work, and the labeller's conditions shape the label's quality and meaning.
