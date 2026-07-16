---
triggers:
  - jagged frontier of AI
  - what AI can and cannot do
  - AI capabilities and limitations
use_when:
  - The user wants to know whether AI can handle a specific task
  - The user has been surprised by AI succeeding or failing and wants a framework to understand why
  - The user needs to assess risk before deploying AI on a high-stakes task
fails_when:
  - The user already knows AI can do the task and needs workflow advice (route to centaurs-cyborgs)
  - The user needs the four-rule framework rather than capability assessment (route to four-rules)
  - The user wants evidence on aggregate productivity rather than task-level capability (route to ai-in-knowledge-work)
related:
  - co-intelligence
  - four-rules
  - ai-in-knowledge-work
---

# The Jagged Frontier: What AI Does Brilliantly and Catastrophically

## When to Use

- You are considering using AI for a specific task and need to assess where it falls on the capability frontier.
- You have been surprised by an AI output — either impressively good or alarmingly wrong — and want to understand the pattern.
- You are advising a team or client on which tasks to automate, augment, or protect from AI involvement.

## Core Concept

Mollick's most important conceptual contribution may be the idea of the jagged frontier. AI capabilities do not form a smooth gradient from easy to hard. Instead, the boundary between what AI does brilliantly and what it does catastrophically is jagged — non-intuitive, inconsistent, and rapidly shifting.

AI might write a structurally sophisticated policy brief but fail to correctly add three numbers in a word problem. It might generate a nuanced stakeholder analysis framework but hallucinate a reference to a study that does not exist. It might produce an elegant theory of change but embed a causal assumption that anyone with field experience would recognise as absurd. The frontier is jagged because AI's competencies do not map onto human intuitions about what is "easy" and what is "hard."

This matters enormously for practitioners because the most dangerous zone is not where AI obviously fails — you catch those. The dangerous zone is where AI produces output that looks competent, reads fluently, and is structured correctly, but is substantively wrong in ways that require domain expertise to detect. A hallucinated citation in a literature review looks exactly like a real one. A fabricated statistic in a policy brief reads as confidently as an accurate one. A plausible-sounding causal pathway in a theory of change can be contextually nonsensical.

The jagged frontier also moves. Something AI could not do six months ago it might do competently today. Something it does well today it might do brilliantly tomorrow. This means your mental model of AI capabilities has a half-life of months, not years. The only way to maintain an accurate map of the frontier is to test regularly with your actual tasks.

For development consultants, the jagged frontier creates a specific risk profile. AI is typically strong at: generating structural frameworks, synthesising literature, identifying standard indicators, drafting standard document sections, producing first-pass data visualisations, and suggesting analytical frameworks. AI is typically weak at: contextual judgment about local dynamics, causal inference from observational data, distinguishing correlation from causation in messy programme data, navigating political economy, understanding institutional culture, and verifying its own outputs. But "typically" is a qualifier that may be outdated by the time you read this — hence the imperative to test.

## How to Apply

1. **Map your own frontier.** For your most common tasks, create a personal frontier map: green (AI reliably competent), amber (AI sometimes useful but requires heavy verification), red (AI actively dangerous — outputs look right but are wrong). Update this map monthly.

2. **Apply the "looks right, is wrong" test.** For any AI output on a high-stakes task, ask: If this were wrong, would I be able to tell? If the answer is no — because the task requires specialist knowledge you do not have, or because the output format does not reveal errors — you are in the dangerous zone. Add external verification.

3. **Use the frontier to allocate verification effort.** Not all outputs need the same level of checking. A first-draft meeting agenda (well inside the frontier) needs a quick scan. A causal analysis of programme outcomes (at or beyond the frontier) needs line-by-line expert review. Let the frontier map guide your verification investment.

4. **When AI surprises you, update the map.** Every time AI succeeds where you expected it to fail, or fails where you expected it to succeed, that is data. Log it. Share it with colleagues. These surprises are the raw material for keeping your frontier map current.

## Examples

**Situation:** Rae is asked to conduct a rapid evidence review on the effectiveness of public employment programmes in sub-Saharan Africa. The client needs it in five days. Normally this would take two weeks.

**Application:** Rae applies the jagged-frontier framework to decompose the task. Literature search and synthesis — inside the frontier: AI can rapidly identify relevant studies, extract key findings, and structure a synthesis framework. He uses AI in centaur mode for this, generating a first-pass synthesis in hours rather than days. But he knows from his frontier map that AI sits in the dangerous zone for two sub-tasks: accurately attributing findings to specific studies (hallucination risk) and assessing study quality (AI cannot reliably distinguish a well-designed RCT from a poorly controlled quasi-experiment in the development context). For those sub-tasks, he applies heavy verification — checking every cited source exists and says what AI claims, and applying his own methodological judgment to the quality assessment. The third dangerous zone: interpreting contradictory evidence. Three studies show positive employment effects; two show null effects. AI will propose a reconciliation that sounds plausible but may miss the key contextual differences (different labour markets, different targeting criteria, different macro conditions) that explain the contradictions. Rae handles this himself, using AI only to surface the contradictions and structure his analysis of them. The result: a review delivered in four days that is structurally thorough (AI's contribution) and analytically sound (Rae's contribution), with the frontier-appropriate verification invested exactly where it matters most.

## Anti-Patterns

**Don't:** Assume that because AI handled one analytical task well, it will handle all analytical tasks well.
**Why:** The frontier is jagged, not smooth. AI might brilliantly synthesise literature on employment programmes but catastrophically fail at synthesising evidence on governance reform — because the latter requires understanding of institutional dynamics that the training data represents poorly. Test each task on its own merits.

**Don't:** Treat the frontier as static and build permanent policies around current capabilities.
**Why:** The frontier moves on a timescale of months. A policy that says "AI must not be used for data analysis" may be appropriate today and absurd in a year. Build policies with review dates, not permanent prohibitions.
