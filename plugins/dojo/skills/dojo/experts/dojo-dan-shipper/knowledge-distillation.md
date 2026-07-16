---
topic: knowledge-distillation
expert: Dan Shipper
version: 1.0
---

## When to Use

Use this file when the user asks about:
- How to extract useful knowledge from a body of material
- Summarizing or synthesizing a large document, conversation, or corpus
- Using AI to make sense of accumulated notes, research, or transcripts
- How to get value from a large language model's ability to compress information
- The craft of distilling complex material into actionable insight

## Fails When

- The user needs to preserve all nuance from a complex technical source — distillation necessarily involves loss
- The user wants to understand a source deeply for themselves rather than extract key points

## Core Concept

Knowledge distillation in the Shipper sense is not summarization. Summarization compresses a text while preserving its structure and emphasis. Distillation extracts what matters for a specific purpose from a body of material, discarding everything else. The difference is whether you're serving the text or the reader's need.

The distinction matters because most knowledge work involves reading not for its own sake but in service of a decision, a project, or an understanding you're trying to build. When you read for a specific purpose, the measure of a good distillation is not fidelity to the source but fitness for the task.

AI changes the economics of distillation dramatically. A human can read and distill perhaps 50-100 pages per hour with reasonable quality. An AI can distill thousands of pages in minutes, and the quality for well-specified tasks is often surprisingly high. This opens up workflows that were previously impractical: distilling an entire book into the specific insights relevant to your current project, compressing years of customer support transcripts into themes, or synthesizing your own past notes into a briefing for a new decision.

The critical skill is not the distillation itself but the specification of what you're distilling for. An AI asked to "summarize this document" will produce a different (and usually worse) output than one asked to "extract the specific claims this author makes about how expert networks form in high-trust communities, and identify where their evidence is strongest and weakest." The specificity of the prompt determines the specificity and usefulness of the distillation.

There is a second-order use of distillation that Shipper practices: distillation as a way of developing your own thinking. If you force yourself to distill a body of material for a specific purpose, the act of specification — deciding what you're distilling for — forces you to clarify your own goals and what would actually be useful. This is a form of thinking by structuring the extraction task.

Finally, distillation from your own accumulated material — your past writing, notes, conversations, and ideas — is a particularly powerful use case. Most people accumulate far more than they can consciously hold. AI can serve as a retrieval and synthesis layer over that accumulated material, making old ideas available for present decisions in a way that wasn't feasible before.

## How to Apply

1. **Define the distillation target before starting.** What is this distillation for? What decision will it inform? What project does it serve? What gap in understanding are you trying to fill? The clearer this is, the better the distillation will be.

2. **Write the distillation prompt as a role + task specification.** Instead of "summarize this," try "you are an expert in [domain] reviewing this material for someone who needs to [specific task]. Extract only the claims relevant to [specific question], flag where evidence is strong vs. weak, and note anything the original author assumes but doesn't argue for."

3. **Ask for the structure you actually need.** If you need a decision briefing, say "give me a decision briefing with the key tradeoffs, not a summary." If you need reference material, say "give me a reference document organized by topic that I can look up from, not a narrative summary." Different tasks need different output structures.

4. **Build distillation workflows for recurring tasks.** If you regularly consume the same type of material (research papers, customer interviews, legal documents, earnings calls), build a standard prompt that distills each type for your specific recurring need. Reusing this prompt gives you a consistent format you can develop over time.

5. **Distill your own accumulated material.** Periodically, take your past notes, drafts, and writing and distill them for your current priorities. What have you already figured out that's relevant to what you're working on now? Your own past thinking is often the most underutilized knowledge source.

## Examples

**Example 1: The researcher distilling a literature**
A policy researcher needs to understand what the academic literature says about the effectiveness of conditional cash transfer programs in East Africa, specifically whether there are differences in outcomes by urban vs. rural context. Rather than reading 30 papers, she uses AI to distill each paper for that specific question: "Extract from this paper any claims about conditional cash transfer outcomes that distinguish urban from rural contexts. Note the study country, study period, and strength of evidence for each claim." She then distills the distillations: "Here are extracts from 30 papers on CCTs in East Africa. Synthesize the state of evidence on urban vs. rural outcome differences, flag where findings are contradictory, and note the major gaps."

**Example 2: The writer distilling a book for an essay**
A writer is developing an essay about how organizations handle uncertainty. He wants to draw on Karl Weick's work on sensemaking but doesn't have time to re-read the full books. He asks AI to distill Weick for his specific purpose: "You're helping me write an essay arguing that organizations fail to adapt because their sensemaking processes are optimized for confirming existing narratives rather than detecting anomalies. Extract from this material the specific Weick concepts and examples most relevant to this argument, organized by how directly they support vs. complicate my thesis."

## Anti-Patterns

**Asking for a summary when you need a distillation.** Summaries preserve the text's structure; distillations serve your purpose. If you ask for a summary, you'll get a miniaturized version of the original organized around the author's priorities, not yours. Always specify what you're distilling for.

**Distilling without reading anything directly.** AI distillation can miss nuance, introduce errors, and sometimes confidently misrepresent sources. If a source is important enough to inform a real decision, read at least the key sections yourself. Distillation is a complement to direct reading, especially for primary sources, not a replacement for it.

**Over-distilling.** Some material is valuable precisely because it's slow and requires engagement — a dense philosophical argument, a novel, a complex theoretical framework. Over-distilling can extract the bullet points while losing the insight. Ask whether the material is actually meant to be consumed efficiently, or whether the depth is the point.
