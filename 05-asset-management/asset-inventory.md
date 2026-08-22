# Information Asset Inventory

## Purpose

This document records key information assets within the EugTech Solutions Ltd Information Security Management System.

It supports ISO/IEC 27001:2022 Annex A control **A5.9 — Inventory of Information and Other Associated Assets**.

## Asset Classification Scheme

EugTech Solutions Ltd uses four information classification levels:

| Classification | Description |
|---|---|
| Public | Information that can be freely shared externally, such as marketing materials and public website content |
| Internal | Information intended for staff use and not for external sharing without approval |
| Confidential | Business-sensitive information shared only on a need-to-know basis |
| Restricted | Highest-sensitivity information with tightly controlled access |

Examples of Restricted information include:

- Client personal data
- Passwords
- Cryptographic keys
- Legal matters
- Financial records
- Employee personal data

## Information Asset Inventory

| Asset ID | Asset Name | Asset Type | Classification | Owner | Location | Controls Applied |
|---|---|---|---|---|---|---|
| A-001 | Client personal data (Azure Blob) | Data | Restricted | Head of Delivery | Azure UK South | Encryption at rest, RBAC, audit logging, Key Vault |
| A-002 | Source code repositories (GitHub) | Software | Confidential | Dev Lead | GitHub Enterprise | Branch protection, secret scanning, 2FA mandatory |
| A-003 | Microsoft 365 tenant | System | Confidential | IT Manager | Microsoft Cloud | MFA, Conditional Access policies, DLP, Defender for Office 365 |
| A-004 | Azure subscription | System | Restricted | ISM | Azure UK South | RBAC, Defender for Cloud, Sentinel, activity logging |
| A-005 | Staff laptops (50 devices) | Hardware | Confidential | IT Manager | Staff locations | BitLocker, MDM, antivirus, auto-lock, VPN |
| A-006 | Client contracts | Data | Restricted | Legal Counsel | SharePoint (encrypted) | Access restricted to Partners and Legal, audit logging |
| A-007 | Financial records | Data | Restricted | Finance Director | SharePoint + local NAS | RBAC, backup, physical access control |
| A-008 | Staff personal data (HR) | Data | Restricted | HR Manager | HR System (cloud) | GDPR controls, access restricted to HR, retention schedule |
| A-009 | AWS accounts (client-managed) | System | Confidential | Cloud Architect | AWS eu-west-2 | IAM, CloudTrail, GuardDuty, SCPs |
| A-010 | VPN infrastructure | System | Confidential | IT Manager | Azure + on-premise | Certificate-based authentication, log monitoring, patch management |

## Asset Ownership

Each information asset must have an assigned owner.

Asset owners are responsible for:

- Ensuring the asset is appropriately classified
- Confirming access remains appropriate
- Ensuring security controls remain suitable
- Supporting periodic asset reviews
- Reporting significant changes affecting the asset
- Supporting risk assessment activities relating to the asset

## Asset Management Requirements

Information assets within the ISMS must:

- Be recorded in the asset inventory
- Have an identified owner
- Have an assigned classification
- Have their location recorded
- Have appropriate controls documented
- Be reviewed periodically

## Relationship to Risk Management

The asset inventory supports the information security risk assessment process.

Assets within this register are considered when identifying:

- Threats
- Vulnerabilities
- Potential impacts
- Existing controls
- Required treatment actions

Examples include:

| Asset | Related Risk |
|---|---|
| Client personal data | Unauthorised access and excessive data retention |
| Staff laptops | Theft or loss exposing client information |
| Source code repositories | Hardcoded credentials committed to GitHub |
| Microsoft 365 | Business email compromise |
| Azure subscription | Unauthorised cloud access |
| AWS accounts | Supplier and cloud access risk |
| VPN infrastructure | Man-in-the-middle attacks affecting remote workers |

## Review

The asset inventory should be reviewed:

- Quarterly
- After significant system changes
- When new assets are introduced
- When assets are retired
- Following significant organisational change
- During internal audit
- When asset ownership changes

## Status

Status: Implemented  
ISO 27001 Mapping: Annex A A5.9  
Assets Documented: 10  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
