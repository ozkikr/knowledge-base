---
url: https://arxiv.org/abs/2506.15655
type: paper
tags: [code-rag, abstract-syntax-tree, code-generation]
date_saved: 2026-02-15
---
# cAST: Enhancing Code Retrieval-Augmented Generation with Structural Chunking via Abstract Syntax Tree
## Summary
This paper argues that chunking strategy is a major bottleneck in code RAG systems and proposes cAST, an AST-aware chunking method. Instead of line-based splitting, cAST recursively partitions large syntax nodes and merges siblings to preserve semantic coherence under token limits. The method improves both retrieval and downstream generation across code benchmarks.

## Key Points
- Identifies semantic breakage from line-based chunking as a hidden source of RAG errors.
- Introduces structure-aware chunking based on AST node boundaries and controlled merging.
- Produces self-contained chunks that better align with code semantics across languages.
- Reports gains on retrieval quality (e.g., Recall@5) and generation success (e.g., Pass@1).

## Related
- [[retrieval-augmented-generation]]
- [[code-intelligence]]
- [[ast-based-analysis]]
