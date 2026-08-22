# Risk Assessment Methodology

## Purpose

This document defines the information security risk assessment methodology used by EugTech Solutions Ltd.

It supports ISO/IEC 27001:2022 Clause 6.1.2.

ISO 27001 does not prescribe a specific risk assessment methodology. The organisation must use an approach that is consistent, reproducible, and documented.

## Risk Assessment Approach

EugTech Solutions Ltd uses a 5 × 5 risk matrix.

Risk is calculated using:

**Risk Score = Likelihood × Impact**

Scores range from 1 to 25.

## Likelihood Scale

| Score | Likelihood |
|---:|---|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost Certain |

## Impact Scale

| Score | Impact |
|---:|---|
| 1 | Negligible |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Critical |

## Risk Scoring Matrix

| Likelihood \ Impact | 1 — Negligible | 2 — Minor | 3 — Moderate | 4 — Major | 5 — Critical |
|---|---:|---:|---:|---:|---:|
| 5 — Almost Certain | 5 | 10 | 15 | 20 | 25 |
| 4 — Likely | 4 | 8 | 12 | 16 | 20 |
| 3 — Possible | 3 | 6 | 9 | 12 | 15 |
| 2 — Unlikely | 2 | 4 | 6 | 8 | 10 |
| 1 — Rare | 1 | 2 | 3 | 4 | 5 |

## Risk Classification

| Risk Score | Classification | Required Response |
|---:|---|---|
| 1–8 | Low | Accept or monitor |
| 9–15 | Medium | Treat with controls and review quarterly |
| 16–25 | High | Immediate treatment required and escalation to management |

## Risk Assessment Process

The risk assessment process is:

1. Define risk criteria and organisational risk appetite.
2. Identify information assets from the asset inventory.
3. Identify threats and vulnerabilities affecting each asset.
4. Assess likelihood from 1 to 5.
5. Assess impact from 1 to 5.
6. Calculate the risk score using likelihood × impact.
7. Compare the risk against the organisation's risk criteria.
8. Select an appropriate risk treatment decision.
9. Apply controls where required.
10. Record residual risk after treatment.
11. Maintain the result in the Risk Register.

## Risk Treatment Options

Each identified risk must be considered for one of four treatment options:

| Treatment | Meaning |
|---|---|
| Accept | Retain the risk where it is within risk appetite |
| Treat | Implement controls to reduce likelihood and/or impact |
| Transfer | Transfer part of the risk through insurance, contract, or another party |
| Avoid | Stop the activity creating the risk |

## Residual Risk

Residual risk is the remaining risk after controls or treatment actions have been applied.

Residual risk must be documented so that management can determine whether the remaining exposure is acceptable.

## Risk Ownership

Information security risks must have an accountable risk owner.

Where treatment is required, actions, owners, target dates, costs, and implementation status are recorded in the Risk Treatment Plan.

## Review

The risk assessment and Risk Register must be reviewed:

- At least annually
- After significant organisational or technological change
- After significant security incidents
- When new threats or vulnerabilities are identified
- Where existing controls materially change

## Records Produced

This methodology produces:

- Risk Register
- Risk Treatment Plan
- Residual risk assessments
- Statement of Applicability inputs

## Status

Status: Implemented  
ISO 27001 Mapping: Clause 6.1.2  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
