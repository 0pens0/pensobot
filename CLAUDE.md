# CLAUDE.md - pensobot

> Agent instructions for Claude Code working in this repository.

---

## What this repo is

**pensobot** is the soul of Oren's Hermes personal AI agent - one canonical file, **`SOUL.md`**.

User identity and context lives in **[pensoai USER.md](https://github.com/0pens0/pensoai/blob/main/USER.md)**. Do not duplicate user facts here.

```
SOUL.md    → Agent identity, rules, tone, behaviours, example interactions
```

---

## Editing rules

**Everything about the agent goes in SOUL.md.** Do not create subdirectories or split files unless Oren explicitly asks.

**British English.** Short dashes (` - `), not em dashes. Punchline first. No AI filler.

**Update frontmatter** (`version`, `last_updated`) when making substantive changes.

**Security rules are non-negotiable.** Do not soften destructive-op approval, credential handling, or allowlist rules without explicit instruction.

**User facts stay in pensoai.** Job title, infrastructure, expense workflows → USER.md.

---

## What Claude gets wrong here

- Adding Oren-specific facts to SOUL.md instead of pensoai USER.md
- Creating extra files or directories when SOUL.md suffices
- Softening security rules or adding "unless urgent" exceptions

---

## Commit hygiene

Imperative commit messages. No secrets. One logical change per commit.
