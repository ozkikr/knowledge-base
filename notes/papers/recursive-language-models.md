---
url: https://arxiv.org/abs/2512.24601
type: paper
tags: [llm, long-context, inference-time-scaling, recursive-models]
date_saved: 2026-02-14
---
# Recursive Language Models

## Summary
Proposes Recursive Language Models (RLMs), an inference paradigm that lets LLMs process arbitrarily long prompts by treating them as an external environment the model can programmatically examine, decompose, and recursively call itself over. RLM-Qwen3-8B outperforms base Qwen3-8B by 28.3% and approaches vanilla GPT-5 quality on long-context tasks.

## Key Points
- RLMs treat long prompts as external environment, allowing programmatic examination and recursive self-calls
- Can process inputs up to two orders of magnitude beyond model context windows
- Even for shorter prompts, dramatically outperforms vanilla frontier LLMs and common long-context scaffolds
- Post-trained first natively recursive language model (RLM-Qwen3-8B)
- Comparable cost to standard approaches while significantly improving quality

## Related
- [[inference-time-scaling]]
- [[long-context]]
- [[test-time-compute]]
