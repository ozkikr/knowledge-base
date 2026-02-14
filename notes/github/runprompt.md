---
url: https://github.com/chr15m/runprompt
type: github-repo
languages: [Python]
tags: [llm, cli, prompt-templates, dotprompt, structured-output]
date_saved: 2026-02-14
---
# runprompt

## Summary
A single-file Python script that runs LLM .prompt files (Google's Dotprompt format) from the shell. Supports structured JSON output via Picoschema, prompt chaining via pipes, pre-prompt shell commands for dynamic context, and multiple LLM providers. Installable via uvx, pip, or direct download.

## Key Points
- Runs Dotprompt (.prompt) files containing prompt text + metadata (model, schema, config) in one file
- Supports structured JSON output with Picoschema format for extraction tasks
- Prompt chaining: pipe JSON output from one prompt as template variables into the next
- Pre-prompt `before:` commands execute shell commands to gather dynamic context before sending
- Special variables: {{STDIN}}, {{ARGS}}, {{INPUT}} for flexible input handling

## Related
- [[files-to-prompt]]
- [[baml]]
