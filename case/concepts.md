# Case Concepts

> v0.2 — July 2026. Four candidate concepts, each with a draft case prompt (the actual text teams would receive), tier-mapped artifact ideas, sourcing path, and risks. Decision matrix and recommendation at the end. The AI/agent requirement these feed into is defined in [spec.md](spec.md).

**What makes a concept work here:** real stakes (a client who can say "we'd actually do this"), enough grounding material for agents to be built on (docs, data, history — agents need substrate), and an artifact with *after-life* — something still running a month after the event.

---

## Concept 1 — Launch campaign for a real Charlottesville business

**The pitch.** A local business — restaurant group, retailer, service brand — needs a launch or growth campaign: new location, new offering, repositioning. Teams get a real founder, a real budget number, real constraints, and the founder sits on the judging panel.

**Draft case prompt.**
> *[Client] has operated in Charlottesville for [N] years and is preparing to [open a second location / launch a new offering] in [month]. Owner [name] has a marketing budget of $[X], no dedicated marketing staff, and a customer base that skews [demographic]. Your team will deliver: (1) a segmentation and targeting analysis for the launch market; (2) a 90-day campaign plan within budget; (3) a working agent that executes one recurring piece of that campaign so it runs without a marketing hire. You will present to [name], who will tell you whether they'd actually do it.*

**Tier-mapped artifact ideas.**
- *Tier 2:* a content engine that turns one weekly input from the owner ("this week's special is X") into channel-ready posts, email copy, and a Google Business update; or an inbound lead/reservation qualifier.
- *Tier 3:* segmentation → creative variants per segment → scheduled 90-day calendar, with the owner approving batches rather than writing anything.

**Sourcing path.** Batten's community network, the Charlottesville chamber, or Darden alumni who own local businesses. One committed client needed ~6 weeks before case drop; a backup client is cheap insurance.

**Sponsor angle.** "MBAs built AI agents that a Main Street business actually kept using" — SMB adoption story, which is precisely the segment every AI platform is fighting for.

**Risks.** Client flakes (mitigate: backup client); client's needs too small to stretch 8 teams (mitigate: all teams work the same client, competing on approach — this also makes judging apples-to-apples).

**Judge appeal: highest.** The founder-in-the-room verdict ("I'd run this Monday") is worth more than any rubric.

---

## Concept 2 — Go-to-market for a Batten portfolio venture

**The pitch.** An early-stage venture from Batten's ecosystem gets its first serious GTM plan. Teams work from the venture's actual materials plus a founder Q&A. Dovetails exactly with Batten's stated role as idea-source — this is the concept that makes the Batten partnership load-bearing rather than decorative.

**Draft case prompt.**
> *[Venture] has built [product] and has [early traction marker: N pilot users / first paying customer / LOI]. The founding team is technical; nobody owns go-to-market. Your team will deliver: (1) ICP definition and positioning the founder can put on the website tomorrow; (2) a launch-quarter GTM plan with channel priorities and budget allocation under $[X]; (3) a working agent performing one growth function the venture lacks headcount for. The winning artifact will be offered to the venture to keep.*

**Tier-mapped artifact ideas.**
- *Tier 2:* outbound content engine grounded in the venture's positioning docs; an onboarding/activation assistant; a competitive-intel monitor producing weekly structured briefs.
- *Tier 3:* ICP scoring → personalized outreach sequences → pipeline tracker handoff.

**Sourcing path.** Batten Founder/Search Fellows and venture programs — one warm ask through the existing relationship. The "winner's artifact is offered to the venture" line should be in the case packet; it's the after-life mechanism made explicit.

