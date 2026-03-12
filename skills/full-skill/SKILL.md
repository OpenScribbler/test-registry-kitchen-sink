---
name: Full Skill
description: A skill exercising every available frontmatter field
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
  - Glob
  - Grep
context: fork
agent: Explore
model: claude-sonnet-4-20250514
---

# Full Skill

This skill populates every Claude Code frontmatter field to test round-trip preservation:

- `allowed-tools` — restricts which tools the skill can use
- `context: fork` — runs in isolated context
- `agent` — specifies agent personality
- `model` — preferred model for execution

## Instructions

When invoked, analyze the codebase using only the allowed tools and provide a summary.
