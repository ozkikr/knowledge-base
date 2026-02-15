---
url: https://github.com/pgdogdev/pgdog
type: github-repo
languages: [Rust, Python, JavaScript, Blade, PLpgSQL, Go]
tags: [postgresql, connection-pooling, sharding]
date_saved: 2026-02-15
---
# PgDog
## Summary
PgDog is a Rust-based PostgreSQL proxy focused on scaling workloads through connection pooling, query load balancing, and database sharding. It is positioned as a production-oriented alternative to simple poolers, with health checks, transaction/session modes, and multi-host routing.

## Key Points
- Provides PostgreSQL connection pooling for high client concurrency with fewer backend connections.
- Supports application-layer load balancing across primaries and replicas.
- Includes sharding support for distributing data across multiple database nodes.
- Offers Kubernetes and Docker-based quick-start paths for deployment.
- Emphasizes operational resilience with health checks and connection recovery behaviors.

## Related
- [[PostgreSQL]]
- [[Connection Pooling]]
- [[Database Sharding]]
