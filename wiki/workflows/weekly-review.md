# Workflow: Weekly Context Review

## Purpose

Define the recurring weekly review context for keeping the stack current enough that an agent can reason from it.

This page is durable operating context, not the agent runbook. Agent execution rules live in `.agents/skills/pm-context-stack/SKILL.md`.

## Inputs

- `wiki/okrs.md`
- `wiki/roadmap.md`
- `wiki/decision-log.md`
- `wiki/assumptions/`
- new material in `inbox/`
- new source captures in `raw/`

## Context Rules

- Treat new `inbox/` and `raw/` material as source material, not durable context.
- Update the smallest relevant wiki page when new durable context is found.
- Add or revise decisions and assumptions before changing roadmap or OKR text.
- Append the context delta to `wiki/log.md` after meaningful changes.
- Draft generated weekly outputs in `artifacts/` when a file output is needed.

## Output

A short weekly context delta:

- what changed
- what matters
- what needs a decision
- what should be communicated
