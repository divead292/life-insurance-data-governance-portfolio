# Metadata, Lineage, Security, and DR Trust Model

## Business Context
This project creates a trust model for enterprise reporting and analytics across LifePlus, FAST, SQL Server, PostgreSQL, Snowflake, AWS Redshift, Microsoft Purview, and Power BI.

## Objective
Design a metadata, lineage, security, and disaster recovery governance model that improves trust, transparency, resilience, and auditability for reporting and analytics.

## Governance Layers
- Metadata management
- Data lineage
- Report certification
- Security classification
- DLP alignment
- Disaster recovery governance
- Audit evidence and control reporting

## Compliance / Privacy Overlay
This project includes trust and control design considerations for:
- PCI DSS where cardholder payment data exists
- PHI / HIPAA where health-related data is handled by regulated entities
- GDPR where EU personal data is processed or transferred
- CCPA where California consumer privacy rights and obligations apply

## Workflow Across Applications
LifePlus / FAST → SQL Server / PostgreSQL → Snowflake / Redshift → Microsoft Purview metadata and lineage → Power BI trusted reporting → DR and governance review
