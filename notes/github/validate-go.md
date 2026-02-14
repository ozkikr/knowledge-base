---
url: https://github.com/connectrpc/validate-go
type: github-repo
languages: [Go]
tags: [grpc, connect, validation, protobuf, cel]
date_saved: 2026-02-14
---
# validate-go - Request Validation for Connect

## Summary
A Connect interceptor that automates data validation by encoding constraints into Protobuf schemas. Powered by protovalidate and the Common Expression Language (CEL), it provides flexible, efficient validation consistent across languages without code generation.

## Key Points
- Connect interceptor for automatic request validation
- Constraints defined in Protobuf schemas using buf.validate annotations
- Powered by protovalidate and CEL expressions
- Supports simple predefined constraints (email, bounds) and complex CEL expressions
- No additional code generation required

## Related
- [[connect-rpc]]
- [[protobuf]]
- [[go-libraries]]
