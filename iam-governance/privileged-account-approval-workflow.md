# Privileged Account Approval Workflow

## Purpose

Privileged access creates elevated risk and requires stronger approval, monitoring, and review.

## Privileged Access Examples

- Super administrator
- Billing administrator
- Password manager administrator
- File storage administrator
- Email administrator
- CRM administrator
- Security tool administrator

## Approval Workflow

```text
Request Submitted
      ↓
Manager Approval
      ↓
System Owner Approval
      ↓
Risk Review
      ↓
MFA Confirmed
      ↓
Admin Access Granted
      ↓
Logged in Privileged Access Register
      ↓
Quarterly Review
```

## Required Fields

| Field | Requirement |
|---|---|
| Business justification | Must explain why standard access is insufficient |
| Access duration | Permanent or temporary |
| MFA status | Must be enabled |
| Backup admin | Must be identified for critical systems |
| Monitoring | Admin activity logs must be available where supported |
| Review date | Must be reviewed at least quarterly |

## Privileged Access Rules

1. Admin access should be named to an individual user.
2. Shared admin accounts should be avoided.
3. MFA is mandatory.
4. Temporary privileged access should expire automatically when possible.
5. Admin access should not be used for daily non-admin work.
6. Privileged accounts must be included in quarterly access reviews.
