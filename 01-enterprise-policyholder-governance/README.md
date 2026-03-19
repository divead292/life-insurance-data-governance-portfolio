# Enterprise Policyholder & Producer Governance Framework

## Business Context
This project models a life insurance data governance framework across LifePlus, FAST, SQL Server, PostgreSQL, Snowflake, AWS Redshift, Microsoft Purview, and Power BI.

## Objective
Design an enterprise governance framework for policyholder, producer, beneficiary, policy, billing, and underwriting data with clear ownership, stewardship, classification, access control, DLP, and auditability.

## Scope
- Policyholder
- Producer
- Beneficiary
- Policy
- Billing
- Underwriting class
- Payment-related data where applicable
- Health-related underwriting data where applicable

## Governance Layers
- Data ownership and stewardship
- Critical data elements (CDEs)
- Business glossary
- Data classification
- Data security and DLP
- Access control model
- Governance workflow and approvals

## Compliance / Privacy Overlay
This project includes governance design considerations for:
- PCI DSS where payment card data is present
- PHI / HIPAA where health-related protected data is processed by regulated entities
- GDPR where EU personal data is in scope
- CCPA where California consumer personal information is in scope

## Workflow Across Applications
LifePlus / FAST → SQL Server / PostgreSQL → Snowflake / Redshift → Microsoft Purview classification and metadata → Access and DLP controls → Power BI governed reporting → Audit and governance review
