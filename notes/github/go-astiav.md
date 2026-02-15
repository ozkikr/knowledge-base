---
url: https://github.com/asticode/go-astiav
type: github-repo
languages: [Go, C, Dockerfile]
tags: [ffmpeg, golang, media-processing]
date_saved: 2026-02-15
---
# go-astiav
## Summary
go-astiav is a Go library providing C bindings for FFmpeg/libav with a more Go-idiomatic API style. It includes examples mapped to upstream FFmpeg samples and practical guidance on memory lifecycle patterns. The project is aimed at developers building media pipelines in Go while retaining low-level FFmpeg power.

## Key Points
- Wraps FFmpeg n8.0 APIs for Go applications.
- Focuses on idiomatic interfaces, typed constants, and tested behavior.
- Ships extensive examples for demuxing, transcoding, filtering, hardware paths, and more.
- Documents allocation/unref/free patterns to avoid lifecycle bugs.
- Includes setup guidance for source builds and cross-platform workflows.

## Related
- [[FFmpeg]]
- [[Go Media Tooling]]
- [[CGO Bindings]]
