# PMX Context Frame Example

This is a minimal example of a personal context stack for one product manager.

It is a lightweight repo for keeping PM context in a shape that coding agents can read, update, and reason from.

This is a wiki example, not a plugin distribution. It requires no plugin, MCP
server, package install, or scheduler. The bracketed content is a template, not
verified product knowledge. Replace it with your own context and sources.

## Quick Start

1. Clone or copy this repo.
2. Replace the example pages in `wiki/` with your own product context.
3. Put unprocessed notes, exports, and pasted threads in `inbox/`.
4. Move useful source material into `raw/`.
5. Ask your coding agent to use the dedicated skill:

```text
Use the PM context stack skill. Read the repo and help me run a weekly context review.
```

## How To Use It

Start an agent session by asking it to read:

1. `AGENTS.md`
2. `.agents/skills/pm-context-stack/SKILL.md`
3. `wiki/index.md`
4. the newest relevant dated entries in `wiki/log.md`, not the whole history
5. the relevant wiki page and its supporting sources

Keep first reads bounded to the relevant section. If a search index is used,
treat snippets as leads and inspect the current file before making claims.
Do not keep querying a confirmed empty, foreign, or stale retrieval route.

Then ask for the work you need:

```text
Use the PM context stack skill. Prepare a stakeholder update from the current OKRs, roadmap, decision log, and open assumptions.
```

```text
Use the PM context stack skill. Review the context stack and surface cross-stream opportunities for next quarter.
```

```text
Use the PM context stack skill. Turn the notes in inbox into durable wiki updates and a short weekly review.
```

## How It Works

The repo has four simple layers:

- a maintained wiki-style context stack in `wiki/`
- raw source captures in `raw/`
- an intake folder in `inbox/`
- generated working outputs in `artifacts/`

One dedicated Markdown instruction skill lives in `.agents/skills/pm-context-stack/`.

The wiki is the maintained memory. Raw files are provenance. Inbox is intake. Artifacts are outputs.

Agents should start from the wiki, not the raw files. Raw files are there to verify where claims came from or to add detail when needed.

## Repo Shape

```text
AGENTS.md
README.md
wiki/
  index.md
  log.md
  wiki-system.md
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

## How To Modify It

Start with the minimum useful stack:

- `wiki/product-brief.md`
- `wiki/okrs.md`
- `wiki/roadmap.md`
- `wiki/team-structure.md`
- `wiki/stakeholder-map.md`
- `wiki/decision-log.md`

Then add only what you need:

- add assumptions under `wiki/assumptions/`
- add larger decisions under `wiki/decisions/`
- add recurring workflows under `wiki/workflows/`
- add raw source folders for the tools you actually use
- update `.agents/skills/pm-context-stack/SKILL.md` when your recurring workflows change

Keep one durable object in one place. Link related pages with `[[wikilinks]]`.

## Maintenance Rule

Keep the wiki current enough that an agent can reason from it. Keep the raw files available enough that an agent can check where claims came from.

Follow [the wiki operating guidance](wiki/wiki-system.md) for evidence, owners,
review triggers, conflicts, and historical context. A file edit or rebuilt
search index does not validate a claim. Unknown ownership and missing evidence
stay explicit; old knowledge is reviewed, not automatically deleted.

For a review without changes, ask:

```text
Audit this wiki for evidence, ownership, stale current-context pointers, and
broken links. Do not edit files or reset review dates. Report proposed repairs.
```

Weekly review is a suggested practice, not an installed automation. Configure
any schedule separately in your own tool, with explicit permissions. Copying
this repository does not schedule work or authorize publication.

The folder is the product memory. The artifacts are downstream.
