---
url: https://github.com/ebitengine/purego
type: github-repo
languages: [Go]
tags: [ffi, cgo-free, cross-compilation, ebitengine]
date_saved: 2026-02-14
---
# purego

## Summary
A library for calling C functions from Go without Cgo, born from the Ebitengine game engine project. Enables simple cross-compilation, faster builds, smaller binaries, and dynamic linking.

## Key Points
- No C compiler needed—cross-compile by just setting GOOS
- Smaller binaries (no C wrapper functions generated)
- Supports dynamic linking and plugin systems at runtime
- Tier 1 support for Android, iOS, Linux, macOS, Windows (amd64/arm64)
- Works as Cgo fallback (CGO_ENABLED=1) for incremental porting

## Related
- [[gollama.cpp]] - uses purego for llama.cpp bindings
- [[ebitengine]] - game engine that spawned this project
