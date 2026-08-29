# Lifecycle Rules

## Unit Status
Suggested status path:

```text
Available
→ Pending
→ Reserved
→ Contracted / Sold
```

Additional statuses may include:
- Blocked
- Management Hold
- Cancelled
- Resale
- Handover Ready
- Delivered

## Reservation Rules
- Active reservation requires customer, unit, salesperson/channel, date, and expiry.
- Unit cannot have two overlapping active reservations.
- Expired reservation should release inventory unless explicitly extended.
- Reservation cancellation must retain history.

## Contract Rules
- Contract must reference one customer and one or more approved units according to business model.
- Contract value must reconcile to pricing and approved discounts.
- Payment schedule total must reconcile to contract receivable amount.
- Contract cancellation/reversal must remain auditable.

## Collection Rules
- Every receipt maps to contract/customer.
- Payment method must be recorded.
- Unallocated receipts require exception status.
- Returned cheque must reverse or reopen receivable according to policy.

## Commission Rules
- Commission basis must be explicit.
- Eligibility event must be defined.
- Approval and payment are separate statuses.
