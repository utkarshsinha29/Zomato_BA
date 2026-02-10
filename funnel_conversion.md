# Funnel Conversion Analysis

This section analyzes step-wise conversion rates across the
end-to-end food ordering funnel. Funnel stages were calculated
sequentially to ensure that each stage is a subset of the
previous one.

## Conversion Rates

| Funnel Stage | Conversion Rate |
|-------------|-----------------|
| Menu → Cart | 50% |
| Cart → Checkout | 50% |
| Checkout → Payment | 100% |
| Payment → Delivery | 100% |

## Highest Drop-Off Stage

The highest drop-off occurs at the **Menu → Cart stage**, where
only **50% of users proceed to add items to the cart**.

## Business Interpretation

This indicates early-stage decision friction, suggesting that
users are either not sufficiently convinced by the menu,
pricing, or perceived value to continue the ordering journey.

Since conversion remains strong after checkout initiation,
payment systems and delivery operations are not the primary
bottlenecks at this stage.

## Analytical Notes
- Funnel built using event-level data
- Sequential dependency enforced across stages
- Conversion rates validated to be ≤ 100%
