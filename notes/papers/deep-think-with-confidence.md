---
url: https://arxiv.org/abs/2508.15260
type: paper
tags: [llm-reasoning, test-time-scaling, confidence-filtering]
date_saved: 2026-02-15
---
# Deep Think with Confidence
## Summary
This paper introduces Deep Think with Confidence (DeepConf), a test-time method for improving LLM reasoning by filtering low-quality traces using internal confidence signals. Instead of blindly scaling with majority voting, DeepConf keeps stronger candidates during or after generation to improve efficiency and accuracy. Across reasoning benchmarks, it reports major gains, including near-perfect AIME 2025 accuracy at high sample counts with large token savings.

## Key Points
- Targets a core weakness of self-consistency: diminishing returns and high compute cost.
- Uses model-internal confidence to prune weak reasoning paths without additional training.
- Integrates into existing inference/serving pipelines with minimal extra tuning burden.
- On challenging math benchmarks, it improves accuracy while cutting generated tokens substantially.

## Related
- [[llm-reasoning]]
- [[test-time-scaling]]
- [[self-consistency]]
