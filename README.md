# test-registry-kitchen-sink

Comprehensive test registry for syllago. Exercises all 7 content types, all 11 providers, and all provider-specific metadata fields.

## Contents

| Type | Items | Description |
|------|-------|-------------|
| Skills | 4 | Minimal, full frontmatter, user-invocable, restricted |
| Agents | 4 | Minimal, Claude-specific, Gemini-specific, multi-tool |
| MCP | 3 | stdio+autoApprove, HTTP+headers, Gemini trust/filtering |
| Rules | 11 | One per provider (all 11 providers) |
| Hooks | 4 | One per provider that supports hooks |
| Commands | 5 | One per provider that supports commands |
| Loadouts | 1 | References items from this registry |

**Total: 32 items**

## Purpose

Used for automated testing of syllago's registry scanning, catalog discovery, and provider-specific metadata handling. Not intended for production use.
