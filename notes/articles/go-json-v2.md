---
url: https://antonz.org/go-json-v2/
type: article
tags: [go, json, stdlib, go-1.25, encoding]
date_saved: 2026-02-14
---
# JSON Evolution in Go: From v1 to v2

## Summary
The `encoding/json/v2` package coming in Go 1.25 is a major update with breaking changes. It adds new features like MarshalWrite/UnmarshalRead, a new options system, improved tags, and better performance while fixing longstanding API issues and behavioral flaws.

## Key Points
- New `MarshalWrite`/`UnmarshalRead` for direct io.Writer/Reader operations (replacing Encoder/Decoder for simple cases)
- `MarshalEncode`/`UnmarshalDecode` with new `jsontext` package for streaming
- New options system: `FormatNilMapAsNull`, `MatchCaseInsensitiveNames`, `Multiline`, `OmitZeroStructFields`, etc.
- Encoder/Decoder types moved to new `jsontext` package with changed interfaces
- Interactive examples throughout the article for hands-on learning

## Related
- [[go-stdlib]]
- [[json]]
- [[go-1.25]]
