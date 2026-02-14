---
url: https://connectrpc.com/docs/go/getting-started/
type: article
tags: [grpc, go, protobuf, connect, api]
date_saved: 2026-02-14
---
# Connect RPC: Getting Started with Go

## Summary
Connect is a slim library for building browser- and gRPC-compatible HTTP APIs in Go. You define services with Protocol Buffer schemas, and Connect generates type-safe server and client code, eliminating hand-written marshaling and routing.

## Key Points
- Uses Protocol Buffers to define services, with code generation via `buf`, `protoc-gen-go`, and `protoc-gen-connect-go`
- Supports browser-compatible and gRPC-compatible HTTP APIs from a single schema
- 15-minute walkthrough covers defining a service, generating code, and calling the API
- Integrates with `buf/validate` for request validation
- No hand-written marshaling, routing, or client code required

## Related
- [[protobuf]]
- [[grpc]]
- [[go-web-frameworks]]
