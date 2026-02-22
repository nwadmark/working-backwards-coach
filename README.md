# Working Backwards Coach

A Claude skill that transforms product ideas into rigorous, customer-first documentation — and pushes you to do the hard thinking before the writing.

## What This Does

Most product teams jump straight to writing docs. This skill forces a different sequence: **think critically first, then document.** It acts as a coach — not a template filler — challenging your assumptions, pushing for specificity, and surfacing the gaps in your thinking before producing any output.

Inspired by Amazon's Working Backwards process, adapted for how product teams actually work today.

## How to Install

1. Go to **Claude.ai → Settings → Skills**
2. Click **+ Add**
3. Upload this repo's folder (or drag in the files)

The skill activates automatically when you ask Claude to help with product ideas, PR/FAQs, PRDs, or product strategy.

## What You Can Create

**Quick 1-Pager** — A single-page decision document. Best for: "Should we build this?" Gives you a Build / Investigate / Pivot / Kill recommendation.

**Product Requirements Document (PRD)** — Detailed spec for engineering handoff. Goals, non-goals, user stories, functional requirements, success metrics, technical considerations, open questions.

**Comprehensive PR/FAQ** — Full working-backwards documentation with press release, FAQs, experience narrative, competitive analysis, and evidence plan.

**Custom** — Mix and match sections based on what you need.

## How to Use It

Start a conversation with Claude and say something like:

- *"I have a product idea about X, help me think through it"*
- *"Should we build this feature?"*
- *"Write a PR/FAQ for [concept]"*
- *"Create a PRD for [feature]"*
- *"How do I validate if customers actually want this?"*

The skill will guide you through the process — gathering context, drafting documentation, running a critical review, and iterating.

## What's in This Repo

```
working-backwards-coach/
├── SKILL.md                              # Core skill instructions
├── working-backwards-coach.skill         # Skill manifest
├── references/
│   ├── document-templates.md             # Templates for all document types
│   └── evaluation-rubric.md              # Product evaluation framework
├── LICENSE                               # MIT
└── README.md
```

## The Philosophy

The best product documents aren't the ones with the most polished formatting. They're the ones backed by the clearest thinking. This skill is opinionated about a few things:

**Customer-first, always.** Write from the customer's point of view before considering internal concerns. No "users" or "people" — name the actual persona.

**Evidence over opinion.** Every assumption gets labeled. If you don't have evidence, the skill will tell you to go get some before writing a PR/FAQ.

**Specificity is a feature.** Vague value propositions get challenged. "Better user experience" isn't a benefit — what specifically changes for the customer?

**Scope discipline matters.** What you're NOT building is as important as what you are. If everything is in scope, nothing is.

**Don't skip the hard questions.** Who specifically is this for? What could kill this idea? Will someone actually pay for it? The skill pushes you to answer these before producing any output.

**Conciseness is respect.** Target 1-2 pages. Every sentence must earn its place. If your executives need to read it, make it worth their time.

## Critical Review Framework

Every document gets evaluated across four dimensions:

- **Value** — Will customers buy it or choose to use it?
- **Usability** — Can users figure out how to use it?
- **Feasibility** — Can we build it with current resources?
- **Business Viability** — Does this work for our business?

Each dimension is rated Strong / Moderate / Weak / Unknown, leading to a clear recommendation: **Build, Investigate, Pivot, or Kill.**

## Data Integrity

The skill never fabricates data. If you haven't provided market sizes, competitive pricing, or customer metrics, it uses `[PLACEHOLDER]` labels and tells you exactly what research you need to do. Assumptions are always labeled as assumptions.

## Contributing

Issues and PRs welcome. If you've found ways to improve the coaching workflow or templates, I'd love to hear about it.

## License

MIT — use it however you'd like.

Built with ❤️ by NW (https://github.com/nwadmark)
