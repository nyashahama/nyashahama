# Nyasha Hama

**Software Engineer · Product & Backend Systems**<br>
Cape Town, South Africa

[Portfolio](https://www.nyashahama.xyz) · [CV](https://www.nyashahama.xyz/nyasha_hama_cv.pdf) · [LinkedIn](https://www.linkedin.com/in/nyasha-hama-5b1312229/) · [Email](mailto:nyashahama5@gmail.com)

I build operational products from interface to data model, with particular attention to retries, access boundaries, and recoverable failures. My public work spans Next.js and Go products, Rust tooling for bounded payment-failure testing, and maintainer-merged changes to Turso and CrossHair.

## Start with the work

| Project | Engineering question | Inspect |
| --- | --- | --- |
| **[ClinicPulse](https://github.com/nyashahama/clinic-pulse)** | How does a field report survive weak connectivity without becoming a duplicate or hiding a conflict? | [Offline sync implementation](https://github.com/nyashahama/clinic-pulse/blob/main/services/api/internal/service/offline_sync.go) · [Regression tests](https://github.com/nyashahama/clinic-pulse/blob/main/services/api/internal/service/offline_sync_test.go) · [Demo](https://clinic-pulse-five.vercel.app) |
| **[StrataHQ](https://github.com/nyashahama/StrataHQ)** | How do bank-statement rows become reviewable payments when references are ambiguous? | [Import service](https://github.com/nyashahama/StrataHQ/blob/main/backend/internal/levy/bank_statement_import.go) · [Matching tests](https://github.com/nyashahama/StrataHQ/blob/main/backend/internal/levy/bank_statement_import_test.go) · [Seeded beta demo](https://strata-hq-blue.vercel.app) |
| **[TxProof](https://github.com/nyashahama/tx-proof)** | What can an ambiguous provider outcome do to a payment flow, and how can the failure be replayed? | [Campaign planner](https://github.com/nyashahama/tx-proof/blob/main/crates/tiv-core/src/plan.rs) · [Configured-run regression](https://github.com/nyashahama/tx-proof/blob/main/crates/tiv-cli/tests/configured_run.rs) · [CI](https://github.com/nyashahama/tx-proof/actions/workflows/rust.yml) |

ClinicPulse is an alpha demonstration. StrataHQ is a beta demonstration with seeded data. TxProof searches bounded histories against a synthetic reference application. The linked code and tests show the implemented boundaries.

## Maintainer-merged contributions

- **Turso, Rust:** Contributed two schema-transition correctness fixes to a SQLite-compatible engine. The work covers preserving `AUTOINCREMENT` state after `DROP COLUMN` and clearing stale sequence metadata after an `ALTER COLUMN` transition. [PR #6993](https://github.com/tursodatabase/turso/pull/6993) · [PR #7117](https://github.com/tursodatabase/turso/pull/7117)
- **CrossHair, Python/C:** Moved callable-target normalization into the C tracer while preserving keyword handling, dispatch, and descriptor errors; added behavioral regression coverage. [PR #413](https://github.com/pschanely/CrossHair/pull/413)

## Additional backend work

- **[Java commerce and search backend](https://github.com/nyashahama/optimizing-search-algorithms-in-e-commerce-platforms-backend):** Java 21/Spring Boot API with SQL LIKE, PostgreSQL full-text, in-memory, and OpenSearch paths, Kafka indexing, asynchronous benchmark jobs, and authorization/endpoint contracts.
- **[Guard Rail](https://github.com/nyashahama/guard-rail):** Beta Rust policy runtime for internal API traffic, credential stripping, audit records, and replay against recorded or current policies.

I also study algorithms in [C++ and Java](https://leetcode.com/u/VG3KDXbWh4/). Current confidential full-stack work includes C#; client and implementation details remain under NDA.

If a project is relevant to your team, I am happy to walk through the failure case, the tradeoffs, the test boundary, and what I would change for a production deployment.
