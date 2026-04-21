# Inventory, Vendor & Stock Analytics Dashboard
**Power BI | DAX | SQL Server | SAP ERP | Star Schema**

## Overview
A 360° inventory visibility dashboard built for operations 
and procurement teams — tracking stock movement, vendor 
balances, and production stage status in real time.

Replaced multiple static Excel reports used across 
operations and procurement with a single, drill-down 
Power BI solution connected directly to SAP ERP data.

## Business impact
- Eliminated multiple manual Excel reports for ops & procurement
- Gave management real-time visibility into vendor balances 
  and stock levels
- Drill-down capability reduced ad-hoc data requests to 
  the BI team

## Dashboard pages
| Page | What it shows |
|------|--------------|
| Stock overview | Current stock levels by SKU, category, location |
| Stock movement | Inflow, outflow, and net movement over time |
| Vendor balances | Outstanding payables and vendor-wise stock supply |
| Production tracking | Stage-wise production pipeline status |
| Ageing analysis | Slow-moving and dead stock identification |

## Key DAX measures
- Stock turnover ratio
- Days inventory outstanding (DIO)
- Vendor-wise supply share %
- Dead stock flag (items with 0 movement > 90 days)
- Production stage completion %

## Tech stack
| Layer | Tool |
|-------|------|
| Visualisation | Power BI Desktop & Service |
| Data model | Star schema (fact + dimension tables) |
| Data source | SAP ERP (via SQL Server) |
| ETL | SQL Server + Power Query (M) |
| DAX | Inventory KPIs, ageing logic, drill-through |

## Screenshots
[Add 2–3 dashboard screenshots here]

## Data note
All data in this repo uses anonymised/sample data.
Production dashboard runs on live SAP ERP data.
