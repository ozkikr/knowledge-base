---
url: https://github.com/ncoder-ai/VibeVoice-FastAPI
type: github-repo
languages: [Python, Shell, Dockerfile]
tags: [tts, fastapi, openai-compatible, vibevoice, voice-api]
date_saved: 2026-02-15
---
# VibeVoice-FastAPI
## Summary
VibeVoice-FastAPI provides a production-ready FastAPI service around VibeVoice models with an OpenAI-compatible speech endpoint. It is designed for self-hosted TTS workflows with Docker-first deployment, voice directory management, and streaming output. The project focuses on practical API compatibility so existing TTS clients can be adapted with minimal changes.
## Key Points
- Exposes `/v1/audio/speech` and related voice endpoints in an OpenAI-style interface.
- Supports custom voice libraries by loading local audio files as reusable voice presets.
- Includes Docker and compose workflows, health checks, and deployment-oriented configuration.
- Supports multiple response formats and long-form streaming generation paths.
## Related
- [[text-to-speech]]
- [[fastapi]]
- [[openai-compatible-api]]
