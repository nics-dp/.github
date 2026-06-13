# Security Policy

This policy applies to all repositories owned by the **nics-dp** organization
unless a repository provides its own `SECURITY.md`.

## Reporting a Vulnerability

We take the security of our software seriously and appreciate responsible
disclosure.

**Preferred channel - GitHub Private Vulnerability Reporting:**

1. Open the **Security** tab of the affected repository.
2. Click **Report a vulnerability** to open a private advisory draft.
3. Provide a clear description, affected versions, reproduction steps, and
   impact assessment.

Private Vulnerability Reporting keeps the report confidential between you and
the maintainers until a fix is published. For repositories where this option
is unavailable, please contact the repository maintainers directly through the
organization.

**Please do not** open public issues, pull requests, or discussions for
security vulnerabilities, and do not disclose the issue publicly until a fix
has been released and coordinated with the maintainers.

## What to Include

- A description of the vulnerability and its potential impact.
- The affected repository, version, commit, or release.
- Step-by-step reproduction or a proof of concept.
- Any suggested remediation, if known.

## Our Commitment

- We aim to acknowledge new reports within **5 business days**.
- We will keep you informed of remediation progress.
- We follow a coordinated disclosure process and will credit reporters who
  wish to be acknowledged, once a fix is available.

## Supported Versions

Unless a repository states otherwise, security fixes are provided for the
**latest released version** on the default branch. Older versions are
supported on a best-effort basis.

## Scope

This policy covers code and configuration maintained within nics-dp
repositories. Vulnerabilities in third-party dependencies should be reported
upstream; if a dependency issue affects our software, we will track and
remediate it through our dependency management process.
