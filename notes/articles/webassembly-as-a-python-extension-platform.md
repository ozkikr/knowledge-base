---
url: https://nullprogram.com/blog/2026/01/01/
type: article
tags: [webassembly, python, wasm, extensions, wasmtime]
date_saved: 2026-02-14
---
# WebAssembly as a Python Extension Platform

## Summary
Explores using WebAssembly as an extension mechanism for Python, shipping architecture-independent Wasm blobs inside Python libraries without requiring native toolchains. Covers wasmtime-py as the preferred runtime and highlights critical pitfalls around signed pointer handling.

## Key Points
- Wasm extensions give Python speed gains and access to capabilities written in other languages, without requiring a C toolchain on the host
- wasmtime-py is the best current option: ships binaries for all major platforms, 3-10x faster than wasm3, but ~18MiB and has unstable API
- Critical pitfall: Wasm runtimes treat all integers as signed, so pointers from malloc must be masked (`& 0xffffffff`) to avoid negative pointer bugs
- wasmtime-py's read/write methods accept negative indices (Python convention), compounding the signed pointer issue
- Found a real-world buffer overflow in a PDF reader library due to this exact negative pointer trap

## Related
- [[WebAssembly]]
- [[Python Extensions]]
- [[wasmtime]]
- [[Memory Safety]]
