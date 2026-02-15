---
url: https://deepeval.com/docs/getting-started-rag
type: article
tags: [rag, evaluation, deepeval, llm-testing, observability]
date_saved: 2026-02-15
---
# RAG Evaluation Quickstart
## Summary
This quickstart walks through evaluating retrieval-augmented generation systems with DeepEval. It covers end-to-end RAG testing, plus separate evaluation of retriever and generator components. It also introduces multi-turn RAG evaluation for chatbot-style interactions.
## Key Points
- Models each RAG interaction as an `LLMTestCase` with retrieval context and output.
- Demonstrates metric-driven evaluation (e.g., answer relevancy, contextual precision).
- Shows tracing-based component evals using `@observe` and dataset iterators.
- Supports both single-turn and conversational RAG quality checks.
- Integrates with Confident AI for centralized result tracking and benchmarking.
## Related
- [[rag-evaluation]]
- [[deepeval]]
- [[llm-metrics]]
