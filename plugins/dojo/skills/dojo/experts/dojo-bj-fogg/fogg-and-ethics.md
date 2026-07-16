---
triggers:
  - "user asks about ethics of behaviour design"
  - "user asks about manipulation versus empowerment"
  - "user worries about using behavioural techniques on others"
use_when:
  - "ethical concerns about behaviour design need addressing"
  - "the line between helpful behaviour design and manipulation needs clarifying"
  - "someone is designing behaviour change for others and needs ethical guardrails"
fails_when:
  - "you dismiss ethical concerns as overblown"
  - "you provide a simple rule that resolves all ethical questions — the tensions are real"
  - "you ignore that even well-intentioned behaviour design can be paternalistic"
related:
  - "fogg-and-persuasive-technology.md"
  - "behaviour-design-for-teams.md"
  - "behaviour-crafting.md"
---

# Fogg and Ethics

## When to Use
- When ethical concerns about behaviour design arise — particularly when designing for others.
- When the distinction between helpful nudging and manipulation needs clarifying.
- When programme designers, managers, or technologists need ethical frameworks for behaviour design.

## Core Concept
Behaviour design raises an inescapable ethical question: if you can systematically cause people to do things, who decides what they should do? Fogg addresses this through a simple principle: behaviour design is ethical when it serves the person whose behaviour is being changed, and unethical when it serves the designer at the person's expense.

This principle is clear in personal use. When you design your own tiny habits — choosing your own anchor, your own behaviour, your own aspiration — you are both designer and user. Autonomy is fully preserved. The ethical questions emerge when someone else is the designer: a manager designing team behaviours, a programme officer designing beneficiary behaviours, a technologist designing user behaviours.

Fogg identifies three ethical tests. First, transparency: does the person know their behaviour is being designed? Hidden behaviour design — manipulating choice architectures without disclosure — is ethically suspect regardless of intent. Second, benefit direction: does the designed behaviour primarily benefit the person performing it, or the person designing it? A medication reminder benefits the patient. An infinite scroll feature benefits the platform. Third, autonomy preservation: can the person opt out without penalty? If the designed behaviour is effectively mandatory — if opting out carries consequences — the designer has an additional ethical burden to ensure the behaviour genuinely serves the person.

The development sector faces particular ethical complexity. Programmes routinely design behaviour for beneficiaries — encouraging adoption of health practices, agricultural techniques, financial behaviours. These are well-intentioned, but the designer (the programme) and the user (the beneficiary) have different power positions, different information, and potentially different values. Fogg's framework would ask: does the beneficiary understand that their behaviour is being designed? Does the designed behaviour serve their interests as they define them? Can they opt out without losing access to other programme benefits?

These questions do not always have comfortable answers, but asking them is the ethical floor.

## How to Apply
1. **Apply the transparency test.** "Does the person know their behaviour is being designed? If not, start there."
2. **Apply the benefit test.** "Who benefits from this behaviour — the person doing it or the person designing it?"
3. **Apply the autonomy test.** "Can the person opt out without penalty? If not, is the behaviour genuinely in their interest?"
4. **Design with, not for.** "Wherever possible, involve the person in designing their own behaviour change. This preserves autonomy and improves design quality."

## Examples
**Situation:** A development programme wants to use behavioural nudges to increase savings rates among smallholder farmers — default enrolment in a savings programme with opt-out.
**Application:** Fogg would say: "Default enrolment is powerful behaviour design — it exploits the status quo bias to increase participation. But run the ethical tests. Transparency: do farmers understand they have been automatically enrolled? Not buried in terms and conditions — do they genuinely understand? If the default is hidden, it is manipulation regardless of intent. Benefit: does saving benefit the farmers? Probably yes, but are the savings products appropriate? Are the interest rates fair? Are the terms clear? A default that enrolls farmers in a product with hidden fees is exploitation dressed as empowerment. Autonomy: can farmers opt out easily, without social pressure, without losing access to other programme benefits? If opting out is technically possible but practically difficult — if they have to visit an office, fill out a form, explain their decision — the 'opt-out' is an ability barrier designed to prevent the very behaviour it claims to allow. My recommendation: default enrolment is ethically acceptable if the product genuinely serves the farmers, the default is clearly communicated, and opting out is genuinely easy. If any of those conditions is not met, you are using behaviour design techniques against the people you are supposed to serve."

## Anti-Patterns
**Don't:** Assume good intentions resolve ethical concerns.
**Why:** Well-intentioned behaviour design can still be paternalistic, manipulative, or harmful if it overrides autonomy, lacks transparency, or primarily serves the designer's goals.

**Don't:** Avoid behaviour design because of ethical concerns.
**Why:** Not designing behaviour is itself a choice — it defaults to whatever existing forces are shaping behaviour, which may be worse. The answer is ethical design, not no design.
