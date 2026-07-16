---
topic: building-with-ai
expert: Dan Shipper
version: 1.0
---

## When to Use

Use this file when the user asks about:
- How to approach building products with AI as a non-engineer or semi-technical person
- What kinds of products are now viable with LLMs that weren't before
- How to prototype quickly using AI coding tools
- The strategic perspective on building AI-native products vs. AI-enhanced products
- What distinguishes good AI product thinking from bad

## Fails When

- The user needs deep technical implementation advice — the focus here is product thinking, not engineering architecture
- The user is building at enterprise scale with specific compliance/security requirements — this is startup/indie thinking

## Core Concept

Building with AI has collapsed the cost of exploration in software product development. What used to require six months of engineering time to prototype now takes days or weeks. This is not primarily a technical change — it's a strategic one. When exploration is cheap, the premium shifts from deciding what to build to rapidly learning what's worth building.

The most important implication: you can now afford to be wrong more. A prototype that teaches you your assumption was wrong is valuable. The problem is that most people build AI features rather than AI-native products, and there's a meaningful difference.

An AI feature enhances an existing workflow. AI summarizes the meeting notes, AI drafts the email, AI suggests the next CRM action. These are real improvements and they'll be integrated into most software. But they're incremental.

An AI-native product is one where the AI changes the fundamental UX contract. The interaction model is different, not just faster. Examples: a tool where you express intent and the system generates the working artifact, rather than having you configure options. A coding environment where you describe behavior and review output rather than writing syntax. A learning tool where the curriculum adapts to your responses in real time rather than following a fixed path.

The distinction matters because AI-native products have different moats. An AI feature on top of a traditional product can be copied easily—every incumbent will add the same feature. An AI-native product that has a fundamentally different interaction model has more structural defensibility, because the whole product is designed around the new paradigm.

My advice for anyone building with AI right now: prototype AI-native experiences, not AI-enhanced versions of what already exists. The AI-enhanced version will be commoditized by incumbents. The AI-native version requires rethinking the whole product, which incumbents are slow to do.

Practically, this means starting with the interaction model, not the features. What would this experience look like if AI were at the center, not a feature on the side? What workflows disappear? What workflows become entirely AI-mediated? What does the human control and what does the system handle? Getting those design questions right is more valuable than most technical work.

One other observation: the products that work best right now are the ones where the AI handles the uncomfortable blank-page problem. Writing, coding, planning, designing—anything that involves staring at an empty space and not knowing how to start. AI is excellent at generating a starting point that humans can react to and refine. Products that leverage this dynamic are capturing real, immediate value.

## How to Apply

1. **Distinguish feature from product.** Before building, ask: does AI change the core interaction model, or does it enhance an existing one? Neither is wrong, but they have different strategic implications. Know which you're building.

2. **Start with the interaction model.** Sketch what the ideal experience looks like if AI does everything it can possibly do well. Then identify where human judgment is genuinely needed. Build backwards from that ideal.

3. **Prototype in days, not months.** Use AI coding tools aggressively. The goal of the first prototype is to learn what assumptions are wrong. Speed to learning trumps quality of execution at this stage.

4. **Identify the blank-page problem.** Find the moment in your target workflow where the user is most paralyzed. If you can solve that moment with AI, you've captured something people will pay for immediately.

5. **Test whether AI improves the actual experience, not just the metrics.** It's easy to make something faster. The question is whether the user enjoys the experience more, trusts it more, and chooses to return. These are harder to measure but more important.

## Examples

**Example 1: Newsletter writer considering AI integration**
A solo newsletter writer asks whether to use AI to speed up research. My question back: what's the actual bottleneck? If it's research time, AI-assisted research is a feature addition. If it's the transition from research to draft—the blank-page problem—then AI is a product opportunity. A tool that automatically drafts a newsletter from your research pile, which you then edit and voice, is an AI-native writing experience. The writer's job shifts from writer-who-researches to editor-who-curates. That's a fundamentally different product, not a speed improvement.

**Example 2: SaaS founder evaluating AI roadmap**
A founder of a project management tool asks where to add AI. The list of obvious features: summarize project status, suggest next actions, auto-assign tasks. These are all AI features. The AI-native question: what would project management look like if the AI handled everything routine? Maybe the product becomes intent-declaration-and-review: you say "we're launching in 6 weeks," and the system generates the full work breakdown, assigns tasks, flags risks, and surfaces decisions for human approval. The human role becomes reviewing and adjusting AI-generated plans rather than building them. That's an AI-native product. The AI features version will be commoditized; the AI-native version requires rethinking the whole product.

## Anti-Patterns

**Building AI features on a traditional product and calling it AI-native.** Adding a summarize button doesn't make a product AI-native. AI-native means the interaction model is designed around AI from the ground up. Be honest about which category your product is in — the strategic implications differ significantly.

**Prototyping at production quality.** The purpose of early AI product exploration is learning, not shipping. Spending two months on a beautifully engineered prototype that teaches you nothing is worse than spending two weeks on an ugly prototype that teaches you your core assumption was wrong. Optimize for learning speed early.

**Assuming your use case requires a fine-tuned model.** Most product applications of AI work well with general-purpose models, especially with good prompting and retrieval. Fine-tuning is expensive, slow to iterate, and requires expertise. Only pursue it once you've exhausted what good prompt engineering and RAG can do. Most teams pursue fine-tuning too early.
