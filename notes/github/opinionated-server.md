---
url: https://github.com/jrockway/opinionated-server
type: github-repo
languages: [Go]
tags: [grpc, server-boilerplate, observability, prometheus, jaeger]
date_saved: 2026-02-14
---
# opinionated-server

## Summary
A Go package providing opinionated boilerplate for gRPC/HTTP servers with structured logging (zap), distributed tracing (Jaeger), metrics (Prometheus), and configuration (go-flags) all pre-wired.

## Key Points
- Uses zap for structured logging with runtime log-level changes via HTTP
- Jaeger distributed tracing with B3 propagation for all gRPC/HTTP calls
- Prometheus metrics with pre-instrumented HTTP and gRPC handlers
- go-flags for configuration via flags and environment variables
- Saves hours of repetitive server setup boilerplate

## Related
- [[grpc]]
- [[observability]]
- [[go-server-patterns]]
