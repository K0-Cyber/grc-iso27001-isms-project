# ISO/IEC 27001:2022 GRC & ISMS Implementation Project

## Project Overview

This portfolio project simulates the implementation of an Information Security Management System (ISMS) aligned to ISO/IEC 27001:2022 for EugTech Solutions Ltd, a fictional UK technology consultancy providing cloud consultancy and managed services to SME clients.

The project demonstrates how ISO 27001 requirements can be translated into practical Governance, Risk and Compliance (GRC) documentation, including ISMS scope definition, policy development, information security risk assessment, risk treatment, Annex A control selection, asset management, incident response, business continuity, internal audit, and management review.

The project covers the mandatory ISO/IEC 27001 management system clauses and demonstrates the methodology for applying a representative selection of Annex A controls across the organisational, people, physical, and technological control themes.

---

## Simulated Organisation

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| Sector | Technology — Cloud Consultancy and Managed Services |
| Size | 50 employees across London and remote UK |
| Clients | 20 SME clients across financial services, healthcare, and retail |
| Key Assets | Client data, source code, Azure/AWS cloud infrastructure, Microsoft 365, staff laptops |
| Regulatory Context | UK GDPR, Data Protection Act 2018, potential PCI-DSS requirements |
| ISMS Scope | Cloud services, managed services, and internal IT systems supporting client delivery |
| Standard | ISO/IEC 27001:2022 |
| Project Type | Simulated GRC and ISMS portfolio project |

---

## Why This Project

The purpose of this project is to demonstrate practical ISO 27001 and GRC capability beyond theoretical knowledge.

The project focuses on:

- Information security risk assessment and treatment
- Policy development at executive and operational levels
- Annex A control selection and justification
- Statement of Applicability methodology
- Information asset identification and classification
- Supplier security governance
- Incident response planning
- Business continuity
- Internal audit
- Management review
- Continual improvement
- Linking governance controls to technical evidence

---

## Project Deliverables

| Deliverable | ISO 27001 Reference | Purpose |
|---|---|---|
| ISMS Scope Statement | Clause 4.3 | Defines what is inside and outside the ISMS |
| Information Security Policy | Clause 5.2 | Demonstrates leadership commitment to information security |
| Acceptable Use Policy | Annex A A5.10 | Defines acceptable use of information and associated assets |
| Remote Working Policy | Annex A A6.7 | Defines information security requirements for remote working |
| Supplier Security Policy | Annex A A5.19 | Defines third-party and cloud supplier security requirements |
| Risk Assessment Methodology | Clause 6.1.2 | Defines how information security risks are identified and scored |
| Risk Register | Clause 6.1.2 | Records identified risks, ratings, owners, controls, and residual risk |
| Risk Treatment Plan | Clause 6.1.3 | Defines actions for treating unacceptable information security risks |
| Statement of Applicability | Clause 6.1.3 | Documents Annex A control applicability, implementation, evidence, and status |
| Asset Inventory | Annex A A5.9 | Records key information assets, owners, classification, location, and controls |
| Incident Response Procedure | Annex A A5.24 | Defines how security incidents are identified, contained, eradicated, recovered from, and reviewed |
| Business Continuity Plan | Annex A A5.29 | Defines how information security is maintained during disruption |
| Internal Audit Report | Clause 9.2 | Demonstrates systematic assessment of ISMS implementation |
| Management Review Minutes | Clause 9.3 | Demonstrates leadership review of ISMS performance and improvement |

---

## Repository Structure

```text
grc-iso27001-isms-project/
├── README.md
├── 01-scope/
│   └── isms-scope-statement.md
├── 02-policies/
│   ├── information-security-policy.md
│   ├── acceptable-use-policy.md
│   ├── remote-working-policy.md
│   └── supplier-security-policy.md
├── 03-risk-management/
│   ├── risk-assessment-methodology.md
│   ├── risk-register.md
│   └── risk-treatment-plan.md
├── 04-statement-of-applicability/
│   └── statement-of-applicability.md
├── 05-asset-management/
│   └── asset-inventory.md
├── 06-incident-response/
│   └── incident-response-procedure.md
├── 07-business-continuity/
│   └── business-continuity-plan.md
├── 08-internal-audit/
│   └── internal-audit-report.md
├── 09-management-review/
│   └── management-review-minutes.md
└── 10-evidence/
    └── Planned supporting evidence from technical security labs
```

---

## Risk Management Approach

The project uses a documented 5 × 5 information security risk assessment methodology.

### Risk Calculation

**Risk Score = Likelihood × Impact**

| Score | Classification | Response |
|---:|---|---|
| 1–8 | Low | Accept or monitor |
| 9–15 | Medium | Treat with controls and review |
| 16–25 | High | Immediate treatment and management escalation |

Each risk records:

- Asset
- Threat
- Likelihood
- Impact
- Risk rating
- Control
- Residual risk
- Status
- Risk owner
- Treatment action where required

The project risk register contains 10 information security risks including unauthorised cloud access, device loss, hardcoded credentials, excessive supplier access, phishing, ransomware, business email compromise, data retention, and key-person dependency.

---

## Statement of Applicability

