---
url: https://github.com/messkan/prompt-cache
type: github-repo
languages: [Go, Shell, YAML]
tags: [llm-cache, semantic-cache, latency, cost-optimization]
date_saved: 2026-02-15
---
# prompt-cache
## Summary
prompt-cache is a semantic caching layer for LLM applications designed to reduce latency and token spend. It sits between application and model provider to return cached responses for semantically similar prompts with verification safeguards. The project targets production use with metrics, health checks, and operational controls.
## Key Points
- Implements semantic prompt caching to reduce duplicate LLM inference costs.
- Emphasizes correctness with safer matching/verification over naive cache hits.
- Includes production readiness features such as Prometheus metrics and structured logging.
- Built in Go for low-latency middleware deployment.
## Related
- [[LLM Caching]]
- [[Inference Optimization]]
- [[AI Gateway]]
