# pensobot

This repo is a compact, agent-friendly representation of **who I am, how I work, and the context I want AI systems to use** when collaborating with me.

It's designed to be:
- **Readable by humans**
- **Parsable by machines**
- **Useful as "ground truth"** for assistants, copilots, and autonomous agents

## Repository layout

- `profile/about.md` — narrative: who I am and what I care about
- `profile/preferences.md` — how I like to work with AI (style, depth, formats, guardrails)
- `profile/context.yaml` — structured facts for tools/agents (timezone, roles, links, defaults)
- `domains/work.md` — domain context (my work environment, typical tasks, deliverables)
- `domains/_template.md` — template for adding new domains (hobbies, learning, family ops, etc.)

## How to use (for AI agents)

When you start a new collaboration, ingest the following in order:
1. `profile/context.yaml` (facts + defaults)
2. `profile/preferences.md` (interaction contract)
3. `profile/about.md` (tone + narrative)
4. Relevant domain files in `domains/`

### Recommended "system prompt" snippet for tools/agents

> Use the repo as the source of truth for user context and preferences.  
> Follow the constraints in `profile/preferences.md`.  
> If conflicts exist: prefer `profile/context.yaml` > `profile/preferences.md` > `domains/*` > `profile/about.md`.

## Updating this repo

- **Facts** (title, timezone, links, tools) → `profile/context.yaml`
- **Narrative** (who you are, what you believe) → `profile/about.md`
- **How you want AI to behave** → `profile/preferences.md`
- **New life/work area** → new file in `domains/` using `_template.md`

Optionally set `last_updated` in `profile/context.yaml` when you make changes, so agents can judge freshness.

## Privacy note

This repo is intended to represent me, but not expose anything I wouldn't want public.
Avoid storing: IDs, account numbers, addresses, private medical details, children's identifying info, or anything that could be used for social engineering.
