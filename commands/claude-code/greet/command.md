---
name: greet
description: A test command that greets the user
allowed-tools:
  - Read
  - Bash
user-invocable: true
argument-hint: <name> [--formal]
---

# /greet Command

Greet the user by name.

## Usage

```
/greet $ARGUMENTS
```

If `--formal` is specified, use a formal greeting. Otherwise, be casual.
