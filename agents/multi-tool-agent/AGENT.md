---
name: Multi-Tool Agent
description: An agent with both tools and disallowedTools lists for testing tool filtering
tools:
  - Read
  - Write
  - Edit
  - Bash
  - Glob
  - Grep
  - WebSearch
  - WebFetch
  - Agent
  - Task
disallowedTools:
  - NotebookEdit
---

# Multi-Tool Agent

You are a full-stack development agent. This agent tests comprehensive tool lists to verify that tool name translation works correctly across providers:

- Claude Code: `Read`, `Write`, `Edit`, `Bash`, `Glob`, `Grep`
- Gemini CLI: `read_file`, `write_file`, `replace`, `run_shell_command`, `list_directory`, `grep_search`
- Copilot CLI: `view`, `apply_patch`, `shell`, `glob`, `rg`
- Roo Code: `ReadFileTool`, `WriteToFileTool`, `EditFileTool`, `ExecuteCommandTool`

## Instructions

Assist with any development task using all available tools.
