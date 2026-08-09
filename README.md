# Nyasha Hama

**Full-Stack Software Engineer · Product & Platform Engineering**  
React · Next.js · TypeScript · Go · Java · PostgreSQL

Cape Town, South Africa  
[Portfolio](https://portfolio-topaz-one-58.vercel.app/) · [Résumé (PDF)](https://portfolio-topaz-one-58.vercel.app/nyasha_hama_cv.pdf) · [LinkedIn](https://www.linkedin.com/in/nyasha-hama-5b1312229/) · [Email](mailto:nyashaahama@gmail.com)

I build operational products across responsive React and Next.js interfaces, Go services, PostgreSQL data models, background jobs, CI, and observability. My upstream work includes three merged PRs across Turso's Rust database engine and CrossHair's Python/C tracer.

## Selected Work

- **[ClinicPulse](https://github.com/nyashahama/clinic-pulse)** — Alpha clinic-operations product for public discovery, offline-capable field reporting, district review, partner access, and administrative governance. Built with Next.js, Go, and PostgreSQL; at the Aug 2026 revision, all 543 frontend tests and the full Go test suite passed. [Demo](https://clinic-pulse-five.vercel.app)

- **[StrataHQ](https://github.com/nyashahama/StrataHQ)** — Beta property-operations product for agents, trustees, and residents. Covers transactional levy reconciliation, bank-statement imports, idempotent background jobs, and maintenance workflows with Next.js, Go, PostgreSQL, sqlc, and Redis. [Demo](https://strata-hq-blue.vercel.app)

- **[E-Commerce Search Backend](https://github.com/nyashahama/optimizing-search-algorithms-in-e-commerce-platforms-backend)** — Java 21 and Spring Boot commerce backend with SQL LIKE, PostgreSQL full-text, in-memory, and OpenSearch discovery paths; Kafka-driven indexing; asynchronous benchmark jobs; and contract, authorization, and buyer-flow smoke tests in CI.

## Upstream Open Source

- **Turso · Rust** — Fixed SQLite-compatible schema and metadata invariants around `AUTOINCREMENT`: preserving state after `DROP COLUMN`, then clearing stale `sqlite_sequence` metadata when `ALTER COLUMN` removes the row-ID alias. [PR #6993](https://github.com/tursodatabase/turso/pull/6993) · [PR #7117](https://github.com/tursodatabase/turso/pull/7117)

- **CrossHair · Python/C** — Moved call-target normalization into the C tracer without changing keyword handling or trace dispatch, with regressions for Python and C bound methods, callable instances, and descriptor errors. [PR #413](https://github.com/pschanely/CrossHair/pull/413)

## Engineering Toolkit

- **Languages:** TypeScript, Go, Java, SQL, JavaScript, Rust, C#, C++
- **Frontend:** React, Next.js, Tailwind CSS, TanStack Query, responsive UI, design systems, accessibility testing
- **Backend & Data:** REST APIs, Go (Chi), Spring Boot, Node.js, PostgreSQL, pgx, sqlc, Redis, background jobs, SQLite internals
- **Platform & Quality:** Docker, Linux, Prometheus, structured logging, request tracing, GitHub Actions, Playwright, Vitest, CI/CD

## Contact

Open to full-stack product roles with meaningful frontend work and deep backend/platform ownership.  
[nyashaahama@gmail.com](mailto:nyashaahama@gmail.com) · [linkedin.com/in/nyasha-hama-5b1312229](https://www.linkedin.com/in/nyasha-hama-5b1312229/)
