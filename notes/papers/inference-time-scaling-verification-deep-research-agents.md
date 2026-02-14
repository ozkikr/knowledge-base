---
url: https://arxiv.org/abs/2601.15808
type: paper
tags: [deep-research, verification, inference-scaling, self-improvement, ai-agents]
date_saved: 2026-02-14
---
# Inference-Time Scaling of Verification: Self-Evolving Deep Research Agents via Test-Time Rubric-Guided Verification

## Summary
Proposes DeepVerifier, a rubric-based outcome reward verifier for Deep Research Agents (DRAs) that enables self-improvement at inference time without additional training. Instead of improving policy via post-training, agents iteratively verify outputs using rubrics derived from a DRA Failure Taxonomy (5 major categories, 13 sub-categories).

## Key Points
- DeepVerifier outperforms vanilla agent-as-judge and LLM judge baselines by 12%-48% in meta-evaluation F1
- Test-time scaling delivers 8%-11% accuracy gains on GAIA and XBench-DeepResearch
- DRA Failure Taxonomy classifies agent failures into 5 major and 13 sub-categories
- Plug-and-play module: produces rubric-based feedback for iterative bootstrapping
- Releases DeepVerifier-4K: 4,646 high-quality agent steps for SFT on verification

## Related
- [[deep-research]]
- [[inference-time-scaling]]
- [[ai-agent-evaluation]]
- [[reward-models]]
