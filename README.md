<div align="center">

# 🤖 PensoBot

### *My AI Business Card*

**A compact, agent-friendly representation of who I am, how I work, and the context I want AI systems to use when collaborating with me.**

[![AI-ready](https://img.shields.io/badge/AI--ready-ground%20truth-8B5CF6?style=flat-square)](.)
[![Human-readable](https://img.shields.io/badge/Human--readable-Markdown-10B981?style=flat-square)](.)
[![Machine-parseable](https://img.shields.io/badge/Machine--parseable-YAML%20%7C%20MD-3B82F6?style=flat-square)](.)

---

</div>

## ✨ What is this?

Think of it as **a persistent “me” that any assistant, copilot, or autonomous agent can load** — so I don’t have to repeat myself and the AI has a single source of truth for:

| 🎯 | **Identity** — who I am, what I believe, how I show up |
|----|--------------------------------------------------------|
| 📋 | **Preferences** — how I like answers (punchline first, structured, British English, security by default) |
| 🔗 | **Context** — timezone, role, links, tools, working style (machine-readable) |
| 🏢 | **Domains** — work context, typical requests, success criteria, patterns I like |

So when I say *“use my repo”*, the agent gets **facts + tone + guardrails** in one go.

---

## 📁 Repository layout

| Path | Purpose |
|------|--------|
| `profile/about.md` | Narrative: who I am and what I care about |
| `profile/preferences.md` | How I like to work with AI (style, depth, formats, guardrails) |
| `profile/context.yaml` | Structured facts for tools/agents (timezone, roles, links, defaults) |
| `domains/work.md` | Work context: typical tasks, deliverables, success criteria |
| `domains/_template.md` | Template for new domains (hobbies, learning, etc.) |

---

## 🤖 How to use (for AI agents)

When you start a new collaboration, ingest in this order:

1. **`profile/context.yaml`** — facts + defaults  
2. **`profile/preferences.md`** — interaction contract  
3. **`profile/about.md`** — tone + narrative  
4. **Relevant domain files** in `domains/`

### 💡 System prompt snippet

> Use this repo as the source of truth for user context and preferences.  
> Follow the constraints in `profile/preferences.md`.  
> If conflicts exist: **context.yaml** > **preferences.md** > **domains/\*** > **about.md**.

---

## 🔄 Updating this repo

| Update type | Put it here |
|-------------|--------------|
| **Facts** (title, timezone, links, tools) | `profile/context.yaml` |
| **Narrative** (who you are, what you believe) | `profile/about.md` |
| **How you want AI to behave** | `profile/preferences.md` |
| **New life/work area** | New file in `domains/` using `_template.md` |

*Tip: set `last_updated` in `profile/context.yaml` when you change facts, so agents can judge freshness.*

---

## 🔒 Privacy

This repo represents me in a way I’m comfortable sharing. I don’t store IDs, account numbers, addresses, private medical details, or anything that could be used for social engineering.

---

<div align="center">

**📌 [penso.io](https://penso.io) · [LinkedIn](https://www.linkedin.com/in/openso/) · [X](https://twitter.com/openso)**

*One repo. One source of truth. Better AI collaboration.*

</div>
