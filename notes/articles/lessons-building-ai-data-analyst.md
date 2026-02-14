---
url: https://www.pedronasc.com/articles/lessons-building-ai-data-analyst
type: article
tags: [ai-data-analyst, text-to-sql, semantic-layer, malloy, multi-agent, retrieval]
date_saved: 2026-02-14
---
# Lessons on Building an AI Data Analyst

## Summary
Pedro Nascimento shares lessons from 3 years building an AI data analyst at Findly (YC). The key insight: text-to-SQL alone is insufficient — real user questions require multi-step plans, code execution, external context, and a strong semantic layer. The product evolved from simple SQL generation into a full generative BI platform.

## Key Points
- Text-to-SQL is a capability, not a product — real questions need multi-step workflows (plan → SQL → Python transforms → validate → visualize → drill-down)
- Context is the product: a semantic layer (Malloy) encodes business meaning and drastically reduces SQL complexity and errors
- Use a multi-agent, research-oriented system that can retrieve, code, and learn from its environment
- Retrieval is a recommendation problem: mix keyword, embeddings, and fine-tuned reranker; optimize precision, recall, latency
- Benchmarks ≠ production — users expect human-level answers with defensible reasoning, not just pass@k metrics

## Related
- [[text-to-sql]]
- [[semantic-layer]]
- [[multi-agent-systems]]
- [[retrieval-augmented-generation]]
