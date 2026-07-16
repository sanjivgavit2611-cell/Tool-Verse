# Security Policy

## 🛡️ Supported Versions

Tool Verse is a continuously updated resource collection, not versioned software — there are no release branches to track. Security fixes and corrections are applied only to the latest commit on `main`.

| Version | Supported |
|---|---|
| `main` (latest) | ✅ |
| Anything else (forks, old commits) | ❌ |

## ⚠️ What Counts as a Security Issue Here

Tool Verse is mostly documentation, but a few things in this repository do carry real security surface:

- 🔗 A listed resource whose official link has been hijacked, is serving malware, or leads somewhere unsafe
- ⚙️ A vulnerability in any automation under `scripts/` or `.github/workflows/` — for example, something that could leak secrets or allow code execution via a pull request
- 🔓 A GitHub Actions workflow misconfiguration exploitable through untrusted pull requests

Broken links, outdated info, or quality issues that aren't security-related belong in a regular [issue](https://github.com/sanjivgavit2611-cell/Tool-Verse/issues) instead — see [CONTRIBUTING.md](CONTRIBUTING.md).

## 📬 Reporting a Vulnerability

**Please don't report security issues through public GitHub issues** — disclosing a vulnerability before it's fixed can put other users at risk.

Report privately instead:

1. **Preferred:** [Report a vulnerability](https://github.com/sanjivgavit2611-cell/Tool-Verse/security/advisories/new) via this repository's Security tab
2. **Alternative:** Email the maintainer directly at **259667776+sanjivgavit2611-cell@users.noreply.github.com**

Please include:

- A clear description of the issue and where it was found
- Steps to reproduce, if applicable
- Any potential impact you're aware of

## ⏱️ What to Expect

- **Acknowledgement:** within 3–5 days of your report
- **Assessment:** we'll investigate and confirm whether it's a valid security issue
- **Fix & disclosure:** once resolved, we'll credit you (unless you'd rather stay anonymous) and may publish a GitHub Security Advisory

## 🤝 Responsible Disclosure

We ask for reasonable time to investigate and address a reported issue before it's disclosed publicly. We're committed to working with reporters to understand and resolve problems quickly.

Thank you for helping keep Tool Verse and its community safe. 🙏
