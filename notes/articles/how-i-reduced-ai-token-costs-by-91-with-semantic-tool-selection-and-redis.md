---
url: https://mlops.community/how-i-reduced-ai-token-costs-by-91-with-semantic-tool-selection-and-redis/
type: article
tags: [tool-selection, llm-cost-optimization, redis]
date_saved: 2026-02-15
---
# How I Reduced AI Token Costs by 91% with Semantic Tool Selection and Redis
## Summary
This article presents a semantic tool-routing architecture that drastically cuts token overhead by selecting only relevant tools per query. The system uses multi-component embeddings (description, params, examples, returns) plus Redis vector search and adaptive ranking. Reported outcomes include major token reduction, lower cost, and improved retrieval precision for enterprise tool ecosystems.

## Key Points
- Replaces “send every tool every time” with semantic preselection.
- Embeds tool metadata in multiple weighted components for better intent matching.
- Uses Redis vector indexing and caching to balance latency and operational simplicity.
- Applies adaptive cutoff logic based on score drop-offs instead of fixed top-k only.
- Reports strong gains in token use, relevance metrics, and response speed.

## Related
- [[semantic-retrieval]]
- [[llm-routing]]
- [[vector-search]]
