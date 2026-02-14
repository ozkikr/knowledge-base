---
url: https://github.com/santinic/audiblez
type: github-repo
languages: [Python]
tags: [audiobooks, tts, epub, kokoro, text-to-speech]
date_saved: 2026-02-14
---
# Audiblez - Generate Audiobooks from E-books

## Summary
Audiblez converts .epub e-books into .m4b audiobooks using Kokoro-82M, a lightweight (82M params) text-to-speech model with natural-sounding output. It supports multiple languages, CUDA acceleration, and has both CLI and GUI interfaces.

## Key Points
- Converts .epub to .m4b audiobooks using Kokoro-82M TTS (Apache licensed)
- GPU: ~600 chars/sec on T4 (5 min for Animal Farm); CPU: ~60 chars/sec on M2 MacBook
- Supports 🇺🇸 🇬🇧 🇪🇸 🇫🇷 🇮🇳 🇮🇹 🇯🇵 🇧🇷 🇨🇳 languages
- v4 adds graphical interface and CUDA support
- Requires espeak-ng and ffmpeg; installable via pip

## Related
- [[neutts-air]] - on-device TTS models
