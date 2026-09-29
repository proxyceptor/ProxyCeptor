# Security policy

Thank you for helping keep ProxyCeptor and its users safe.

## Reporting a vulnerability

**Please do not open a public issue, discussion or pull request for security problems.**

Report privately in either of these ways:

- **GitHub:** open the [Security tab](https://github.com/proxyceptor/ProxyCeptor/security) of this repository and choose **Report a vulnerability**.
- **Email:** [admin@proxyceptor.com](mailto:admin@proxyceptor.com) with the subject line `SECURITY:` followed by a short title.

A useful report includes:

- the affected surface (website, dashboard, API, JavaScript SDK, Chrome extension or Commander) and its URL or version,
- step-by-step instructions to reproduce, with a minimal proof of concept,
- the impact you expect (what an attacker could read, change or run),
- whether you have shared the issue with anyone else.

Please don't include real API keys, tokens or other people's data in the report. Redact them.

## What happens next

- We aim to acknowledge your report within a few working days.
- We'll confirm the issue, tell you how we plan to fix it, and keep you updated until it's resolved.
- Once a fix has shipped, we're happy to credit you publicly if you'd like.

ProxyCeptor does not run a paid bug bounty at the moment.

## Scope

In scope:

- `proxyceptor.com`, `app.proxyceptor.com` and `api.proxyceptor.com`
- the ProxyCeptor JavaScript SDK (`proxyceptor-sdk.js`) and floating widget
- the ProxyCeptor Chrome extension
- Commander (`proxyceptor.com/test`)

Out of scope: denial-of-service and load testing, spam or social engineering, physical attacks, and vulnerabilities in third-party services we don't control.

## Good-faith research

We won't pursue or support legal action against research done in good faith that follows this policy. Please:

- only test against accounts and workspaces you own,
- never access, change or delete other users' data, and stop as soon as you see any,
- avoid anything that degrades the service for others,
- give us reasonable time to fix the issue before disclosing it publicly.
