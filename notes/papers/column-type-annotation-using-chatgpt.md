---
url: https://arxiv.org/pdf/2306.00745
type: paper
tags: [table-understanding, chatgpt, semantic-annotation]
date_saved: 2026-02-15
---
# Column Type Annotation using ChatGPT
## Summary
This work evaluates ChatGPT for semantic column type annotation in relational tables, a key task for data lake search and integration. The authors test prompt designs across zero-shot and few-shot settings, including a two-step annotation pipeline that narrows label space by inferred entity class. With instructions and staged prompting, ChatGPT reaches competitive F1 scores above 85% with minimal task-specific examples.
## Key Points
- Frames column type annotation as semantic labeling of relational table columns.
- Compares zero-shot, one-shot, and instruction-enhanced prompting strategies.
- Uses a two-step pipeline to first infer entity class then restrict candidate types.
- Shows competitive performance versus fine-tuned RoBERTa with far fewer labeled examples.
## Related
- [[Table Annotation]]
- [[Prompt Engineering]]
- [[Data Integration]]
