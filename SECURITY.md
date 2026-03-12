# Security Policy

## Reporting a Vulnerability

**Do not report security vulnerabilities via public GitHub issues.**

If you discover a security vulnerability in Tokey, please disclose it responsibly by opening a [GitHub Security Advisory](https://github.com/ndizazzo/tokey.ai/security/advisories/new) (private, only visible to maintainers).

Include as much of the following as possible:

- **Type of vulnerability** (e.g. XSS, SSRF, RCE, auth bypass, information disclosure)
- **Affected component** (web, backend, tui, agent, simulator, core)
- **Steps to reproduce** — a minimal proof of concept if possible
- **Impact** — what an attacker could achieve
- **Suggested fix** (optional)

## Response Timeline

| Stage | Target |
|---|---|
| Acknowledgement | Within 3 business days |
| Initial assessment | Within 7 business days |
| Fix or mitigation | Depends on severity |

Critical vulnerabilities (CVSS ≥ 9.0) will be prioritised immediately.

## Scope

The following are **in scope**:

- Authentication / authorisation flaws
- Data exposure or leakage
- Remote code execution
- Server-side request forgery (SSRF)
- SQL / command injection
- Dependency vulnerabilities with exploitable attack vectors

The following are **out of scope**:

- Issues in third-party dependencies (please report upstream)
- Theoretical vulnerabilities without a working proof of concept
- Social engineering attacks
- Issues requiring physical access

## Disclosure Policy

We ask that you give us reasonable time to address a vulnerability before any public disclosure. We will coordinate a disclosure timeline with you after a fix is ready.

We do not currently operate a bug bounty programme.
