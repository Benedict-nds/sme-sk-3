---
name: solution-matching
description: Match each triaged need to a concrete solution we could build, configure, or recommend (CRM, chatbot, automation, simple tool, process change), and write the non-digital guidance for needs that are not software problems. Use when a client has an approved triage and no solutions file yet, or when asked what we could build or recommend for a client.
---

# Solution matching

Turn an approved triage into specific, realistic proposals. Follow the `house-rules` skill throughout.

## Inputs

That client's approved `work/needs-brief.md` and `work/triage.md`. If either is missing, stop and say so.

## Method

For each need in the triage:

1. **Digital now or digital later:** propose the simplest solution that solves the root cause. Name the type (for example CRM, chatbot, form and spreadsheet automation, booking or ordering page, invoicing or stock tool, dashboard) and say whether we would **build** it, **configure** an existing tool, or **recommend** one the client should buy.
2. Prefer the smallest thing that works. If a spreadsheet with a simple automation solves it, do not propose a platform.
3. Check fit against what the client's own files say about budget, staff skills, devices, connectivity, and tools they already use. Say what it rests on. If the files are silent, mark it "(inference)" and add the question to "Verify with client".
4. Give one alternative where a reasonable one exists.
5. **Non-digital help:** write practical guidance instead: the process, training, or policy change, in three to five concrete steps the owner could start this week. Do not force software here.
6. **Not realistic:** say why, and what the client could do instead.
7. Never invent features, tools, or integrations you are not sure exist. If unsure, say so.
8. Do not give prices or timelines. Costs and timelines are separate steps.

## Output

Write `work/solutions.md`:

| Need | Proposed solution | Type (build / configure / recommend) | Why it fits (evidence) | Client effort | Alternative | Risks |
|---|---|---|---|---|---|---|

Then add:
- **Non-digital guidance:** one short section per need, with the steps.
- **Not recommended:** needs we should not build for, with reasons.
- **Verify with client:** open questions that could change a proposal.
- **Reusable across clients? (inference):** one line per proposal saying whether the same solution might fit other clients. This helps the cross-client step; do not read other clients' files to answer it.

This is a draft for board approval.
