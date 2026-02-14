---
url: https://clickhouse.com/blog/qbit-vector-search
type: article
tags: [vector-search, clickhouse, quantization, database, performance]
date_saved: 2026-02-14
---
# QBit: Vector Search with Query-Time Precision in ClickHouse

## Summary
ClickHouse introduced QBit, a column type that stores float vectors as bit planes, allowing users to choose how many bits to read during vector search. This enables tuning recall and performance at query time without changing the stored data.

## Key Points
- QBit stores vectors as bit planes, enabling variable precision at query time
- No upfront decisions needed — adjust precision/speed tradeoff per query
- Complements existing HNSW-based ANN search in ClickHouse
- Brute-force vector search has been supported in ClickHouse for years
- Useful for RAG, recommendations, and semantic search use cases

## Related
- [[bleve]] - Search library with vector support
- [[usearch]] - Vector search engine
