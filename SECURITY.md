# Security Policy

This is the **organization-wide default** for `supernovae-st` repositories.
Repositories with their own `SECURITY.md` (the engine, the spec, the site,
the SDK, the docs, the tap) refine this policy for their specific surface;
everything else — including the editor extension, the agent plugin
marketplace and the workflow registry — falls back to this one.

## Supported Versions

Only the default branch (`main`) of each repository is supported.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub
issues, discussions, or pull requests.**

Send an email to **security@supernovae.studio** with ·

- A description of the issue and the repository it affects
- Steps to reproduce or a minimal proof-of-concept
- The commit SHA, release version or deployed URL where you observed it

We acknowledge receipt within **72 hours** and aim for a substantive
response (initial triage + ETA) within **7 days**. Supply-chain reports
(anything that ships to users: extension packages, registry entries,
formulas, install scripts) are treated as highest severity.

## Disclosure Process

1. **Triage** · maintainers verify the report and confirm the scope
2. **Fix development** · patch authored privately
3. **Public release** · GitHub Security Advisory + patched release
4. **Credit** · reporter named in the advisory unless anonymity is requested

We aim for **≤90 days** between report and public disclosure, shorter for
actively-exploited issues.
