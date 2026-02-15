---
url: https://openworkers.com/introducing-openworkers
type: article
tags: [workers, edge-computing, rust, self-hosting]
date_saved: 2026-02-15
---
# Introducing OpenWorkers – Self-hosted Cloudflare Workers in Rust
## Summary
Announcement and technical overview of OpenWorkers, an open-source runtime for running Cloudflare-Workers-style JavaScript on self-hosted infrastructure.

## Key Points
- Implements V8-isolate execution with resource limits (CPU/memory) for sandboxed workloads.
- Supports key bindings/APIs including KV, PostgreSQL, S3/R2-compatible storage, fetch/streams/crypto, and service bindings.
- Describes a multi-service architecture (proxy, API, runners, scheduler, logging, messaging, database).
- Emphasizes Cloudflare Workers compatibility while avoiding vendor lock-in.
- Positions self-hosting as a way to keep data in-house and control cost predictability.

## Related
- Edge runtime architecture
- Isolate-based sandboxing
- Serverless platforms
