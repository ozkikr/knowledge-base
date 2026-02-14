---
url: https://github.com/karpathy/nanochat
type: github-repo
languages: [Python, CUDA]
tags: [llm-training, gpt-2, pretraining, finetuning, chat-ui]
date_saved: 2026-02-14
---
# nanochat

## Summary
nanochat by Andrej Karpathy is the simplest experimental harness for training LLMs on a single GPU node. It covers tokenization, pretraining, finetuning, evaluation, inference, and a ChatGPT-like web UI. You can train a GPT-2 capability model for ~$72 (3 hours on 8xH100) with a single `--depth` dial controlling all hyperparameters.

## Key Points
- Single complexity dial (`--depth`) auto-configures all hyperparameters optimally
- Covers full LLM pipeline: tokenization → pretraining → finetuning → eval → inference → chat UI
- GPT-2 speedrun leaderboard for community collaboration
- Designed for single GPU node, minimal/hackable code
- Spot instance cost can be as low as ~$20

## Related
- [[nanoGPT]]
- [[LLM Training]]
- [[GPT-2]]
- [[Scaling Laws]]
