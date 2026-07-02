<div align="center">

# Pensobot

### *Agent Soul*

**Long-lasting agent identity for Pensobot - personality, rules, tone, behaviours.**

[![Canonical](https://img.shields.io/badge/Canonical-SOUL.md-8B5CF6?style=flat-square)](SOUL.md)
[![User context](https://img.shields.io/badge/User-pensoai%20USER.md-10B981?style=flat-square)](https://github.com/0pens0/pensoai)

---

</div>

## What is this?

**One file. One source of truth about the agent.**

| Repo | File | Purpose |
|------|------|---------|
| **pensobot** (this repo) | `SOUL.md` | Agent personality, rules, tone, behaviours |
| **pensoai** | `USER.md` | Oren's identity, context, preferences, infrastructure |

Hermes loads **SOUL.md** first (who the agent is), then **USER.md** (who Oren is).

---

## Load order

1. **`SOUL.md`** - agent identity and non-negotiable rules
2. [pensoai/USER.md](https://github.com/0pens0/pensoai/blob/main/USER.md) - user context

### Context hierarchy

1. Explicit approval (`/approve` or "yes, do it")
2. **SOUL.md** - agent rules
3. **USER.md** - Oren's context
4. Common sense

---

## Updating

Everything about the agent goes in **`SOUL.md`**. Update `last_updated` in the frontmatter when you change rules or tone.

Oren's facts, preferences, infrastructure → [pensoai](https://github.com/0pens0/pensoai).

---

<div align="center">

**[SOUL.md](SOUL.md) · [pensoai](https://github.com/0pens0/pensoai) · [penso.io](https://penso.io)**

*Agent in one file. User in another. Long-lasting context.*

</div>
