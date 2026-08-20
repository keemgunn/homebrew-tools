# Security Policy

## Reporting a vulnerability

Do not open a public issue for a suspected vulnerability.

Use GitHub's **Security → Report a vulnerability** form for this repository. Include the affected formula, version, reproduction steps, impact, and any suggested mitigation.

This repository contains Homebrew packaging metadata. Vulnerabilities in an installed tool itself should also be reported to that tool's upstream repository.

## Supply-chain expectations

- Release URLs must be immutable and versioned.
- Every downloaded artifact must have a verified SHA-256 checksum.
- GitHub Actions dependencies must remain pinned to full commit SHAs.
- Secrets and access tokens must never be committed to formulas or workflows.
