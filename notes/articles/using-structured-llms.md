---
url: https://developers.llamaindex.ai/python/framework/understanding/extraction/structured_llms/
type: article
tags: [llamaindex, structured-output, pydantic, extraction]
date_saved: 2026-02-15
---
# Using Structured LLMs
## Summary
This page demonstrates LlamaIndex structured extraction by wrapping an LLM with a Pydantic schema. It shows invoice parsing from PDF text into typed Python objects and JSON output. The guide highlights schema validation benefits while noting model outputs can still require careful review.
## Key Points
- Uses `as_structured_llm()` to bind model output to a Pydantic schema.
- Parses document text (example: invoice) into typed fields and nested objects.
- Returns both serialized JSON text and parsed Pydantic object representations.
- Supports regular completion/chat APIs with structured output behavior.
- Can be combined with query engines for structured RAG responses.
## Related
- [[llamaindex]]
- [[structured-output]]
- [[pydantic]]
