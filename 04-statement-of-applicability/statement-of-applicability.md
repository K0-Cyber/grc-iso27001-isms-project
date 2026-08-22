# Statement of Applicability (SoA)

## Purpose

This document records a representative selection of ISO/IEC 27001:2022 Annex A controls for EugTech Solutions Ltd.

The Statement of Applicability demonstrates how Annex A controls are considered in the context of the organisation, its information security risks, and its ISMS.

It supports ISO/IEC 27001:2022 Clause 6.1.3.

## Scope of This Portfolio SoA

ISO/IEC 27001:2022 Annex A contains 93 controls.

A complete production Statement of Applicability would assess all 93 controls and document whether each control is applicable, together with justification and implementation status.

This portfolio version demonstrates the methodology using a representative selection of controls across all four Annex A themes:

1. Organisational controls
2. People controls
3. Physical controls
4. Technological controls

## Status Definitions

| Status | Meaning |
|---|---|
| Implemented | Control is represented as implemented within the simulated ISMS |
| Partially Implemented | Control has been partly implemented but further work remains |
| Not Implemented | Applicable control has not yet been implemented |
| Not Applicable | Control is not applicable and would require documented justification |

> **Portfolio Evidence Note:** Some evidence references below relate to planned supporting technical labs. Those technical evidence files will be added to `10-evidence/` when the relevant labs are completed. Their absence from the current repository does not mean they have already been technically validated.

---

# Theme 1 — Organisational Controls

## Annex A 5.1–5.37

| Clause | Control | Implementation | Evidence | Status |
|---|---|---|---|---|
| A5.1 | Policies for information security | Information Security Policy v1.0 approved by board, reviewed annually, and communicated to all staff | Signed policy document, staff acknowledgement register | Implemented |
| A5.2 | Information security roles and responsibilities | ISM role defined in job description. RACI matrix documented for security activities | Org chart, job descriptions, RACI matrix | Implemented |
| A5.9 | Inventory of information and other associated assets | Asset register covering information assets with owner, classification, and location | Asset register, quarterly review records | Implemented |
| A5.10 | Acceptable use of information and assets | Acceptable Use Policy distributed to staff at onboarding and annually thereafter | Signed AUP acknowledgements, training completion records | Implemented |
| A5.12 | Classification of information | Four-tier classification scheme: Public, Internal, Confidential, Restricted. Labelling policy enforced | Classification policy, labelled sample documents | Implemented |
| A5.15 | Access control | Access provisioned through Entra ID using least-privilege RBAC. Quarterly access reviews through PIM | Entra ID role assignments, access review reports | Partially Implemented |
| A5.17 | Authentication information | MFA enforced for all accounts through Conditional Access. Password policy minimum 12 characters | Conditional Access policy screenshots, MFA registration report | Implemented |
| A5.19 | Information security in supplier relationships | Supplier Security Policy with questionnaire for vendors. Contractual security clauses included | Supplier register, signed supplier agreements | Partially Implemented |
| A5.24 | Information security incident management planning | Incident Response Procedure documented with severity classification, escalation paths, and post-incident review | Incident Response Procedure, incident log | Implemented |
| A5.29 | Information security during disruption | Business Continuity Plan with RTO and RPO defined per service | BCP document, annual test results | Partially Implemented |
| A5.31 | Legal, statutory, regulatory and contractual requirements | UK GDPR compliance programme, Data Protection Act 2018 registration, and client contract review | ICO registration, legal register, contract templates | Implemented |

---

# Theme 2 — People Controls

## Annex A 6.1–6.8

| Clause | Control | Implementation | Evidence | Status |
|---|---|---|---|---|
| A6.1 | Screening | Background checks including DBS, references, and right-to-work checks for new hires and contractors | HR onboarding records, background check certificates | Implemented |
| A6.3 | Information security awareness, education and training | Annual security awareness training and quarterly phishing simulations. New starter training within 14 days | Training completion reports, phishing simulation results | Implemented |
| A6.4 | Disciplinary process | Disciplinary procedure covers information security violations. Security incidents are logged and investigated | HR policy, incident investigation records | Implemented |
| A6.5 | Responsibilities after termination or change of employment | Offboarding checklist includes account disabling, device return, and access revocation within 24 hours | Offboarding checklist, AD deactivation records | Implemented |
| A6.7 | Remote working | Remote Working Policy. VPN mandatory. Devices encrypted. Clean-screen requirements apply in public locations | Remote Working Policy, VPN logs, MDM compliance reports | Implemented |

---

# Theme 3 — Physical Controls

## Annex A 7.1–7.13

| Clause | Control | Implementation | Evidence | Status |
|---|---|---|---|---|
| A7.1 | Physical security perimeters | London office protected by key-card access, CCTV and visitor sign-in. Server room protected by keypad and CCTV | Access-control records, CCTV retention policy, visitor register | Implemented |
| A7.2 | Physical entry | Visitors escorted at all times. NDA required for sensitive areas. Visitor badges issued | Visitor register, escorting policy | Implemented |
| A7.7 | Clear desk and clear screen | Clear-desk policy enforced. Screens automatically lock after five minutes. Confidential waste shredded | Policy document, spot-check audit results | Partially Implemented |
| A7.8 | Equipment siting and protection | Laptop locks used in office. Servers hosted in Azure UK South under Microsoft physical security controls | Asset locations in asset register, Azure compliance documentation | Implemented |
| A7.9 | Security of assets off-premises | Laptop full-disk encryption using BitLocker. MDM remote-wipe capability. Encrypted USB only | MDM policy, BitLocker compliance report | Implemented |

