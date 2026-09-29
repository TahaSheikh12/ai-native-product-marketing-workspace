# AI-Native Product Marketing Workspace

> A portable operating system for evidence-led product marketing decisions.

**Platforms:** Cursor · Claude Code · Codex  
**Scope:** PMM strategy · commercial analysis · evidence governance · human approval

## Purpose

AI assistants often rely on temporary chat context and isolated prompts. This workspace provides a durable operating model: shared context, clear workflows, reusable analytical methods and quality controls.

It is designed to support product marketing judgment, not automate it.

## Operating model

### Five workflows

| Stage | Decision | Output |
|---|---|---|
| **Discover** | Where is the evidence-backed opportunity? | Opportunity brief |
| **Define** | Who should we prioritise, and what should we stand for? | PMM strategy brief |
| **Activate** | How should the strategy reach the market? | Market activation plan |
| **Grow** | How should adoption, retention or expansion improve? | Customer growth plan |
| **Learn** | What happened, why, and what should change? | Performance review |

### Eight analytical skills

- Evidence synthesis
- Segment opportunity analysis
- Competitive analysis
- Pricing and packaging analysis
- Revenue whitespace analysis
- Cross-sell/up-sell analysis
- Win/loss analysis
- Performance measurement

Select one workflow based on the decision, then add only the analytical skills required to support it. A deck, memo or battlecard is an output format, not a workflow.

## What the workspace demonstrates

- **Product marketing:** positioning, go-to-market planning, activation and growth
- **Commercial analysis:** segment opportunity, revenue whitespace, expansion and win/loss
- **AI system design:** distinct roles for rules, context, workflows, skills and templates
- **Evidence governance:** separate records for sources, claims, limitations and approvals
- **Adoption:** a structure designed for colleagues, not only its creator
- **Portability:** one operating model across Cursor, Claude Code and Codex

## Evidence of use

An earlier private product marketing version was used for approximately five months and adopted by four colleagues. When enterprise tooling changed, the workspace was migrated from Cursor to Claude Code. This public version is a clean reconstruction with Codex support.

The value is the operating model: recurring work can be structured once, improved through use and retained when tools change.

## Start in five minutes

1. Complete `context/product.md`, `context/audiences.md` and `context/current-priorities.md`.
2. Add working preferences to `context/operator-profile.md`.
3. Open the folder in Cursor, Claude Code or Codex.
4. Ask the assistant to read `WORKSPACE.md` and `START-HERE.md`, summarise the context and identify important gaps.
5. Save reviewed deliverables under `outputs/`.

Unknown fields should remain blank. The system is instructed not to invent evidence to complete a template.

## Review path

1. [`WORKSPACE.md`](WORKSPACE.md) — shared operating instructions
2. [`workflows/README.md`](workflows/README.md) — outcome routing
3. [`skills/README.md`](skills/README.md) — analytical boundaries
4. [`context/evidence-register.md`](context/evidence-register.md) and [`context/claims-and-proof.md`](context/claims-and-proof.md) — evidence governance
5. [`docs/architecture.md`](docs/architecture.md) — system design
6. [`docs/origin-and-evolution.md`](docs/origin-and-evolution.md) — provenance and development

## Structure

```text
product-marketing-workspace/
├── WORKSPACE.md       Shared operating instructions
├── START-HERE.md      Setup guide
├── context/           Knowledge, evidence and decisions
├── workflows/         Five PMM outcomes
├── skills/            Eight analytical methods
├── templates/         Reusable deliverable structures
├── quality/           Review and health checks
└── docs/              Architecture and provenance
```

## Design principles

1. Decisions before deliverables.
2. Evidence before claims.
3. One owner for each concern.
4. Explicit human approval.
5. Portability over platform dependence.
6. No employer, customer or confidential material in the public workspace.

## Provenance

The original inspiration was an internal Cursor learning workspace created by a senior leader. I did not create that original system. I adapted its file-based approach to product marketing, developed the operating model through use, supported adoption by four colleagues and migrated it when the enterprise tool changed.

This repository is an independent reconstruction. It contains no original private scripts, employer information, customer data or confidential examples. See [`docs/origin-and-evolution.md`](docs/origin-and-evolution.md) for further detail.

## Use and distribution

- Do not add credentials, personal data or restricted material.
- Keep populated working copies private unless approved for publication.
- Review analysis and claims before external use.
- Run `quality/workspace-health-check.md` before sharing a populated copy.

## Status

Version 1.0. Future changes will be based on practical product marketing use.
