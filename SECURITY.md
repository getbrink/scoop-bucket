# Security

This repository is the Scoop bucket for the Brink operator CLI. It holds one manifest, no
product code. What it does carry is the hash a `scoop install` trusts.

## Reporting a vulnerability

Email security@getbrink.io. Do not open a public issue for a security report.

You will receive an acknowledgement within three working days. We ask for ninety days before
public disclosure so a fix can ship; we will tell you when it has.

## Scope

- `brink.json`: a URL or a `hash` that does not match the artefact Brink published.
- Anything in the manifest that would install or execute something other than the released
  binary.

Vulnerabilities in the Brink CLI itself belong to `getbrink/brink`; each product repository
carries its own `SECURITY.md` with the same address.
