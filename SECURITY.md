# Cosmic Relay Security Policy

Cosmic Relay is a proprietary Windows application currently distributed as public alpha tester builds. This policy describes how security-sensitive reports should be handled for the public distribution repository and official tester builds.

## Reporting a security issue

Please **do not open a public GitHub issue containing vulnerability details**, exploit steps, credentials, tokens, proof-of-concept code, or other sensitive technical information.

If GitHub's **Private vulnerability reporting** option is available on this repository, use that channel so the report and technical details remain private.

If private vulnerability reporting is not available, open a minimal public issue titled **[Security] Request private contact** without including sensitive technical details. A private reporting channel can then be arranged.

When reporting a security issue, include only the information necessary to reproduce and understand the problem:

- Cosmic Relay version
- Windows version
- affected component or workflow
- reproduction steps
- expected and observed behavior
- security impact
- relevant logs or screenshots after removing credentials, tokens, personal information, and unrelated private data

## Scope

Security reports may include issues involving:

- official Cosmic Relay binaries or release packages
- update or release-distribution behavior
- local settings or diagnostic-data handling
- unsafe file permissions or storage behavior
- accidental secret, token, or credential exposure
- code execution or privilege-escalation behavior attributable to Cosmic Relay
- vulnerabilities in bundled third-party components when they materially affect Cosmic Relay users

General bugs, media compatibility problems, playback-control issues, and feature ideas should use the normal public issue forms instead.

## Supported versions

Security fixes are applied to the latest public tester build. Older alpha builds may no longer receive fixes unless a release note states otherwise.

## Disclosure

Please allow reasonable time to investigate and prepare a fix before publicly disclosing a security issue. Confirmed security fixes will be documented appropriately when a corrected build is released.

## Privacy

Do not include account credentials, authentication tokens, private keys, personally identifying information, unrelated logs, or other sensitive data in a report.

Cosmic Relay diagnostics may include the current track title, artist, and raw Windows media-session identifier. Review and remove information that is not necessary for the security report before sharing diagnostics.
