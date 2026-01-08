# Authentication & Brute Force Vulnerability

## Vulnerability Identified
The application is vulnerable to brute-force authentication attacks.

## Proof of Concept
Common credentials were used to successfully log in:
- Username: admin
- Password: password

## Result
Login was successful without any restriction, lockout, or CAPTCHA enforcement.

## Impact
- Unauthorized account access
- Credential stuffing attacks
- Account takeover

## Severity
High

## Mitigation
- Implement account lockout after failed attempts
- Enforce strong password policies
- Use CAPTCHA or rate limiting
- Enable Multi-Factor Authentication (MFA)
