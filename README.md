# Trat

I build backend and infrastructure tools, with a focus on Python, secure APIs, Docker, and automation.

## Featured projects

### [ComposeGuard](https://github.com/Trat1100/composeguard)

A Python CLI that flags common Docker Compose security and reliability risks. It produces text or JSON reports, supports CI failure thresholds, and uses static analysis without starting containers. See the [v0.1.0 release](https://github.com/Trat1100/composeguard/releases/tag/v0.1.0).

### [Backup Sentinel](https://github.com/Trat1100/backup-sentinel)

A read-only CLI that checks backup file counts, freshness, and optional SHA-256 sidecars across named backup sets. It emits text or JSON reports and never modifies backup files. See the [v0.1.0 release](https://github.com/Trat1100/backup-sentinel/releases/tag/v0.1.0).

### [HookHarness](https://github.com/Trat1100/hookharness)

A local-first webhook test CLI with timestamped HMAC signing, bounded retries, a loopback verifier, and replay rejection. See the [v0.1.0 release](https://github.com/Trat1100/hookharness/releases/tag/v0.1.0).

### [SchemaShift](https://github.com/Trat1100/schema-shift)

A read-only database schema drift checker for SQLite, PostgreSQL, and MySQL. It compares catalog metadata without reading application rows. See the [v0.1.0 release](https://github.com/Trat1100/schema-shift/releases/tag/v0.1.0).

### [HostDoctor](https://github.com/Trat1100/hostdoctor)

A privacy-conscious Linux first-response CLI for memory, load, disk, inodes, listening sockets, and failed systemd services. It makes no changes and uploads no data. See the [v0.1.0 release](https://github.com/Trat1100/hostdoctor/releases/tag/v0.1.0).

## Technical focus

- Python tooling, FastAPI, and SQLAlchemy
- Docker Compose and deployment safety
- Webhook integrations and API security
- Database schema inspection and drift reporting
- Linux operations, automation, and CI
- Backup freshness and data integrity
- Authentication, authorization, and tenant boundaries
- Node.js, Server-Sent Events, and OBS tooling
- TypeScript and procedural motion graphics

I aim for clear setup instructions and honest limits: ComposeGuard performs static checks; Backup Sentinel does not test restores; SchemaShift compares schema metadata; HostDoctor is read-only; and HookHarness is a development test tool, not a production webhook service.

## Contact

[hello@trat.tech](mailto:hello@trat.tech)