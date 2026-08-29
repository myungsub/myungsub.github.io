---
title: 'Beyond the Verdict: Evidence-Aligned Evaluation of Visual Prompt-Injection Guardrails'
authors:
- Suyoung Lee
- Myungsub Choi
date: '2026-08-09'
publishDate: '2026-08-29T12:00:00.000000Z'
publication_types:
- paper-conference
publication: '*To appear at the ECCV 2026 2nd Workshop on Benchmarking Evidence-Aligned
  Multimodal Reasoning (BEAM 2)* (Oral)'
abstract: |-
  Verdict-only evaluation does not reveal whether a vision-language model (VLM) used the visual evidence that should support its decision. We study this problem in web-agent guardrails, where a VLM judges whether on-screen text conflicts with a user instruction. We introduce Mind2Web-Injection, a benchmark of 9,954 instruction–screenshot pairs with instruction-relative labels, pixel-exact evidence boxes, and matched image-side counterfactuals. Across six VLMs, two models with nearly identical average precision differ ninefold in Evidence-Aligned Detection (EAD), the fraction of attacks both detected and correctly localized. To diagnose these failures, we propose two training-free interventions. ReadGate improves grounding without changing verdicts, while CmdCompare tests whether explicit instruction–command comparison resolves instruction-side inconsistency. These results motivate reporting verdict correctness, evidence localization, and counterfactual responsiveness separately.
links:
- type: site
  url: https://openreview.net/forum?id=b3CCaLYaxL
---
