---
url: https://popovicu.com/posts/running-go-tools-in-browser/
type: article
tags: [golang, wasm, webassembly, browser, bazel]
date_saved: 2026-02-14
---
# Running Go Tools in a Browser

## Summary
A step-by-step guide to compiling Go code to WebAssembly (WASM) and running it in the browser. Uses the Mrav CPU assembler as an example, exposing Go functions to JavaScript via the `syscall/js` package and building with Bazel (or standard Go tooling).

## Key Points
- Go's `syscall/js` package exposes Go functions to JavaScript in the browser
- Binary structure: expose functions via `js.Global().Set()`, then block on a channel read to keep the WASM module alive
- Build with `GOARCH=wasm GOOS=js` or Bazel's `go_cross_binary` with a wasm_js platform
- Requires `wasm_exec.js` from Go source; use `WebAssembly.instantiateStreaming` to load the binary
- Useful for educational tools and letting users experiment with projects without local setup

## Related
- [[webassembly]]
- [[golang]]
- [[browser-tooling]]
