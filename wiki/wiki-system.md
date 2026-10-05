# Wiki Operating Guidance

This page defines the basic maintenance contract for this wiki. It is guidance,
not an automated validator or a configured schedule.

## Layers and authority

- `wiki/` is the maintained home for reusable context.
- `raw/` preserves source material and provenance.
- `inbox/` holds unprocessed captures.
- `artifacts/` holds downstream drafts and outputs.

Keep one durable object in one home and link related objects. The wiki records
knowledge; it is not independent proof of its claims. A copied quote or generated
artifact is not new evidence. Identify the authoritative source and preserve
conflicts rather than silently choosing the newest timestamp.

## Evidence and accountable ownership

For important or time-sensitive claims, record enough to make the next check
actionable:

```text
Accountable owner: person or role, or unknown
Authority/source: specific path, URL, decision, or source identifier
Last validated: actual check date, or not yet checked
Evidence and scope: what was checked, including relevant source date/version
Next check: source-appropriate cadence or invalidating event
Unresolved: missing evidence, conflicting authority, or incomplete coverage
```

The accountable owner is not automatically the author or last editor. Do not
invent owners or dates. Template placeholders are not evidence.

An ownership change is a review trigger even if periodic review is not due.
Verify the handoff, record its evidence and affected claim scope, and flag known
downstream decisions or outputs relying on the previous owner's authority.
Link to the specific relied-on claim in the existing page. Preserve earlier
validation evidence and disclose unknown downstream coverage. A handoff does
not prove every dependent claim is wrong or authorize rewriting it.

## Why and when context needs review

Classify the reason separately from the cadence:

| Cause | Check |
| --- | --- |
| Reality changed | Re-read the authoritative source or retrieve live values |
| Decision changed | Find an applicable, authorized superseding decision |
| Dependency changed | Verify the relevant tool, model, schema, or process version |
| Relevance changed | Check usefulness in the current task and scope |

Fast-changing values are best checked at use. Medium-changing context needs a
source-appropriate review point; slow-changing guidance can be checked at
milestones. Durable context has no passive expiry but still needs review on
contradiction or an invalidating event. These are judgments, not universal
half-lives. Events override cadence; age alone proves neither falsity nor a
reason to delete knowledge.

Retain supported context, revise contradicted claims, externalize values better
retrieved from a maintained source, or retire superseded active guidance while
preserving history. If a check cannot establish an outcome, leave it unresolved.
An external pointer must say where and when to retrieve and what to do if the
source is unavailable.

## Current versus historical context

Keep the current focus compact in [[index]], with stable pointers to [[okrs]],
[[roadmap]], and relevant decisions. Do not copy changing cycle labels or live
metrics into agent instructions. Preserve historical dates and scope, and link
superseded decisions to their replacements. An unset metric, target, or initial
confidence value is not a measured outcome.

## Retrieval and maintenance

Read the relevant page and recent log section before deeper source captures.
If search is available, verify its workspace/scope and read current files, not
snippets alone. An empty or stale route is not a missing-document verdict.
After confirming a route is bad, stop using it for both discovery and reads.
Expand bounded reads through documented continuation or line ranges, keeping
history addressable rather than truncating it.

Audits report proposed repairs without changes. Authorized maintenance makes
the smallest source-supported update, preserves raw material and unresolved
checks, updates [[index]] only for structural changes, and adds one meaningful
dated entry to [[log]]. Do not refresh dates merely because a file was edited,
an index rebuilt, or a review attempted. Publication and scheduled execution
require separate permission; no automation is inherited from this example.
