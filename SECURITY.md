# Security Policy

## Reporting a vulnerability

Email **security@getsmartdash.com**. If that bounces, use **support@getsmartdash.com** with
`SECURITY` in the subject line.

Please do **not** open a public issue or discussion for a security report. This repository is
public, and an unfixed vulnerability posted here is visible to everyone before we can act on it.

Include what you need to make the problem reproducible: the app version (Settings → About), the
platform and OS version, the steps, and what you observed. If a source configuration is involved,
describe its shape rather than sending real credentials.

We aim to acknowledge a report within three working days.

## Scope

The Smart Dash mobile app and the getsmartdash.com backend. This repository holds no source code,
so there is nothing to report against the repository itself.

Particularly interested in:

- Anything that exposes source credentials. API keys, passwords and endpoint addresses are
  encrypted on the device before they sync, and our servers hold ciphertext they cannot read — see
  [Encryption](https://getsmartdash.com/docs/account/encryption). A way around that is the most
  serious class of bug we can have.
- Anything that lets one account read or modify another account's dashboards, sources or tags.
- Authentication or session handling flaws.

## Out of scope

- Reports produced solely by an automated scanner, with no demonstrated impact.
- Findings against a device or broker you point Smart Dash at. That is your infrastructure.
- Denial of service through volume.
- Missing hardening headers on marketing pages with no user data.

## Disclosure

Please give us a reasonable window to ship a fix before publishing. Store review adds days to any
mobile release that we do not control. We will tell you when the fix is out, and we are happy to
credit you by name or handle in the [changelog](https://getsmartdash.com/changelog) unless you
would rather stay anonymous.
