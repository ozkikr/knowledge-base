---
url: https://netflixtechblog.medium.com/high-throughput-graph-abstraction-at-netflix-part-i-e88063e6f6d5
type: article
tags: [graph-databases, oltp, netflix]
date_saved: 2026-02-15
---
# High-Throughput Graph Abstraction at Netflix: Part I
## Summary
Netflix describes an internal graph abstraction optimized for OLTP-style graph workloads that need very high throughput and low latency. The system builds on existing Netflix data abstractions (KV, TimeSeries, EVCache) and currently serves large-scale production demand. Part I focuses on schema design, indexing strategy, and storage layout for efficient graph traversal.

## Key Points
- Targets graph workloads requiring millions of ops/sec with strict latency constraints.
- Uses strongly typed property-graph schemas to enforce data quality and improve query planning.
- Organizes graph data into namespaces mapped to underlying datastore resources.
- Separates edge link indexes from edge property indexes for scalability and upsert efficiency.
- Integrates with control-plane automation for provisioning, schema management, and operations.

## Related
- [[Property Graphs]]
- [[High-Throughput OLTP]]
- [[Graph Indexing]]
