---
url: https://docs.ray.io/en/latest/data/working-with-llms.html
type: article
tags: [ray, vllm, batch-inference, llm, distributed-computing]
date_saved: 2026-02-14
---
# Working with LLMs — Ray Data

## Summary
Ray Data's `ray.data.llm` module integrates with LLM inference engines (primarily vLLM) to enable scalable batch inference. It provides a Processor abstraction that handles preprocessing, inference, and postprocessing on Ray Data datasets.

## Key Points
- `build_processor` API constructs processors with vLLM engine configuration
- Supports batch inference, embedding models, and OpenAI-compatible API endpoints
- Configurable concurrency (engine replicas) and batch size
- Preprocessing converts inputs to OpenAI chat format; postprocessing extracts generated text
- Results consumable via `iter_rows()`, `take()`, `show()`, or `write_parquet()`

## Related
- [[vllm]]
- [[batch-inference]]
- [[ray-data]]
- [[mlx-lm]]
