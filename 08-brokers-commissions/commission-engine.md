# Commission Engine

## Formula

```text
Commission Amount
= Approved Basis Amount × Commission Rate
```

## Possible Basis Amounts
- Net contract value
- Collected amount
- Eligible collected amount
- Unit base price
- Net selling price
- Other approved commercial basis

## Suggested Status Flow

```text
Calculated
→ Pending Eligibility
→ Eligible
→ Pending Approval
→ Approved
→ Payable
→ Paid
```

## Example Commission Dimensions
- Direct / Indirect
- Salesperson
- Team
- Internal broker
- External broker
- Project
- Unit
- Contract
- Collection milestone

## Control Principles
- Rule effective date must be stored.
- Rate source must be traceable.
- Manual overrides require approval.
- Cancelled contracts trigger eligibility review.
- Paid commissions cannot silently disappear after reversal.
