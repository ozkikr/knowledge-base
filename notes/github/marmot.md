---
url: https://github.com/maxpert/marmot
type: github-repo
languages: [Go]
tags: [sqlite, distributed, replication, mysql, gossip-protocol]
date_saved: 2026-02-14
---
# Marmot

## Summary
Marmot v2 is a leaderless, distributed SQLite replication system with MySQL wire protocol compatibility. It uses a gossip-based protocol with distributed transactions and eventual consistency, allowing any node to accept writes with no single point of failure.

## Key Points
- Leaderless architecture with no single point of failure; any node accepts writes
- MySQL protocol compatible — works with DBeaver, MySQL Workbench, mysql CLI, and even WordPress
- Percolator-style distributed transactions with conflict detection
- DDL replication with automatic idempotency and cluster-wide locking
- Tunable consistency (ONE/QUORUM/ALL) and automatic split-brain recovery via anti-entropy

## Related
- [[sqlite]]
- [[distributed-systems]]
- [[mysql]]
- [[rqlite]]
