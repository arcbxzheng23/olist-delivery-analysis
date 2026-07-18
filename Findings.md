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