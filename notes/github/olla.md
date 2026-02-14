---
url: https://github.com/thushan/olla
type: github-repo
languages: [Go]
tags: [llm, proxy, load-balancer, infrastructure, routing]
date_saved: 2026-02-14
---
# Olla - High-Performance LLM Proxy and Load Balancer

## Summary
Olla is a high-performance, low-latency proxy and load balancer for managing LLM infrastructure. It intelligently routes requests across local and remote inference nodes with unified model discovery, automatic failover, and circuit breakers.

## Key Points
- Smart load balancing with priority-based routing and automatic failover
- Dual proxy engines: Sherpa (simple) and Olla (high-performance with circuit breakers)
- Unified model catalogues with per-provider and cross-provider routing
- Health monitoring with continuous endpoint checks and automatic recovery
- Single CLI application and config file deployment

## Related
- [[llm-infrastructure]]
- [[load-balancing]]
- [[go-libraries]]
