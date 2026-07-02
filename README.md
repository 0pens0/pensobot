<div align="center">

# Pensobot

### *Agent Soul*

**Long-lasting agent identity - runtime-agnostic via pensoai context manifest.**

[![SOUL](https://img.shields.io/badge/Canonical-SOUL.md-8B5CF6?style=flat-square)](SOUL.md)
[![Deploy](https://img.shields.io/badge/Sync-pensoai%20manifest-3B82F6?style=flat-square)](https://github.com/0pens0/pensoai/blob/main/context.manifest.yaml)

---

</div>

## What is this?

| File | Purpose | Load |
|------|---------|------|
| `SOUL.md` | Persona, voice, values | Always |
| `AGENTS.md` | Rules, decision patterns, memory contract | Always |
| `IDENTITY.md` | Name, emoji (OpenClaw) | Always |

User context: **[pensoai USER.md](https://github.com/0pens0/pensoai/blob/main/USER.md)**

## Deploy

From pensoai repo (no duplicate config per agent):

```bash
cd ~/git/pensoai && ./scripts/sync-context.sh openclaw
```

## Split

- **SOUL.md** - who the agent *is* (persona only)
- **AGENTS.md** - how the agent *operates* (rules, memory)
- **USER.md** (pensoai) - who Oren *is*

---

<div align="center">

**[SOUL.md](SOUL.md) · [pensoai](https://github.com/0pens0/pensoai)**

</div>
