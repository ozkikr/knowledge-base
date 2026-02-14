---
url: https://github.com/simonw/files-to-prompt
type: github-repo
languages: [Python]
tags: [llm-tools, prompt-engineering, cli, developer-tools]
date_saved: 2026-02-14
---
# files-to-prompt

## Summary
A CLI tool by Simon Willison that concatenates a directory of files into a single prompt for use with LLMs. Supports filtering by extension, .gitignore awareness, and output in plain text, Claude XML, or Markdown with fenced code blocks.

## Key Points
- Concatenates directory contents into a single LLM-ready prompt
- Multiple output formats: plain, Claude XML (`--cxml`), Markdown (`--markdown`)
- Respects .gitignore by default, with `--ignore` patterns via fnmatch
- Supports line numbers, hidden files, and file output options
- Built entirely using Claude 3 Opus as documented in a blog post

## Related
- [[Simon Willison]]
- [[LLM Prompting]]
- [[Developer Tools]]
- [[repomix]]
