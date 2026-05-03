# quickq-docs

> Published documentation site for the [`quickq`](https://github.com/quickq-io/quickq) ecosystem.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

This repository hosts the published version of the quickq documentation. The canonical source of the docs lives in the main [`quickq`](https://github.com/quickq-io/quickq) repo under `docs/` (mkdocs-material site); a future build pipeline will sync builds from there into this repo for hosting.

## Where to read the docs today

Until the published site is up, read the docs from source:

```bash
git clone https://github.com/quickq-io/quickq.git
cd quickq
uv sync
uv run mkdocs serve         # opens http://127.0.0.1:8000
```

Or browse the markdown directly on GitHub:

- **[End-to-End Walkthrough](https://github.com/quickq-io/quickq/blob/main/docs/tutorials/end-to-end.md)** — the beta tester quickstart
- **[The Study Journey](https://github.com/quickq-io/quickq/blob/main/docs/tutorial.md)** — phase-by-phase tour
- **[Architecture](https://github.com/quickq-io/quickq/blob/main/docs/architecture.md)**
- **[Design Decisions](https://github.com/quickq-io/quickq/blob/main/docs/design_decisions.md)**

## Related repos

- **[quickq](https://github.com/quickq-io/quickq)** — Python SDK + CLI, plus the canonical mkdocs source
- **[quickq-forms](https://github.com/quickq-io/quickq-forms)** — FHIR delivery layer (the `quickq serve` server)

## License

Apache License 2.0 — see [LICENSE](LICENSE).
