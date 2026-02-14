---
url: https://blog.jetbrains.com/go/2025/10/16/the-10x-commandments-of-highly-effective-go/
type: article
tags: [go, best-practices, testing, packages, code-quality]
date_saved: 2026-02-14
---
# The "10x" Commandments of Highly Effective Go

## Summary
Ten mantras for Go excellence by John Arundel of Bitfield Consulting. Covers writing reusable packages, testing everything, writing readable code, and leveraging Go's standard library and tooling effectively.

## Key Points
- Write packages, not programs — main should only parse flags and handle errors
- Test everything — test names should be sentences, focus on user-visible behavior
- Write code for reading — have colleagues read it to find stumbling points
- Flexible packages return data instead of printing, errors instead of panicking
- Keep module structure simple: ideally one package

## Related
- [[tdd-shameless-green]] - TDD in Go
- [[sqlclosecheck]] - Go linting
- [[grpc-method-discipline]] - Go/gRPC
