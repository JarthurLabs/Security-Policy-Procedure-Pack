# Google Workspace Security Validation Checklist

## Purpose

This checklist connects governance requirements to practical SaaS administration checks. It is written as a lightweight validation example for a small business using Google Workspace-style controls.

## Scope

- Users
- MFA enrollment
- Admin roles
- External sharing
- Inactive accounts
- Login alerts
- Groups
- Audit logs

## Validation Checklist

| Check ID | Control Area | Validation Question | Expected State | Evidence Type | Status |
|---|---|---|---|---|---|
| GW-001 | MFA | Are all active users enrolled in MFA? | Required for all active users | MFA report export or admin screenshot | Planned |
| GW-002 | Admin Access | Are super admin accounts limited? | Only approved named admins | Admin role export | Planned |
| GW-003 | Admin MFA | Do all admins have MFA enabled? | 100% admin MFA | Admin MFA export | Planned |
| GW-004 | Inactive Users | Are inactive users disabled or reviewed? | No unexplained inactive users over 30 days | User activity report | Planned |
| GW-005 | External Sharing | Is external sharing restricted or monitored? | Limited to approved business need | Drive sharing settings screenshot | Planned |
| GW-006 | Groups | Are sensitive groups owner-managed? | Owners assigned to sensitive groups | Group owner export | Planned |
| GW-007 | Audit Logs | Are login and admin audit logs available? | Logs enabled and reviewable | Admin log screenshot | Planned |
| GW-008 | Recovery Options | Are account recovery methods controlled? | Recovery options reviewed | Admin settings screenshot | Planned |
| GW-009 | Password Manager | Are users using approved password manager? | Approved password manager adopted | User enrollment report | Planned |
| GW-010 | Suspicious Login Alerts | Are suspicious login alerts enabled? | Alerts enabled for admins | Alert settings screenshot | Planned |

## Findings Summary Template

| Finding | Risk | Recommendation | Owner | Due Date |
|---|---|---|---|---|
| Some users not enrolled in MFA | Account takeover risk | Enforce MFA policy and follow up with users | IT Administrator | 30 days |
| Too many admin users | Excessive privilege risk | Remove unnecessary admin roles | IT Administrator | 30 days |
| External sharing too permissive | Data exposure risk | Restrict sharing and monitor exceptions | IT Administrator | 60 days |

## Why This Matters

Policy requirements are only useful if they can be validated. This checklist shows how access governance, MFA policy, and sharing controls can be compared against actual SaaS administration settings.
