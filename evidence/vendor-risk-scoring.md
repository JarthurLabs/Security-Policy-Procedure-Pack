# Vendor Risk Scoring Example

## Scenario

Northstar Dental Billing LLC is evaluating a SaaS document-sharing vendor called **FileBridge Cloud**. The vendor may store billing support documents and employee-uploaded files.

## Scorecard

| Category | Weight | Score | Weighted Score | Notes |
|---|---:|---:|---:|---|
| Data sensitivity | 20% | 4 | 0.80 | Vendor may store billing-related documents |
| Authentication controls | 20% | 2 | 0.40 | Supports MFA and SSO |
| Security documentation | 15% | 3 | 0.45 | Security page available; full report requires request |
| Incident notification | 15% | 3 | 0.45 | Notification terms need contract review |
| Data deletion/export | 10% | 2 | 0.20 | Export and deletion supported |
| Subprocessors | 10% | 3 | 0.30 | Subprocessor list needs review |
| Business criticality | 10% | 3 | 0.30 | Useful but not mission-critical |

**Total Weighted Risk Score:** 2.90 / 5.00

## Decision

Conditional approval.

## Required Conditions

1. MFA must be enabled before rollout.
2. Sensitive files must be limited to approved folders.
3. Vendor security documentation must be saved.
4. Data deletion/export terms must be reviewed.
5. A vendor owner must be assigned.
