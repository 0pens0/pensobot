# Domain: Work

This file captures the working context I most often need AI help with.

## Role snapshot

I operate as a senior technical leader who supports:
- platform engineering strategy and adoption
- enterprise architecture decisions
- hands-on prototypes and reference implementations
- AI platform enablement with guardrails

## Typical requests I give AI

### Architecture & strategy
- Compare platform approaches (Kubernetes vs PaaS, build pipelines, runtime patterns)
- Create decision frameworks and tradeoff tables
- Produce reference architectures (including security boundaries)

### Enablement & delivery
- Workshop agendas, scripts, narratives for exec + developer audiences
- Runbooks for deployments (especially complex infra)
- Templates: Terraform modules, YAML manifests, automation scripts

### Troubleshooting
- Debugging steps that are safe, incremental, and verifiable
- Root-cause hypotheses with tests to validate/falsify
- Recovery/rollback plans

## My success criteria

- The output should be immediately usable.
- It should anticipate real-world constraints: IAM, DNS, certificates, change control, audit requirements.
- It should include "how to verify" and "how to undo".

## Tone and positioning

When writing for customers or public content:
- keep it crisp and credible
- avoid vendor theatre
- use simple language and concrete examples
- emphasise developer experience + operational reality

## Default assumptions (unless I say otherwise)

- Enterprise context: change control, audit, IAM, and operational constraints apply unless I specify otherwise.
- Platform context: Tanzu / VCF / Kubernetes unless I point at something else.
- Timezone and locale: Europe/London, British English (already in `profile/context.yaml`).

## Common patterns I like

- "Three options + recommendation"
- "Checklist + command blocks"
- "Diagram description + components + trust boundaries"
- "If X fails, do Y" fallback paths
