# Data Quality Governance Workflow for Underwriting, Billing, and Claims

## Business Context
This project addresses enterprise data quality governance across LifePlus, FAST, SQL Server, PostgreSQL, Snowflake, AWS Redshift, Microsoft Purview, and reporting layers.

## Objective
Build a governance-led data quality operating model with business rules, severity and triage, lineage-based root cause analysis, issue remediation workflows, SLA tracking, and KPI reporting.

## In-Scope Domains
- Underwriting
- Billing
- Claims
- Policy administration
- Beneficiary data
- Payment-related data where applicable
- Health-related data where applicable

## Governance Layers
- Data quality rules
- Data profiling and monitoring
- Lineage-based issue tracing
- Root cause classification
- Remediation ownership
- KPI and SLA reporting
- Compliance-aware issue handling

## Compliance / Privacy Overlay
This project includes quality governance controls for:
- PCI DSS-sensitive billing/payment data
- PHI / HIPAA-related health data handling
- GDPR personal data accuracy and traceability needs
- CCPA consumer data handling, correction, and response readiness

## Cross-System Workflow
LifePlus / FAST → SQL Server / PostgreSQL → Snowflake / Redshift → Data quality checks → Microsoft Purview lineage tracing → Issue intake / remediation workflow → Power BI KPI dashboard
