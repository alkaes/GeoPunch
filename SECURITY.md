# Security policy

GeoPunch holds your OrangeHRM password and talks to your company's HR server, so security reports are taken seriously.

## Reporting a vulnerability

**Please don't open a public issue.** Report privately in one of these ways:

- GitHub: [Report a vulnerability](https://github.com/alkaes/GeoPunch/security/advisories/new) (private to you and the developer).
- Email: alkaes@gmail.com with "GeoPunch security" in the subject.

Include the GeoPunch version, what an attacker could do, and the steps to reproduce. You'll get a reply within 7 days. Once a fix is released you'll be credited in the release notes unless you'd rather not be.

## In scope

- The GeoPunch Android app: storage of credentials and data on the phone, its network traffic, its exported components (widget, Quick Settings tile, shortcuts, notifications).
- How GeoPunch signs in to OrangeHRM and handles the session.

## Out of scope

- Vulnerabilities in OrangeHRM itself. Report those to OrangeHRM.
- A phone that is already rooted or compromised.
- Findings that need physical access to an unlocked phone.

## Supported versions

Only the latest version on Google Play receives fixes.