The Statement of Applicability demonstrates how Annex A controls are assessed against the organisation's risk and business context.

The project demonstrates controls across all four ISO/IEC 27001:2022 Annex A themes:

1. **Organisational controls**
2. **People controls**
3. **Physical controls**
4. **Technological controls**

Each documented control records:

- Control reference
- Control name
- Implementation approach
- Supporting evidence
- Implementation status

Example controls include:

- A5.1 — Policies for information security
- A5.9 — Inventory of information and associated assets
- A5.15 — Access control
- A5.17 — Authentication information
- A5.19 — Information security in supplier relationships
- A5.24 — Information security incident management planning
- A5.29 — Information security during disruption
- A6.3 — Information security awareness, education and training
- A6.7 — Remote working
- A8.2 — Privileged access rights
- A8.5 — Secure authentication
- A8.8 — Management of technical vulnerabilities
- A8.15 — Logging
- A8.16 — Monitoring activities
- A8.20 — Network security
- A8.24 — Use of cryptography

---

## Information Asset Management

The project includes an information asset inventory containing 10 key assets.

Examples include:

- Client personal data stored in Azure
- GitHub source code repositories
- Microsoft 365 tenant
- Azure subscription
- Staff laptops
- Client contracts
- Financial records
- Staff HR data
- AWS accounts
- VPN infrastructure

Assets are classified using four levels:

| Classification | Meaning |
|---|---|
| Public | May be freely shared externally |
| Internal | Intended for internal staff use |
| Confidential | Business-sensitive and restricted to need-to-know access |
| Restricted | Highest-sensitivity information requiring tightly controlled access |

---

## Incident Response

The Incident Response Procedure uses a five-phase lifecycle:

```text
IDENTIFY
   ↓
CONTAIN
   ↓
ERADICATE
   ↓
RECOVER
   ↓
LEARN
```

Incidents are classified from:

- **P1 — Critical**
- **P2 — High**
- **P3 — Medium**
- **P4 — Low**

The procedure includes escalation, containment, forensic evidence preservation, recovery, lessons learned, risk-register updates, and assessment of UK GDPR breach-notification obligations.

---

## Internal Audit

The simulated internal audit assesses mandatory ISO 27001 clauses and selected Annex A controls.

The audit produced five findings:

| Finding Type | Count |
|---|---:|
| Minor Nonconformities | 2 |
| Observations | 3 |
| Major Nonconformities | 0 |

Key findings relate to:

- Supplier security questionnaire completion
- Vulnerability management formalisation
- Security awareness training completion
- ISMS KPI management review
- Contractor device asset registration

Corrective actions are assigned with responsible owners and target completion dates.

---

## Management Review

The management review demonstrates leadership involvement in ISMS performance.

Areas reviewed include:

- Security incidents
- Internal audit findings
- Security awareness completion
- Defender for Cloud Secure Score
- Supplier questionnaire completion
- Patch compliance
- Corrective actions
- Security budget
- Continual improvement

The project demonstrates the ISO 27001 improvement cycle from risk identification through implementation, audit, corrective action, and management review.

---

## Technical Evidence Integration

A future `10-evidence` folder will link the GRC documentation to technical evidence from separate hands-on cybersecurity labs.

Planned examples include:

```text
Sentinel-dashboard-screenshot.png
Defender-secure-score.png
EntraID-CA-policies.png
```

These technical labs have not yet been completed, so the evidence is intentionally not presented as implemented within this repository at this stage.

Once completed, the evidence will support controls such as:

| Annex A Control | Planned Technical Evidence |
|---|---|
| A5.15 Access Control | Entra ID and Conditional Access |
| A5.17 Authentication | MFA and Conditional Access |
| A8.2 Privileged Access | Entra ID Privileged Identity Management |
| A8.5 Secure Authentication | Authentication monitoring |
| A8.9 Configuration Management | Azure network and security configuration |
| A8.15 Logging | Microsoft Sentinel |
| A8.16 Monitoring | Microsoft Defender |
| A8.20 Network Security | Azure VNet and NSG configuration |
| A8.24 Cryptography | Azure Key Vault |

---

## Skills Demonstrated

- ISO/IEC 27001:2022
- Governance, Risk and Compliance (GRC)
- Information Security Management Systems
- Information Security Risk Assessment
- Risk Treatment
- Statement of Applicability methodology
- Annex A control mapping
- Information asset management
- Security policy development
- Supplier security governance
- Incident response
- Business continuity
- Internal auditing
- Management review
- Corrective action
- Continual improvement
- Audit evidence and traceability

---

## Portfolio Positioning

This project demonstrates the ability to translate ISO/IEC 27001 requirements into practical GRC documentation and an auditable management-system structure.

It is designed as portfolio evidence for roles including:

- GRC Analyst
- Compliance Analyst
- Information Security Analyst
- Risk Analyst
- Information Security Manager

---

## Disclaimer

This is a simulated portfolio project created for educational and professional development purposes.

EugTech Solutions Ltd is fictional. References to systems, controls, risks, audit findings, and management activity are simulated examples used to demonstrate ISO/IEC 27001:2022 implementation methodology.

This project does not represent ISO 27001 certification or a production ISMS.
