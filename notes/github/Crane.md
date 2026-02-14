---
url: https://github.com/lucasjinreal/Crane
type: github-repo
languages: [Rust]
tags: [llm-inference, rust, candle, apple-silicon, tts, ocr, vlm]
date_saved: 2026-02-14
---
# Crane 🦩 — Rust-based LLM/VLM Inference Engine

## Summary
Crane is a pure Rust inference engine built on the Candle framework, supporting LLM, VLM, TTS, ASR, OCR, and VAD models. It aims to be a simpler, cleaner alternative to llama.cpp with blazing-fast performance on CPU and GPU (especially Apple Silicon via Metal).

## Key Points
- Supports Qwen3, Qwen3-VL, PaddleOCR-VL, Spark-TTS, Moonshine ASR, Silero VAD
- Claims 50x faster than native PyTorch on Apple M-series chips
- Compiles to a single binary like llama.cpp but with cleaner Rust codebase
- No GGUF conversion needed — runs models directly
- Hardware agnostic: CPU/CUDA/Metal execution from unified codebase

## Related
- [[llama.cpp]]
- [[Candle]]
- [[Rust ML]]
- [[Apple Silicon]]
