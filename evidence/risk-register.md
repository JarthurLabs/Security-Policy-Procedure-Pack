# Risk Register

## Purpose

This risk register shows how a small business could prioritize security gaps discovered during documentation and governance review.

## Scoring Method

| Score | Likelihood | Impact |
|---|---|---|
| 1 | Rare | Minimal operational impact |
| 2 | Unlikely | Limited inconvenience |
| 3 | Possible | Moderate business disruption |
| 4 | Likely | Significant business or customer impact |
| 5 | Very likely | Severe business, legal, or customer trust impact |

```text
Risk Score = Likelihood x Impact
```

| Risk ID | Risk | Likelihood | Impact | Inherent Risk Score | Existing Control Gap | Recommended Control | Owner | Status |
|---|---|---:|---:|---:|---|---|---|---|
| R-001 | Former employees or contractors retain SaaS access | 4 | 5 | 20 | No documented offboarding checklist | Access control standard and offboarding checklist | Operations Manager | Open |
| R-002 | Weak passwords or missing MFA lead to account takeover | 4 | 5 | 20 | MFA not required for all business-critical apps | Password and MFA standard | IT Admin | In Progress |
| R-003 | Employees mishandle customer billing data | 3 | 5 | 15 | No acceptable use or data handling rules | Acceptable use policy and awareness guide | Compliance Lead | Open |
| R-004 | Security incidents are handled inconsistently | 3 | 4 | 12 | No incident response procedure | Incident response procedure | Operations Manager | In Progress |
| R-005 | New SaaS vendors are approved without security review | 3 | 4 | 12 | No vendor review checklist | Vendor risk review checklist | Department Manager | Open |
| R-006 | Employees fail to report phishing attempts | 3 | 3 | 9 | No security awareness guidance | Security awareness one-pager | IT Admin | Planned |

## Prioritization Logic

The first two risks are prioritized because they combine high likelihood with high impact. Account access failures are often easier to prevent than recover from, especially in small businesses without a full security team.

## How to Explain This in an Interview

> I used a simple likelihood-and-impact scoring model so the project would show prioritization. I did not want every policy to look equally important. Access and authentication risks scored highest because they could directly lead to unauthorized access to business systems.
