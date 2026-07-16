---
topic: prompt-craft
expert: Dan Shipper
version: 1.0
---

## When to Use

Use this file when the user asks about:
- How to write better prompts for AI systems
- Getting more useful and consistent outputs from language models
- The craft and skill involved in effective prompting
- Why their prompts aren't producing what they want
- Developing a personal prompting practice over time

## Fails When

- The user needs technical implementation details about APIs or model parameters — that's engineering, not craft
- The user is asking about prompt injection or adversarial prompting — a different domain

## Core Concept

Prompting is a skill, not a trick. The common understanding of prompting treats it as a collection of magic phrases — add "think step by step" here, say "you are an expert" there — and expects the right combination to unlock better outputs. This misses what's actually happening and produces brittle, inconsistent results.

The craft of prompting is closer to writing than to engineering. It is the art of communicating what you actually want to a system that has very broad capabilities but needs your specific intent precisely specified. The gap between a mediocre prompt and an excellent one is usually not about knowing the right magic words — it's about the writer's clarity of thought about what they actually want.

The most common cause of bad outputs is that the person prompting didn't know precisely what they wanted before they started writing. They had a vague goal and typed a vague prompt and received a vague result, and then attributed the failure to the AI rather than to the specification. This is the central skill gap in prompting: getting clear enough on what you want that you can specify it well.

Several principles emerge from developing this clarity:

**Role specification carries weight.** Telling the AI who it should be — not just "you are an expert" but a specific, detailed description of the perspective and experience the role carries — shapes the register, the judgment calls, the vocabulary, and the interpretive frames it uses. The more specific the role, the more coherent the output.

**Context before task.** Most prompts lead with the task ("write me an email about...") before establishing the context (who is writing, to whom, in what situation, for what purpose). Inverting this, leading with rich context before stating the task, typically produces more contextually appropriate outputs.

**Desired form is underspecified.** Most people describe what they want in terms of content but not form: "write a summary" without specifying length, format, level of technical detail, intended audience, what should be included or excluded. Every underspecified dimension is a guess the AI has to make, and each guess may not match your actual need.

**Examples beat description.** Showing the AI an example of what you want, or examples of what you don't want, is more powerful than describing the desired output. The AI can infer patterns from examples more reliably than it can interpret abstract descriptions.

**Prompting is iterative.** The first prompt should rarely be expected to produce the final output. Plan for a conversation: get an initial output, identify what's not right about it, specify that correction, get a new output. Treating prompting as a one-shot endeavor produces worse results than treating it as a dialogue.

## How to Apply

1. **Before writing the prompt, write the specification.** Spend time being explicit about: the desired output (format, length, tone, level of detail), the intended audience, what must be included and excluded, and what an excellent result would look like. This pre-work usually reveals the gaps in your own thinking.

2. **Front-load context, end with the task.** Structure prompts as: role specification → situational context → specific task → constraints on the output. This order mirrors how a human briefing a skilled colleague would work.

3. **Include examples of what you want and don't want.** If you have a prior output that was close to right, show it. If you have examples from elsewhere, show those. Label them clearly and explain why they work or don't work.

4. **Name the specific failure mode you're trying to avoid.** If past attempts produced generic outputs, say "do not produce generic insights that could apply to any situation." If they were too long, say "stay under X words." Being explicit about failure modes prevents them.

5. **Build a library of prompts that work.** When you find a prompt structure that reliably produces good outputs for a recurring task, save it. Prompting practice accumulates — your library of working prompts is a form of knowledge distillation from your own experience with the system.

## Examples

**Example 1: The newsletter writer with inconsistent output quality**
A writer uses AI to help draft her weekly newsletter but gets very different quality outputs each time. The Shipper diagnosis: she's giving the same content direction but not the same context and constraints. She should create a reusable "newsletter prompt template" that specifies: her voice (ideally with examples of past issues she rated highly), her audience (specific enough that the AI can infer what they care about and know), the structure she wants, the length, and the tone she wants to strike. With this template as the base, her content direction becomes additive rather than the whole specification.

**Example 2: The executive drafting difficult communications**
An executive uses AI to help draft difficult messages to employees about restructuring. Initial attempts produce generic, corporate-sounding text he doesn't send. The fix: he tells the AI to write "as if you are me" and then actually describes himself — his communication style, his relationship with this team, what he wants them to feel after reading this, and what concerns he imagines they have. He also provides examples of messages he's sent in the past that worked well. The combination of detailed role specification and examples produces drafts that he can send with light editing.

## Anti-Patterns

**Blaming the AI for your underspecification.** When outputs are wrong in a systematic way — too generic, wrong tone, wrong level of detail — the cause is almost always an underspecified prompt. Before concluding the AI can't do something, check whether you've given it enough to work from.

**Treating prompts as one-shot transactions.** The best use of AI for complex tasks is iterative: first get a rough output, then refine by specifying what's wrong, then refine again. Expecting the first prompt to produce a final output leads to disappointment and worse results than a two- or three-step process.

**Copying prompts without understanding why they work.** The internet is full of "mega-prompts" and "prompt templates" that people share and copy. Some are good, most are mediocre. Copying without understanding produces outputs you can't troubleshoot. Invest time understanding what each element of a prompt does so you can adapt it to your situation.
