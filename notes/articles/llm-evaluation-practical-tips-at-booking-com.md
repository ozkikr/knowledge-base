---
url: https://booking.ai/llm-evaluation-practical-tips-at-booking-com-1b038a0d6662
type: article
tags: [llm, evaluation, llm-as-judge, mlops, booking-com]
date_saved: 2026-02-14
---
# LLM Evaluation: Practical Tips at Booking.com

## Summary
Booking.com shares lessons from one year of developing Judge-LLM systems for evaluating GenAI applications. The article covers the LLM-as-judge framework, where a more powerful LLM evaluates a target LLM's outputs, enabling scalable monitoring with minimal human involvement.

## Key Points
- LLM-as-judge uses a powerful LLM to replicate human judgment for evaluating target LLM outputs
- Human annotation is needed only once to create a "golden dataset" representative of production data
- The judge-LLM solves a classification task, so standard metrics (accuracy, F1, precision, recall) apply
- Key LLM risks addressed: hallucination, instruction-following failures, and cost management
- Once judge accuracy exceeds a threshold vs human labels, it can be deployed for continuous production monitoring

## Related
- [[llm-evaluation]]
- [[mlops]]
- [[golden-dataset]]
