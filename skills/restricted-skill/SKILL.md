---
name: Restricted Skill
description: A skill with disallowed tools to test restriction handling
disallowed-tools:
  - Bash
  - Write
  - Edit
disable-model-invocation: true
---

# Restricted Skill

This skill tests the `disallowed-tools` and `disable-model-invocation` fields. It should only be able to read and search, never execute commands or modify files.

## Instructions

Analyze the codebase using read-only tools. Report findings but never make changes.
