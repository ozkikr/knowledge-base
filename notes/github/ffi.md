---
url: https://github.com/jupiterrider/ffi
type: github-repo
languages: [Go, C]
tags: [ffi, purego, libffi, cgo-free, interop]
date_saved: 2026-02-14
---
# JupiterRider/ffi

## Summary
A purego binding for libffi in Go, enabling calling C functions — including passing and returning structs by value — without cgo. Supports darwin, linux, freebsd, and windows on amd64/arm64 architectures.

## Key Points
- Extends purego with libffi capabilities (struct pass/return by value)
- No cgo required — pure Go interop with C shared libraries
- Cross-platform: macOS, Linux, FreeBSD, Windows on amd64/arm64 (+linux/riscv64)
- libffi binaries embedded for Windows and macOS (zero extra dependencies)
- Leverages libffi which is pre-installed on most systems (Python/Ruby dependency)

## Related
- [[purego]] - base library for cgo-free C interop in Go
- [[search]] - kelindar/search uses similar purego approach
- [[go-interop]] - Go foreign function interfaces
