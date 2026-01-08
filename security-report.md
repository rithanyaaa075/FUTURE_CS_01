# Web Application Security Testing Report

This report summarizes vulnerabilities identified during security testing.

## Target Application
Intentionally vulnerable web application (DVWA / OWASP Juice Shop)

## Tools Used
- OWASP ZAP
- Burp Suite
- SQLMap

## Summary
Vulnerabilities such as SQL Injection, XSS, and authentication flaws were identified and documented.
The application allows unlimited login attempts with weak credentials, making it vulnerable to brute-force attacks. No lockout or rate limiting mechanisms were observed.
