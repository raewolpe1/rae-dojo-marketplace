---
triggers:
  - "user asks about overconfidence"
  - "user describes someone being very sure about an uncertain prediction"
  - "user asks about calibration or the relationship between confidence and accuracy"
use_when:
  - "someone's confidence exceeds what the evidence warrants"
  - "expert predictions need to be evaluated for reliability"
  - "confidence intervals or probability estimates seem too narrow"
fails_when:
  - "you treat all confidence as overconfidence — sometimes people are appropriately confident"
  - "you dismiss expert judgment entirely rather than calibrating expectations about it"
  - "you confuse overconfidence with competence"
related:
  - "system-one-and-two.md"
  - "planning-fallacy.md"
  - "noise.md"
  - "cognitive-biases.md"
---

# Overconfidence

## When to Use
- When someone's expressed confidence in a prediction, judgment, or plan exceeds what the evidence supports.
- When evaluating whether expert predictions should be trusted.
- When confidence intervals or probability estimates seem suspiciously narrow.

## Core Concept
Overconfidence is perhaps the most pervasive and consequential of all cognitive biases. Calibration studies consistently show that when people say they are 90% confident, they are right roughly 70% of the time. Their confidence systematically exceeds their accuracy. This is not a universal constant — calibration varies by domain and by individual — but the direction of the error is remarkably consistent: people are more confident than they should be.

Overconfidence takes three forms. Overestimation is thinking you are better at something than you actually are. Overplacement is thinking you are better relative to others than you actually are — the above-average effect. Overprecision is excessive certainty about the accuracy of your beliefs, manifesting as confidence intervals that are too narrow. Overprecision is the most consequential for professional judgment because it means people are surprised by outcomes far more often than their confidence warrants.

The mechanism is WYSIATI — What You See Is All There Is. System 1 constructs the best story it can from the information available and generates a sense of confidence based on the coherence of that story. But coherence and accuracy are different things. A simple story constructed from limited information can feel very coherent — and therefore very confident — precisely because it has not been complicated by the additional information that would reveal its inadequacy. The less you know, the easier it is to construct a coherent story. This is why overconfidence often increases with expertise up to a point: the expert knows enough to construct an elaborate, coherent narrative but not enough to see how many ways it could be wrong.

The domains where expert judgment is most reliable are those with high-validity environments and immediate feedback — chess, some sports, short-range weather forecasting. In low-validity environments — political forecasting, long-range economic prediction, clinical diagnosis of rare conditions — expert confidence is a particularly poor guide to accuracy.

## How to Apply
1. **Ask for confidence intervals.** When someone gives a point estimate, ask: "What is your 90% confidence interval?" Then check: is the true answer inside that interval roughly 90% of the time? In most domains, it is not.
2. **Test for WYSIATI.** "What information would you need to see to change your mind? What don't you know?"
3. **Use reference class data.** When someone is confident about a specific prediction, compare it with the base rate for that class of predictions. How often are similar predictions correct?
4. **Separate confidence from competence.** A person can be genuinely skilled and still systematically overconfident about the precision of their judgments.

## Examples
**Situation:** A consulting team has completed a rapid assessment and their lead analyst presents findings with high confidence: "I'm very sure that the programme's targeting mechanism is excluding the most vulnerable households."
**Application:** Kahneman would say: "The confidence is a red flag, not a reassurance. In a rapid assessment — limited data, short timeframe, complex targeting dynamics — high confidence typically reflects the coherence of the analyst's narrative rather than the quality of the evidence. WYSIATI is operating: the analyst has constructed a story from the available information that feels compelling and complete. But a rapid assessment, by definition, has not seen everything. Ask the analyst: how many households did you speak with? What is the statistical power of your sample? What are the three most plausible alternative explanations for what you found? If you assigned a probability to your conclusion — not 'very sure' but a number — what would it be? And then check: is that number consistent with how often rapid assessments of this type produce accurate targeting conclusions? The answer, I suspect, is that the base rate for accurate targeting conclusions from rapid assessments is lower than the analyst's expressed confidence implies."

## Anti-Patterns
**Don't:** Treat all confidence as overconfidence.
**Why:** In high-validity environments with extensive practice and immediate feedback, confident experts can be well-calibrated. The problem is that most professional judgment does not occur in such environments.

**Don't:** Equate overconfidence with incompetence.
**Why:** The most competent professionals are often overconfident — their skill at constructing coherent narratives from limited data produces subjective confidence that exceeds objective accuracy. Calibration is a separate skill from competence.
