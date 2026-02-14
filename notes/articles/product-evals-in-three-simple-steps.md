---
url: https://eugeneyan.com/writing/product-evals/
type: article
tags: [llm-evaluation, evals, machine-learning, product-development, llm-as-judge]
date_saved: 2026-02-14
---
# Product Evals in Three Simple Steps

## Summary
Eugene Yan's practical guide to building product evaluations for LLM systems in three steps: labeling a small dataset, aligning LLM evaluators, and running experiment/evaluation harnesses. Emphasizes binary labels over Likert scales, organic failures over synthetic ones, and individual evaluators per dimension over "God Evaluators."

## Key Points
- Use binary pass/fail labels instead of Likert scales — easier to calibrate for both humans and LLM-evaluators
- Aim for 50-100 fail cases out of 200+ samples; use smaller models to generate organic failures rather than synthetic defects
- Build one evaluator per dimension (faithfulness, relevance, etc.) rather than a single catch-all evaluator
- For win/lose comparisons, run evaluation twice with swapped order to account for position bias
- Evaluate evaluators on precision, recall, and Cohen's Kappa; benchmark against human performance, not perfection

## Related
- [[llm-as-judge-best-practices]]
- [[deepeval]]
- [[personal-ai-evals-aug-2025]]
- [[practical-blueprint-evaluating-conversational-ai-at-scale-dash]]
