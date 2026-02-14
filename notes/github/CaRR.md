---
url: https://github.com/THUDM/CaRR
type: github-repo
languages: [Python]
tags: [reinforcement-learning, deep-search, RAG, citation-aware, GRPO]
date_saved: 2026-02-14
---
# CaRR — Citation-Aware Rubric Rewards

## Summary
CaRR introduces Citation-aware Rubric Rewards and Citation-aware Group Relative Policy Optimization (C-GRPO) for training deep search agents via RL. It addresses shortcut exploitation and hallucination problems in outcome-only reward approaches by decomposing questions into verifiable rubrics requiring evidence grounding.

## Key Points
- Addresses flaws in binary outcome rewards: shortcut exploitation and hallucinations
- Decomposes multi-hop questions into atomic, verifiable rubrics
- Each rubric requires entity identification and citation-backed evidence
- Open-sourced SFT trajectories and RL QA pairs on Hugging Face (CaRR-DeepDive)
- Implemented as a remote reward model server for integration with RL training

## Related
- [[reinforcement-learning]] - training methodology
- [[deep-search-agents]] - agentic web search
- [[GRPO]] - Group Relative Policy Optimization
