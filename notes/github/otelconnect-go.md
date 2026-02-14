---
url: https://github.com/connectrpc/otelconnect-go
type: github-repo
languages: [Go]
tags: [opentelemetry, grpc, connect-rpc, observability, tracing]
date_saved: 2026-02-14
---
# otelconnect-go

## Summary
otelconnect-go adds OpenTelemetry tracing and metrics collection to Connect RPC servers and clients. It provides a simple interceptor-based API that integrates with OpenTelemetry's global or custom TracerProvider and MeterProvider.

## Key Points
- Single interceptor for both tracing and metrics on Connect RPC
- Works with both servers and clients via `connect.WithInterceptors`
- Uses OpenTelemetry's global TracerProvider/MeterProvider by default
- Optional custom providers via `WithTracerProvider` and `WithMeterProvider`
- Part of the Connect RPC ecosystem (better gRPC alternative)

## Related
- [[opentelemetry]]
- [[connect-rpc]]
- [[grpc]]
- [[observability]]
