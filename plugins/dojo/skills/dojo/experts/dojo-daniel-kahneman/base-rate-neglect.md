---
triggers:
  - "user asks about base-rate neglect or base-rate fallacy"
  - "user ignores statistical frequencies in favour of individual stories"
  - "user asks about how to combine prior probabilities with new evidence"
use_when:
  - "someone is judging probability based on a specific case while ignoring the base rate"
  - "a vivid individual case is overriding statistical evidence"
  - "Bayesian reasoning needs to be applied — updating prior probabilities with new evidence"
fails_when:
  - "you demand base rates without acknowledging that they are often unavailable or unreliable"
  - "you treat base-rate neglect as always irrational — sometimes the case-specific evidence is genuinely dominant"
  - "you explain Bayes' theorem mechanically without connecting it to the psychology"
related:
  - "availability-heuristic.md"
  - "cognitive-biases.md"
  - "regression-to-mean.md"
  - "system-one-and-two.md"
---

# Base-Rate Neglect

## When to Use
- When someone is making a probability judgment based on the features of a specific case while ignoring the statistical frequency of such cases.
- When individual stories are overriding statistical evidence in decision-making.
- When prior probabilities need to be combined with case-specific evidence.

## Core Concept
Base-rate neglect is the tendency to ignore or underweight statistical base rates when evaluating the probability of an event, particularly when vivid, case-specific information is available. The classic demonstration is the taxi-cab problem. A city has 85% green taxis and 15% blue taxis. A witness in an accident identified the taxi as blue, and witnesses are 80% accurate. What is the probability that the taxi was blue? Most people say 80%, because they anchor on the witness's accuracy. The correct Bayesian answer is about 41%, because the low base rate of blue taxis (15%) substantially lowers the posterior probability even after the witness evidence.

The mechanism is the representativeness heuristic. When people judge probability, they ask "how representative is this case of the category?" rather than "how frequent is this category?" A programme applicant who matches the profile of a successful participant feels like a good bet — but if only 10% of applicants with that profile actually succeed, the individual assessment is overriding the base rate. System 1 sees the compelling individual story; System 2 should check the statistics, but it often doesn't.

Base-rate neglect is particularly consequential in professional judgment. Medical diagnosis, where rare diseases are over-diagnosed because symptoms match the disease profile despite its low prevalence. Programme evaluation, where a single compelling success story overrides disappointing average outcomes. Hiring, where a charismatic interview performance overrides the low base rate of interview accuracy as a predictor of job performance.

Kahneman and Tversky showed that base rates are used when they are perceived as causal and concrete, but neglected when they are merely statistical. Telling people "30% of participants in this programme type drop out" has less impact than telling them "3 out of every 10 people sitting in front of you right now will drop out." The same information, framed as a causal story about real people, has more impact than an abstract statistic.

## How to Apply
1. **Always start with the base rate.** Before evaluating case-specific evidence, ask: "What is the prior probability? How often does this type of thing happen in general?"
2. **Make base rates causal and concrete.** "Of the last 20 programmes of this type, 14 failed to reach their targets" is more psychologically effective than "70% underperform."
3. **Use Bayesian updating explicitly.** Start with the base rate, then adjust based on the strength of the new evidence. The adjustment should be smaller than most people's intuition suggests.
4. **Challenge compelling individual cases.** "This case is vivid and compelling, but how representative is it? What's the base rate for cases that look like this?"

## Examples
**Situation:** A programme officer is enthusiastic about a new implementing partner whose proposal is excellent: detailed, well-written, with an impressive track record presentation. They want to fast-track the partnership.
**Application:** Kahneman would say: "Your enthusiasm is based on case-specific evidence — the quality of the proposal and the impressiveness of the presentation. But what is the base rate? What proportion of partners with excellent proposals actually deliver excellent implementation? In my experience — and this is consistent with the research on the relationship between proposals and performance — the correlation is modest. Good proposal-writing is a skill; good implementation is a different skill. Before fast-tracking, check the base rate: of the last 20 partners you selected based on strong proposals, how many performed well? If the answer is 12 out of 20, then a strong proposal raises your probability from whatever the overall base rate is — perhaps 50% of partners perform well — to something like 60%. That is useful but not decisive. It does not justify fast-tracking. Your System 1 sees the compelling proposal and generates confidence based on the coherence of the story. The base rate should temper that confidence considerably."

## Anti-Patterns
**Don't:** Demand base rates when they are genuinely unavailable.
**Why:** Sometimes there is no reference class. In truly novel situations, case-specific reasoning may be all that is available. The injunction to use base rates applies when they exist and are accessible, not always.

**Don't:** Treat base-rate neglect as always irrational.
**Why:** Sometimes case-specific evidence is so strong that it should dominate the base rate. A positive HIV test has a very high true-positive rate, and even in low-prevalence populations, the case evidence swamps the base rate. The question is always about the relative strength of the two types of evidence.
