---
name: revenue-whitespace-analysis
description: Identify underrepresented internal revenue or penetration cells across products, segments, geographies or channels. Use at an aggregate product-by-dimension grain; use segment-opportunity-analysis for external market attractiveness and cross-sell-up-sell-analysis for individual accounts.
---

# Revenue whitespace analysis

Find where current revenue or penetration appears low relative to a defensible comparator, then separate measurable gaps from hypotheses that require commercial validation.

## MECE boundary

- **Unit of analysis:** an aggregate product × segment, geography or channel cell.
- **Owns:** internal mix, penetration and portfolio whitespace.
- **Does not own:** external market sizing, account-level expansion or incremental-revenue forecasting without demand evidence.

## Establish the analysis

Before calculating, state:

- the analytical grain, such as product × segment × region;
- the revenue period, currency and treatment of recurring versus one-time revenue;
- the parent total used for mix calculations;
- the comparator and why it is appropriate;
- whether the question concerns mix, penetration, addressable market or incremental revenue.

Do not combine periods, currencies or incompatible revenue definitions silently.

## Minimum useful data

- Revenue by the selected dimensions and period
- Customer or account counts where penetration matters
- Product availability and customer eligibility
- A comparator: strategy target, relevant peer cohort, prior period or external benchmark

Useful additions include margin, growth, retention, product maturity, capacity and market-size evidence.

## Analysis

1. Validate totals, duplicates, missing values and category definitions.
2. Calculate current mix share within the stated parent total.
3. Calculate penetration separately when an eligible-account denominator exists.
4. Compare each cell with the selected benchmark.
5. Express mix gap as:

   `benchmark share × current parent revenue − current cell revenue`

6. Label that result a **mix-equivalent gap**, not incremental revenue.
7. If addressable-market or eligible-account data exists, develop a separate incremental opportunity estimate with explicit assumptions.
8. Remove or flag cells where the product is unavailable, the segment is ineligible, the benchmark is not comparable or data quality is weak.
9. Build low, base and high scenarios when assumptions materially affect the estimate.
10. Prioritise using transparent factors such as gap size, growth, margin, strategic fit, feasibility and confidence. Show the components rather than hiding them inside one unexplained score.

## Interpretation safeguards

- Zero revenue may mean missing data, ineligibility, a new product or deliberate strategy—not whitespace.
- A high peer share may reflect a different product mix, acquisition history or customer base.
- Positive mix gaps compete with one another when the parent total is fixed; do not sum them as guaranteed growth.
- Revenue concentration can be strategically correct.
- Correlation between a dimension and growth does not establish causation.
- Keep internal mix, customer penetration and external market whitespace as distinct measures.

## Output

Provide:

- Scope, grain, period and comparator
- Data-quality findings
- Current revenue mix and penetration where available
- Ranked whitespace table with current value, benchmark, gap, confidence and exclusions
- Low, base and high scenarios where appropriate
- Drivers and alternative explanations
- Recommended validation actions
- Claims the data cannot support

Recommendations should identify the next commercial question or experiment, not merely the largest numerical gap.
