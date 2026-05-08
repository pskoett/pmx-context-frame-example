# Workflow: Stakeholder Update

## Purpose

Describe the standing shape of stakeholder updates for this context stack.

This page is durable operating context, not the agent runbook. Agent execution rules live in `.agents/skills/pm-context-stack/SKILL.md`.

## Inputs

- [[product-brief]]
- [[okrs]]
- [[roadmap]]
- [[stakeholder-map]]
- [[decision-log]]

## Context Rules

- Tailor the update to the stakeholder's needs in [[stakeholder-map]].
- Include only relevant OKRs, roadmap items, assumptions, decisions, and risks.
- Separate facts from asks.
- Make tradeoffs explicit when requesting a decision or support.
- Save generated drafts in `artifacts/` when a file output is needed.

## Output Shape

```text
Subject:
Audience:
What changed:
Why it matters:
Decision or support needed:
Risks:
Next update:
```
