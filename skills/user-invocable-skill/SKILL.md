---
name: User Invocable Skill
description: A skill that users can invoke directly via slash command
user-invocable: true
argument-hint: <target-file> [--verbose]
---

# User Invocable Skill

This skill tests the `user-invocable` and `argument-hint` frontmatter fields. When a skill is user-invocable, it appears as a slash command in the UI.

## Usage

```
/user-invocable-skill src/main.go --verbose
```

Analyze the specified target file and report findings.
