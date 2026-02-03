# Code Review Prompts

## General Code Review
```
Please review this {language} code for:
- Code quality and readability
- Best practices adherence
- Potential bugs
- Performance issues
- Security vulnerabilities
- Maintainability

Code:
{paste code}
```

## Security Review
```
Review this code for security vulnerabilities:
{paste code}

Focus on:
- Input validation
- SQL injection risks
- XSS vulnerabilities
- Authentication/authorization issues
- Data exposure
- Cryptographic weaknesses
```

## Performance Review
```
Analyze this code for performance optimization opportunities:
{paste code}

Consider:
- Time complexity
- Space complexity
- Database query efficiency
- Caching opportunities
- Algorithm efficiency
```

## Architecture Review
```
Review the architecture of this {system/module}:
{describe architecture or paste code}

Evaluate:
- Design patterns usage
- Separation of concerns
- SOLID principles
- Scalability
- Maintainability
```

## API Design Review
```
Review this API design:
{paste API specification or code}

Check:
- RESTful principles
- Endpoint naming
- HTTP methods usage
- Status codes
- Request/response formats
- Error handling
- Versioning strategy
```

## Test Coverage Review
```
Review these test cases for:
{paste test code}

Evaluate:
- Test coverage completeness
- Edge cases handled
- Test quality and readability
- Mocking strategy
- Assertion quality
```
