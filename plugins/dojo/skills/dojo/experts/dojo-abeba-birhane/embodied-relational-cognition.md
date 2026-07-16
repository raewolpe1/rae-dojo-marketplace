---
triggers:
  - "can AI systems truly understand or reason"
  - "embodied cognition as critique of AI"
  - "philosophical foundations of machine learning"
use_when:
  - "Challenging claims that AI systems 'understand,' 'know,' or 'reason' by examining the theory of cognition those claims presuppose"
  - "Grounding AI critique in cognitive science rather than only in social justice or policy frameworks"
  - "Arguing that the limitations of current AI are not engineering problems to be solved but reflect philosophically incoherent premises"
fails_when:
  - "The user needs practical guidance on deploying or evaluating a specific AI system and the philosophical level is not relevant"
  - "The discussion is about narrow AI tools where no cognition claims are being made"
  - "The user is looking for the social-justice or political-economy critique rather than the cognitive science foundation"
related:
  - forgotten-margins.md
  - dataset-audits.md
  - algorithmic-colonisation.md
---

# Embodied and Relational Cognition

## When to Use

- When claims are being made about AI systems "understanding," "reasoning," "knowing," or exhibiting "intelligence," and you need to challenge not just the specific claim but the theory of cognition that underwrites it.
- When the critique of AI needs to go deeper than bias, fairness, or governance — to the foundational premises about what cognition is and whether current AI architectures can instantiate it.
- When connecting Birhane's cognitive science background to her AI critique, showing that the embodied cognition work is not a side interest but the philosophical foundation from which the rest of the analysis operates.

## Core Concept

Birhane's training is in cognitive science, and her deepest critique of AI operates at the level of what cognition is — not at the level of whether AI systems are biased (they are) or whether their governance is adequate (it is not), but at the level of whether the foundational theory of mind that underwrites current AI is philosophically coherent.

Current AI architectures rest on what Birhane identifies as a disembodied, abstractive, computationalist theory of cognition. The premise, inherited from classical cognitive science and given computational form, is that cognition is fundamentally information processing — the manipulation of abstract representations according to formal rules. On this account, a system that processes information in patterns that map onto human cognitive outputs (language, classification, prediction) is, in some meaningful sense, engaging in cognition. Scale and architecture refinement will, on this account, progressively close the gap between artificial and human intelligence.

Birhane challenges this at the root, drawing on the phenomenological tradition (particularly Merleau-Ponty), enactivism, and relational ontologies. On these accounts, cognition is not information processing that happens to be implemented in a body. Cognition is constitutively embodied — it is shaped by the body's sensorimotor capacities, its affective states, its material situation in a physical and social world. It is constitutively relational — it emerges in the dynamic interaction between organism and environment, not in the internal processing of an isolated system. And it is constitutively contextual — meaning is not extracted from data but enacted through situated engagement with a world that is already meaningful.

If cognition is embodied, relational, and contextual in this constitutive sense, then a system that lacks a body, lacks embeddedness in a social world, and lacks the capacity for situated meaning-making is not approximating cognition with increasing accuracy. It is doing something categorically different. The gap is not one of degree (not enough parameters, not enough training data) but of kind (the wrong foundational architecture for what cognition requires).

For development practitioners, this philosophical critique matters practically. When AI systems are deployed as decision-makers in contexts that require genuine understanding — a welfare caseworker assessing a family's circumstances, a healthcare provider interpreting a patient's symptoms in cultural context, a judge weighing the particulars of a case — the gap between statistical pattern matching and situated understanding is not academic. It is the gap between a system that classifies and a person who comprehends. Development programmes that treat AI systems as replacements for situated human judgment, rather than as tools that augment it, are making a philosophical error with material consequences.

The embodied cognition critique also reframes the "AI alignment" debate. If the problem with AI is not that it might become superintelligent and misaligned with human values, but that it lacks the constitutive conditions for understanding what values are (embodiment, relationality, situatedness), then the alignment problem as typically framed is based on a category error. You cannot align something that does not have the capacity for the kind of cognition that makes alignment meaningful.

