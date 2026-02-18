---
url: https://github.com/orbitinghail/graft
type: github-repo
tags: [storage-engine, replication, edge-computing, offline-first, sqlite, rust, distributed-systems, sync]
languages: [Rust]
date_saved: 2026-02-18
---

# Graft

Open-source transactional storage engine optimized for lazy, partial, and strongly consistent replication — designed for edge, offline-first, and distributed applications.

## Summary

Graft is a transactional storage engine that turns object storage into a transactional system with page-granularity updates. It supports lazy (on-demand) and partial replication with Serializable Snapshot Isolation, making it ideal for edge/mobile apps that need to sync only the data they need.

## Key Points

- **Lazy replication**: clients sync data on demand (saves network/compute)
- **Partial replication**: minimize bandwidth by syncing only required data
- **Strong consistency**: Serializable Snapshot Isolation
- **Transactional object storage**: consistent updates at page granularity, no schema imposed
- **Instant read replicas**: decoupled metadata/data, no replay needed
- SQLite extension available (easiest integration path)
- Rust crate for direct embedding
- Alpha quality — contact maintainer before production use
- Apache 2.0 / MIT dual license
- From the creator of SQLSync

## Use Cases

- Offline-first and mobile applications
- Cross-platform synchronization
- Stateless replicas for serverless/embedded
- Storage and replication layer for databases

## Related

- [[sqlsync]] — predecessor project by same author
- [[cr-sqlite]] — CRDTs for SQLite (different approach to sync)
- [[litestream]] — SQLite replication (streaming, not transactional)
- [[electric-sql]] — sync layer for Postgres/SQLite
