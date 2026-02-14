---
url: https://arpitbhayani.me/blogs/qkv-matrices/
type: article
tags: [transformers, attention-mechanism, deep-learning, llm-internals]
date_saved: 2026-02-14
---
# The Q, K, V Matrices

## Summary
A ground-up explanation of Query, Key, and Value matrices in the transformer attention mechanism. Uses intuitive analogies (database lookups) and simple NumPy examples to show how self-attention lets each token attend to every other token simultaneously, replacing sequential RNN processing.

## Key Points
- Q (Query) = "what am I looking for?", K (Key) = "what do I contain?", V (Value) = "what information do I hold?"
- Attention replaced sequential RNN processing, enabling parallel computation and better long-range dependency capture
- The attention pipeline: input → linear projections → Q, K, V → attention scores → softmax → weighted values → output
- Uses a concrete 3-word example ("Cat eats fish") with 4D embeddings to walk through the math
- Q, K, V matrices are learned weight matrices that reshape input embeddings into different representational subspaces

## Related
- [[how-llm-inference-works]]
- [[transformer-architecture]]
- [[self-attention]]
