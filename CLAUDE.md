# CLAUDE.md - pensobot

> Agent instructions for Claude Code working in this repository.
> Keep this file lean. Document what Claude gets wrong, not what it already does right.

---

## What this repo is

**pensobot** is the soul of Oren's Hermes personal AI agent - personality, rules, tone, and operational guardrails. It is not a code project; it is an agent identity artefact.

**User context** (who Oren is, infrastructure, preferences, expenses) lives in **[pensoai](https://github.com/0pens0/pensoai)**. Do not duplicate user facts here.

```
SOUL.md    → Agent identity, rules, tone, behaviours, example interactions
```

---

## Editing rules

**British English throughout.** Use British spellings in all prose.

**Short dashes, not em dashes.** Use ` - ` (hyphen with spaces) not em dashes in all prose.

**Punchline first.** Lead with the conclusion or key fact.

**No AI-sounding filler.** Write like a thoughtful senior engineer.

**Agent rules stay here; user facts stay in pensoai.** If you're about to add Oren's job title, infrastructure details, or expense workflows - put them in pensoai instead.

---

## Structure rules

**Do not add new top-level directories** without explicit instruction.

**Do not rename SOUL.md.** Hermes and agent consumers reference it by path.

**`.gitignore` is not to be modified** unless asked.

---

## Content rules

**SOUL.md is the canonical agent file.** Keep frontmatter (`name`, `version`, `last_updated`) current when making substantive changes.

**Security rules are non-negotiable.** Do not soften, remove, or add exceptions to destructive-op approval, credential handling, or allowlist rules without explicit instruction from Oren.

**Example interactions** in SOUL.md should demonstrate rule enforcement, not shortcuts.

---

## What Claude gets wrong here

- Adding Oren-specific facts to SOUL.md instead of pensoai.
- Writing em dashes instead of hyphens.
- Softening security rules or adding "unless urgent" exceptions.
- Duplicating content from pensoai profile files.

---

## How to find user context

- [pensoai](https://github.com/0pens0/pensoai) - `profile/context.yaml`, `profile/preferences.md`, `USER.md`, `domains/*`

Do not infer user facts. If something belongs in pensoai, add it there.

---

## Commit hygiene

Commit messages use the imperative form: `Update SOUL.md expense workflow reference` not `Updated...`.

Do not commit secrets, tokens, or credentials under any circumstances.
