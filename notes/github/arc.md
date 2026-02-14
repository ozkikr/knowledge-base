---
url: https://github.com/Basekick-Labs/arc
type: github-repo
languages: [Go]
tags: [time-series, database, iot, duckdb, parquet, arrow, high-performance]
date_saved: 2026-02-14
---
# Arc

## Summary
High-performance time-series database built on DuckDB for Industrial IoT and analytics. Achieves 18.6M records/sec ingestion with sub-second queries on billions of rows, using portable Parquet files and standard DuckDB SQL.

## Key Points
- 18.6M records/sec ingestion via MessagePack Columnar protocol
- Built on DuckDB with full SQL support (window functions, CTEs, joins)
- Data stored in portable Parquet format
- Targets racing telemetry, smart cities, mining, medical devices, observability
- AGPL-3.0 licensed

## Related
- [[roaring]] - bitmap data structures for indexing
- [[pgvectorscale]] - Postgres extensions
- [[timeline]] - time-based scheduling
