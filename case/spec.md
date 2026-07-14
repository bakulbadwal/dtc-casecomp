# Technical Spec — What Teams Ship

> v0.1 — July 2026. **Toolchain assumptions as of this date; AI tooling is moving fast — re-validate everything in this doc ~4 weeks before case drop.** Working assumption: Microsoft Copilot / Copilot Studio as the required platform (sponsor-dependent). The tier structure below is deliberately tool-agnostic and survives a platform change.

## The core design choice

The requirement is **not** "use AI to help with your case." Every team can already do that, and judges can't score it. The requirement is a **working artifact**: an agent that performs a real marketing function for the case client, demoed live. That single constraint is what makes this event different from every other case competition.

## Requirement tiers

Tiers keep the floor accessible to every Darden student while giving ambitious teams headroom. **Tier 2 is the expectation; Tier 1 alone caps a team's artifact score.**

### Tier 1 — Floor (every team)
- Copilot-assisted market research, segmentation, and campaign economics
- Campaign deck (the classic case-comp deliverable)
- **AI-process log** (required, see below)

### Tier 2 — Target (scoring expectation)
One working **Copilot Studio agent** performing a real function from the team's own campaign design, e.g.:
- Lead-qualification agent (intake conversation → scored/routed lead)
- Content-variant engine (one campaign concept → channel-specific copy at scale)
- Customer/donor FAQ agent grounded in the client's actual materials
- Competitive-intelligence monitor with structured briefs

Demoed **live** at finals. "It broke during the demo but the design was sound" is a rubric row, not a disqualification — see [rubric.md](rubric.md).

### Tier 3 — Stretch (tiebreaker territory)
A multi-step pipeline where agents hand off to each other: **segmentation → creative generation → campaign plan/schedule**, or equivalent. This is where the winner separates.

## AI-process log (required, all tiers)

A 1–2 page appendix: which tools, for what, what the humans decided vs. what the AI produced, one thing the AI got wrong and how the team caught it. This flips the usual academic-integrity anxiety — **AI use here is required and disclosed, not suspected and hidden** — and it's what lets judges score *skill* rather than tool access.

## Prerequisites & dependencies (flag early)

| Dependency | Why it matters | Owner |
|---|---|---|
| **Copilot Studio access per team** | Good news (verified July 2026): the individual **free trial** covers demo-stage builds — full agent-building access, demoable to judges; trial agents just can't be *published*, which a demo-format competition doesn't need. Sponsor-provisioned licenses are only required if teams should publish/persist agents beyond the event. The school's own Microsoft EDU agreement may already include seats — worth one email to IT. Either way, confirm the access story **at sponsorship-agreement stage, not event week**. | Teams self-serve (trial) or sponsor (publishing) |
| Kickoff tooling workshop (90 min) | Most participants will be new to agent-building; a hands-on session moves the whole field from Tier 1 to Tier 2 | Organizers + sponsor SEs |
| Sponsor office hours during build window | Unblocks teams; doubles as the sponsor's recruiting touchpoint | Sponsor |
| Client data/materials pack | Agents need something real to be grounded in (menus, price lists, past campaigns, FAQ docs) | Case client + organizers |

## Ground rules

- **Teams:** 3–5 students; no technical background required or expected — the workshop plus Copilot Studio's low-code surface is the point.
- **Build window:** 10–14 days between case drop and submission (a weekend is too short for Tier 2 quality; a month kills urgency).
- **Allowed tools:** the sponsor platform is required for the artifact; other AI tools are permitted for research/prep and must appear in the process log. (If organizers prefer a single-platform rule, that's one line in this spec — decide before case drop.)
- **Submission gate:** deck (PDF) + 3-minute artifact demo video + AI-process log. Live demo at finals for shortlisted teams.
