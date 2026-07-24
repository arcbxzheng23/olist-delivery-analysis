# Olist Delivery Delay Analysis — Findings Log

## Key findings
- 8.1% of delivered orders (7,826 of 96,470) arrived after the estimated delivery date
- Late orders average 2.57 stars vs 4.29 for on-time — a 1.7-star gap
- 46% of late orders receive a 1-star review, vs 6.6% of on-time orders (7x rate)
- 5-star share drops from 62% (on-time) to 22% (late)

## Data quality notes
- 8 orders marked "delivered" have no delivery timestamp — excluded
- 551 orders have multiple reviews; kept most recent review per order
- Dedup did not change results (gap: 1.73 stars before and after)

## Open questions
- Which sellers/regions/product categories drive lateness?
- What is a late order worth in lost repeat purchases?

Lateness is geographic, not category-driven — Northeast states run up to 24% late vs ~6% in the São Paulo region; RJ is the biggest concentrated opportunity

Recommendation. Late deliveries are the single biggest driver of 1-star reviews (46% vs 6.6%), and they are geographic, not product-related — concentrated on the long-haul lanes from the São Paulo hub to the Northeast (Alagoas 24%, Maranhão 20%, Ceará 15%) and to Rio de Janeiro (13.5%). I'd prioritize two moves: (1) Target Rio de Janeiro first — it combines a high late rate with the largest order volume (12,350), so carrier/SLA improvements there recover the most reviews per dollar; (2) Recalibrate delivery-date promises for the Northeast — if we can't yet ship faster, setting more realistic estimated dates would cut the "arrived late" gap that triggers 1-star reviews, since lateness is measured against our own promise.

Quantified impact: Bringing RJ's late rate to the national average would recover an estimated ~250–360 one-star reviews — from a single lane, before touching the Northeast.