---
url: https://github.com/artie-labs/ducktape
type: github-repo
languages: [Go]
tags: [duckdb, rest-api, http2, streaming, microservice]
date_saved: 2026-02-14
---
# Ducktape

## Summary
Ducktape is a lightweight REST API microservice for DuckDB with HTTP/2 streaming support. It isolates DuckDB behind a network boundary to avoid CGO complications in pure Go apps, achieving ~90% of native DuckDB throughput (~757 MiB/sec vs ~848 MiB/sec).

## Key Points
- Streams NDJSON over HTTP/2 for high-throughput ingestion into DuckDB
- Uses DuckDB's Appender API for fast, type-aware row insertion
- Avoids CGO dependency issues for Go cross-compilation and CI/CD
- Includes a native Go client library
- Supports local DuckDB files and MotherDuck

## Related
- [[DuckDB]]
- [[data-ingestion]]
- [[microservices]]
