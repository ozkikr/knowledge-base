---
url: https://github.com/hybridgroup/yzma
type: github-repo
languages: [Go]
tags: [llama.cpp, local-inference, golang, multimodal, ai-tooling]
date_saved: 2026-02-15
---
# yzma
## Summary
yzma is a Go-native way to integrate llama.cpp directly into applications for local inference with hardware acceleration. It avoids cgo by using purego/ffi, making it easier to track newer llama.cpp features while keeping deployment simple.
## Key Points
- Runs local LLM and VLM inference on Linux, macOS, and Windows.
- Supports accelerators like CUDA, Metal, and Vulkan.
- Includes examples for chat, multimodal prompts, and model downloads.
- Emphasizes in-process performance instead of external model servers.
## Related
- [[llama.cpp]]
- [[Local LLM]]
- [[Go AI Tooling]]
