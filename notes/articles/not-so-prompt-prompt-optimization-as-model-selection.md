---
url: https://www.gojiberries.io/not-so-prompt-prompt-optimization-as-model-selection/
type: article
tags: [prompt-engineering, optimization, llm, evaluation, model-selection]
date_saved: 2026-02-14
---
# Not so Prompt: Prompt Optimization as Model Selection

## Summary
This article frames prompt optimization as a budgeted black-box optimization problem complicated by opaque prompt-to-performance mappings and noisy measurements. It advocates for constrained optimization with statistical guarantees, structured prompt decomposition, and end-to-end evaluation under production-like conditions.

## Key Points
- Prompt optimization suffers from sampling noise, decoding randomness, retrieval variability, and judge variability
- Two approaches: collapse to single monetary objective, or constrained optimization with hard boundaries on secondary metrics
- Maintain statistical confidence bounds (P95/P99) under production-like load rather than point estimates
- Decompose prompts into structured components (instruction, constraints, demos, schema) for combinatorial search vs monolithic string editing
- Use stratified K-fold evaluation with paired comparisons; prevent leakage from demonstrations into eval folds

## Related
- [[essential-graphrag]] - RAG evaluation and performance
- [[gorag]] - RAG implementation in Go
