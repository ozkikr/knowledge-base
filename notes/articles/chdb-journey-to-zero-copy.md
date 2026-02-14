---
url: https://clickhouse.com/blog/chdb-journey-to-zero-copy
type: article
tags: [clickhouse, chdb, pandas, python, olap, zero-copy]
date_saved: 2026-02-14
---
# The Journey to Zero-Copy: How chDB Became the Fastest SQL Engine on Pandas DataFrame

## Summary
How chDB v2 achieved 87x speedup over v1 by eliminating serialization overhead between Python DataFrames and ClickHouse's query engine. Covers zero-copy integration, GIL-free parallel string encoding in C++, automatic DataFrame variable discovery, and achieving native ClickHouse performance on Pandas data.

## Key Points
- chDB v1 had 4 serialization/deserialization steps, making every query >100ms regardless of complexity
- v2 enables zero-copy: reference DataFrame variables directly in SQL via `Python(df)` syntax
- Rewrote Python string encoding in C++ to avoid GIL contention, achieving 15x speedup on string-heavy queries
- Automatic variable discovery searches local/global scope for DataFrame references without explicit registration
- Minimizes CPython API calls by batching all Python interactions before the parallel ClickHouse pipeline starts

## Related
- [[clickhouse]]
- [[pandas-performance]]
- [[python-c-extensions]]
