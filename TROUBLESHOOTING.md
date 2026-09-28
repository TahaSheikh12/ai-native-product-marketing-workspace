# Troubleshooting

## The output is generic

Check that the workspace contains specific product, audience and evidence context. Confirm the AI selected a workflow based on the decision, not merely the requested format. Add missing context rather than asking for more polished language.

## The AI chose the wrong workflow

State the primary decision in one sentence and use `workflows/README.md`. If the request spans several lifecycle stages, create separate deliverables in the order discover, define, activate, grow and learn.

## Two skills appear to overlap

Use the boundary tests in `skills/README.md` and identify the analytical unit:

- external market or segment;
- internal aggregate revenue cell;
- existing account and product;
- competitor or alternative;
- commercial opportunity;
- offer or price point;
- source or observation;
- initiative, cohort and time period.

Use multiple skills only when the units are different and each produces a distinct supporting analysis.

## The AI invented evidence or strengthened a claim

Stop the draft. Ask it to show the evidence ID for every material claim. Move unsupported content to open questions, and review `context/claims-and-proof.md` before continuing.

## Context has become cluttered

Keep active work in `current-priorities.md`, confirmed decisions in `decisions.md`, traceable sources in `evidence-register.md`, approved claims in `claims-and-proof.md` and brief continuity notes in `session-log.md`. Remove duplicates and retire stale entries rather than adding another source of truth.

## Results are numerically plausible but untrustworthy

Check grain, time period, currency, population, denominator, exclusions, missing values and comparator. Confirm that the matching analytical skill was used. Do not proceed until the definitions are explicit.

## A rule is ignored

Confirm the workspace was opened at its root and the platform instruction file is visible:

- Cursor: `.cursor/rules/product-marketing.mdc`
- Claude Code: `CLAUDE.md`
- Codex: `AGENTS.md`

Each should point to `WORKSPACE.md`. Restart or begin a fresh session after changing persistent rules.

## The workspace may contain confidential material

Stop external sharing. Remove credentials, personal data, customer-identifying details and restricted employer information. Replace demonstrations with public, synthetic or explicitly approved material. Re-run `quality/workspace-health-check.md` before distribution.
