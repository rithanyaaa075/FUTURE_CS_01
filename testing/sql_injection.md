# SQL Injection Testing

## Vulnerability Identified
SQL Injection vulnerability was identified in the User ID parameter.

## Proof of Concept
Payload used:
1' OR '1'='1

## Result
The application returned all user records instead of a single user, confirming SQL Injection.

## Impact
- Authentication bypass
- Unauthorized data access
- Database enumeration

## Severity
High

## Mitigation
- Use prepared statements
- Parameterized queries
- Input validation
- Least privilege for DB users

