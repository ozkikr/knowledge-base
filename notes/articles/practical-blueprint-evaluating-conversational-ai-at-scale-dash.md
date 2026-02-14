---
url: https://dropbox.tech/machine-learning/practical-blueprint-evaluating-conversational-ai-at-scale-dash
type: article
tags: [llm-evaluation, rag, dropbox, datasets, metrics, conversational-ai]
date_saved: 2026-02-14
---
# A Practical Blueprint for Evaluating Conversational AI at Scale

## Summary
Dropbox's engineering blog post sharing their evaluation playbook for Dash, their AI assistant. Covers the full arc of datasets, metrics, tooling, and workflows learned from building a production conversational AI system. Key insight: evaluation should be baked into every step, not tacked on at the end.

## Key Points
- Curate datasets from both public benchmarks (Natural Questions, MS MARCO, MuSiQue) and internal production logs
- Define actionable metrics and rubrics for scoring LLM outputs
- Treat every experiment like production code with standardized evaluation
- Build representative query and content datasets from real user behavior
- Use LLMs to generate synthetic questions spanning diverse content types (tables, images, tutorials)

## Related
- [[LLM-evaluation]]
- [[RAG]]
- [[RAGChecker]]
- [[LangWatch]]
