---
url: https://blog.codingconfessions.com/p/compiling-python-to-run-anywhere
type: article
tags: [python, compiler, performance]
date_saved: 2026-02-14
---
# Compiling Python to Run Anywhere

## Summary
A guest post by Yusuf Olokoba (founder of Muna) exploring how to compile pristine Python code into cross-platform machine code. The approach generates optimized kernels while keeping Python source unchanged, targeting server, desktop, mobile, and web platforms.

## Key Points
- Compiles Python entirely ahead-of-time with no source modifications
- Runs without a Python interpreter with minimal overhead vs C/C++
- Targets cross-platform: server, desktop, mobile, and web
- Previous attempts include Jython, RustPython, Numba, PyTorch, and Mojo
- AI turned out to be a missing piece in the compilation approach

## Related
- [[cpython-internals]] - Understanding Python's runtime
- [[performance-engineering]] - Systems-level optimization
