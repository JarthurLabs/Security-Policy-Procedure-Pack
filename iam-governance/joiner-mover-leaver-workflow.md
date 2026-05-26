# Joiner / Mover / Leaver Workflow

## Purpose

This workflow defines how employee and contractor access is managed during onboarding, role changes, and offboarding.

## Scope

Applies to:

- Employees
- Contractors
- Temporary users
- SaaS application accounts
- Admin accounts
- Shared drives
- Customer data systems

---

## 1. Joiner Workflow

A joiner is a new employee, contractor, or temporary user.

### Required Steps

| Step | Owner | Evidence |
|---|---|---|
| Manager submits access request | Hiring manager | Access request form |
| Access role is selected | Manager + system owner | Role-based access matrix |
| IT creates account | IT administrator | User account record |
| MFA enrollment is confirmed | IT administrator | MFA status screenshot/export |
| User receives security expectations | Manager | Training acknowledgement |
| Access is logged | IT administrator | Access tracker entry |

### Joiner Rule

No user should receive access before:

1. Manager approval
2. System owner approval for sensitive systems
3. MFA enrollment for required applications
4. Documented business need

---

## 2. Mover Workflow

A mover is a user changing job role, department, manager, or responsibilities.

### Required Steps

| Step | Owner | Evidence |
|---|---|---|
| Manager reports role change | Manager | Role change ticket |
| Current access is reviewed | System owner | Access review checklist |
| Unneeded access is removed | IT administrator | Access removal record |
| New access is requested | Manager | Access request form |
| Privileged access is separately approved | System owner | Privileged approval record |

### Mover Rule

Role changes should trigger both access removal and access addition. The review should not only add new permissions.

---

## 3. Leaver Workflow

A leaver is an employee, contractor, or temporary user leaving the company.

### Required Steps

| Step | Owner | Evidence |
|---|---|---|
| Manager confirms departure date | Manager | Offboarding request |
| Account access is disabled | IT administrator | Account status screenshot/export |
| SaaS sessions are revoked | IT administrator | Admin console record |
| Shared drive access is removed | IT administrator | Permission change record |
| Files are transferred if needed | Manager + IT | Transfer confirmation |
| Password manager access is revoked | IT administrator | User removal record |
| Completion is recorded | Operations manager | Offboarding checklist |

### Leaver Rule

Access removal should occur the same business day as departure, or immediately for involuntary termination.

---

## Control Rationale

The JML workflow reduces the risk of orphaned accounts, excessive access, and unauthorized access after role changes or departure.
