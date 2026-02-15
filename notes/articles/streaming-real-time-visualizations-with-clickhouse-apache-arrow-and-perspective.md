---
url: https://clickhouse.com/blog/streaming-real-time-visualizations-clickhouse-apache-arrow-perpsective
type: article
tags: [clickhouse, apache-arrow, perspective, real-time-analytics, streaming]
date_saved: 2026-02-15
---
# Streaming Real-Time Visualizations with ClickHouse, Apache Arrow and Perspective
## Summary
This post demonstrates a lightweight approach for real-time browser visualizations by streaming ClickHouse query deltas in Apache Arrow format into Perspective tables. It uses polling over HTTP and client-side WebAssembly processing to keep interactivity high while controlling memory with row limits. The example uses forex tick data and discusses practical performance limits and architectural tradeoffs.

## Key Points
- Integrates ClickHouse + Perspective with minimal JavaScript and no heavy framework dependency.
- Uses Arrow output for efficient transport and direct browser ingestion.
- Implements sliding-window polling and query patterns tuned for timestamp-ordered data.
- Shows how Perspective can keep constant memory overhead by retaining only recent rows.
- Notes current limitations (no websocket native push) and points toward future improvements.

## Related
- [[clickhouse]]
- [[apache-arrow]]
- [[real-time-visualization]]
