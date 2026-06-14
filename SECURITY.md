# Security Policy

This policy applies to all repositories owned by the **nics-dp** organization
unless a repository provides its own `SECURITY.md`. Organization profile:
<https://github.com/nics-dp>.

## Reporting a Vulnerability

We take the security of our software seriously and appreciate responsible
disclosure.

**Preferred channel - GitHub Private Vulnerability Reporting (PVR):**

1. Open the **Security** tab of the affected repository.
2. Click **Report a vulnerability** to open a private advisory draft.
3. Provide a clear description, affected versions, reproduction steps, and
   impact assessment.

See GitHub's guide for step-by-step instructions:
<https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability>

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

## References

- GitHub Private Vulnerability Reporting:
  <https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/about-coordinated-disclosure-of-security-vulnerabilities>
- Coordinated disclosure overview:
  <https://docs.github.com/en/code-security/security-advisories>
- OpenSSF vulnerability disclosure guide:
  <https://github.com/ossf/oss-vulnerability-guide>
