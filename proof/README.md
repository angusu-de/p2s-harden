# php-fpm-audit public CI evidence

Separate account, same maintainer; CI evidence, not a third-party audit.

Commit: `9dbb2742dd3f21c358936ff5115a50ae75ca6510` · [Run 40230453680, attempt 1](https://github.com/angusu-de/p2s-harden/actions/runs/40230453680)

**12/12 jobs passed.** Overall workflow: `success`.

[Source repository](https://github.com/IamAngusU/php-fpm-audit) and CI fork were checked at this same commit.

This snapshot describes the linked commit. Check the commit before relying on it for a newer checkout.

[Machine-readable evidence](public-proof.json)

## linux (python:3.8.20-slim-bookworm)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Fixture tests in disposable Linux container: `success`
- Reproduce upload guard behavior with real Nginx and FPM: `skipped`
- Retain reproducible upload lab evidence: `skipped`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## linux (python:3.12-slim-bookworm)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Fixture tests in disposable Linux container: `success`
- Reproduce upload guard behavior with real Nginx and FPM: `success`
- Retain reproducible upload lab evidence: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## PHP-FPM 8.2

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real PHP-FPM settings and audit comparison: `success`
- Summarize runtime evidence: `success`
- Retain runtime image identities and observations: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## PHP-FPM 8.3

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real PHP-FPM settings and audit comparison: `success`
- Summarize runtime evidence: `success`
- Retain runtime image identities and observations: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## PHP-FPM 8.4

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real PHP-FPM settings and audit comparison: `success`
- Summarize runtime evidence: `success`
- Retain runtime image identities and observations: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## PHP-FPM 8.5

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real PHP-FPM settings and audit comparison: `success`
- Summarize runtime evidence: `success`
- Retain runtime image identities and observations: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## System Ubuntu 24.04 (PHP 8.3)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real Ubuntu systemd discovery, fix and rollback: `success`
- Retain Ubuntu system evidence: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## System Debian 12 (PHP 8.2)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real Debian systemd discovery, fix and rollback: `success`
- Retain Debian system evidence: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## System Ubuntu 22.04 (PHP 8.1)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real Ubuntu systemd discovery, fix and rollback: `success`
- Retain Ubuntu system evidence: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## System Debian 13 (PHP 8.4)

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Real Debian systemd discovery, fix and rollback: `success`
- Retain Debian system evidence: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## windows

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Run actions/setup-python@a26af69be951a213d495a4c3e4e4022e16d87065: `success`
- Check generated launchers: `success`
- PowerShell native transport tests: `success`
- Strict Rust JSON parser interoperability: `success`
- Post Run actions/setup-python@a26af69be951a213d495a4c3e4e4022e16d87065: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`

## Release provenance

Result: `success`

- Set up job: `success`
- Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Rebuild exact tested source and require matching public heads: `success`
- Sign build provenance for all four distribution files: `success`
- Retain exact distribution files and signed bundle: `success`
- Run actions/upload-artifact@ea165f8d65b6e75b540449e92b4886f43607fa02: `success`
- Post Run actions/checkout@11d5960a326750d5838078e36cf38b85af677262: `success`
- Complete job: `success`
