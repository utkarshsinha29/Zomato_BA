# Data Quality Checks

## Primary Key Validation
- No duplicate user_id found in users
- No duplicate order_id found in orders
- No duplicate payment_id found in payments

## Referential Integrity
- All orders map to valid users
- All orders map to valid restaurants
- All payments map to valid orders
- All delivery records map to valid orders

## Null Checks
- No nulls in critical fields (IDs, order_value, order_status)
- failure_reason contains nulls for successful payments (expected)

## Date Range Validation
- Order dates range between 2024 and 2025

## Business Logic Checks
- No delivered orders with failed payments
- Cancelled orders do not have delivery times (or documented as limitation)
