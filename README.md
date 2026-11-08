# Pitch Deck Engine

A modular AI-ready skill for startup pitch decks, slide audits, and VC elevator pitches, grounded in Slidebean, HBS, and MIT Sloan.

**Current version** · `v1.0.0`

## What it does

- Turns your company materials into a working brief, a spoken elevator pitch, and a fundraising deck.
- Links key claims to their sources and flags evidence you still need.
- Audits existing decks and rewrites selected slides around one conclusion and its proof.

## What you get

A full build delivers three items as four files when the tools support those formats:

- A working brief PDF for you. It organizes your case, the evidence, and the decisions you still need to make.
- A separate elevator pitch PDF with a short script you can say out loud to investors.
- A fundraising deck in two formats. You get an editable PowerPoint and a matching PDF you can send.

## Default behavior

The engine follows Slidebean’s framework for building investor-ready pitch decks. It organizes the story around who needs your product, what you’ve proven at your funding stage, and what the investment would help you do next.

Before layout, the engine turns each slide’s takeaway into a clear headline and pairs it with evidence. It moves extra detail to the speaker notes or appendix so investors can follow the deck on their own. Ask for an outline to get a slide plan. You can also request a standalone elevator pitch or a one-pager to send to investors.

## Architecture / Package structure

```text
pitch-deck-engine/
├── SKILL.md
├── README.md
├── TEST-PROMPTS.md
├── SOURCES.md
├── CREATOR.md
├── CHANGELOG.md
├── PACKAGE-DESCRIPTION.md
├── LICENSE
├── .gitignore
├── references/
│   ├── investment-case.md
│   ├── pitch-brief.md
│   ├── slide-copy.md
│   └── visual-system.md
└── docs/
    └── images/
        └── social-preview.png
```

## Agent Skill installation

The repository root follows the [Agent Skills specification](https://agentskills.io/specification).

Claude Code:

```bash
ln -s /absolute/path/pitch-deck-engine ~/.claude/skills/pitch-deck-engine
```

OpenAI Codex:

```bash
ln -s /absolute/path/pitch-deck-engine ~/.codex/skills/pitch-deck-engine
```

Then ask:

```text
Use $pitch-deck-engine to review this seed deck, rewrite dense slides, and tie the ask to a measurable milestone.
```

## Notes

A fictional warehouse startup has trial data and wants to claim shorter wait times. The slide headline reads **Three warehouses tested the prototype**. The proof underneath reads **12 deliveries in unpaid trials**. The evidence ledger flags the comparable wait-time measurement still needed.

Two fictional cases have been walked through by hand. Fresh-session testing and a public worked example with matching PowerPoint and PDF exports are pending. See [test prompts](TEST-PROMPTS.md) and [source notes](SOURCES.md).

## Creator and license

Created by [Jack Dalrymple](https://www.jackdalrymple.com/), Founder of [Cap and Cut](https://capandcut.com/). See [CREATOR.md](CREATOR.md).

Released under the MIT License. See [LICENSE](LICENSE).