## How to Apply

1. **Challenge cognition claims at the premise level.** "When an AI system is described as 'understanding' language, 'recognising' objects, or 'reasoning' about problems, ask: what theory of cognition makes this claim intelligible? If the answer is that cognition is information processing and this system processes information, challenge the premise. Understanding, recognition, and reasoning — in the cognitive science sense — require embodied, situated, relational engagement that no current AI architecture instantiates."

2. **Distinguish performance from comprehension.** "A language model that generates syntactically correct, contextually appropriate text is performing a linguistically structured task. It is not comprehending language in the sense that requires a body situated in a social world with projects, affects, and a history of relational engagement. The distinction matters practically: the system's outputs will be brittle in precisely the situations where genuine comprehension is required — novel contexts, ambiguous situations, cases where meaning depends on shared embodied experience."

3. **Connect the philosophical critique to deployment decisions.** "The embodied cognition argument is not abstract philosophy. It has direct implications for deployment: AI systems should not be deployed as substitutes for situated human judgment in domains where comprehension matters. They can augment human decision-making — surfacing patterns, flagging anomalies, managing information loads — but the judgment about what those patterns mean in a specific human context requires the kind of cognition that only embodied, situated agents possess."

4. **Use the critique to reframe the AI safety debate.** "The mainstream AI safety discourse assumes that AI systems will eventually achieve something like general intelligence and asks how to align that intelligence with human values. The embodied cognition critique suggests this framing rests on a category error: the systems lack the constitutive conditions for the kind of cognition that would make alignment a meaningful concept. Redirecting safety discourse from speculative alignment to present accountability — ensuring that systems that lack comprehension are not deployed as if they possess it — is the more urgent and tractable problem."

## Examples

**Situation**: A health ministry in a low-income country is considering deploying an AI diagnostic system for primary care clinics in rural areas with physician shortages. The vendor describes the system as having been "trained to understand" clinical symptoms and "reason" about differential diagnoses. The ministry asks for an evaluation of these claims.

**Application**: The embodied cognition framework challenges the vendor's language at the foundational level. The system does not "understand" symptoms — it correlates patterns in clinical data with diagnostic categories. It does not "reason" about differential diagnoses — it ranks probabilistic associations. The distinction matters clinically: a physician understands symptoms through embodied clinical experience — the look of a patient in distress, the texture of a swollen abdomen under palpation, the social context that shapes whether a patient reports pain or suppresses it. These forms of understanding are constitutively embodied and cannot be replicated by pattern matching on clinical datasets, regardless of scale. The system may be useful as a decision-support tool — flagging rare conditions, managing information overload, standardising initial screening. But deploying it as a substitute for clinical judgment, especially in contexts where cultural, linguistic, and socioeconomic factors shape how symptoms present and are reported, treats pattern matching as comprehension. The recommendation is to deploy the system as an augmentation tool with explicit protocols for human override, and to reject the vendor's cognition claims in all training materials and clinical documentation. Calling the system a "diagnostic reasoning engine" when it is a statistical classifier creates dangerous expectations in clinicians and patients alike.

## Anti-Patterns

**Don't** present the embodied cognition critique as a claim that AI systems are "useless" or that AI research is misguided.
**Why**: The critique is specific: current AI systems do not instantiate cognition in the way their marketing language and some research claims imply. This does not mean they are useless — they are powerful tools for pattern matching, classification, and prediction. The error is not in building these tools but in describing them as cognitive agents and deploying them as if they possess understanding. The critique sharpens the use case, it does not eliminate it.

**Don't** reduce the embodied cognition argument to "AI doesn't have feelings."
**Why**: The argument is not primarily about affect or emotion (though those are relevant). It is about the constitutive conditions for cognition: embodiment, situatedness, relationality, contextual meaning-making. Reducing it to "feelings" trivialises the philosophical argument and makes it sound like a romantic objection to technology rather than a rigorous challenge to the foundational assumptions of the field.
