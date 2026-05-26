# Customer Security Questionnaire Response Pack

## Purpose

This response pack provides consistent, evidence-backed answers to common customer security questions.

## Response Table

| ID | Customer Question | Response | Evidence Reference |
|---|---|---|---|
| Q-001 | Do you enforce MFA for employees? | MFA is required for critical systems including email, password manager, billing systems, file storage, and admin accounts. | `iam-governance/mfa-enforcement-matrix.md` |
| Q-002 | Do you require MFA for administrator accounts? | Yes. Admin accounts require MFA and are included in quarterly access reviews. | `iam-governance/privileged-account-approval-workflow.md` |
| Q-003 | How do you remove access when an employee leaves? | Departing users follow the leaver workflow, including same-day account disablement, session revocation, file transfer, and permission removal. | `iam-governance/joiner-mover-leaver-workflow.md` |
| Q-004 | How often do you review user access? | High-risk systems and privileged access are reviewed quarterly. Contractor access may be reviewed monthly. | `iam-governance/quarterly-access-review-process.md` |
| Q-005 | Do you have an incident response process? | Yes. The incident response procedure defines identification, containment, investigation, eradication, recovery, and lessons learned. | `procedures/incident-response-procedure.md` |
| Q-006 | How do you review third-party vendors? | Vendors are reviewed based on data sensitivity, authentication controls, security documentation, incident notification, deletion/export, subprocessors, and business criticality. | `evidence/vendor-risk-scoring.md` |
| Q-007 | Do you have an acceptable use policy? | Yes. The acceptable use policy defines approved use, data handling rules, software restrictions, and reporting expectations. | `policies/acceptable-use-policy.md` |
| Q-008 | Do you train employees on security expectations? | Employees receive security awareness guidance covering MFA prompts, suspicious email, password handling, and data sharing. | `templates/security-awareness-one-pager.md` |
| Q-009 | How do you manage privileged access? | Privileged access requires business justification, MFA confirmation, owner approval, logging, and quarterly review. | `iam-governance/privileged-account-approval-workflow.md` |
| Q-010 | Do you maintain evidence for security controls? | Evidence references are maintained in access reviews, vendor reviews, technical validation checklists, and the traceability matrix. | `program/security-program-traceability-matrix.md` |
| Q-011 | How do you handle exceptions to security policies? | Exceptions require justification, risk statement, compensating control, expiration date, and approval. | `program/exception-handling-process.md` |
| Q-012 | How do you validate security settings in SaaS platforms? | A lightweight technical validation checklist reviews MFA, admins, external sharing, inactive users, and audit logging. | `technical-validation/google-workspace-security-audit.md` |

## Standard Response Language

When responding to customers, avoid overstating maturity. Use accurate wording such as:

```text
We maintain documented security governance processes for access control, MFA, incident response, vendor review, and security exceptions. These processes are reviewed periodically and supported by internal evidence such as access review records, policy review dates, and technical validation checklists.
```
