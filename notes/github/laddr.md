---
url: https://github.com/AgnetLabs/laddr
type: github-repo
languages: [Python]
tags: [multi-agent, framework, distributed, microservices]
date_saved: 2026-02-14
---
# Laddr

## Summary
A Python framework for building multi-agent systems where agents communicate, delegate tasks, and execute work in parallel. Designed like a microservices architecture for AI agents with built-in message queues, observability, and horizontal scalability.

## Key Points
- Two modes: Coordinator-Orchestrator (dynamic) and Sequential Deterministic Workflow (fixed pipeline)
- Horizontal scaling: each agent scales independently with multiple workers
- Built-in observability: automatic logging, Langfuse integration, real-time metrics
- Uses Redis Streams for load balancing and fault tolerance
- Supports SQLite and PostgreSQL for tracing

## Related
- [[multi-agent]] [[distributed-systems]] [[ai-agents]] [[orchestration]]
