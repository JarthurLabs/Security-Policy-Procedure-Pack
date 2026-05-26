# MFA Enforcement Matrix

## Purpose

This matrix defines where MFA is required, why it matters, and how evidence should be collected.

| System | Data / Function | MFA Required | Enforcement Priority | Evidence |
|---|---|---|---|---|
| Email | Company communication, password resets | Yes | Critical | Admin console MFA report |
| Password Manager | Stored credentials | Yes | Critical | User MFA status export |
| File Storage | Customer and internal documents | Yes | High | Admin settings screenshot |
| CRM | Customer records and activity | Yes | High | User security settings export |
| Billing System | Financial and customer billing data | Yes | Critical | Admin access report |
| Project Management | Internal work tracking | Yes | Medium | App security settings |
| HR / Payroll | Employee personal data | Yes | Critical | Admin settings screenshot |
| Customer Support Tool | Customer communications | Yes | High | User access report |
| Marketing Tool | Public campaigns, limited data | Recommended | Medium | App settings screenshot |

## Enforcement Rules

- MFA is mandatory for all admin accounts.
- MFA is mandatory for systems containing customer, financial, employee, or credential data.
- MFA exceptions require documented approval and expiration.
- New systems should not be approved without MFA support unless risk is formally accepted.

## Metrics

| Metric | Target |
|---|---|
| MFA coverage for critical systems | 100% |
| MFA coverage for admin accounts | 100% |
| Open MFA exceptions | 0 preferred; all must have expiration |
| Users not enrolled in MFA | 0 for required systems |
