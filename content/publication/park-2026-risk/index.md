---
title: 'Risk Is Not Review Value: Wrong-Answer Exposure Under Bounded Review Budgets'
authors:
- SangJin Park
- Myungsub Choi
- Jineok Kim
- Minseung Kang
date: '2026-08-10'
publishDate: '2026-08-29T12:00:00.000000Z'
publication_types:
- paper-conference
publication: '*KDD 2026 Workshop on Secure and Trustworthy Large Language Models (SeT-LLM)*'
abstract: |-
  LLM assistants often produce more answers than humans can review before users see them. Most evaluations ask whether an answer is wrong, unsupported, or low-confidence. Bounded review budgets instead ask which answers should be checked first under a fixed review budget. Risk alone is not enough: a high-risk answer may be hard to repair, while a moderately risky answer may be directly correctable from available evidence. For generated-answer evaluation, we model review prioritization as exposure reduction, where review value combines estimated wrongness, intervention affordance, impact, and cost. We evaluate review queues with Wrong-Answer Exposure Ratio (WAER), the fraction of wrong answers left unreviewed, and post-repair residual exposure (PRRE), the fraction still exposed after deterministic benchmark-supported repairs. On a 720-item TAT-QA/SciFact stress benchmark, review-value ranking keeps answer-level WAER nearly unchanged at 20% budget (0.605 vs. 0.600) but lowers PRRE from 0.881 to 0.716. These results show that trustworthy LLM evaluation should measure not only error detection, but also how limited review capacity reduces exposed wrong answers.
links:
- type: site
  url: https://openreview.net/forum?id=qmco237nV6
---
