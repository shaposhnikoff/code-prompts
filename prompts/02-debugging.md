# Debugging Prompts

## General Debugging
```
I'm getting this error in {language}:
{error message}

Code:
{paste your code}

Please:
1. Identify the root cause
2. Explain why it's happening
3. Provide a fix
4. Suggest how to prevent similar issues
```

## Performance Issue
```
This {language} code is running slowly:
{paste code}

Profile information:
{any profiling data}

Please:
- Identify bottlenecks
- Suggest optimizations
- Provide refactored code
- Explain the performance improvement
```

## Logic Error
```
This function is producing incorrect output:
Input: {input}
Expected: {expected output}
Actual: {actual output}

Code:
{paste code}

Help me understand what's wrong and how to fix it.
```

## Memory Leak
```
I suspect a memory leak in this {language} code:
{paste code}

Symptoms:
{describe symptoms}

Please help identify and fix the memory leak.
```

## Race Condition
```
I'm experiencing intermittent bugs that suggest a race condition:
{describe the issue}

Code:
{paste concurrent code}

Please identify potential race conditions and suggest fixes.
```

## Integration Issue
```
I'm having trouble integrating {library/API} with my {language} code:
{describe the issue}

My code:
{paste code}

Error/unexpected behavior:
{describe}

Please help resolve this integration issue.
```

## Edge Case Bug
```
My function works for most inputs but fails for:
{describe edge case}

Function:
{paste code}

Please identify why this edge case fails and provide a fix.
```
