# Cross-Site Scripting (XSS) – Reflected

## Vulnerability Identified
Reflected Cross-Site Scripting (XSS) vulnerability was identified in user input fields.

## Proof of Concept
Payload used:
<script>alert('XSS')</script>

## Result
The injected JavaScript executed successfully, displaying an alert popup.

## Impact
- Session hijacking
- Cookie theft
- Defacement
- Phishing attacks

## Severity
High

## Mitigation
- Output encoding
- Input sanitization
- Content Security Policy (CSP)


