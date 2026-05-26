# Role-Based Access Examples

## Purpose

This document shows how access can be assigned by business role instead of one-off permission decisions.

## Role Matrix

| Role | Email | File Storage | CRM | Billing | Password Manager | Admin Console | Vendor Portal |
|---|---|---|---|---|---|---|---|
| Billing Specialist | Standard | Billing folder | Read/write assigned accounts | Standard user | User vault | No access | No access |
| Operations Manager | Standard | Operations + billing folders | Manager access | Approver | Team vault | Limited admin | Reviewer |
| IT Administrator | Standard | IT folder | Technical admin if needed | No billing data by default | Admin | Admin | Technical reviewer |
| Sales / Customer Success | Standard | Sales folder | Read/write assigned accounts | No access | User vault | No access | No access |
| Finance Manager | Standard | Finance folder | Read-only customer profile | Finance admin | Finance vault | No access | Reviewer |
| Contractor | Limited | Assigned folder only | Limited, time-bound | No access | Contractor vault | No access | No access |

## Role-Based Access Rules

1. Access should be assigned by role where possible.
2. Exceptions should be documented.
3. Contractors should have expiration dates.
4. Admin rights should be separate from standard business access.
5. Role changes should trigger mover review.
