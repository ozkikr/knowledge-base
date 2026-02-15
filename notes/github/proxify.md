---
url: https://github.com/poixeai/proxify
type: github-repo
languages: [TypeScript, Go, Shell, CSS, HTML, Dockerfile, JavaScript]
tags: [ai-gateway, reverse-proxy, llm-apis, self-hosted]
date_saved: 2026-02-15
---
# Proxify
## Summary
Proxify is a self-hosted reverse proxy gateway for AI APIs that exposes multiple providers behind a unified base URL. It focuses on high-performance streaming behavior for LLM use cases, including heartbeat and tail-latency optimizations. The project combines a Go backend gateway with a web dashboard for configuration and management.
## Key Points
- Unifies multiple upstream AI APIs behind route prefixes (e.g., `/openai`, `/gemini`, `/claude`).
- Built for streaming-heavy LLM workloads with output smoothing and keepalive behavior.
- Designed to run lightweight, including small server footprints.
- Supports Docker and manual deployment workflows with configurable routes and auth.
- Emphasizes privacy via self-hosted control of API traffic.
## Related
- [[API Gateway]]
- [[LLM Infrastructure]]
- [[Reverse Proxy]]
