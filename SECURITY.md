# Security Policy

This policy applies to every repository in the Engineering Notes organisation, unless a repository publishes its own.

## Scope

The code in this organisation is educational: it demonstrates patterns such as ledgers, idempotency, webhooks, consensus and evaluation harnesses, and it is not production software. A flaw in a pattern can still mislead the people who learn from it, so reports are welcome.

In scope:

- A race condition, injection, validation gap or cryptographic mistake in any demonstrated pattern.
- A way to replay, forge or tamper with a message that an article says is rejected.
- A dependency with a known vulnerability that affects how the code runs.
- A secret or credential committed by mistake.

Out of scope: placeholder credentials in mocks that are labelled as such, and findings that need physical access to a contributor's machine.

## Reporting a vulnerability

Do not open a public issue, discussion or pull request. Use one of these private channels:

1. **GitHub private vulnerability reporting**, preferred: open the repository's **Security** tab and choose **Report a vulnerability**.
2. **Email**: mwangijoenjoroge@gmail.com, with the subject line `Security: <repository name>`.

Include the repository, folder and file, a description of the issue, steps to reproduce, and the impact.

## What to expect

| Stage | Target |
|---|---|
| Acknowledgement | Within 3 working days |
| Initial assessment | Within 10 working days |
| Fix or mitigation | Depends on severity. You will be kept informed |

Confirmed issues are fixed in code, and if an article is affected, a correction is published. Reporters are credited in the advisory unless they prefer to stay anonymous.

## Supported versions

Only the latest commit on `main` of each repository is supported.
