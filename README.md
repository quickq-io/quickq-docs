# quickq-docs

> Placeholder repository in the [`quickq`](https://github.com/quickq-io/quickq) ecosystem.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

The published documentation site lives at **<https://quickq-io.github.io/quickq/>**, served from the `gh-pages` branch of the [`quickq`](https://github.com/quickq-io/quickq) repository (built by a GitHub Actions workflow on every push to `main` that touches `docs/` or `mkdocs.yml`).

This repo currently has no role beyond holding the `quickq-docs` name. It may be repurposed later for non-mkdocs assets (slide decks, posters, recorded demos) or archived.

## Read the docs

- Published site: <https://quickq-io.github.io/quickq/>
- mkdocs source: [`quickq/docs/`](https://github.com/quickq-io/quickq/tree/main/docs)
- Local preview: `git clone https://github.com/quickq-io/quickq.git && cd quickq && uv sync && uv run mkdocs serve`

## Related repos

- **[quickq](https://github.com/quickq-io/quickq)** — Python SDK + CLI, plus the canonical mkdocs source
- **[quickq-forms](https://github.com/quickq-io/quickq-forms)** — FHIR delivery layer (the `quickq serve` server)

## License

Apache License 2.0 — see [LICENSE](LICENSE).
