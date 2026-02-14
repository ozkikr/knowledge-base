---
url: https://github.com/dianlight/gollama.cpp
type: github-repo
languages: [Go, C]
tags: [llama-cpp, llm, purego, cgo-free, inference]
date_saved: 2026-02-14
---
# gollama.cpp

## Summary
High-performance Go bindings for llama.cpp using purego and libffi for cross-platform compatibility without CGO. Supports GPU acceleration via Metal, CUDA, HIP, Vulkan, OpenCL, and SYCL across macOS, Linux, and Windows.

## Key Points
- Pure Go implementation—no CGO required, uses purego and libffi for C interop
- Cross-platform: macOS (CPU/Metal), Linux (CPU/NVIDIA/AMD), Windows (CPU/NVIDIA/AMD)
- Version-synchronized with llama.cpp releases
- Includes optional go:embed bundle for runtime libraries on all platforms
- Low-level GGML tensor library bindings for advanced use cases

## Related
- [[purego]] - underlying FFI library used
- [[llama.cpp]] - the C++ inference engine being wrapped
