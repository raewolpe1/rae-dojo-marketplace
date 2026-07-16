---
id: digital-literacy
title: "Digital Literacy: Evaluating Tools, Understanding Privacy, and Managing Dependencies"
tags: [digital-literacy, privacy, critical-thinking, tools, dependencies]
---

## When to Use

Use this topic when someone wants to think more critically about the tools they use, is concerned about privacy and data practices, wants to evaluate whether a tool is worth adopting or continuing to use, is worried about becoming too dependent on specific tools or platforms, or wants to understand the business model behind free tools they rely on. Also use when someone is building digital literacy skills for themselves or teaching these skills to others.

## Fails When

Digital literacy advice fails when it becomes paralyzing — when the answer to every tool evaluation question is "be cautious" without helping someone actually make a decision. It also fails when it assumes that privacy and productivity are always in tension (they're not — many privacy-respecting tools are excellent), or when it treats all risks as equal when they vary enormously by context, threat model, and user. A journalist covering government corruption has different privacy needs than a community newsletter writer.

## Core Concept

Digital literacy is the ability to use digital tools critically rather than just competently — to understand not just *how* a tool works but *why* it works that way, what interests are embedded in its design, what it costs to use it (in money, data, attention, and dependency), and what you'd lose if it disappeared tomorrow.

**Every free tool has a business model.** This is not cynicism; it's a structural reality. A tool that doesn't charge money either has investors who expect eventual monetization, operates on a freemium model, or is sustained by grants and donations. Understanding how a tool makes money tells you a great deal about its incentives. A tool that makes money by selling advertising has incentives to keep you engaged, which may or may not align with your interests. A tool that charges a subscription has incentives to keep you satisfied, which more often aligns with your interests.

**Data is the price of free.** Tools that collect data about your usage aren't inherently malicious — many improve their products from that data — but the terms of data collection, storage, and sharing vary enormously. What matters most: Can your data be sold to third parties? What happens to your data if the company is acquired or goes bankrupt? Can you export your data? Does using this tool put anyone else at risk (sources, subjects, contacts) whose interests you should consider?

**Vendor lock-in is a real switching cost.** The effort of switching tools is systematically underestimated at adoption time. People evaluate a tool's benefits at adoption and its switching costs at exit — when the costs are most visible. Before adopting any tool you'll rely on heavily, ask: Can I export my data in a standard format? Is there a clear migration path to alternatives? What happens if this service shuts down?

**Complexity creates attack surface.** The more tools in your workflow, the more places there are for something to go wrong: an account to be compromised, a service to go down, an integration to break. Productivity gains from additional tools need to be weighed against this. A simpler workflow with fewer tools is more resilient.

**Evaluating tools means evaluating the team behind them.** Track record matters: has the company been transparent about incidents? Have they honored their commitments to users? Have their terms of service changed in ways that disadvantaged users? Have they sold user data or made privacy promises they later rolled back? A team's past behavior is the best available evidence of its future behavior.

**Digital literacy includes knowing what you don't know.** Privacy and security are specialized fields. Most people cannot realistically audit the security practices of every tool they use. A practical approach: focus on the highest-stakes data (communications with sources, financial information, access credentials), use strong defaults (reputable tools with good track records, standard encryption), and follow updates from trusted security journalists and researchers rather than trying to become an expert.

## How to Apply

1. **Before adopting any significant tool, spend 10 minutes on its business model.** What does it charge, to whom, for what? Who funds it? If it's free, how does it sustain itself? This is usually findable from the company's about page, pricing page, and a quick news search.

2. **Check the data practices before importing sensitive information.** Before putting anything sensitive into a tool — client communications, source contacts, financial data — read its privacy policy with specific questions: Is data sold to third parties? Where is data stored and subject to which laws? Can you delete your data? What happens in an acquisition?

3. **Do a dependency audit annually.** List the tools you use heavily. For each: What would happen if this service shut down tomorrow? Can you export your data? Is there a viable alternative? Which tools are high-risk because you can't easily leave?

4. **Prefer tools with data portability.** When comparable tools exist, choose ones that let you export your data in open, standard formats. This is especially important for notes, writing, contacts, and any data you've invested significant time building.

5. **Apply threat modeling appropriate to your situation.** What actually are the risks you're protecting against? Advertisers tracking your behavior? Governments with subpoena power? Corporate espionage? Casual snoopers? Different threats require different defenses. Most people need basic hygiene (strong passwords, 2FA, reputable tools) rather than advanced operational security.

6. **Teach critical evaluation alongside tool skills.** When teaching tools — to students, colleagues, or in any training context — include a discussion of the tool's business model, data practices, and alternatives. Competence with a tool is incomplete without the critical layer.

## Examples

**Example 1: The Newsletter Writer's Tool Stack Audit**
A newsletter writer with 5,000 subscribers was using six tools for their workflow: an email platform, a writing app, a link management tool, a social scheduling tool, an analytics tool, and a CRM for subscriber management. After a digital literacy audit, they realized three of these tools had unclear data practices (one was free with no obvious revenue model), two had terms of service that claimed broad rights to user-generated content, and two couldn't export data in useful formats. They consolidated to four tools, switching to ones with clearer business models and better data portability. They paid more (two of the replacements charged subscription fees) but felt significantly less exposed.

**Example 2: Teaching Digital Literacy in a Journalism Program**
A journalism professor was teaching students to use AI writing tools without teaching them to evaluate those tools critically. After integrating digital literacy into the AI tools unit, students learned to ask: Who made this tool and how do they make money? What happens to the queries and documents I put into it? Could this expose source information? What are the terms of service? One student discovered that a popular AI tool's terms explicitly allowed using user inputs to train future models — a significant concern for journalists with confidential sources. The critical evaluation changed how students chose and used tools.

## Anti-Patterns

**Privacy theater.** Using privacy-branded tools without understanding whether they actually protect what you care about. A "private" browser mode doesn't protect you from your ISP or employer. A privacy-first email provider doesn't help if your contacts use Gmail. Meaningful privacy requires understanding what you're protecting against and whether your choices actually address it.

**Platform maximalism.** Centering your entire workflow in one company's ecosystem (Google, Microsoft, Apple, Meta) for the convenience, without considering the dependency this creates or what it means to have all your data in one place. The switching cost from deep platform integration is enormous and often only becomes visible at the worst possible moment.

**Evaluating only at adoption.** Assessing a tool once when you decide to use it, never re-evaluating as the tool's terms, ownership, and practices change. Companies get acquired. Privacy policies change. Business models pivot. A tool that was fine at adoption may not be fine three years later.
