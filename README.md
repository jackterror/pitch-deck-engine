# Pitch Deck Engine

A modular AI-ready skill for startup pitch decks, slide audits, and VC elevator pitches, grounded in Slidebean, HBS, and MIT Sloan.

## What it does

- Builds a short pitch brief, a spoken VC elevator pitch, and a slide plan from your company materials.
- Links key claims to their sources and flags evidence you still need.
- Audits existing decks and rewrites selected slides around one conclusion and its proof.
- Delivers an editable PowerPoint and matching PDF when you request a finished deck and the authoring tools support both.

## Default behavior

The engine follows Slidebean’s fundraising sequence and adapts the evidence to your stage. A finished deck defaults to a version investors can read on their own. Ask for an outline to get a slide plan. You can also request a standalone elevator pitch or a one-pager to send to investors.

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

The skill is in preview. Two fictional cases have been walked through by hand. Full deck runs and PowerPoint and PDF export verification are pending. See [test prompts](TEST-PROMPTS.md) and [source notes](SOURCES.md).

## Creator and license

Created by [Jack Dalrymple](https://www.jackdalrymple.com/), Founder of [Cap and Cut](https://capandcut.com/). See [CREATOR.md](CREATOR.md).

Released under the MIT License. See [LICENSE](LICENSE).
