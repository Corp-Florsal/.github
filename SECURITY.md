# Security Policy

## Reporting a vulnerability

Do not disclose security vulnerabilities in public issues.

Report suspected vulnerabilities privately to the organization owner or designated maintainer with:

- Affected repository and version.
- Clear description of the risk.
- Steps to reproduce.
- Potential impact.
- Suggested mitigation, when available.

## Sensitive information

Never commit:

- Passwords or API keys.
- Private certificates or tokens.
- Client financial or personal information.
- Production database exports.
- Unredacted invoices, payroll files or identity documents.

Use environment variables and `.env.example` files without real secrets.

## Response priorities

- Critical: active compromise, credential exposure or sensitive-data leakage.
- High: exploitable access-control or financial-integrity issue.
- Medium: limited-impact vulnerability or insecure configuration.
- Low: hardening recommendation without immediate exposure.

Security fixes may be handled privately before public disclosure.