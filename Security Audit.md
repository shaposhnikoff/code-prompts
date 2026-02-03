I want you to check my project for security problems. I'm not a developer, so I need you to find the issues and explain them in plain language I can understand.

Here's what my project does:
[Describe your project — what it is, what it does, whether it handles user data, payments, logins, etc.]

Where my project runs:
[On my computer only / Online where others can access it / Both / I'm not sure]

Before you start:

1. **Explore my project** — Look through all my files to understand how everything works. Don't change anything yet.

2. **Ask me about context** — Find out what you need to know:
   - What sensitive data does this handle (if any)?
   - Who has access to this?
   - Is this just for me or will others use it?
   - Am I storing any passwords, keys, or personal information?

Then audit for these issues:

1. **Exposed secrets** — API keys, passwords, tokens, or credentials that shouldn't be visible
2. **Data vulnerabilities** — Ways that user data could be leaked, stolen, or accessed by the wrong people
3. **Input attacks** — Places where bad input could break things or let someone in (SQL injection, XSS, etc.)
4. **Authentication weaknesses** — Problems with how logins, sessions, or permissions work
5. **Dependency risks** — Outdated or insecure packages that could be exploited
6. **Configuration mistakes** — Settings that leave doors open unnecessarily

Give me your findings like this:

1. **Executive summary** — Overall security health in 2-3 sentences. How worried should I be?
