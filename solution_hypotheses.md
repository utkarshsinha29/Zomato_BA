# Solution Hypotheses

This document maps identified root causes to potential solutions
that can improve order conversion and reduce revenue leakage.

## Root Cause → Solution Mapping

### 1. Card Payment Failures
**Problem:** Card payments show the highest failure rate.

**Hypothesis:** Improving card payment reliability and retry logic
will increase checkout-to-payment conversion.

**Proposed Solutions:**
- Smart retry mechanism for card payments
- Clearer error messaging with retry CTA
- Auto-fallback to UPI on failure

---

### 2. Early Funnel Drop (Menu → Cart)
**Problem:** High drop-off before checkout initiation.

**Hypothesis:** Improving menu clarity and price transparency
will increase add-to-cart rate.

**Proposed Solutions:**
- Show delivery ETA upfront on menu
- Highlight popular items / bestsellers
- Simplify pricing and reduce surprise charges

---

### 3. Delivery SLA Breaches
**Problem:** Longer delivery times increase cancellations.

**Hypothesis:** Improving delivery time predictability will
reduce cancellations.

**Proposed Solutions:**
- Accurate ETA display before checkout
- Priority assignment to experienced delivery partners
