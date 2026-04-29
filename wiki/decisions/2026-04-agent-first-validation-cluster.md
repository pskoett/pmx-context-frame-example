# Decision: Agent-First Validation Cluster

## Date

2026-04-29

## Status

Proposed.

## Decision

Use vibe-coded internal apps as the first validation class for the agent-first self-service platform experience.

## Context

The DX stream needs a practical AI adoption workflow. The Platform stream needs a safe proving ground for self-service workload setup. Vibe-coded apps are useful because they are real enough to expose platform friction but usually lower-risk than production workloads.

## Options Considered

- Keep DX AI adoption and platform validation as separate roadmap items.
- Validate self-service only with production-bound workloads.
- Use vibe-coded apps as the bridge between AI adoption and platform validation.

## Reasoning

The bridge option gives both streams evidence from the same investment. DX can measure whether agents help developers complete real delivery workflows. Platform can observe where the self-service path fails before production workloads depend on it.

## Expected Consequences

- A clearer shared story for stakeholders.
- Faster feedback on the self-service path.
- Need for explicit guardrails so prototype apps do not become unmanaged production systems.

## Review Trigger

Review after the first 10 pilot apps or after the first security escalation, whichever comes first.

## Sources

- `raw/slack/2026-04-22-ai-platform-overlap.md`
- `raw/tickets/2026-q2-agent-first-platform-validation.md`
