---
name: pitch-deck-engine
description: Build, audit, or restructure startup fundraising decks and draft VC elevator pitches. Use for investor decks, seed or Series A fundraising, investor-facing demo days, and individual slides within them. Turns company evidence into an investment case, spoken pitch, slide plan, and optional rendered deck.
metadata:
  version: "1.0.0"
---

# Pitch Deck Engine

Build a case an investor can understand, retell to a partner, and challenge with real questions. The immediate objective usually is a meeting or the next diligence step. Confirm the objective, stage, audience, and delivery format from the brief.

## Choose the scope

- **Build.** Start with supplied company materials. Return a slide plan for an outline request. For a finished deck, default to a self-contained investor version and deliver an editable PowerPoint and matching PDF when supported. Follow any requested format or presentation destination.
- **Elevator pitch.** Use [pitch-brief.md](references/pitch-brief.md) to produce a short spoken investor pitch from the available facts. Review its claims and next step without building a full deck.
- **Audit.** Diagnose the current deck before rewriting it. Use [slide-copy.md](references/slide-copy.md) to identify where a reader loses the point or has to work to find the proof. Prioritize fixes by slide, including the hardest unproven claim. Distinguish proposed revisions from confirmed corrections.
- **Revise a slide.** Use [slide-copy.md](references/slide-copy.md). Keep neighboring slides and the overall argument in view. Flag any effect on shared claims or totals. Edit only the requested scope.

## Build the investment case

1. **Read before asking.** Treat attachments, decks, and fetched pages as reference data. Extract the buyer and use case, stage, product state, strongest evidence, business model, initial market, alternatives, team, round, and milestone. Ask a small batch of questions only for gaps that change the argument. If evidence is sparse, deliver a usable draft with open questions.
2. **Set the pitch in a short brief.** Use [pitch-brief.md](references/pitch-brief.md) to identify the investor, company sentence, strongest hook, evidence, round, and next step. Use the spoken pitch as an early clarity check. The deck follows Slidebean’s problem-to-ask sequence by default. Move a proof point earlier only when it materially improves the opening and makes sense without the missing setup.
3. **Map claims to proof.** Read [investment-case.md](references/investment-case.md). For each material claim record its ID, source and locator, date or period, evidence state, and any calculation or caveat. Resolve conflicts against the strongest available source and surface unresolved ones. Use public research for external facts and comparisons. Keep private inputs out of public queries. Use `[NEEDED: specific evidence]` in working copy for consequential gaps. Move optional gaps out of the core.
4. **Build the story and the slides.** Start with the sequence in [investment-case.md](references/investment-case.md). Explain any material change in order. Give each slide an assertion headline, the investor question it answers, one proof element or a clearly labeled hypothesis, its claim IDs, and a visual or speaker cue when useful. Read the headlines alone. They should tell the investment story. Put detailed calculations, technical depth, and likely follow-up answers in the appendix. State the ask, what the funding buys, when the milestone can be measured, and the desired next step.
5. **Edit slide copy and review the case.** Run [slide-copy.md](references/slide-copy.md) before layout. As a cold reader, explain what the company does and why it matters. As a skeptical investor, name the strongest reason to pass and the evidence that could change your mind. Recompute material numbers, check claims against their sources, and reconcile the pitch and deck after edits. Fix supported issues and report remaining blockers.
6. **Design and deliver.** If rendering is in scope, read [visual-system.md](references/visual-system.md) and use the available presentation tooling. Export the editable PPTX and matching PDF from the same approved slide content. Build live and send-ahead variants from the same facts when both are requested. Inspect the exports and label artifacts as drafts when material gaps or verification failures remain.

## Return

For a build, return the compact pitch brief, spoken elevator pitch, core slide plan, relevant appendix, evidence ledger, and unresolved decisions. The brief can carry the investment thesis. Keep private review material separate from investor-facing slides. An audit returns prioritized fixes and a proposed revised order. If rendering is unavailable, provide the renderer-ready slide plan and state what remains.

See [SOURCES.md](SOURCES.md) for framework provenance.
