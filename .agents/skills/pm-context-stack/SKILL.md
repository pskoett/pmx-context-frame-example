---
name: pm-context-stack
description: Maintain or review a personal Markdown context wiki, synthesize sources, prepare stakeholder updates, and inspect goal, roadmap, decision or assumption alignment. Use the repository's wiki guidance without requiring plugins, integrations, or a scheduler.
---

# PM Context Stack Skill

Use this skill when asked to work from this PM context stack, prepare stakeholder updates, run weekly reviews, inspect roadmap or OKR alignment, synthesize decisions, or find cross-stream opportunities.

## Operating Principle

The context stack is the maintained knowledge home. Verify claims against
their actual authority; neither the wiki nor a generated artifact is independent
proof. Follow `wiki/wiki-system.md` for evidence, owners, and review triggers.

Do not begin by drafting. First load the relevant context, then decide what output is needed.

## Read Order

1. Read `AGENTS.md`.
2. Read `wiki/index.md`.
3. Read the newest relevant dated entries in `wiki/log.md` with bounded sections.
4. Read the specific wiki pages related to the task.
5. Read raw sources only when claims need verification or more detail.

## Core Workflow

1. Identify the user request type:
   - context review
   - stakeholder update
   - OKR or roadmap review
   - decision support
   - assumption testing
   - artifact drafting
2. Establish whether the request is audit-only, authorized maintenance, or drafting. Audit-only work does not edit files.
3. Read relevant current wiki files. Check the workspace/scope of any search tool, and stop using a confirmed foreign, empty, or stale route. Snippets are leads, not evidence.
4. Check linked decisions, assumptions, and sources, including authority, actual source/check dates and accountable owners. Unknown ownership or unavailable evidence stays explicit.
5. Separate facts, assumptions, historical observations, proposals, decisions, risks, and recommendations. New suggestions do not supersede accepted decisions without authority.
6. Produce the requested output and name important evidence or access gaps.
7. For authorized changes, update only the smallest relevant wiki page. Preserve sources and prior validation evidence; update review dates only for claims actually checked.
8. Update the index for structural changes and append a meaningful dated log entry once. Repeat ingests should not duplicate objects, claims, or logs.

## Decision Support

When asked to recommend a path:

- state the current context
- identify the decision to make
- list options
- compare tradeoffs
- name the assumptions each option depends on
- recommend the next reversible step
- use stable current-context pointers rather than copied cycle names or old confidence values

## Stakeholder Updates

When preparing an update:

- read `wiki/stakeholder-map.md`
- tailor the update to that stakeholder's needs and concerns
- include only relevant OKRs, roadmap items, decisions, and risks
- distinguish verified outcomes from targets, unset metrics, and historical baselines
- make asks explicit
- save drafts under `artifacts/` if asked to create a file

## Weekly Review

When running a weekly review:

- inspect the relevant intake, sources, and due or unresolved evidence
- check known ownership changes and specific dependent claims, not only page age
- distinguish audit findings from authorized source-backed repairs
- preserve raw captures in place unless movement or archiving is explicitly requested
- leave partial or unavailable-source checks unresolved without resetting dates
- update wiki pages for durable changes only within authorized scope
- update assumptions or decisions before updating roadmap text
- append the context delta to `wiki/log.md`
- do not install tools, create schedules, publish, commit, or push as a side effect; weekly automation is a separate, consent-based setup

## Output Quality

Outputs should be concise, grounded in the wiki, and explicit about uncertainty.

Use this structure when useful:

```text
Context:
What changed:
Why it matters:
Risks or assumptions:
Recommendation:
Next action:
Sources:
```
