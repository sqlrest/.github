# sqlrest

> **SQL is the API. Everything else is plumbing.**

Most data stacks spend enormous effort translating between the database and the world above it: an ORM here, a hand-written service there, a query language that compiles to another query language, layer upon layer of mapping whose only job is to carry rows from one side to the other. SQL already describes the data perfectly. The work gathered here starts from a contrary premise — that the translation layer is the problem, and that the shortest path between an application and its data is the one that keeps SQL at the center.

So the focus is the unglamorous, load-bearing machinery around PostgreSQL: turning queries into endpoints without a bespoke backend, managing how a schema changes over time, testing what the database actually does rather than what an application imagines it does, and the small, exact algorithms that keep all of it correct. Foundational, sharp-edged tools — the kind you stop noticing precisely because they work.

The throughline is respect for the database as a first-class system rather than a dumb store to be hidden behind code. Lean on what SQL and Postgres already do well, strip away the ceremony that surrounds them, and let the data speak for itself.

## Explore

- **[sql.rest](https://sql.rest)** — the project home
- **[sqlid](https://github.com/sqlrest/sqlid)** — stable, normalization-aware identity for SQL statements

---

<p align="center"><em>Keep SQL at the center. Remove everything in its way.</em></p>
