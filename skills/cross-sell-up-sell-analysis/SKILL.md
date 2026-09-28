---
name: cross-sell-up-sell-analysis
description: Identify existing-customer expansion opportunities from product holdings, usage, eligibility and peer patterns. Use at the account-by-product grain; use revenue-whitespace-analysis for aggregate portfolio gaps and segment-opportunity-analysis for external markets.
---

# Cross-sell and up-sell analysis

Identify credible account-level expansion opportunities while separating product adjacency, customer need and commercial readiness.

## MECE boundary

- **Unit of analysis:** an existing account × product, module or tier.
- **Owns:** account-level cross-sell and up-sell prioritisation.
- **Does not own:** aggregate portfolio strategy, net-new market selection, churn prediction or automated sales decisions.

## Definitions

- **Cross-sell:** adoption of a different product family or solution by an existing customer.
- **Up-sell:** expansion within an existing product family through higher tier, capacity, users, usage or scope.

Keep the two opportunity types separate because their signals, motions and value estimates differ.

## Minimum useful data

- Account identifier and comparable customer segment
- Current product holdings, contract value or revenue
- Product eligibility and availability
- Renewal or contract timing
- Product hierarchy that distinguishes families, modules and tiers

Useful additions include usage, seat or capacity limits, customer needs, service history, opportunity history, adoption health and product compatibility.

## Analysis

1. Confirm the account-product grain and observation date.
2. Standardise the product hierarchy and resolve duplicate or bundled holdings.
3. Apply eligibility and availability rules before scoring opportunity.
4. Build an account-product matrix that distinguishes held, eligible-unheld, ineligible and unknown states.
5. Select comparable peer cohorts using relevant features such as segment, size, industry, geography or operating model.
6. For cross-sell, examine peer attach rates, product adjacency and validated customer needs.
7. For up-sell, examine capacity utilisation, tier limits, usage growth, seat penetration and contract timing.
8. Estimate value using a defensible reference such as eligible-peer median or documented pricing. Avoid using the largest customer as the default benchmark.
9. Reduce priority when the current product has poor adoption, unresolved service issues, elevated churn risk or no evidence of need.
10. Rank opportunities using visible components: fit, signal strength, timing, potential value, feasibility and confidence.

If no trained and validated propensity model exists, call the result a **rule-based prioritisation** or **opportunity heuristic**.

## Analytical safeguards

- Never treat lack of a product holding as evidence of need.
- Avoid using information recorded after the opportunity outcome when evaluating historical signals.
- Keep product eligibility distinct from commercial readiness.
- Account revenue can reflect negotiated pricing rather than product need.
- Peer adoption is a clue, not a causal recommendation.
- Exclude sensitive personal attributes and avoid automated decisions about individuals.

## Output

Provide:

- Scope, observation date and product hierarchy
- Eligibility and exclusion rules
- Cohort methodology
- Separate cross-sell and up-sell opportunity tables
- Account, opportunity type, product, evidence, timing, value range, confidence and recommended next step
- False-positive risks and missing evidence
- Aggregate opportunity by segment or product without double counting
- Suggested discovery questions for commercial validation

The output should help a commercial team decide where to investigate, not generate an indiscriminate contact list.
