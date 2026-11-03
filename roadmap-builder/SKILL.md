---
name: roadmap-builder
description: Turn one client's approved needs brief and triage into a phased roadmap with a completion timeline. Use when a client has an approved triage and no roadmap yet, or when asked for a plan, phases, timeline, schedule, or what to do first, second, and third for a client.
---

# Roadmap builder

Turn an approved triage into a plan the client can follow and we can deliver. Follow the `house-rules` skill throughout.

## Inputs

That client's `work/needs-brief.md` and `work/triage.md`, both approved by the board. If `portfolio/patterns.md` exists and is approved, use it only to note where work can be shared with other clients. Do not copy other clients' details into this roadmap.

If either approved file is missing, stop and say so.

## Method

1. Start from the triage's recommended first phase. Do not add work the triage did not support.
2. Build phases in this order: digital now, then digital later once its dependency is met. Place non-digital help (process, training, policy) in the phase where it helps most, often alongside the first tool.
3. For each phase, give: goal, what is delivered, who does what (us vs the client), dependencies, and a success measure taken from the client's own words in the needs brief.
4. Estimate effort as a range in person-days and duration in weeks. Label every estimate `(estimate)` and state what it assumes. If the team's weekly capacity is not given, assume it and say so at the top.
5. Use relative timing (Week 1, Week 2) counted from board approval, unless a start date is given.
6. Keep phases small: three phases or fewer, each short enough that the client sees a result within about a month.
7. List risks and the **decisions needed from the client**, such as access, data, or a person to own the tool.
8. Do not give prices. Cost estimation is a separate step.

## Output

Write `work/roadmap.md` (internal, with notes and assumptions):

- **Assumptions** (capacity, start, anything unconfirmed)
- **Phases** (as above)
- **Timeline** table: Week | Phase | Milestone | Owner
- **Risks and dependencies**
- **Decisions needed from the client**

Then write `work/roadmap-client.md`: the same plan in plain language for the client. No internal notes, no other clients, no jargon. Each phase says what changes for them and what we need from them.

Both files are drafts until the board approves them.
