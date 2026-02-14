---
url: https://huggingface.co/microsoft/VibeVoice-Realtime-0.5B
type: article
tags: [tts, text-to-speech, realtime, microsoft, open-source-model]
date_saved: 2026-02-14
---
# VibeVoice-Realtime-0.5B - Microsoft's Real-Time TTS Model

## Summary
VibeVoice-Realtime is a 0.5B parameter lightweight real-time text-to-speech model from Microsoft supporting streaming text input and robust long-form speech generation. It produces initial audible speech in ~300ms and uses an interleaved windowed design with diffusion-based acoustic latent generation at an ultra-low 7.5 Hz frame rate.

## Key Points
- 0.5B parameters, deployment-friendly with ~300ms first audible latency
- Streaming text input allows speaking from first LLM tokens before full answer
- Primarily English but exhibits multilingual capability across 9 additional languages
- Uses efficient acoustic tokenizer at 7.5 Hz (no semantic tokenizer)
- Single speaker only; multi-speaker available in other VibeVoice variants

## Related
- [[text-to-speech]]
- [[streaming-inference]]
- [[diffusion-models]]
- [[microsoft-research]]
