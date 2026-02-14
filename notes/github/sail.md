---
url: https://github.com/lakehq/sail
type: github-repo
languages: [Rust, Python]
tags: [spark, data-processing, stream-processing, distributed-computing]
date_saved: 2026-02-14
---
# Sail

## Summary
Sail is an open-source unified and distributed multimodal computation framework by LakeSail. It's compatible with the Spark Connect protocol (no code rewrites needed), is ~4x faster than Spark, 94% cheaper on infrastructure, and is 100% Rust-native with no JVM overhead.

## Key Points
- Compatible with Spark SQL and DataFrame API via Spark Connect protocol
- ~4x faster than Spark (up to 8x in specific workloads), outperforms Databricks and Snowflake on ClickBench
- 94% cheaper infrastructure costs compared to Spark
- 100% Rust-native — memory safety, instant startup, predictable performance
- Available as Python package (`pysail`) on PyPI, deployable on Kubernetes

## Related
- [[Apache Spark]]
- [[Rust]]
- [[Distributed Computing]]
- [[Data Processing]]
