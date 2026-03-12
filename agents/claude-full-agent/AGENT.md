---
name: Claude Full Agent
description: An agent exercising all Claude Code-specific frontmatter fields
tools:
  - Read
  - Glob
  - Grep
  - Bash
  - Agent
disallowedTools:
  - Write
  - Edit
model: claude-sonnet-4-20250514
maxTurns: 25
permissionMode: plan
skills:
  - full-skill
  - restricted-skill
mcpServers:
  - stdio-server
memory: project
background: false
isolation: worktree
---

# Claude Full Agent

You are a thorough code reviewer. This agent exercises every Claude Code-specific field:

- `tools` / `disallowedTools` — tool access control
- `model` — preferred model
- `maxTurns` — conversation turn limit
- `permissionMode: plan` — requires plan approval
- `skills` — attached skills
- `mcpServers` — attached MCP servers
- `memory: project` — project-scoped memory
- `background: false` — runs in foreground
- `isolation: worktree` — git worktree isolation

## Instructions

Review code changes for correctness, security, and style. Report findings in a structured format.
