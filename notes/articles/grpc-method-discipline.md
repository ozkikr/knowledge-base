---
url: https://matttproud.com/blog/posts/grpc-method-discipline.html
type: article
tags: [grpc, distributed-systems, api-design, streaming]
date_saved: 2026-02-14
---
# Flowchart for Choosing gRPC Method Types

## Summary
A practical guide for choosing between unary and streaming gRPC method types. Uses a blob upload service as an example to explore the tradeoffs between simplicity (unary) and scalability (streaming), providing a decision flowchart.

## Key Points
- Unary RPCs are simpler to build, maintain, and reason about
- Streaming RPCs handle large payloads and incremental data better
- gRPC's appeal: cross-platform, native wire format, interceptors, multiple method structures
- The choice between unary and streaming has real cost implications for maintenance
- Provides a systematic flowchart for making the decision

## Related
- [[go-best-practices]]
- [[distributed-systems]]
