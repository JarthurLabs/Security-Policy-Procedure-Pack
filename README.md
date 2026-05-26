# Small Business Security Governance Program

## Overview

This repository contains a lightweight security governance program for a simulated 25-person professional services company, **Northstar Dental Billing LLC**. The program is designed to improve operational security around identity and access management, policy governance, vendor risk, incident response, and customer security assurance.

The materials are intentionally practical. They are written for a small organization that needs clearer ownership, repeatable processes, and evidence-ready documentation without overbuilding an enterprise compliance program.

> All company names, users, vendors, systems, and data are synthetic and safe for public use.

---

## Business Scenario

Northstar Dental Billing LLC uses common SaaS tools for email, file storage, CRM, billing support, password management, project management, and customer communication. The company is beginning to receive more customer security questions and wants to improve its security readiness before pursuing larger client contracts.

The business needs a small but structured security program that can answer five questions:

1. Who owns security decisions?
2. How is employee access requested, changed, reviewed, and removed?
3. How are vendors reviewed before they are approved?
4. What happens when a security incident is reported?
5. What evidence supports customer security questionnaire responses?

---

## Program Objectives

| Objective | Why It Matters |
|---|---|
| Establish security ownership | Reduces confusion and improves accountability |
| Standardize IAM governance | Reduces excessive access, orphaned accounts, and privilege creep |
| Create policy and procedure baselines | Gives employees and managers clear expectations |
| Connect risks to controls and procedures | Supports traceability and audit readiness |
| Add customer assurance evidence | Supports sales, implementation, and customer trust conversations |
| Add technical validation | Shows governance is connected to actual operational checks |

---

## Repository Structure

```text
.
├── README.md
├── CHANGELOG.md
├── COMMIT_GUIDE.md
├── policies/
├── procedures/
├── iam-governance/
├── program/
├── customer-assurance/
├── technical-validation/
├── evidence/
├── data/
├── reports/
├── screenshots/
└── templates/
```

---

## Core Deliverables

| Area | Deliverables |
|---|---|
| IAM Governance | Joiner/mover/leaver workflow, access request form, quarterly access review, privileged account approval, MFA enforcement matrix, role-based access examples |
| Security Program Operations | Security roadmap, 30/60/90-day remediation plan, ownership chart, exception handling, policy review schedule, KPIs |
| GRC Traceability | Security program traceability matrix connecting business risks, policies, controls, procedures, owners, and status |
| Policy Governance | Acceptable use, password/MFA, access control, incident response, vendor risk, awareness material |
| Customer Assurance | Mock customer security questionnaire and evidence-backed response pack |
| Technical Validation | Lightweight Google Workspace-style security audit checklist with MFA, admin, sharing, and logging validation |
| Evidence | Risk register, vendor scorecard, before/after maturity analysis, screenshots, CSV evidence files |

---

## Security Program Traceability

The traceability matrix is the center of this repository. It connects business risk to security documentation and operational controls.

See: [`program/security-program-traceability-matrix.md`](./program/security-program-traceability-matrix.md)

| Business Risk | Policy | Control | Procedure | Owner | Status |
|---|---|---|---|---|---|
| Credential theft | Password and MFA Standard | MFA enforcement | IAM access review | IT Administrator | Implemented |
| Orphaned accounts | Access Control Standard | JML workflow | Offboarding checklist | Operations Manager | Implemented |
| Vendor data exposure | Vendor Risk Standard | Vendor scorecard | Vendor review checklist | Business Owner | In Progress |
| Delayed incident response | Incident Response Procedure | Escalation workflow | Incident response procedure | Operations Manager | Implemented |

---

## IAM Governance Highlights

Identity and access management is the strongest operational focus of this program. The IAM section defines how access is requested, approved, changed, reviewed, and removed.

See: [`iam-governance/`](./iam-governance/)

Key IAM deliverables:

- Joiner / mover / leaver workflow
- Access request form
- Quarterly access review process
- Privileged account approval workflow
- MFA enforcement matrix
- Role-based access examples
- Offboarding checklist

---

## Technical Validation Layer

This repository includes a lightweight technical validation layer to connect governance documents to system-level checks.

See: [`technical-validation/google-workspace-security-audit.md`](./technical-validation/google-workspace-security-audit.md)

The validation checklist reviews:

- MFA enforcement
- Super admin account limits
- External file sharing
- Inactive users
- Password manager adoption
- Login alerting
- Admin audit log review
- Group-based access

This is not a production audit. It is a small operational validation example showing how governance requirements can be checked against SaaS administration settings.

---

## Customer Security Questionnaire Pack

Customer-facing security assurance is included because small SaaS and services companies often need to answer security questions during sales, onboarding, renewal, and vendor review.

See: [`customer-assurance/questionnaire-response-pack.md`](./customer-assurance/questionnaire-response-pack.md)

The response pack includes evidence references for questions like:

- Do you enforce MFA?
- How do you handle employee offboarding?
- How do you review vendors?
- Do you have an incident response process?
- How often do you review access?

---

## Framework Alignment

This repository uses practical mapping to:

- NIST Cybersecurity Framework 2.0
- CIS Controls v8.1 concepts

The mapping is intentionally lightweight. It is used to organize governance work, not to claim formal compliance certification.

---

## How This Would Operate in a Real Company

1. Leadership assigns owners for security, IT administration, vendor review, and incident response.
2. Access requests follow the access request workflow.
3. Role changes trigger mover reviews.
4. Departures trigger same-day access removal.
5. Admin access requires documented approval.
6. Vendors are scored before approval.
7. Policies are reviewed on a defined schedule.
8. Security metrics are reported monthly.
9. Customer questionnaire responses reference supporting evidence.
10. Technical validation checks confirm whether controls are operating.

---

## Limitations

This repository does not represent:

- A formal audit
- Legal advice
- Full NIST CSF implementation
- Full CIS Controls implementation
- Production security certification
- Real customer evidence
- A SOC or penetration testing project

It is a practical small-business governance model built with synthetic data.
