# Data Quality Checklist

## Units
- [ ] Unique unit ID
- [ ] Valid project
- [ ] Valid status
- [ ] No duplicate unit code within defined scope
- [ ] Price >= 0

## Customers
- [ ] Unique customer ID
- [ ] Duplicate-detection rules
- [ ] Protected contact data
- [ ] Valid segmentation values

## Reservations
- [ ] Valid customer
- [ ] Valid unit
- [ ] No overlapping active reservation
- [ ] Expiry date present

## Contracts
- [ ] Valid customer/unit
- [ ] Net value reconciles
- [ ] Payment schedule reconciles
- [ ] Cancellation reason for cancelled contracts

## Collections
- [ ] Valid contract/customer
- [ ] Positive posted amount
- [ ] Valid payment method
- [ ] Reversals linked to source

## Commissions
- [ ] Valid source transaction
- [ ] Beneficiary exists
- [ ] Rate/basis traceable
- [ ] Approval state valid
