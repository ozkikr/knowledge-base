---
url: https://github.com/CogitatorTech/infera
type: github-repo
languages: [Rust]
tags: [duckdb, ml-inference, onnx, sql, database-extension]
date_saved: 2026-02-14
---
# Infera

## Summary
Infera is a DuckDB extension written in Rust that enables running ML models directly in SQL queries. It uses Tract as the backend inference engine and supports ONNX format models, eliminating the need to export data to Python/R for inference and import results back.

## Key Points
- Run ONNX ML models directly in SQL queries inside DuckDB
- Built in Rust using Tract inference engine
- Supports local and remote models, single and multi-value outputs
- Thread-safe, fast, and memory-efficient
- Eliminates data movement between database and ML environments

## Related
- [[DuckDB]]
- [[ONNX]]
- [[In-Database ML]]
- [[Rust]]
