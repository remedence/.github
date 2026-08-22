# Remedence

A security remediation and evidence platform for MSPs and security teams. Remedence turns security findings into independently verified closure, preserves the evidence behind each fix, and makes the result easy to prove to customers.

**Security work. Proven complete.**

> **PATCHED ≠ VERIFIED FIXED**

## Current release

Persistent local core v1 is shipped on [`remedence`](https://github.com/remedence/remedence) `main`.

The current open-source release provides durable SQLite-backed findings, remediation records, retained failed verification history, independent verification, locked evidence metadata, append-only audit history, immutable report snapshots, Markdown report download, database backup foundations, and a production-local mode that serves the built UI and `/api/v1` from one loopback Node process.

Local v1 intentionally binds to `127.0.0.1` and does not yet provide hosted SaaS authentication, production multi-user RBAC, managed vendor integrations, or hosted verification workers. It should not be exposed directly to an untrusted network.

## Repositories

- [`remedence`](https://github.com/remedence/remedence) — canonical open-source platform and persistent local core
- [`remedence.github.io`](https://github.com/remedence/remedence.github.io) — official public website
- [`.github`](https://github.com/remedence/.github) — organization profile and shared GitHub configuration

Future multi-tenant, managed-cloud, SDK, connector, and deployment repositories should be split out only when they need independent release cycles.

`Remediate → Verify → Prove`
