---
url: https://github.com/sirius-db/sirius
type: github-repo
languages: [C++, CUDA]
tags: [gpu, sql, database, analytics, duckdb]
date_saved: 2026-02-14
---
# Sirius - GPU-Native SQL Engine

## Summary
Sirius is a GPU-native SQL engine that plugs into existing databases like DuckDB via the Substrait query format. Built on NVIDIA CUDA-X libraries (cuDF, RMM), it delivers ~8x speedup over CPU query engines at equivalent hardware costs for analytical workloads.

## Key Points
- GPU-accelerated SQL analytics via standard Substrait query format
- Plugs into DuckDB (and Doris coming soon) with no query rewrites needed
- ~8x speedup over CPU engines at same hardware rental cost (TPC-H SF=100)
- Built on NVIDIA CUDA-X, cuDF, and RAPIDS Memory Manager
- Requires NVIDIA Volta+ GPUs with CUDA >= 13.0

## Related
- [[duckdb]]
- [[gpu-computing]]
- [[analytics]]
- [[substrait]]
