# GenLayer Outcome Market — Corroborating Evidence Fixtures

This repository is the corroborating, commit-versioned fixture ledger for the
[Outcome Market](https://github.com/Manablaq/genlayer-outcome-market) Bradbury
release qualification. It is deliberately separate from the primary fixture
repository so the contract can enforce repository-separated corroboration.

The fixtures quote one pinned file from the official
[`genlayerlabs/genlayer-docs`](https://github.com/genlayerlabs/genlayer-docs)
repository. The observed authoritative bytes have SHA-256:

```text
844d219afb599bc08c51d9580458bf88d68f8f9947aa90562f9aa3dfc4c26a0e
```

Fixtures under `records/negative/` intentionally contradict or violate the
canonical schema and exist only to prove that settlement fails closed.

Repository separation is a contract requirement, not proof of separate
ownership. Both fixture repositories are maintained by the application owner
and are transparent test artifacts, not independent journalism or an oracle.
Corroborating commit-pinned evidence fixtures for Outcome Market Bradbury release verification.
