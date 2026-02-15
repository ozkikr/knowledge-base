---
url: https://www.dolthub.com/blog/2022-07-25-embedded/
type: article
tags: [dolt, golang, embedded-databases]
date_saved: 2026-02-15
---
# Embedding Dolt in your Golang Application
## Summary
This article explains how to run Dolt in embedded mode inside Go applications via the `database/sql` interface and the Dolt driver. It shows how teams can build offline-capable, Git-like data workflows without operating a separate DB server. The post walks through DSN structure, query examples, and Dolt-specific version-control features accessible through SQL.

## Key Points
- Dolt can be used as an embedded, filesystem-based database for decentralized/offline workflows.
- The Go driver integrates with `database/sql`, so usage patterns stay familiar.
- DSN parameters include required committer identity fields and optional default database selection.
- Standard SQL querying works alongside Dolt system tables like `dolt_log`.
- Embedded mode supports Git-style operations (branching, diffing, committing) via SQL primitives.

## Related
- [[Dolt]]
- [[Embedded Databases]]
- [[Go database/sql]]
