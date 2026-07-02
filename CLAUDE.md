# CLAUDE.md - pensobot

## What this repo is

Pensobot agent identity - runtime-agnostic. Deployed via [pensoai sync-context.sh](https://github.com/0pens0/pensoai/blob/main/scripts/sync-context.sh).

```
SOUL.md      → Persona, voice, invariants (keep lean)
AGENTS.md    → Operations, security, memory contract, decision patterns
IDENTITY.md  → OpenClaw identity record (name, emoji)
```

User facts: pensoai USER.md only.

## Editing rules

- Persona/tone → SOUL.md
- Rules, if/then patterns, memory contract → AGENTS.md
- Oren's job, infra, expenses → pensoai USER.md or vault/
- British English; no em dashes; security rules non-negotiable in AGENTS.md

## After edits

Run sync from pensoai: `./scripts/sync-context.sh <runtime>`

Smoke test: ask agent to summarise itself in two sentences.
