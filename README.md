<div align="center">

# Pensobot

### *Hermes Agent Soul*

**The personality, rules, and operational identity of Pensobot - Oren's personal AI agent running on Hermes.**

[![Agent soul](https://img.shields.io/badge/Agent-soul%20%26%20rules-8B5CF6?style=flat-square)](.)
[![Hermes](https://img.shields.io/badge/Runtime-Hermes-10B981?style=flat-square)](.)

---

</div>

## What is this?

**Pensobot** is the soul of Oren's personal AI agent - not a chatbot personality, but a thinking partner with guardrails.

This repo holds:

| | |
|---|---|
| **Identity** | Who Pensobot is and what it's for |
| **Rules** | Security, access, operational safety (non-negotiable) |
| **Tone** | How Pensobot communicates |
| **Behaviours** | Default responses, escalation, example interactions |

**User context** (who Oren is, his infrastructure, preferences, expenses) lives in **[pensoai](https://github.com/0pens0/pensoai)**.

---

## Repository layout

| Path | Purpose |
|------|--------|
| `SOUL.md` | Agent identity, rules, tone, behaviours - load this first |
| `CLAUDE.md` | Instructions for editing this repo |

---

## How Hermes loads Pensobot

1. **`SOUL.md`** - agent personality and non-negotiable rules
2. **[pensoai](https://github.com/0pens0/pensoai)** - user context (`context.yaml`, `preferences.md`, `USER.md`, `domains/*`)

### Context hierarchy

1. Explicit approval (`/approve` or "yes, do it")
2. **SOUL.md** (this repo)
3. **pensoai** user context
4. Common sense

---

## Updating this repo

| Update type | Put it here |
|-------------|-------------|
| **Agent rules, security, tone** | `SOUL.md` |
| **Oren's facts, preferences, infrastructure** | [pensoai](https://github.com/0pens0/pensoai) |

Do not put user-specific facts in this repo. Keep the split clean: **pensobot = agent**, **pensoai = user**.

---

<div align="center">

**[pensoai](https://github.com/0pens0/pensoai) · [penso.io](https://penso.io)**

*Agent soul. User identity. Clear separation.*

</div>
