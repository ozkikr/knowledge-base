---
url: https://arxiv.org/abs/2511.19858v1
type: paper
tags: [rag, medical-ai, llm-evaluation, prompting, clinical-nlp]
date_saved: 2026-02-14
---
# A Systematic Analysis of LLMs with RAG-enabled Dynamic Prompting for Medical Error Detection and Correction

## Summary
Evaluates zero-shot, static prompting with random exemplars (SPR), and retrieval-augmented dynamic prompting (RDP) for medical error detection and correction across nine LLMs. RDP consistently outperforms other strategies, reducing false positives by ~15% and improving recall.

## Key Points
- Evaluated on MEDEC dataset with GPT, Claude, Gemini, and OpenAI o-series models
- Three subtasks: error flag detection, error sentence detection, error correction
- Zero-shot prompting shows low recall, especially for abbreviation-heavy errors
- RDP reduces false-positive rate by ~15% and improves recall by 5-10%
- Demonstrates that retrieved exemplars improve reliability across diverse LLM architectures

## Related
- [[rag]]
- [[medical-ai]]
- [[prompting-strategies]]
- [[llm-evaluation]]
