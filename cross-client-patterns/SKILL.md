---
name: cross-client-patterns
description: Find problems that repeat across several clients and propose shared solutions, working only from approved needs briefs and triage files in the portfolio folder. Use when two or more clients have an approved needs brief and triage, or when asked what problems cut across clients, what general solution could serve several SMEs, or what to build once and reuse.
---

# Cross-client patterns

Look across clients to find problems worth solving once for many. Follow the `house-rules` skill throughout, with the exceptions below.

## What you may read

Only the `portfolio/` folder. It holds copies of each client's approved files, named `<client>-needs-brief.md` and `<client>-triage.md`. Never open raw intake forms or transcripts, and never look in any client's own folder. If a pattern needs detail that is not in these files, list it under "Needs checking in the client's own folder" for a human to follow up.

## Method

1. List every need from every triage file, one line each, tagged with its client.
2. Group needs that share a **root cause**, not just a similar-sounding symptom. "Lost orders" at a shop with no order record and "lost orders" at a shop whose staff skip the record are different problems. Keep them apart.
3. A pattern needs at least two clients. A need that appears in only one client stays in that client's own plan.
4. For each pattern, say how many clients it affects out of how many were reviewed. With fewer than three clients, call every pattern tentative.
5. For each pattern, propose a shared solution only if it would suit each affected client's budget, skills, and connectivity. Say which parts can be built once and which must be customised per client.
6. Mark every inference as `(inference)`. Never merge two needs by guessing they are the same.

## Output

Write `portfolio/patterns.md`:

**Clients reviewed:** the list, and how many.

| Pattern | Clients affected | Root cause | Evidence | Shared solution | Build once vs customise | Effort |
|---|---|---|---|---|---|---|

Evidence cites files like `[acme-triage: need 3]`.

Then add:
- **Best candidates to build once:** at most three, each with a one-line reason.
- **Needs unique to one client:** a short list, so nothing is lost.
- **Needs checking in the client's own folder:** anything you could not settle from the portfolio files.

This file names clients, so it is internal. Do not copy it anywhere that clients can see.
