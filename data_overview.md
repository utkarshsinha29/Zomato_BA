# Data Overview & Grain

| Table | Grain | Business Meaning |
|------|------|------------------|
| users | 1 row per user | Customer master |
| restaurants | 1 row per restaurant | Restaurant catalogue |
| orders | 1 row per order | Revenue-generating event |
| order_events | Multiple rows per order | User funnel tracking |
| payments | 1 row per order | Payment outcome |
| delivery | 1 row per order | Last-mile execution |
| delivery_partners | 1 row per partner | Delivery workforce |
