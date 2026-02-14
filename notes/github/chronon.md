---
url: https://github.com/airbnb/chronon
type: github-repo
tags: [feature-platform, ml-infrastructure, airbnb, data-engineering, feature-store]
date_saved: 2026-02-14
---
# Chronon (Airbnb)

## Summary
Chronon is a data platform by Airbnb that abstracts away the complexity of data computation and serving for AI/ML applications. Users define features as transformations of raw data, and Chronon handles batch/streaming computation, backfills, low-latency serving, and correctness guarantees.

## Key Points
- Supports batch tables, event streams, and services as data sources
- Provides low-latency online serving with managed pipelines for batch and realtime updates
- Scalable, point-in-time accurate backfills for model training with online/offline consistency
- Built-in observability for data freshness and online/offline consistency monitoring
- Supports complex windowed aggregations over arbitrary window sizes

## Related
- [[feature-store]]
- [[ml-infrastructure]]
- [[data-pipelines]]
