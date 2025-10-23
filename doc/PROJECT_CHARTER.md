# Project Charter — PRT BI Deep Dive
## Purpose
Transform PRT raw operational data into a Power BI dashboard enabling operational & strategic decisions.
## Scope
Ingest 5 CSVs → PostgreSQL staging → warehouse star schema → Power BI dataset & multi-page report.
## Key Stakeholders
- Sponsor: [Name / Role]
- Product Owner: [Name]
- Data Engineer: [You]
- BI Lead: Theo Ola
## KPIs (MVP)
- On-Time Performance (% on-time) by route/day
- Avg riders per route/day
- Peak-hour ridership per route
- Route Utilization (ons / scheduled trips)
## Acceptance Criteria
- SQL ↔ DAX parity for OTP and Avg riders
- Dataset published to PowerBI Service and scheduled refresh configured
