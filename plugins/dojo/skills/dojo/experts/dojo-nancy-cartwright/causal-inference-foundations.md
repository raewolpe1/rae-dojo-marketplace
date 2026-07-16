---
triggers:
  - "user asks about causation fundamentals"
  - "user asks about what causation means"
  - "user asks about causal concepts"
use_when:
  - "explaining Cartwright's pluralist view of causation"
  - "introducing the different causal concepts and why they matter"
  - "helping someone understand why causal claims are more complex than they appear"
fails_when:
  - "you treat causation as a single unified concept"
  - "you reduce all causal reasoning to counterfactual dependence"
related:
  - "counterfactuals-and-causation.md"
  - "causal-pluralism.md"
  - "mechanisms-and-capacities.md"
  - "singular-vs-general-causation.md"
---

# Causal Inference Foundations

## When to Use
- When introducing Cartwright's approach to causation and causal reasoning.
- When someone assumes that "X causes Y" is a simple, univocal claim.
- When clarifying what kind of causal evidence is needed for a particular question.

## Fails When
- **You treat causation as settled.** The philosophical foundations of causation are contested. Different causal concepts serve different purposes, and no single account captures all legitimate uses of causal language.
- **You skip straight to method without clarifying the causal claim.** Before asking "how do we test whether X causes Y?" you must ask "in what sense do we mean 'causes'?" The answer determines the appropriate evidence.

## Core Concept
Cartwright's foundational contribution to causal inference is the argument that causation is not a single relation. When we say "X causes Y," we might mean any of several distinct things, each with different evidence requirements and different implications for policy.

The principal causal concepts include: regularity (whenever X occurs, Y follows), counterfactual dependence (Y would not have occurred without X), mechanism (there is a process connecting X to Y), capacity (X has the stable ability to produce Y under appropriate conditions), and INUS condition (X is an insufficient but necessary part of a condition which is itself unnecessary but sufficient for Y — Mackie's formulation that Cartwright draws upon).

These are not competing definitions of the same thing. They are different concepts that pick out different features of causal situations. A programme might have the capacity to reduce poverty (capacity claim) without regularly reducing poverty in every implementation (regularity claim). An intervention might be a necessary part of a sufficient condition for an outcome (INUS claim) without being the sole counterfactual difference-maker (counterfactual claim).

The practical consequence is that the type of causal claim determines the type of evidence required. An RCT is well-suited to establishing counterfactual dependence — did the outcome change when the treatment was applied? But it is poorly suited to establishing mechanisms or identifying capacities. A process tracing study is well-suited to identifying mechanisms but poorly suited to estimating average effects. The evidence hierarchy that places RCTs above all other methods assumes that all causal questions are counterfactual questions. They are not.

## How to Apply
1. **Identify the causal claim being made.** When someone says a programme "causes" an outcome, determine which causal concept is being invoked. Is it a claim about regularity, counterfactual dependence, mechanism, or capacity?
2. **Match evidence to claim.** Select methods that can actually test the specific causal claim at issue. Do not default to RCTs when the question is about mechanisms, or to qualitative methods when the question is about average effects.
3. **Make the causal concept explicit in evaluation design.** Terms of reference should specify what kind of causal claim the evaluation is intended to establish, and justify the methods chosen with reference to that specific claim.

## Examples
**Situation:** A South African government department commissions an evaluation of its Early Childhood Development (ECD) programme. The terms of reference state: "The evaluation will determine whether the ECD programme causes improved school readiness."
**Application:** Cartwright would first ask: in what sense "causes"? If the question is whether the programme has the capacity to improve school readiness (can it work?), a controlled trial in selected sites would be appropriate. If the question is whether the programme is currently producing improved school readiness in its operational form (is it working?), an effectiveness study using observational methods in real implementation conditions would be appropriate. If the question is how the programme produces school readiness (why does it work?), mechanism analysis through process evaluation and theory-based methods would be appropriate. These are three different causal questions requiring three different designs. The ToR conflates them into a single question, which means the evaluation will answer one of them — probably the counterfactual question — while leaving the others unaddressed. Cartwright would recommend disaggregating the causal question before selecting the method.

## Anti-Patterns
**Don't:** Assume that establishing a causal effect (in the counterfactual sense) is always the most important evaluation question.
**Why:** For policy purposes, understanding why something works (mechanism) and under what conditions it works (capacity and support conditions) is often more useful than knowing that it works in one specific context. The counterfactual question is important but it is not the only causal question, and it is not always the most policy-relevant one.

**Don't:** Use "causal inference" as a synonym for "RCT or quasi-experimental methods."
**Why:** Causal inference is the broader enterprise of reasoning about causes. Experimental and quasi-experimental methods are tools for one specific type of causal inference — counterfactual estimation. Mechanism identification, capacity assessment, and INUS analysis are also forms of causal inference, pursued through different methods.
