# Product Brief

## Name

Agent-first platform experience for vibe-coded apps.

## Problem

The organization is adopting AI tools faster than its platform experience can absorb.

Developers can create software with agents, but the path from agent-generated code to a running internal workload is still shaped around humans manually navigating docs, CLIs, tickets, and tribal knowledge.

At the same time, the platform team needs a practical validation environment for the new self-service deployment stack before production workloads depend on it.

## Product Thesis

Use vibe-coded apps as the first workload class for an agent-first self-service platform experience.

This creates one investment with two outcomes:

- Developer Experience gets a concrete AI adoption workflow beyond tooling rollout.
- Platform Engineering gets a lower-risk proving ground for self-service workload setup.

## Users

- Internal developers building small tools, prototypes, and operational apps with AI agents.
- Platform engineers validating golden paths and self-service deployment flows.
- DX enablement leads measuring practical AI proficiency.

## Non-Goals

- Replacing production platform migration work.
- Treating vibe-coded apps as automatically production-grade.
- Letting agents bypass security, ownership, observability, or compliance requirements.

## Success Signals

- A developer can move from agent-generated app to deployed internal workload without opening a platform ticket.
- The agent-facing setup path produces the same required metadata as the human-facing path.
- Platform rough edges are found before production workloads depend on the new stack.
- AI adoption reporting shifts from tool access to completed workflows.

## Related Context

- [[okrs]]
- [[roadmap]]
- [[assumptions/agent-first-platform-experience]]
- [[decisions/2026-04-agent-first-validation-cluster]]

## Sources

- `raw/docs/2026-04-weekly-context-dump.md`
- `raw/slack/2026-04-22-ai-platform-overlap.md`
- `raw/tickets/2026-q2-agent-first-platform-validation.md`
