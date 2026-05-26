# Incident Response Procedure

## Document Owner

Operations Manager

## Purpose

This procedure defines how employees and managers should respond to suspected cybersecurity incidents.

## Scope

This procedure applies to suspected incidents involving company systems, accounts, data, devices, vendors, and customer information.

## Incident Examples

- Phishing email clicked
- Suspicious MFA prompt
- Lost or stolen laptop
- Accidental customer data sharing
- Malware pop-up
- Unauthorized login alert
- Vendor breach notification
- Ransomware message

## Response Phases

### 1. Identification

Collect basic facts:

- Who reported the issue?
- What happened?
- When was it discovered?
- Which system or account is involved?
- Is customer data involved?
- Are screenshots or logs available?

### 2. Containment

Possible containment actions:

- Disable affected account
- Reset password
- Revoke active sessions
- Disconnect device from network
- Block suspicious sender or domain
- Limit access to affected folder

### 3. Investigation

Review available evidence:

- Login history
- Email headers
- File access history
- Device alerts
- Vendor notifications
- User activity timeline

### 4. Eradication

Remove the cause:

- Delete malicious email
- Remove unwanted browser extension
- Patch affected software
- Remove unauthorized user
- Revoke risky application consent

### 5. Recovery

Restore normal operations:

- Re-enable account after validation
- Confirm MFA is active
- Confirm files are intact
- Notify affected stakeholders if required
- Monitor for repeat activity

### 6. Lessons Learned

After the incident:

- Document root cause
- Update procedures
- Add training if needed
- Improve controls
- Record the incident in the incident log

## Severity Levels

| Severity | Description | Example |
|---|---|---|
| Low | Limited issue with no sensitive data | Spam email reported |
| Medium | Possible account or data exposure | Suspicious login attempt |
| High | Confirmed unauthorized access or sensitive data exposure | Compromised email account |
| Critical | Major business disruption or widespread data exposure | Ransomware or active breach |

## Evidence to Preserve

- Screenshots
- Email headers
- Login timestamps
- IP addresses
- User reports
- Vendor messages
- System alerts

## Communication Rules

Do not speculate. Communicate only confirmed facts, known impact, next steps, and owner.
