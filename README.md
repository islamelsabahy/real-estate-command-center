[![License](https://img.shields.io/github/license/islamelsabahy/real-estate-command-center)](LICENSE) [![Maintained by](https://img.shields.io/badge/maintained%20by-Islam%20El--sabahy-blue)](https://github.com/islamelsabahy)

# Real Estate Command Center

An executive operating model and analytics foundation for real-estate developers and brokerages.

The project brings sales, inventory, customers, contracts, collections, cash flow, brokers, commissions, and executive KPIs into one structured command center.

## Core Business Areas

- Projects and phases
- Units inventory
- Leads and opportunities
- Reservations and contracts
- Customers
- Payment schedules
- Collections
- Cheques
- Cash-flow forecasting
- Brokers
- Sales teams
- Commissions
- Executive KPIs
- Risk and exception reporting

## Business Lifecycle

```text
Lead
  ↓
Opportunity
  ↓
Unit Selection
  ↓
Reservation
  ↓
Contract
  ↓
Payment Schedule
  ↓
Collection
  ↓
Cheque / Payment Tracking
  ↓
Commission Eligibility
  ↓
Commission Approval
  ↓
Executive Reporting
```

## Executive Dashboard

### Commercial
- Total inventory value
- Available inventory
- Reserved inventory
- Sold inventory
- Sales value MTD / QTD / YTD
- Units sold
- Reservation conversion
- Sales cancellation rate
- Average selling price
- Sales by project / phase / unit type
- Sales by salesperson / team / channel

### Collections
- Contracted value
- Due to date
- Collected to date
- Collection %
- Outstanding receivables
- Overdue receivables
- Aging
- Upcoming installments
- Cheques due
- Returned / bounced cheques

### Cash Flow
- Expected monthly inflow
- Quarter forecast
- Project cash-flow forecast
- Customer concentration
- Collection risk
- Forecast vs actual

### Brokerage & Commissions
- Broker-attributed sales
- Commission earned
- Commission approved
- Commission paid
- Pending commissions
- Commission by channel
- Commission by salesperson / broker

## Repository Structure

```text
.
├── 01-business-model/
├── 02-data-model/
├── 03-sales/
├── 04-inventory/
├── 05-customers-contracts/
├── 06-collections/
├── 07-cash-flow/
├── 08-brokers-commissions/
├── 09-dashboard/
├── 10-controls/
├── templates/
├── sample-data/
├── examples/
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## Recommended Dimensions

- Project
- Phase
- Building
- Unit
- Unit type
- Sales channel
- Sales team
- Salesperson
- Broker
- Customer segment
- Customer geography
- Contract type
- Payment method
- Bank
- Collection status
- Reservation status
- Contract status
- Date

## Key Principles

1. One unit cannot have overlapping active reservations.
2. Every contract must reconcile to its payment schedule.
3. Every receipt must map to a customer, contract, and payment method.
4. Every commission must have a calculation basis and approval state.
5. Every KPI must trace back to transactional data.
6. Forecasts must distinguish contractual due dates from expected collection dates.
7. Cancellations and reversals must remain traceable.
8. Customer and payment data must be protected.
9. Demo/sample data must never contain real customer information.
10. Executive dashboards must show exceptions, not only totals.

## Roadmap

- [x] Business model
- [x] Core data model
- [x] Sales pipeline model
- [x] Inventory model
- [x] Customer and contract model
- [x] Collections model
- [x] Cash-flow forecast model
- [x] Broker and commission model
- [x] Executive KPI catalog
- [x] Dashboard specification
- [x] Data-quality controls
- [x] Sample CSV datasets
- [ ] Interactive dashboard app
- [ ] PostgreSQL/Supabase schema
- [ ] API layer
- [ ] Authentication and RBAC
- [ ] Automated alerts
- [ ] Odoo integration adapter
- [ ] AI executive summary

## Author

Eng. Islam El Sherbiny  
IT Management · Real Estate Technology · ERP/Odoo · Digital Transformation · AI & Automation
