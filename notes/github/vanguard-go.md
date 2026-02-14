---
url: https://github.com/connectrpc/vanguard-go
type: github-repo
languages: [Go]
tags: [grpc, rest, protobuf, connect-rpc, http-transcoding]
date_saved: 2026-02-14
---
# Vanguard — REST/gRPC/Connect Protocol Transcoding for Go

## Summary
Vanguard is a Go library that enables seamless transcoding between REST and RPC protocols (gRPC, gRPC-Web, Connect). It uses Google's HTTP transcoding annotations on Protobuf service definitions to translate between protocols without code generation.

## Key Points
- Supports REST ↔ gRPC ↔ gRPC-Web ↔ Connect protocol translation
- Works as HTTP middleware wrapping existing handlers
- No code generation required — loads service definitions dynamically
- Useful for migrating REST APIs to schema-driven RPC APIs
- Compatible with Connect, gRPC-Go, and proxy setups

## Related
- [[gRPC]]
- [[Connect-RPC]]
- [[Protobuf]]
- [[API Gateway]]
