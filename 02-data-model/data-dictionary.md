# Core Data Dictionary

## projects

| Field | Type | Description |
|---|---|---|
| project_id | string | Unique project ID |
| project_name | string | Project name |
| status | enum | Active / Closed / Pipeline |
| location | string | Project location |
| launch_date | date | Launch date |

## units

| Field | Type | Description |
|---|---|---|
| unit_id | string | Unique unit ID |
| project_id | string | Related project |
| phase | string | Project phase |
| building | string | Building / cluster |
| unit_code | string | Commercial unit code |
| unit_type | string | Apartment / Villa / etc |
| area_sqm | decimal | Area |
| list_price | decimal | Current list price |
| status | enum | Available / Pending / Reserved / Sold |
| reservation_id | string | Current reservation if applicable |

## customers

| Field | Type | Description |
|---|---|---|
| customer_id | string | Unique customer |
| customer_name | string | Demo or protected name |
| segment | string | Local / Overseas / etc |
| source | string | Direct / Indirect |
| country | string | Geography |
| mobile | string | Protected field |

## contracts

| Field | Type | Description |
|---|---|---|
| contract_id | string | Unique contract |
| customer_id | string | Customer |
| unit_id | string | Unit |
| contract_date | date | Contract date |
| gross_value | decimal | Before discount |
| discount_value | decimal | Approved discount |
| net_contract_value | decimal | Final contract value |
| down_payment | decimal | Down payment |
| status | enum | Draft / Active / Cancelled / Completed |

## payment_schedule

| Field | Type | Description |
|---|---|---|
| installment_id | string | Unique installment |
| contract_id | string | Contract |
| due_date | date | Contractual due date |
| amount_due | decimal | Amount |
| installment_type | string | DP / Quarterly / Annual / etc |
| status | enum | Not Due / Due / Partial / Paid / Overdue |
| expected_collection_date | date | Forecast date |

## receipts

| Field | Type | Description |
|---|---|---|
| receipt_id | string | Unique receipt |
| contract_id | string | Contract |
| customer_id | string | Customer |
| receipt_date | date | Collection date |
| amount | decimal | Amount received |
| payment_method | string | Cash / Cheque / Transfer / etc |
| bank | string | Bank if relevant |
| status | enum | Posted / Pending / Reversed |

## commissions

| Field | Type | Description |
|---|---|---|
| commission_id | string | Unique commission |
| contract_id | string | Source contract |
| beneficiary_type | string | Salesperson / Broker / Team |
| beneficiary_id | string | Beneficiary |
| basis_amount | decimal | Calculation basis |
| commission_rate | decimal | Rate |
| commission_amount | decimal | Calculated amount |
| eligibility_status | enum | Pending / Eligible / Ineligible |
| approval_status | enum | Pending / Approved / Rejected |
| payment_status | enum | Unpaid / Partial / Paid |