**Sponsor angle.** Startup-ecosystem story plus platform stickiness (a venture keeps running an agent built on the sponsor's stack).

**Risks.** Early-stage ambiguity makes judging mushier (mitigate: rubric's business dimension anchors on "would the founder ship this positioning"); venture pivots mid-competition (accept — it's two weeks).

**Judge appeal: high**, especially with the founder judging.

---

## Concept 3 — Market Copilot to small businesses (sponsor meta-case)

**The pitch.** The prospective sponsor's own live problem: AI assistant adoption among SMBs lags enterprise badly. Teams design the campaign that moves SMB owners from "heard of it" to habitual use — building their artifact on the very product they're marketing. Self-referential by design: the artifact *is* the demo of the value proposition.

**Draft case prompt.**
> *SMB adoption of AI assistants trails enterprise adoption by [X] despite a larger addressable market. You are the marketing team tasked with changing that in one vertical of your choosing (e.g., independent restaurants, boutique fitness, local professional services). Deliver: (1) an adoption-barrier analysis for your vertical; (2) a campaign strategy that converts awareness to weekly active use; (3) an agent built on the platform that a business owner in your vertical would find indispensable within one week — your proof that the product delivers what your campaign promises.*

**Tier-mapped artifact ideas.** The artifact *is* the campaign's proof point — a vertical-specific starter agent (restaurant reservation-and-review manager, fitness-studio retention nudger) that doubles as launch-campaign collateral.

**Sponsor angle: maximum.** Thirty MBA perspectives on a real strategic problem, platform usage, and campaign concepts their SMB team can actually mine. This is the concept most likely to *increase* the sponsorship check.

**Risks.** Neutrality — as the sole case, the event reads as a sponsor marketing exercise, and any team's honest finding of product weaknesses gets awkward in the room. **Mitigate by position, not polish: run it as a bonus track or second-flight case, not the main event.**

**Judge appeal: medium** — no external client verdict; sponsor judges grade their own homework.

---

## Concept 4 — UVA-adjacent nonprofit or NIL campaign

**The pitch.** A Charlottesville nonprofit's donor/volunteer campaign, or an NIL marketing strategy in a UVA athletics context — both with direct precedent in Tech Innovators Challenge outcomes (UVA Health pilots, NIL strategy work).

**Draft case prompt (nonprofit variant).**
> *[Nonprofit] runs on [N] staff and [M] volunteers, with donor renewal at [X]% and no marketing budget to speak of. Deliver: (1) a donor and volunteer segmentation built from what the organization already knows; (2) a renewal-and-recruitment campaign executable by two part-time staff; (3) an agent that removes one recurring communications burden permanently. Budget for tools: effectively zero — sustainability of your solution is scored.*

**Tier-mapped artifact ideas.** Donor-segment messaging engine; volunteer onboarding flow; grant-deadline monitor with draft-boilerplate assembly. The zero-budget constraint makes agent sustainability a genuinely interesting design problem.

**Sourcing path.** Nonprofit: fast (Charlottesville's nonprofit network is dense, and "free MBA marketing help plus a working tool" is an easy yes). NIL: slower — athletics-department coordination.

**Sponsor angle.** Social-impact story; weaker commercial narrative.

**Risks.** Lower stakes-pressure than a paying business; NIL variant has approval friction. **Judge appeal: medium-high** (mission energy is real, and the zero-budget constraint impresses when handled well).

---

## Decision matrix

| Criterion | 1 · Local business | 2 · Batten venture | 3 · Sponsor meta | 4 · Nonprofit/NIL |
|---|---|---|---|---|
| Real stakes / client verdict | ●●● | ●●● | ● | ●● |
| Sourcing effort (lower = better) | ●● | ●●● | ●●● | ●●● |
| Grounding material for agents | ●●● | ●●● | ●● | ●● |
| Sponsor appeal | ●● | ●● | ●●● | ● |
| Artifact after-life | ●●● | ●●● | ●● | ●●● |
| Approval friction (lower = better) | ●●● | ●●● | ●●● | ●● |

## Recommendation

**Main case: Concept 1 or 2** — whichever client Batten can commit first; they're near-interchangeable in quality, and the honest tiebreaker is sourcing speed. **Concept 3 as the sponsor bonus track** — a named bonus prize ("best use of [platform]") that adds sponsor presence without bending the main rubric or the event's neutrality. **Concept 4 is the fallback** if client sourcing stalls at the 6-week mark.

**Structural suggestion:** all teams on one case, one client. Eight teams on eight different clients is eight times the sourcing work and un-judgeable; eight approaches to one real problem is a competition.

## Case-packet checklist (whichever concept wins)

A complete packet is 2–3 pages plus grounding material — the grounding material is what makes Tier 2 agents possible:

- [ ] Case prompt (one page, in the style of the drafts above — blanks filled)
- [ ] Client background + 30-min recorded founder interview (or live kickoff Q&A)
- [ ] **Data/materials pack**: menus, price lists, past campaign examples, FAQ docs, customer descriptions — whatever the client has; agents are grounded in this
- [ ] Budget number and hard constraints (what the client will *not* do)
- [ ] IP/usage release (one paragraph: teams grant client rights to their output)
- [ ] Rubric summary + AI-process log template (from [rubric.md](rubric.md) / [spec.md](spec.md))
- [ ] Platform access instructions per team (the licensing dependency from [spec.md](spec.md))
