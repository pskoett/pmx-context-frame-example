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
- Follow [[wiki-system]] for authority, evidence dates, accountable owners and review triggers.
- Review overdue or missing evidence as uncertainty, not proof a claim is false.
- Revalidate observed ownership handoffs and known dependent claims before relying on them.
- Preserve sources, original dates and unresolved checks; no edit or index rebuild proves freshness.
- Distinguish audit-only proposals from authorized repairs. Weekly cadence here is guidance, not an installed schedule.

## Output

A short weekly context delta:

- what changed
- what matters
- what needs a decision
- what should be communicated
- what was actually checked, what remains unresolved, and which reviews need an accountable owner
