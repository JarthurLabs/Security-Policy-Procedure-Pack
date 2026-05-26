# Small Business Security Policy & Procedure Pack

## Overview

This is a beginner GRC and security documentation portfolio project for a simulated small business that needs baseline cybersecurity governance, access control, vendor risk, incident response, and employee awareness documentation.

The first version of this project was intentionally documentation-focused. This updated version adds stronger **evidence of work**: control mapping, risk scoring, vendor risk scoring, before/after maturity improvement logic, screenshots, and a changelog.

> All company names, risks, users, vendors, and data are synthetic and safe for public GitHub use.

---

## Business Scenario

A 25-person professional services company called **Northstar Dental Billing LLC** handles customer billing records, employee data, and SaaS-based operational workflows. The company does not have a full security team, but leadership wants to improve security readiness before signing larger client contracts.

The company requested a lightweight security documentation package that could help with:

- Safer employee behavior
- Consistent account access practices
- Clear incident response steps
- Better third-party vendor review
- Stronger customer security questionnaire responses
- Practical alignment to common cybersecurity frameworks

---

## Role Alignment

This project is most relevant for:

- GRC Analyst
- Security Implementation Specialist
- Security Solutions Consultant
- Cybersecurity Analyst, governance-focused
- IAM Analyst, access-control-focused
- SaaS security documentation and onboarding roles

---

## Deliverables Created

| Deliverable | Purpose | Evidence File |
|---|---|---|
| Security policy pack | Establish baseline security expectations | `policies/` |
| Incident response procedure | Define repeatable response steps | `procedures/incident-response-procedure.md` |
| Control mapping | Connect documents to NIST CSF 2.0 and CIS Controls | `evidence/control-mapping.md` |
| Risk register | Show risk prioritization and remediation logic | `evidence/risk-register.md` |
| Vendor risk scoring example | Demonstrate third-party security review | `evidence/vendor-risk-scoring.md` |
| Before/after maturity analysis | Show improvement created by the documentation | `evidence/before-after-analysis.md` |
| Changelog | Show iteration and project improvement | `CHANGELOG.md` |

---

## Evidence of Work

This project goes beyond writing templates. It shows how I made security governance decisions.

### 1. Control Mapping

I mapped each document to relevant NIST CSF 2.0 functions and practical CIS Controls categories. This helps show that the documents are not random policies. Each one supports a security outcome.

See: [`evidence/control-mapping.md`](./evidence/control-mapping.md)

### 2. Risk Register

I created a simple risk scoring model using:

```text
Risk Score = Likelihood x Impact
```

This demonstrates prioritization instead of treating all security issues as equal.

See: [`evidence/risk-register.md`](./evidence/risk-register.md)

### 3. Vendor Risk Scoring

I created a vendor risk scoring example for a simulated SaaS vendor. This shows how a small business could assess third-party risk before approving a tool.

See: [`evidence/vendor-risk-scoring.md`](./evidence/vendor-risk-scoring.md)

### 4. Before/After Improvement Logic

I documented the company’s assumed starting state, the improvement made by each deliverable, and the remaining gaps.

See: [`evidence/before-after-analysis.md`](./evidence/before-after-analysis.md)

---

## Frameworks Referenced

This project uses lightweight mapping to:

- **NIST Cybersecurity Framework 2.0**
- **CIS Controls v8 / v8.1 concepts**

The purpose is not to claim full compliance. The purpose is to show practical beginner-level GRC thinking: mapping business needs, risks, policies, and controls.

---

## Screenshots

| Screenshot | What It Shows |
|---|---|
| `screenshots/control-mapping-overview.svg` | How documents map to controls |
| `screenshots/risk-register-overview.svg` | Risk scoring and prioritization |
| `screenshots/vendor-risk-scorecard.svg` | Vendor review logic |
| `screenshots/policy-pack-overview.svg` | Policy deliverables created |

---

## How This Would Be Used in a Real Company

A small company could use this package as a starting point to:

1. Set clear employee security expectations.
2. Standardize onboarding and offboarding.
3. Require MFA for important systems.
4. Review vendor risk before approving new SaaS tools.
5. Respond more consistently to suspected security incidents.
6. Prepare better answers for customer security questionnaires.

This would not replace a formal audit, legal review, compliance program, or enterprise security team. It is a practical baseline designed for a small organization that needs structure.

---

## Interview Explanation

Use this explanation:

> I created this project to demonstrate beginner GRC and security documentation skills. I started with a realistic small-business scenario, created baseline security policies and procedures, then improved the project by adding evidence of work: control mapping, a risk register, vendor risk scoring, before/after maturity logic, screenshots, and a changelog. My goal was to show not just that I can write policies, but that I understand why each document exists and how it reduces business risk.

---

## What This Demonstrates

- Security documentation
- GRC thinking
- Control mapping
- Basic risk scoring
- Vendor risk review
- Incident response process design
- Access control governance
- Executive-ready communication
- Practical security implementation planning

---

## Limitations

This is a beginner portfolio project using synthetic data. It does not claim:

- Formal compliance certification
- Legal approval
- Full NIST CSF implementation
- Full CIS Controls implementation
- Production security assessment
- Real customer or company evidence

---

## Repository Structure

```text
.
├── README.md
├── CHANGELOG.md
├── HOW_TO_EXPLAIN.md
├── policies/
├── procedures/
├── evidence/
├── data/
├── reports/
├── screenshots/
└── templates/
```
