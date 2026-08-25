# Nyasha Hama

**Software Engineer · Backend, Systems & Product Engineering**<br>
Rust · Go · Java · C++ · TypeScript · PostgreSQL

Cape Town, South Africa<br>
[Portfolio](https://portfolio-topaz-one-58.vercel.app/) · [Résumé (PDF)](https://portfolio-topaz-one-58.vercel.app/nyasha_hama_cv.pdf) · [LinkedIn](https://www.linkedin.com/in/nyasha-hama-5b1312229/) · [Email](mailto:nyashahama5@gmail.com)

I build reliable backends, infrastructure-minded tools, and the product surfaces around them. I reach for Rust when correctness and control matter, Go for simple and operable services, Java and Spring for robust application backends, and C++ for algorithms and systems fundamentals.

## Language Depth

- **Rust** — Building the TxProof tooling below; contributed two merged correctness fixes to Turso's SQLite-compatible engine.
- **Go** — Built REST services with authentication, PostgreSQL, pgx/sqlc, Redis, background processing, observability, and operational tests across ClinicPulse, StrataHQ, and Healthcare Access Connector.
- **Java** — Studied core Java, OOP, data structures, concurrency, JVM concepts, design patterns, networking, and Spring/Spring Boot; built a Java 21 commerce backend with four search paths, Kafka indexing, benchmark jobs, contract tests, and buyer-flow coverage.
- **C++ & algorithms** — Solve data-structure and algorithm problems in C++ and Java across dynamic programming, graph and tree traversal, backtracking, union-find, hashing, and sliding-window techniques. [LeetCode profile](https://leetcode.com/u/VG3KDXbWh4/)
- **AWS foundations** — Self-studied core developer concepts including S3; public code includes an [AWS SES provider implemented with the AWS SDK for Go](https://github.com/nyashahama/healthcare-access-connector-backend/tree/main/internal/email/providers/ses).

## Selected Work

- **[TxProof](https://tx-proof.vercel.app)** — Rust tooling for finding, replaying, and shrinking failure cases in money-moving backends. The search is deliberately bounded rather than presented as formal proof. [Source](https://github.com/nyashahama/tx-proof) · [CI workflow](https://github.com/nyashahama/tx-proof/actions/workflows/rust.yml)

- **[ClinicPulse](https://github.com/nyashahama/clinic-pulse)** — Clinic-operations product for public discovery, offline-capable field reporting, district review, partner access, and administrative governance, built with Next.js, Go, and PostgreSQL. [Demo](https://clinic-pulse-five.vercel.app)

- **[StrataHQ](https://github.com/nyashahama/StrataHQ)** — Property-operations product covering transactional levy reconciliation, bank-statement imports, idempotent background jobs, and maintenance workflows with Next.js, Go, PostgreSQL, sqlc, and Redis. [Demo](https://strata-hq-blue.vercel.app)

- **[E-Commerce Search Backend](https://github.com/nyashahama/optimizing-search-algorithms-in-e-commerce-platforms-backend)** — Java 21 and Spring Boot commerce backend with four comparable search paths, Kafka-driven indexing, asynchronous benchmarks, and executable authorization and endpoint contracts.

## Upstream Open Source

- **Turso · Rust** — Fixed SQLite-compatible schema and metadata invariants around `AUTOINCREMENT`: preserving state after `DROP COLUMN`, then clearing stale `sqlite_sequence` metadata when `ALTER COLUMN` removes the row-ID alias. [PR #6993](https://github.com/tursodatabase/turso/pull/6993) · [PR #7117](https://github.com/tursodatabase/turso/pull/7117)

- **CrossHair · Python/C** — Moved call-target normalization into the C tracer without changing keyword handling or trace dispatch, with regressions for Python and C bound methods, callable instances, and descriptor errors. [PR #413](https://github.com/pschanely/CrossHair/pull/413)

## Engineering Toolkit

- **Backend & Data:** REST APIs, Spring Boot, Go (Chi), PostgreSQL, pgx, sqlc, Redis, background jobs, SQLite internals
- **Systems & Problem Solving:** data structures and algorithms, concurrency fundamentals, failure injection, deterministic replay, database internals
- **Cloud & Platform:** AWS SDK for Go (SES), Docker, Linux, GitHub Actions, CI/CD, Prometheus, structured logging, request tracing
- **Product Delivery:** React, Next.js, responsive UI, design systems, accessibility, Playwright, Vitest

## Contact

Open to backend, platform, systems, and full-stack product roles with substantial backend ownership.<br>
[nyashahama5@gmail.com](mailto:nyashahama5@gmail.com) · [linkedin.com/in/nyasha-hama-5b1312229](https://www.linkedin.com/in/nyasha-hama-5b1312229/)
