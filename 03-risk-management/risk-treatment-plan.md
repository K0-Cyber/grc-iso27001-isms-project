# Risk Treatment Plan

## Purpose

This document records actions taken or planned to reduce unacceptable information security risks to acceptable levels.

It supports ISO/IEC 27001:2022 Clause 6.1.3.

The Risk Treatment Plan links identified risks in the Risk Register to specific treatment actions.

## Risk Treatment Plan — EugTech Solutions Ltd

| Risk ID | Risk | Treatment Action | Owner | Target Date | Cost Estimate | Status |
|---|---|---|---|---|---|---|
| R-001 | Unauthorised client data access | Deploy Conditional Access policies CA-001 to CA-005. Migrate all credentials to Key Vault. Enable GuardDuty and Sentinel alerts. | ISM | Q1 2026 | £0 — Azure Free tier | In Progress |
| R-002 | Laptop theft | Enable BitLocker on all laptops via Intune policy. Enrol all devices in MDM. Configure remote wipe. | IT Manager | Complete | £1,200/year MDM licence | Implemented |
| R-003 | Hardcoded credentials | Implement GitGuardian pre-commit scanning. Migrate all secrets to Key Vault. Provide developer training on secrets hygiene. | Dev Lead | Q1 2026 | £0 — GitGuardian free tier | In Progress |
| R-005 | Phishing attack | Deploy quarterly phishing simulations using KnowBe4 or a free alternative. Conduct security awareness training. Enforce DMARC. | ISM | Q2 2026 | £3,000/year training platform | In Progress |
| R-008 | Business email compromise | Configure DMARC with reject policy, DKIM and SPF for all email domains. Enable Defender for Office 365 advanced phishing protection. | IT Manager | Complete | £0 — included in Microsoft 365 | Implemented |
| R-010 | Key-person dependency | Document critical processes in the knowledge base. Identify backup persons for each key role. Establish a cross-training programme. | CEO | Q3 2026 | £0 — internal effort | Open |

## Treatment Status Summary

| Status | Risks |
|---|---|
| Implemented | R-002, R-008 |
| In Progress | R-001, R-003, R-005 |
| Open | R-010 |

## Relationship to the ISMS

The Risk Treatment Plan links to:

- Risk Assessment Methodology
- Risk Register
- Statement of Applicability
- Annex A control implementation
- Internal audit
- Management review

Treatment activities may result in controls being selected or updated in the Statement of Applicability.

## Treatment Monitoring

Treatment actions should be reviewed against:

- Assigned owner
- Target date
- Implementation progress
- Cost
- Control effectiveness
- Residual risk

Completed actions should be reflected in the Risk Register and supporting control evidence.

## Status

Status: Implemented  
ISO 27001 Mapping: Clause 6.1.3  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
