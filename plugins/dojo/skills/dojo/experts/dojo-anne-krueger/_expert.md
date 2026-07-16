---
name: dojo-anne-krueger
description: >
  Custom panel of 1 expert — a hand-picked roster. Use when user says 'ask dojo',
  names Krueger or Anne Krueger, or asks about a domain they cover. Loaded: Anne O. Krueger
  (rent-seeking, trade reform, IMF policy, economic liberalisation, development strategy).
triggers:
  - "user says 'ask dojo'"
  - "user names Krueger or Anne Krueger"
  - "user asks about rent-seeking"
  - "user asks about trade reform and development"
  - "user asks about IMF conditionality"
  - "user asks about import substitution failure"
  - "user asks about economic liberalisation in developing countries"
  - "user asks about government failure in development"
  - "user asks about exchange rate policy"
---

# Dojo: Anne O. Krueger

## Routing

Load `persona.md` for voice, beliefs, and reasoning style.

**Route by keyword →**

| Keyword / phrase | Topic file |
|---|---|
| rent-seeking, rents, DUP | `rent-seeking-theory.md` |
| import substitution, ISI, inward-looking | `import-substitution-critique.md` |
| trade reform, liberalisation sequence | `trade-reform-strategy.md` |
| IMF, conditionality, structural adjustment | `imf-and-conditionality.md` |
| exchange rate, overvaluation, currency | `exchange-rate-policy.md` |
| government failure, state intervention | `government-failure.md` |
| foreign aid, aid effectiveness | `aid-and-development.md` |
| East Asia, outward orientation, export-led | `east-asian-lessons.md` |
| debt, sovereign debt, crisis | `debt-and-crisis-management.md` |
| agriculture, agricultural policy, rural | `agricultural-policy.md` |
| institutions, governance, corruption | `institutions-and-governance.md` |
| political economy, reform obstacles | `political-economy-of-reform.md` |
| WTO, multilateral, trade rules | `multilateral-trade-governance.md` |
| South Africa, African development, SACU | `krueger-applied-to-southern-africa.md` |
| development practice, policy advice | `krueger-and-development-practice.md` |

If no keyword matches, load `rent-seeking-theory.md` as the default.
