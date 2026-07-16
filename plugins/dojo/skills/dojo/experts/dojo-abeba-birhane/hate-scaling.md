---
triggers:
  - "does scaling up a dataset reduce or increase harmful content"
  - "bigger datasets are cleaner datasets assumption"
  - "relationship between scale and harmful content in AI training data"
use_when:
  - "Challenging the assumption that larger datasets naturally dilute or wash out biases and harmful content"
  - "Evaluating whether a scale-up of data collection will improve or worsen data quality"
  - "Arguing against 'more data fixes bias' narratives in AI development or policy"
fails_when:
  - "The discussion is about computational scaling (model size, parameters) rather than data scaling"
  - "The question concerns synthetic data generation where web-scraping dynamics do not apply"
  - "The user needs practical guidance on data collection rather than a critique of scaling assumptions"
related:
  - dataset-audits.md
  - algorithmic-colonisation.md
  - forgotten-margins.md
---

# Hate Scaling Laws

## When to Use

- When someone assumes or argues that making a dataset larger will naturally improve its quality, reduce its biases, or dilute its harmful content — and that assumption needs to be challenged with empirical evidence.
- When evaluating a proposal to scale up data collection and you need to assess whether the scaling will amplify rather than reduce the harms present in the existing data.
- When the "more data is better" assumption is shaping policy, procurement, or development decisions about AI systems, and the counter-evidence needs to be made visible.

## Core Concept

Hate scaling laws describe an empirical finding that directly contradicts one of the AI industry's foundational assumptions: that larger datasets are cleaner datasets. The assumption has intuitive appeal — if harmful content is a small fraction of the internet, then scraping more of the internet should dilute it to statistical insignificance. The empirical reality is the opposite.

Birhane's research with collaborators demonstrated that as web-scraped datasets grow, the absolute volume of harmful content increases, and in many categories the proportional concentration increases as well. This is not a paradox. It reflects the structure of the internet from which the data is scraped. Hateful, misogynistic, and racially stereotyped content is not uniformly distributed at low density across the web. It is concentrated in specific sources, formats, and communities that are disproportionately well-represented in web-scraping pipelines — because they are prolific, because they are algorithmically amplified, and because they are designed for engagement.

The mechanism works through several channels. First, scraping at scale reaches deeper into the long tail of the web, where content moderation is weaker and harmful content is denser. Second, automated filtering cannot keep pace with scale — classifiers that perform adequately on small datasets develop systematic blind spots when applied to orders-of-magnitude larger corpora. Third, the internet itself is shaped by attention economies that reward extreme and provocative content, so the "firehose" approach to data collection ingests the output of systems designed to amplify harmful material.

For development practice, the hate scaling finding has direct policy implications. When AI vendors claim that their systems improve with more data from deployment contexts — more user interactions, more local language data, more behavioural records — the relevant question is not just "more data about what?" but "more data with what embedded harms?" Scaling up data collection in contexts where content moderation infrastructure is weak, where gender-based violence is normalised in media, or where ethnic stereotypes pervade public discourse will amplify those harms in the training data, not dilute them. The intervention is not more data but better-governed data — smaller, curated, consented, context-specific datasets with auditable provenance.

The hate scaling finding also challenges the political economy of the AI industry, where scale is the primary competitive advantage and the incentive structure rewards maximising data volume over data quality. "Bigger is better" is not a technical finding — it is a business strategy, and one whose costs are externalised onto the communities whose data is scraped and whose harms are amplified.

## How to Apply

1. **Invert the default assumption about scale.** "When a vendor or researcher claims that scaling up data will improve the system, ask for the evidence — specifically, for performance metrics on harmful content disaggregated across the scale-up. The burden of proof should be on the claim that more data is better, not on the challenge to that claim. Our empirical work shows the opposite, and the industry's assumption is an article of faith, not a demonstrated finding."

2. **Audit the data at multiple scales to reveal the scaling curve.** "If you have access to a dataset at different sizes — or to snapshots taken as it grew — compare the composition. What happens to the proportion of stereotyped associations, gendered violence, or racial slurs as the dataset doubles, then doubles again? Plotting the hate scaling curve for a specific dataset is more persuasive than citing the general finding."

3. **Connect scale to the attention economy.** "Web-scraped data is not a random sample of human knowledge. It is a sample of what the internet's attention economy has amplified. When you scale up scraping, you scale up ingestion of attention-optimised content — which is disproportionately extreme, sensational, and harmful. The data pipeline inherits the pathologies of the platform economy."

4. **Propose the alternative: smaller, governed, consented data.** "The alternative to scale is curation. Smaller datasets, assembled with consent, annotated by people with domain expertise and fair compensation, governed by institutions accountable to affected communities. This is more expensive per data point but cheaper in downstream harms. The cost comparison must include the externalised costs of harm, not just the production cost of the data."

## Examples

**Situation**: A government agency is procuring an AI system for automated review of social protection applications. The vendor proposes a "continuous learning" feature where the system improves by ingesting more application data over time. The vendor argues that as the system processes more cases, it will become more accurate and fairer. The agency asks for an evaluation of this claim.

**Application**: The hate scaling framework challenges the vendor's assumption directly. As the system ingests more application data, it will encounter the full distribution of patterns in that data — including whatever structural biases exist in the social protection system itself. If historical application decisions reflect gender bias (women's applications scrutinised more rigorously), geographic bias (rural applications disproportionately rejected), or ethnic bias (certain surnames triggering additional review), the continuous learning system will not dilute these patterns — it will encode them as features of "accurate" decision-making. More data reinforces the existing distribution; it does not correct it. The evaluation should demand that the vendor demonstrate, with disaggregated metrics across gender, geography, and ethnicity, that accuracy improves equally for all groups as scale increases. The prediction from hate scaling research is that it will not — that performance gaps will widen as the system learns the structural biases in the historical data more precisely. The governance recommendation is to reject continuous learning on uncurated administrative data and instead require periodic retraining on audited, balanced datasets with explicit bias correction.

## Anti-Patterns

**Don't** treat hate scaling as an argument that all data is harmful and data collection should stop.
**Why**: The finding is specific: unsupervised web scraping at scale amplifies harmful content. The conclusion is not data nihilism but data governance — curated, consented, audited datasets assembled with structural awareness. Overgeneralising the finding into "data is the problem" misses the point and makes the critique easy to dismiss as impractical.

**Don't** assume that hate scaling applies only to text and image data.
**Why**: The mechanism — that scaling up ingestion from structurally biased sources amplifies rather than dilutes the bias — applies to any data type. Administrative records, sensor data, transaction histories, and geospatial data all carry structural biases from the systems that produced them. The specific findings were demonstrated on multimodal web-scraped data, but the logic extends to any context where the data source is shaped by the inequalities the system is supposed to address.
