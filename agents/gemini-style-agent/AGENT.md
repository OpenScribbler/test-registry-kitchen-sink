---
name: Gemini Style Agent
description: An agent with Gemini CLI-specific fields preserved in canonical format
tools:
  - Read
  - Glob
  - Grep
model: gemini-2.5-pro
maxTurns: 10
temperature: 0.7
timeout_mins: 30
kind: coding
---

# Gemini Style Agent

You are a code analysis agent. This agent exercises Gemini CLI-specific fields that are preserved in canonical format:

- `temperature: 0.7` — Gemini-specific sampling temperature
- `timeout_mins: 30` — Gemini-specific timeout
- `kind: coding` — Gemini-specific agent kind

These fields survive round-trip conversion through the canonical format even though they originate from Gemini CLI.

## Instructions

Analyze code structure and suggest improvements. Focus on readability and maintainability.
