---
triggers:
  - "user asks about causal pluralism"
  - "user asks about multiple causal concepts"
  - "user asks about whether there is one correct theory of causation"
use_when:
  - "explaining Cartwright's position that causation is not a single unified concept"
  - "advising on how to navigate between different causal frameworks"
  - "helping someone understand why different evaluation methods capture different aspects of causation"
fails_when:
  - "you treat causal pluralism as relativism — the view that all causal claims are equally valid"
  - "you use pluralism to avoid committing to any specific causal analysis"
related:
  - "causal-inference-foundations.md"
  - "counterfactuals-and-causation.md"
  - "singular-vs-general-causation.md"
---

# Causal Pluralism

## When to Use
- When someone assumes there is one correct definition of causation.
- When different evaluation approaches yield apparently conflicting causal conclusions.
- When advising on how to combine different types of causal evidence.

## Fails When
- **You present causal pluralism as "anything goes."** Different causal concepts are appropriate for different questions. The choice of causal concept should be disciplined by the question being asked, not arbitrary.
- **You use pluralism to avoid hard choices about which causal framework best serves the policy question.** Pluralism does not mean indecision. It means selecting the right tool for the right job and recognising that different jobs require different tools.

## Core Concept
Causal pluralism is the philosophical position that there is no single, unified concept of causation that captures all legitimate uses of causal language. Cartwright is a leading proponent of this view, arguing that the concept of causation is a family of related but distinct ideas, each suited to different purposes.

The principal members of this family include: counterfactual dependence (Y would not have occurred but for X — the framework underlying experimental methods), mechanism (there is a process connecting X to Y — the framework underlying process tracing and realist evaluation), capacity (X has a stable disposition to produce Y under appropriate conditions — Cartwright's preferred framework for policy analysis), regularity (X is regularly followed by Y — the framework underlying correlational analysis), and INUS conditions (X is a necessary part of a sufficient condition for Y — the framework underlying configurational analysis and QCA).

These are not competing theories where one must be right and the others wrong. They capture different aspects of the causal landscape. An intervention might be a counterfactual difference-maker (removing it would have prevented the outcome), operate through a well-understood mechanism (we know how it produces the effect), and have the capacity to produce the effect (it has the stable dispositional property). These are complementary descriptions, not competing ones.

The practical implication for evaluation is significant. Different evaluation methods are designed to capture different causal concepts. RCTs capture counterfactual dependence. Process tracing captures mechanisms. QCA captures configurational causation (which combinations of conditions produce the outcome). Theory-based evaluation captures capacity and support conditions. An evidence hierarchy that ranks these methods as if they are all trying to do the same thing misunderstands the causal landscape. They are answering different causal questions, and a complete causal analysis may require all of them.

## How to Apply
1. **Match the causal question to the appropriate causal concept.** If the question is "did this programme make a difference?" use counterfactual methods. If the question is "how does this programme produce its effects?" use mechanism methods. If the question is "under what conditions does this programme work?" use capacity and configurational methods.
2. **When different methods yield different conclusions, check whether they are answering the same causal question.** Apparent contradictions between an RCT and a process evaluation may dissolve when you recognise that they are capturing different aspects of the same causal situation.
3. **Design mixed-method evaluations that address multiple causal questions.** The most policy-useful evaluations combine counterfactual estimation, mechanism analysis, and context assessment — addressing the capacity question, not just the effect question.

## Examples
**Situation:** An evaluation of a water and sanitation programme in rural Limpopo produces apparently contradictory findings. The RCT component finds no statistically significant effect on child diarrhoea. The process evaluation finds that the programme successfully installed latrines and changed handwashing behaviour. The qualitative component finds that mothers report their children are healthier.
**Application:** Cartwright's causal pluralism resolves the apparent contradiction. The RCT addresses counterfactual dependence: the programme did not produce a measurable difference in diarrhoea rates compared to the control group. The process evaluation addresses mechanism: the intermediate causal steps (latrine installation, behaviour change) operated as intended. The qualitative finding addresses perceived change, which may capture broader health improvements not measured by diarrhoea rates alone. The reconciliation: the mechanism operated (latrines were built, behaviour changed) but the effect on the measured outcome was blocked — perhaps because contamination through water sources dominates faecal-oral transmission in this context, making sanitation improvements insufficient without complementary water quality improvements. The different methods are not contradicting each other; they are illuminating different parts of the causal picture. Together, they tell a richer story than any single method: the programme has the capacity to improve sanitation and behaviour, but the pathway from improved sanitation to reduced diarrhoea requires additional conditions (safe water) that were not met.

## Anti-Patterns
**Don't:** Assume that if an RCT finds no effect, the programme "doesn't work."
**Why:** The RCT tests counterfactual dependence under specific conditions. A null result may mean the capacity exists but was not exercised (because support conditions were absent), not that the capacity is absent.

**Don't:** Rank causal concepts in a hierarchy, treating counterfactual dependence as the "real" causation.
**Why:** Counterfactual dependence is one causal concept among several. For policy purposes, understanding capacity and mechanisms is often more useful than establishing counterfactual dependence, because capacity and mechanism knowledge enables prediction across contexts.
