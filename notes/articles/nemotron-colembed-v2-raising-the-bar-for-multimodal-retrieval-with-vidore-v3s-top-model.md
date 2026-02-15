---
url: https://huggingface.co/blog/nvidia/nemotron-colembed-v2
type: article
tags: [multimodal-retrieval, embeddings, vidore]
date_saved: 2026-02-15
---
# Nemotron ColEmbed V2: Raising the Bar for Multimodal Retrieval with ViDoRe V3’s Top Model
## Summary
NVIDIA introduces the Nemotron ColEmbed V2 family (3B, 4B, 8B) as late-interaction multimodal embedding models for high-accuracy visual document retrieval. The post positions these models as state-of-the-art on ViDoRe benchmarks, especially ViDoRe V3. It contrasts the approach with single-vector embeddings and explains tradeoffs between retrieval quality and storage/inference complexity.

## Key Points
- Uses ColBERT-style late interaction (multi-vector token matching via MaxSim) extended to multimodal retrieval.
- Reports top leaderboard performance across ViDoRe variants, with the 8B model ranking first on ViDoRe V3.
- Describes architecture changes such as bidirectional attention and contrastive bi-encoder training.
- Highlights a model-size ladder (3B/4B/8B) for different accuracy/compute envelopes.
- Frames the models as strong candidates for enterprise document RAG with text-image retrieval.

## Related
- [[multimodal-rag]]
- [[late-interaction-retrieval]]
- [[embedding-models]]
