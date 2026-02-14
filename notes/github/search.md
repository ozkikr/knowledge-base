---
url: https://github.com/kelindar/search
type: github-repo
languages: [Go]
tags: [vector-search, semantic-search, embeddings, llama-cpp, BERT]
date_saved: 2026-02-14
---
# kelindar/search

## Summary
A Go library for embedded vector search and semantic embeddings using llama.cpp. Designed for small to medium datasets (<100K entries), it uses brute-force search with SIMD optimizations and supports GGUF BERT models for embeddings — all without cgo via purego.

## Key Points
- No cgo required — uses purego to call llama.cpp shared libraries directly
- Supports BERT models in GGUF format for generating embeddings
- Precompiled binaries with Vulkan GPU acceleration for Windows and Linux
- Best suited for datasets under 100,000 entries (brute-force with SIMD)
- Simple API for embedding and searching in Go applications

## Related
- [[vector-search]] - semantic search techniques
- [[llama-cpp]] - underlying inference engine
- [[purego]] - Go library for calling C without cgo
- [[ffi]] - related Go FFI library
