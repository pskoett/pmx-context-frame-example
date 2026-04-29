# PMX Context Frame Example

This is a minimal example of a personal context stack for one product manager.

It combines the two ideas from the PMX context frame repos into one lightweight repo:

- a maintained wiki-style context stack in `wiki/`
- raw source captures in `raw/`
- an intake folder in `inbox/`
- generated working outputs in `artifacts/`
- one dedicated agent skill in `.agents/skills/pm-context-stack/`

There is no app, no CLI, and no required SaaS connection. The repo is the context.

## The Example Scenario

This repo models one PM working across two related streams:

- Developer Experience: AI proficiency, tooling rollout, and agent-first developer workflows.
- Platform Engineering: self-service workload setup, golden paths, and production platform foundations.

The central insight is the article's example: an agent-first platform experience for vibe-coded apps can serve two outcomes at once.

- It drives AI adoption through a real developer workflow.
- It validates the self-service platform stack in a low-risk environment before production workloads depend on it.

## How To Use It With An Agent

Start every session by asking the agent to read:

1. `AGENTS.md`
2. `.agents/skills/pm-context-stack/SKILL.md`
3. `wiki/index.md`
4. `wiki/log.md`

Then ask the agent for the work you need:

```text
Use the PM context stack skill. Prepare a stakeholder update for the Platform VP based on the current OKRs, roadmap, decision log, and open assumptions.
```

Or:

```text
Use the PM context stack skill. Review the context stack and surface cross-stream opportunities for next quarter.
```

## Repo Shape

```text
AGENTS.md
README.md
wiki/
  index.md
  log.md
  product-brief.md
  okrs.md
  roadmap.md
  team-structure.md
  stakeholder-map.md
  decision-log.md
  assumptions/
  decisions/
  workflows/
raw/
  docs/
  slack/
  tickets/
inbox/
artifacts/
.agents/
  skills/
    pm-context-stack/
      SKILL.md
```

## Maintenance Rule

Keep the wiki current enough that an agent can reason from it. Keep the raw files available enough that an agent can check where claims came from.

The folder is the product memory. The artifacts are downstream.
