---
url: https://github.com/otiai10/gosseract
type: github-repo
languages: [Go, C++]
tags: [ocr, tesseract, image-processing]
date_saved: 2026-02-14
---
# gosseract - Go OCR Package

## Summary
Go package providing OCR (Optical Character Recognition) capabilities by wrapping the Tesseract C++ library. Supports macOS, Linux, and Windows with simple API for extracting text from images.

## Key Points
- Wraps Tesseract C++ library via cgo for Go applications
- Simple API: create client, set image, get text
- Cross-platform: macOS (brew), Linux (apt), Windows (vcpkg + MinGW)
- Docker support with pre-built images
- Companion project: ocrserver for ready-made OCR API

## Related
- [[ocrserver]] - HTTP server built on gosseract
- [[tesseract]] - Underlying OCR engine
- [[image-processing]]
