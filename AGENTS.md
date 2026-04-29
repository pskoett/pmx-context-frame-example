# Agent Instructions

This repo is a personal PM context stack with wiki logic built in.

Use `.agents/skills/pm-context-stack/SKILL.md` for recurring PM workflows against this repo.

## Read Order

1. `wiki/index.md`
2. `wiki/log.md`
3. the relevant wiki page for the task
4. the raw source files linked from that wiki page
5. `inbox/` only when triaging new material
6. `artifacts/` only when creating or revising outputs

## Update Rules

- Keep durable context in `wiki/`.
- Keep raw exports, pasted threads, ticket summaries, and source notes in `raw/`.
- Keep unprocessed captures in `inbox/`.
- Keep generated deliverables and drafts in `artifacts/`.
- Prefer updating an existing wiki page over creating a duplicate.
- Use `[[wikilinks]]` when one durable context object depends on another.
- Add source references when wiki content depends on raw material.
- Append a short dated note to `wiki/log.md` after meaningful context changes.

## Wiki Logic

Each durable object should have one home.

- Product direction lives in `wiki/product-brief.md`.
- Goals live in `wiki/okrs.md`.
- Sequencing lives in `wiki/roadmap.md`.
- People and ownership live in `wiki/team-structure.md` and `wiki/stakeholder-map.md`.
- Decisions live in `wiki/decision-log.md` and detailed pages under `wiki/decisions/`.
- Assumptions live under `wiki/assumptions/`.
- Recurring operating workflows live under `wiki/workflows/`.

If a page changes because of new source material, record the source path on that page.
