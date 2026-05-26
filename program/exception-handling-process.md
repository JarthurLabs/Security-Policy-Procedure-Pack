# Exception Handling Process

## Purpose

Security exceptions allow temporary deviations from standards when business needs require it. Exceptions must be documented, approved, and time-bound.

## Examples of Exceptions

- MFA cannot be enabled for a legacy system
- Contractor needs temporary access beyond normal role
- Vendor lacks preferred security documentation
- Shared mailbox requires delegated access
- Admin access needed for a short implementation window

## Required Exception Fields

| Field | Requirement |
|---|---|
| Exception ID | Unique identifier |
| Requestor | Person requesting exception |
| Standard affected | Policy or control being bypassed |
| Business justification | Why exception is needed |
| Risk | What could go wrong |
| Compensating control | How risk is reduced |
| Expiration date | Required |
| Approver | Required |
| Review date | Required |

## Exception Decision

| Decision | Meaning |
|---|---|
| Approved | Exception accepted until expiration |
| Conditional approval | Approved only with compensating controls |
| Denied | Risk is too high or justification is weak |
| More information needed | Cannot decide yet |

## Rule

No exception should be permanent by default.
