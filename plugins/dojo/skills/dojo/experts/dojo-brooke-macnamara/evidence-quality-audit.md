---
triggers:
  - "user asks how to assess whether a study is trustworthy"
  - "user asks about study design criteria for causal claims"
  - "user asks about what makes evidence strong or weak"
use_when:
  - "evaluating the quality of evidence behind a specific claim or intervention"
  - "teaching someone to read research critically"
  - "building a checklist for evidence quality assessment"
fails_when:
  - "you treat the checklist as binary (pass/fail) rather than as a gradient of confidence"
  - "you dismiss a finding because it fails one criterion while being strong on others"
  - "you apply the criteria mechanically without considering the research context"
related:
  - "causal-inference-standards.md"
  - "researcher-and-publication-bias.md"
  - "effect-size-literacy.md"
---

# Evidence Quality Audit

## When to Use
- When evaluating whether a specific study or body of evidence supports the claims being made about it.
- When teaching someone to read research critically rather than accepting claims at face value.
- When building quality assessment criteria for a systematic review or meta-analysis.

## Core Concept
This is Macnamara's core reusable tool — the set of criteria she applies to every body of evidence she evaluates. The criteria are not arbitrary; they reflect decades of methodological research on what distinguishes studies that produce reliable findings from those that produce inflated or spurious ones.

The first criterion is treatment isolation. Was the intervention the only difference between the treatment and control groups? If the treatment group also received more attention, more resources, or different expectations, the observed effect cannot be attributed to the specific intervention. The second criterion is preregistration. Were the hypotheses, primary outcomes, and analysis plan specified before data collection? Post-hoc outcome selection — choosing which outcomes to report after seeing the data — inflates positive findings. The third criterion is adequate power. Was the sample large enough to detect the expected effect reliably? Underpowered studies produce inflated estimates when they reach significance and miss real effects when they do not. The fourth criterion is objective or blinded outcomes. Were outcomes measured by people who did not know which condition participants were in? Self-report outcomes from unblinded participants systematically favour the treatment group. The fifth criterion is appropriate control. Waitlist controls inflate effects because they capture everything that comes with receiving any attention, not just the specific treatment. Active controls isolate the specific ingredient. The sixth criterion is conflict of interest disclosure. Did the authors have financial or institutional stakes in the outcome? If so, did they disclose them, and does the pattern of findings track the incentives?

The quality gradient is the diagnostic: when higher-quality studies show smaller effects, the true effect is probably at the lower end of the distribution. This pattern appeared in both the deliberate practice and growth mindset intervention literatures, and it is the single most important finding in Macnamara's meta-analytic work.

## How to Apply
1. **Apply the criteria systematically.** "For each study, code: randomisation (yes/no/unclear), preregistration (yes/no), blinding (objective outcomes/blinded assessor/unblinded self-report), control type (active/waitlist/no control), sample size, attrition rate, conflict of interest."
2. **Test the quality gradient.** "After coding, test whether effect size correlates with quality. If it does — larger effects in weaker studies — the honest estimate is closer to what the strong studies show."
3. **Report quality alongside findings.** "Never present an average effect size without reporting the quality distribution. An average of d = 0.30 across ten studies means different things if all ten are rigorous versus if the average is driven by five weak studies."
4. **Use as a diagnostic, not a gatekeeping tool.** "The criteria identify where confidence should be calibrated, not which studies should be excluded. A study that fails on blinding but succeeds on everything else provides moderate evidence. A study that fails on everything provides very weak evidence."

## Examples
**Situation:** A programme funder shows you a study claiming d = 0.55 for a youth development intervention and asks whether the evidence justifies scaling the programme nationally.
**Application:** Macnamara would say: "Let me audit the study before answering. Randomised? Yes — good, that addresses selection bias. Preregistered? No — which means we cannot verify that the reported outcomes were the planned outcomes. Sample size? N = 120, which gives about 60 per group — underpowered for detecting a true moderate effect, which means the d = 0.55 is likely inflated by sampling error. Control condition? Waitlist — so the 0.55 includes not just the programme effect but expectancy, attention, and Hawthorne effects. Outcomes? Self-reported life skills — unblinded participants reporting on themselves. Conflicts of interest? The study was conducted by the programme developer. Every one of these factors pushes the estimate upward. A more rigorous study — preregistered, active control, objective outcomes, independent evaluation — would likely show a substantially smaller effect. My recommendation: do not scale based on this single study. Commission an independent replication with an active control and objective outcomes. If the effect survives that test, even at a smaller size, you have something worth scaling."

## Anti-Patterns
**Don't:** Treat quality criteria as a binary pass/fail.
**Why:** No study is perfect. The question is whether the pattern of strengths and weaknesses systematically biases the estimate upward or downward. A study that randomises well but uses self-report outcomes provides partial evidence, not no evidence.

**Don't:** Apply the criteria selectively to findings you dislike.
**Why:** The criteria must be applied consistently across all studies — those that confirm your priors and those that contradict them. Selective application is the researcher bias that Macnamara herself documents.
