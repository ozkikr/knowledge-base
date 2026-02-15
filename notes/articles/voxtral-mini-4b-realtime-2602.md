---
url: https://huggingface.co/mistralai/Voxtral-Mini-4B-Realtime-2602
type: paper
tags: [speech-recognition, realtime-ai, multilingual-models]
date_saved: 2026-02-15
---
# Voxtral Mini 4B Realtime 2602
## Summary
Voxtral Mini 4B Realtime 2602 is a multilingual streaming ASR model from Mistral designed for low-latency transcription with configurable delay. The model uses a causal audio encoder and sliding-window attention to support continuous streaming while remaining competitive with strong offline baselines. It is Apache-2 licensed and positioned for real-time assistants, subtitles, and meeting transcription.

## Key Points
- Targets realtime transcription with configurable delay (roughly 80ms to 2400ms), with 480ms presented as a strong quality/latency tradeoff.
- Combines a ~3.4B language model with a ~970M audio encoder trained for streaming.
- Supports multilingual transcription (13+ languages highlighted in benchmarks).
- Emphasizes practical deployment via vLLM and modest hardware requirements for a 4B model.
- Released with links to a technical report, demo, and production-oriented serving guidance.

## Related
- [[automatic-speech-recognition]]
- [[streaming-inference]]
- [[on-device-ml]]
