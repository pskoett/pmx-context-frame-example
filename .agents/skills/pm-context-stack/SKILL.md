# PM Context Stack Skill

Use this skill when asked to work from this PM context stack, prepare stakeholder updates, run weekly reviews, inspect roadmap or OKR alignment, synthesize decisions, or find cross-stream opportunities.

## Operating Principle

The context stack is the source of truth. Artifacts are generated from it.

Do not begin by drafting. First load the relevant context, then decide what output is needed.

## Read Order

1. Read `AGENTS.md`.
2. Read `wiki/index.md`.
3. Read `wiki/log.md`.
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
2. Pull the relevant wiki pages.
3. Check linked decisions, assumptions, and raw sources.
4. Separate facts, assumptions, risks, and recommendations.
5. Produce the requested output.
6. If the context stack changed, update the smallest relevant wiki page and append to `wiki/log.md`.

## Decision Support

When asked to recommend a path:

- state the current context
- identify the decision to make
- list options
- compare tradeoffs
- name the assumptions each option depends on
- recommend the next reversible step

## Stakeholder Updates

When preparing an update:

- read `wiki/stakeholder-map.md`
- tailor the update to that stakeholder's needs and concerns
- include only relevant OKRs, roadmap items, decisions, and risks
- make asks explicit
- save drafts under `artifacts/` if asked to create a file

## Weekly Review

When running a weekly review:

- scan `inbox/`
- scan recent raw captures
- update wiki pages for durable changes
- update assumptions or decisions before updating roadmap text
- append the context delta to `wiki/log.md`

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
