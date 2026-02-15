---
url: https://github.com/yilinjz/astchunk
type: github-repo
languages: [Python]
tags: [code-chunking, ast, rag]
date_saved: 2026-02-15
---
# ASTChunk
## Summary
ASTChunk is a toolkit for splitting source code into structurally meaningful chunks using abstract syntax trees. Instead of naïve token windows, it preserves semantic and syntactic boundaries to improve downstream retrieval and analysis. It is positioned for code RAG, documentation generation, and code intelligence tasks.

## Key Points
- Builds chunks from AST nodes to better preserve function/class-level structure.
- Supports multiple languages via tree-sitter parsers (Python, Java, C#, TypeScript).
- Offers configurable chunk size, overlap, and metadata expansion options.
- Backed by research work on structural chunking for code retrieval-augmented generation.

## Related
- [[Code RAG]]
- [[Abstract Syntax Tree]]
- [[Chunking strategies]]
