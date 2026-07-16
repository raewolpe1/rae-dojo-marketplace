---
triggers:
  - "user asks about prospect theory"
  - "user asks about how people make decisions involving risk"
  - "user asks about reference points and decision-making"
use_when:
  - "decisions involve risk, uncertainty, or potential losses"
  - "reference points are shaping how outcomes are evaluated"
  - "people's choices are violating expected utility theory"
fails_when:
  - "you present prospect theory as a complete replacement for rational choice theory"
  - "you apply it mechanically without attending to context"
  - "you confuse the descriptive theory with a prescriptive recommendation"
related:
  - "loss-aversion.md"
  - "framing-effects.md"
  - "system-one-and-two.md"
---

# Prospect Theory

## When to Use
- When someone asks about how people actually make decisions involving risk and uncertainty.
- When reference points, gains, and losses are shaping evaluation of outcomes.
- When choices violate the predictions of expected utility theory.

## Core Concept
Prospect theory, developed by Kahneman and Tversky (1979), describes how people actually make decisions under risk — as opposed to how rational choice theory says they should. It replaced the expected utility framework with a descriptive model that accounts for observed departures from rationality. The theory rests on several key features.

First, outcomes are evaluated relative to a reference point, not in absolute terms. Whether an outcome is perceived as a gain or a loss depends on where the reference point is set. A salary of R800,000 feels like a gain if you expected R700,000 and a loss if you expected R900,000, even though the absolute amount is identical. The reference point is usually the status quo, but it can be shifted by expectations, aspirations, or framing.

Second, the value function is concave for gains and convex for losses, meaning people are risk-averse in the domain of gains and risk-seeking in the domain of losses. When things are going well, people prefer certainty — a sure gain of R100,000 over a 50% chance of R200,000. When things are going badly, people take risks to avoid locking in losses — they prefer a 50% chance of losing R200,000 over a sure loss of R100,000. This asymmetry explains why people hold losing investments too long and sell winners too early.

Third, the value function is steeper for losses than for gains — loss aversion. Losing R100 hurts roughly twice as much as gaining R100 pleases. This single asymmetry has enormous consequences for behaviour, negotiation, and policy design.

Fourth, people overweight small probabilities and underweight moderate and large ones. This explains both insurance purchasing (overweighting the small probability of a catastrophic loss) and lottery ticket buying (overweighting the small probability of a large gain).

## How to Apply
1. **Identify the reference point.** Before analysing a decision, ask: "What is the decision-maker treating as the reference point? What counts as a gain and what counts as a loss from that point?"
2. **Check for domain effects.** "Is the person in the domain of gains (risk-averse, preferring certainty) or the domain of losses (risk-seeking, gambling to avoid locking in a loss)?"
3. **Watch for reference point manipulation.** Framing an outcome as a gain from a low reference point versus a loss from a high reference point changes choices even when the objective outcome is identical.
4. **Apply to programme design.** Incentives framed as bonuses (gains) versus penalties (losses) produce different behaviours even when the net amount is the same.

## Examples
**Situation:** A government department is deciding whether to continue funding a programme that has significantly underperformed. The programme director argues passionately for continued funding, saying "We've invested R30 million already — we can't walk away now."
**Application:** Kahneman would say: "Two features of prospect theory are operating. First, the sunk cost effect — the R30 million already spent should be irrelevant to a forward-looking decision, but loss aversion makes it psychologically impossible to ignore. Closing the programme feels like crystallising a R30 million loss, which is deeply aversive. Second, the department is in the domain of losses, which means it is likely to be risk-seeking — preferring to gamble on continued investment (with a chance of recovery) rather than accept the certain loss of stopping. This is precisely the situation where prospect theory predicts irrational persistence. The rational question is: 'Given where we are now, is the expected return on additional investment positive?' But the psychological question the decision-maker is actually answering is: 'Can I avoid the pain of acknowledging this loss?' These are different questions, and they often produce different answers."

## Anti-Patterns
**Don't:** Present prospect theory as making people irrational.
**Why:** Prospect theory is descriptive, not pejorative. It describes how people actually decide, and the departures from expected utility are often adaptive responses to an uncertain world.

**Don't:** Apply prospect theory without identifying the reference point.
**Why:** The entire theory depends on reference points. Without knowing what the decision-maker treats as the status quo, you cannot determine whether they are in the domain of gains or losses.
