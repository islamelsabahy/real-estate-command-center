# Contract Reconciliation

For each active contract:

```text
Net Contract Value
= Down Payment
+ Sum(Future / Due Installments)
+ Approved Other Charges
```

Validation should flag:
- payment schedule total != receivable contract value
- missing installment dates
- negative installments
- duplicate installment sequence
- receipt greater than open balance without approved allocation logic
- cancelled contract with active unpaid commission