---

# Theme 4 — Technological Controls

## Annex A 8.1–8.34

| Clause | Control | Implementation | Evidence | Status |
|---|---|---|---|---|
| A8.2 | Privileged access rights | PIM just-in-time access for administrative roles. No permanently assigned Global Administrator. Quarterly review | PIM assignment reports, access review records | Partially Implemented |
| A8.5 | Secure authentication | MFA mandatory through Conditional Access. FIDO2 for administrator accounts. Legacy authentication blocked | Conditional Access policy export, sign-in logs | Implemented |
| A8.7 | Protection against malware | Microsoft Defender for Endpoint on devices. Automatic updates and email anti-malware protection | Defender dashboard, AV policy, update compliance report | Implemented |
| A8.8 | Management of technical vulnerabilities | Monthly vulnerability scanning. Critical patches targeted within 72 hours | Scan reports, patch-management records | Partially Implemented |
| A8.9 | Configuration management | Azure Policy used for baseline configurations. NSG rules version-controlled in GitHub | Azure Policy compliance report, version-controlled NSG configuration | Partially Implemented |
| A8.12 | Data leakage prevention | Microsoft Purview DLP policies, sensitive-data classification, and email DLP rules | DLP policy configuration, DLP incident log | Partially Implemented |
| A8.13 | Information backup | Automated daily Azure Backup. Weekly full and daily incremental backup. Quarterly restore testing | Azure Backup policy, restore-test records | Implemented |
| A8.15 | Logging | Centralised logging through Microsoft Sentinel. Audit logs for privileged access with 90-day retention | Sentinel workspace, log-retention policy | Implemented |
| A8.16 | Monitoring activities | Sentinel analytics rules for threat detection and Defender for Cloud Secure Score monitoring | Sentinel alert rules, Defender for Cloud dashboard | Implemented |
| A8.20 | Networks security | VNet segmentation across public, private, and management subnets. NSG rules and network flow logs | NSG configuration, flow-log samples | Implemented |
| A8.24 | Use of cryptography | Data encrypted at rest using Azure Storage encryption. TLS 1.2+ in transit. Secrets stored in Key Vault | Key Vault configuration, encryption policy, TLS version reports | Implemented |
| A8.25 | Secure development lifecycle | Security requirements included in development. SAST scanning incorporated into CI/CD. Code review mandatory | Pipeline configuration, SAST reports, code-review records | Partially Implemented |

---

# Implementation Status Summary

| Theme | Implemented | Partially Implemented | Total Demonstrated |
|---|---:|---:|---:|
| Organisational | 8 | 3 | 11 |
| People | 5 | 0 | 5 |
| Physical | 4 | 1 | 5 |
| Technological | 7 | 5 | 12 |
| **Total** | **24** | **9** | **33** |

## Key Partially Implemented Controls

The portfolio identifies several controls requiring further maturity:

- A5.15 — Access control
- A5.19 — Supplier relationships
- A5.29 — Information security during disruption
- A7.7 — Clear desk and clear screen
- A8.2 — Privileged access rights
- A8.8 — Technical vulnerability management
- A8.9 — Configuration management
- A8.12 — Data leakage prevention
- A8.25 — Secure development lifecycle

These partial implementations provide input to:

- Risk treatment
- Internal audit
- Corrective action
- Management review
- Continual improvement

## Relationship to Other Project Documents

This Statement of Applicability links to:

- ISMS Scope Statement
- Information Security Policy
- Acceptable Use Policy
- Remote Working Policy
- Supplier Security Policy
- Risk Assessment Methodology
- Risk Register
- Risk Treatment Plan
- Asset Inventory
- Incident Response Procedure
- Business Continuity Plan
- Internal Audit Report
- Management Review Minutes

## Future Technical Evidence

The source project is designed to link selected Annex A controls to separate hands-on technical labs.

Planned examples include:

| Annex A Control | Planned Technical Evidence |
|---|---|
| A5.15 | Entra ID and Conditional Access |
| A5.17 | MFA and Conditional Access |
| A5.24 | Security incident-response lab |
| A8.2 | Privileged Identity Management |
| A8.5 | Authentication monitoring |
| A8.9 | Azure VNet and NSG configuration |
| A8.15 | Microsoft Sentinel |
| A8.16 | Microsoft Defender |
| A8.20 | VNet segmentation and NSG flow logs |
| A8.24 | Azure Key Vault |
| A8.25 | Secure development lab |

These technical evidence items will be added to the repository as the corresponding labs are completed.

## Status

Status: Portfolio SoA Demonstration  
ISO 27001 Mapping: Clause 6.1.3 and Annex A  
Controls Demonstrated: 33 representative Annex A controls  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
