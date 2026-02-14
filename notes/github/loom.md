---
url: https://github.com/openfluke/loom
type: github-repo
languages: [Go, Python, C#, TypeScript]
tags: [neural-network, deterministic, webgpu, virtual-machine, cross-platform]
date_saved: 2026-02-14
---
# Loom - Deterministic Neural Virtual Machine

## Summary
Loom is a Deterministic Neural Virtual Machine (DNVM) that guarantees bitwise-identical neural network results across all platforms, backends, and language bindings. It combines a JIT compiler generating WebGPU shaders with a pure Go CPU backend, offering polyglot FFI support across Go, Python, C#, TypeScript, and WASM.

## Key Points
- Portable IR using JSON network configs as "bytecode" — define once, execute anywhere
- JIT compilation to WebGPU compute pipelines via runtime WGSL shader generation
- Bit-exact reproducibility (0.0 difference between CPU/GPU, x86/ARM, native/browser)
- Single binary with zero dependencies, transparent CPU/WebGPU routing
- Pre-compiled binaries for Linux, Windows, macOS, Android, and iOS

## Related
- [[WebGPU]]
- [[neural-networks]]
- [[deterministic-computing]]
