---
url: https://huggingface.co/nari-labs/Dia2-2B
type: github-repo
languages: [Python, Rust]
tags: [tts, speech-synthesis, dialogue, streaming, real-time]
date_saved: 2026-02-14
---
# Dia2-2B

## Summary
Dia2 is a streaming dialogue TTS model by Nari Labs that can start generating audio from the first few words without needing the entire text. It supports audio conditioning for natural conversations in real-time, with 1B and 2B parameter variants. Supports up to 2 minutes of English generation.

## Key Points
- Streaming TTS — doesn't need full text to begin audio generation
- Audio conditioning with prefix speakers enables natural conversational speech-to-speech
- Two model sizes: 1B and 2B parameters, using bfloat16 precision
- CLI and Python API with CUDA graph support; Gradio web UI included
- Upcoming: Sori, a Dia2-powered speech-to-speech engine written in Rust

## Related
- [[chatterbox]]
- [[audiblez]]
