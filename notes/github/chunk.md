---
url: https://github.com/chonkie-inc/memchunk
type: github-repo
languages: [Rust, Python, JavaScript]
tags: [chunking, text-processing, simd, performance]
date_saved: 2026-02-14
---
# chunk (formerly memchunk)

## Summary
Chunk is an extremely fast text chunking library achieving up to 1 TB/s throughput. It splits text at semantic boundaries using SIMD instructions and lookup tables, available for Rust, Python, and JavaScript. It powers the chonkie chunking ecosystem.

## Key Points
- Up to 1 TB/s throughput — can chunk all of English Wikipedia in 120ms
- Uses SIMD instructions and lookup tables for performance
- Supports custom chunk sizes, delimiters, and multi-byte patterns
- Available as Rust crate, Python package (chonkie-core), and npm package
- Previously known as memchunk; now part of the broader chonkie project

## Related
- [[chonkie]] - Parent project using chunk as its core
- [[text-splitting]] - General concept of text chunking for NLP/RAG
- [[ragflow]] - RAG engine that benefits from fast chunking
