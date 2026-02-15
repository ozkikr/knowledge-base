---
url: https://towardsdatascience.com/optimizing-vector-search-why-you-should-flatten-structured-data/
type: article
tags: [vector-search, rag, embeddings]
date_saved: 2026-02-15
---
# Optimizing Vector Search: Why You Should Flatten Structured Data
## Summary
The article explains why embedding raw JSON is often suboptimal for semantic retrieval with general-purpose text embedding models. It shows that structural tokens add noise during tokenization, attention, and pooling, which can hurt nearest-neighbor relevance. Converting structured records into concise natural language templates substantially improved retrieval metrics in the reported experiment.

## Key Points
- JSON syntax introduces many low-semantic tokens that dilute embedding quality.
- Transformer attention is trained primarily on natural-language patterns, not punctuation-heavy object notation.
- Mean pooling amplifies the effect of noisy structural tokens in final vectors.
- Flattening structured objects into natural language reduced token count and improved semantic clarity.
- Reported benchmark gains included large improvements in Recall@10 and MRR.

## Related
- [[embedding-models]]
- [[data-preprocessing]]
- [[retrieval-metrics]]
