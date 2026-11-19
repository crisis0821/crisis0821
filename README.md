### crisis0821

Individual developer in Japan. I run my own automation — crypto exchange bots,
market-data collectors, equity-data pipelines, small games and video tooling —
and I'm the only person who maintains and secures it.

**Security work**
- Self-audits of my own stack: dependency advisories (pip-audit, npm audit),
  secret scanning (detect-secrets), credential storage and file permissions
  → [security-notes](https://github.com/crisis0821/security-notes)

**In progress**
- Moving bot credentials from plaintext files to Windows Credential Manager
- Exchange API keys: withdrawal disabled, IP allow-lists, scheduled rotation
- CI → Anthropic via OIDC instead of static API keys

I only test systems I own.
