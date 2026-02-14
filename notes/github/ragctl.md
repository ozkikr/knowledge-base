---
url: https://github.com/datallmhub/ragstudio
type: github-repo
languages: [Python]
tags: [rag, document-processing, ocr, chunking, cli]
date_saved: 2026-02-14
---
# ragctl (formerly ragstudio)

## Summary
ragctl is a production-ready CLI tool for processing documents into chunks for RAG systems. It handles document ingestion, OCR with automatic fallback, and intelligent semantic chunking, supporting multiple export formats and direct Qdrant ingestion.

## Key Points
- Universal document loading: PDF, DOCX, ODT, HTML, Markdown, images
- Smart OCR cascade: EasyOCR → PaddleOCR → pytesseract with quality detection
- Intelligent semantic chunking via LangChain with configurable strategies
- Production batch processing with auto-retry and exponential backoff
- Export to JSON, JSONL, CSV, or directly to Qdrant vector store

## Related
- [[bruin]] - Data pipeline tooling
- [[tangle]] - ML pipeline orchestration
