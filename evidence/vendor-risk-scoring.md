# Vendor Risk Scoring Example

## Purpose

This example shows how a small business could review a new SaaS vendor before approving it for company use.

## Scenario

Northstar Dental Billing LLC is considering a new SaaS document-sharing vendor called **FileBridge Cloud**. The vendor would store billing support documents and employee-uploaded files.

## Scoring Method

Each category is scored from 1 to 5.

| Score | Meaning |
|---|---|
| 1 | Low risk / strong control evidence |
| 2 | Minor concern |
| 3 | Moderate concern |
| 4 | High concern |
| 5 | Severe concern or missing critical evidence |

## Vendor Scorecard

| Category | Weight | Score | Weighted Score | Notes |
|---|---:|---:|---:|---|
| Data sensitivity | 20% | 4 | 0.80 | Vendor may store billing-related documents |
| Authentication controls | 20% | 2 | 0.40 | Supports MFA and SSO |
| Security documentation | 15% | 3 | 0.45 | Provides security page but no full report in basic plan |
| Incident notification | 15% | 3 | 0.45 | Notification language is general |
| Data deletion/export | 10% | 2 | 0.20 | Supports export and deletion requests |
| Subprocessors | 10% | 3 | 0.30 | Subprocessor list exists but needs review |
| Business criticality | 10% | 3 | 0.30 | Workflow useful but not mission-critical |

**Total Weighted Risk Score:** 2.90 / 5.00

## Decision

**Conditional approval**

The vendor can be approved if the business owner confirms:

1. MFA is enabled before rollout.
2. Sensitive files are limited to approved folders.
3. Vendor security documentation is saved for recordkeeping.
4. Data deletion/export terms are reviewed.
5. A vendor owner is assigned.

## How to Explain This in an Interview

> I added vendor risk scoring to show third-party risk thinking. I did not just say a vendor is safe or unsafe. I scored categories based on business impact, data sensitivity, and available security evidence, then made a conditional approval decision.
