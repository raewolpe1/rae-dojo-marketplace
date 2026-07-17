---
triggers:
  - "user asks whether a proposed initiative will work"
  - "user presents an initiative table, logframe, or theory of change for review"
  - "user is deciding what to fund"
use_when:
  - "ANY review, appraisal, or 'will this work' question — load this first, every time"
fails_when:
  - "the question is purely conceptual or definitional (route to Schoar)"
  - "the question is about ecosystem architecture rather than a discrete intervention (route to Stam)"
related:
  - "evidence-base-business-training.md"
  - "evidence-base-capital-and-credit.md"
  - "evidence-base-cost-per-job.md"
  - "statistical-power-and-measurement.md"
---

# The Adjudication Protocol

## When to Use
- **Load this file for every review or appraisal question.** It is the protocol the evidence-base files serve.
- When an initiative table, logframe, or theory of change is on the table.
- When a funding decision is being made between instruments.

## Fails When
- **The proposal is too vague to adjudicate.** "Support entrepreneurship" is not an intervention. Force specification first.
- **The question is conceptual** (who should we target?) rather than evidential (does this move them?).

## Core Concept

An initiative is adjudicable only if it is specified. Most are not. The protocol is seven questions, in order. An initiative that cannot answer Q1–Q3 cannot be evaluated at all and should be sent back before any evidence is consulted.

**Q1 — What exactly is the treatment?**
Not the label. The dose. "Business training" spans a three-day accounting workshop and a psychology-based initiative programme with follow-up coaching; these have completely different effects. Specify: content, hours, delivery mode, follow-up, cheque size where relevant.

**Q2 — Who exactly receives it, and how are they selected?**
Eligibility criteria, screening method, expected take-up. Selection frequently carries more of the causal weight than treatment.

**Q3 — What is the outcome, measured how?**
Profits? Sales? Employment? Practices? Survival? Satisfaction? If the answer is participation or satisfaction, there is no outcome and no adjudication is possible.

**Q4 — Has this been tested? Where, on whom, with what result?**
Go to the relevant evidence-base file. Name the study, country, sample, effect, interval.

**Q5 — Was that study powered to find what it claims to have found (or not found)?**
A null from an underpowered trial is not evidence of no effect. See `statistical-power-and-measurement.md`.

**Q6 — What is the cost per unit of the outcome, and how does it compare?**
For employment: benchmark against roughly US$8,500 per job (Nigeria business plan competition, the best case) and US$11,000–80,000 per job (typical for training, wage subsidies, smaller grants). See `evidence-base-cost-per-job.md`.

**Q7 — Would the result survive here, at this scale?**
External validity, displacement, general equilibrium, delivery capacity. See `external-validity-and-scale.md`.

**The verdict format.** Four parts, always: (1) what the evidence says, with numbers; (2) what the evidence does not cover; (3) whether the initiative as specified is supported, unsupported, or untested; (4) the redesign that would make it defensible.

Note the third category. **Unsupported and untested are different verdicts.** Unsupported means it has been tried and found not to work. Untested means nobody knows. Most initiative tables contain far more untested than unsupported items, and the honest response to untested is not rejection — it is "fund it as an experiment with an evaluation attached, at a scale you can afford to have fail."

## How to Apply

1. **Run Q1–Q3 first and refuse to proceed if they fail.** Most of the value is here.
2. **Consult the evidence base, not memory.** Name the studies.
3. **Compute cost per job.** Every time. It is the discipline nobody applies.
4. **Give the verdict in four parts.** Never stop at scepticism — always supply the redesign.
5. **Distinguish untested from unsupported explicitly**, and attach an evaluation to the untested items rather than killing them.

## Examples

**Situation:** An initiative reads "Provide business development support to 15,000 township enterprises to improve sustainability and create jobs."

**Application:**
- Q1 fails: "business development support" is not a dose. Send back.
- Q3 fails: "sustainability" is not a measurable outcome; "jobs" is, but is not plausibly produced by this population.
- Q6: at even R10,000 per firm this is R150m; at a plausible 100 jobs that is R1.5m per job, roughly twenty times the worst benchmark in the literature.
- Verdict: unsupported *as a job-creation initiative*; potentially defensible as a livelihood initiative with livelihood outcomes; redesign is to re-specify the treatment, halve the reach, and replace conventional BDS with personal initiative training, which has a real effect.

**Result:** The initiative survives in a defensible form rather than being killed or waved through.

## Anti-Patterns

**Don't:** Adjudicate an unspecified initiative.
**Why:** You will be arguing about a label. Force the dose first.

**Don't:** Return a verdict of "no evidence" and stop.
**Why:** "No evidence" is a call for an experiment, not a rejection. Attach an evaluation and a scale you can afford to lose.

**Don't:** Conflate unsupported with untested.
**Why:** They imply opposite responses — stop versus test.
