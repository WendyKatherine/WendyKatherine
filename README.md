# Wendy Gómez

**Backend Engineer · Platform ownership · Python · PostgreSQL · Docker · CI/CD · Linux** — I build and operate production systems, and I'm moving toward platform engineering.

Based in Bogotá (GMT-5) · Remote, working with teams in EST · English B2

---

### How I work

- **Tests before refactors.** A test suite that captures current behaviour is the only safe way to change production code.
- **Least privilege by default.** Separate database roles for migrations and runtime; the application cannot alter the schema.
- **Operable by design.** Health and readiness endpoints, structured logs with request IDs, encrypted backups with a restore that has actually been tested.
- **Decisions written down.** ADRs, runbooks, and technical debt logged the day it is taken — not the day it hurts.

### Featured projects

**[energy-sector-reference-api](https://github.com/WendyKatherine/energy-sector-reference-api)** — reference API for an event and registration platform. Capacity control under concurrency (row-level locking plus a unique constraint), idempotent registrations, RFC 7807 errors, two database roles, multi-stage non-root image, and Terraform to AWS.

**[travel-savings-platform](https://github.com/WendyKatherine/travel-savings-platform)** — fintech backend: append-only ledger, money as an immutable Decimal value object, durable idempotency enforced by a database unique key, and 69 tests including integration against a real Postgres.

**[pricing-service](https://github.com/WendyKatherine/pricing-service)** — pricing microservice with ports and adapters, failures modelled as typed values, layered tests, CI/CD to Oracle Cloud, and an observability endpoint used by the DevOps team.

### Stack

Python · FastAPI · Flask · SQLAlchemy 2.0 · Alembic · PostgreSQL · Redis · Pydantic · Docker · GitHub Actions · pytest · mypy · Terraform · Linux

### Currently

Working through a platform roadmap on a production codebase: environment-based configuration, health checks, structured logging, least-privilege database roles, container images, and infrastructure as code.

I'm interested in backend and platform teams where the platform is treated as a product — building the path other teams use to ship.

### Get in touch

[LinkedIn](https://www.linkedin.com/in/wendy-katherine-gomez-villa-536964241/) · wendykatherinnegomezv@gmail.com
