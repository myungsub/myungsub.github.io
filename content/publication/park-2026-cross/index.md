---
title: 'Cross-Agent Campaign Attribution: Linking Asynchronous Attacks Across LLM Agents'
authors:
- SangJin Park
- Myungsub Choi
- Jineok Kim
- Minseung Kang
date: '2026-07-11'
publishDate: '2026-08-29T12:00:00.000000Z'
publication_types:
- paper-conference
publication: '*ICML 2026 Second Workshop on Agents in the Wild: Safety, Security, and
  Beyond (AIWILD)*'
abstract: |-
  LLM-agent defenses are typically evaluated one session at a time. In deployment, however, attacks can be distributed across independent agents, teams, and runtimes, leaving each local guardrail with only a sparse fragment. We formalize cross-agent asynchronous campaign attribution: linking sessions from the same latent adversarial campaign without shared runtime state, test-time campaign labels, or attacker identity oracles. We introduce Asynchronous Attribution Fingerprint Vectors ($A^2FV$), a lightweight proxy-side reference protocol for scoring pairwise campaign similarity from proxy-observable tool-use, timing, and prompt residue. We also construct SCD-v1, a controlled persona-matched benchmark with benign traffic, isolated attacks, multi-session campaigns, matched non-oracle evasion, and leakage audits. On SCD-v1, $A^2FV$ achieves 0.82 pairwise AUC for campaign linking, while score-only adaptations of per-session detectors and chunked LLM judges remain near chance under the same task. These results establish cross-agent campaign attribution as a distinct evaluation layer for securing LLM agents in the wild.
links:
- type: pdf
  url: https://arxiv.org/pdf/2607.18826
- type: preprint
  url: https://arxiv.org/abs/2607.18826
- type: site
  url: https://openreview.net/forum?id=2MIqLDdZBO
---
