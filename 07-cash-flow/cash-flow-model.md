# Cash Flow Forecast Model

## Contractual Forecast

Uses payment schedule due dates.

```text
Monthly Contractual Inflow
= Sum(amount_due by due month)
```

## Expected Forecast

Uses expected collection date after applying collection assumptions.

```text
Expected Inflow
= Sum(open amount assigned to expected_collection_date)
```

## Recommended Views
- Monthly 12-month forecast
- Quarterly forecast
- Project forecast
- Customer concentration
- Due vs expected
- Forecast vs actual
- Best / Base / Stress scenario

## Example Collection Assumptions

| Risk Class | Expected Timing |
|---|---|
| Low | On due date |
| Medium | Due date + 15 days |
| High | Due date + 45 days |
| Critical | Manual forecast |

These are illustrative assumptions only.
