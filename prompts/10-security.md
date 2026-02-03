# Security Prompts

## Security Audit
```
Perform a security audit of this code:
{paste code}

Check for:
- Input validation vulnerabilities
- Authentication/authorization issues
- Data exposure risks
- Injection vulnerabilities
- Cryptographic weaknesses
- Configuration issues
- Dependency vulnerabilities
```

## Secure Code Generation
```
Write secure {language} code for {functionality}.

Requirements:
{list requirements}

Ensure:
- Input validation and sanitization
- Output encoding
- Secure authentication
- Proper authorization checks
- Protection against common vulnerabilities (OWASP Top 10)
```

## Authentication Implementation
```
Implement secure authentication for {application type}.

Include:
- Password hashing (using bcrypt/argon2)
- Session management
- Token-based auth (JWT)
- Multi-factor authentication
- Password reset flow
- Account lockout mechanism
```

## Authorization Design
```
Design an authorization system for:
{describe application}

Implement:
- Role-based access control (RBAC)
- Permission management
- Resource-level permissions
- Privilege escalation prevention
- Audit logging
```

## Input Validation
```
Add comprehensive input validation to:
{paste code}

Validate:
- Data types
- Length constraints
- Format validation
- Whitelist validation
- Business rule validation
Prevent: SQL injection, XSS, command injection
```

## SQL Injection Prevention
```
Review and fix SQL injection vulnerabilities in:
{paste code}

Provide:
- Identified vulnerabilities
- Secure implementation using prepared statements
- Input validation strategy
- Additional security measures
```

## XSS Prevention
```
Secure this code against XSS attacks:
{paste code}

Implement:
- Input sanitization
- Output encoding
- Content Security Policy
- Safe DOM manipulation
```

## Secrets Management
```
Review how secrets are managed in this code:
{paste code}

Improve:
- Remove hardcoded secrets
- Use environment variables
- Implement secret rotation
- Use secure secret storage (vault)
- Encrypt sensitive data at rest
```

## API Security
```
Secure this API:
{paste API code}

Implement:
- Authentication (OAuth 2.0/JWT)
- Rate limiting
- Input validation
- CORS configuration
- API key management
- Request signing
- HTTPS enforcement
```

## Cryptography Review
```
Review the cryptographic implementation:
{paste code}

Check:
- Algorithm selection
- Key management
- Random number generation
- Padding schemes
- Mode of operation
- Salt usage
Ensure compliance with current standards.
```
