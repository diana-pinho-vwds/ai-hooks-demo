# AI hooks demo

A small repository for demonstrating AI hooks against files in different directories.

The `.env` files are intentionally tracked and contain fictional placeholders only. Never put real credentials or sensitive data in this repository. Tracking environment files is for this demo only, not a production recommendation.

Fixtures:

- `.env` and `.env.local`: repository-root environment files
- `services/api/.env`: nested API configuration
- `services/web/.env.example`: nested example configuration
- `config/staging/.env`: environment-specific configuration
- `dummy.txt`, `docs/`, and `data/`: text, Markdown, and CSV fixtures
- `services/`, `scripts/`, and `config/settings.json`: sample source, HTML, and JSON fixtures

All content is fictional and intended for reading or editing during hook tests. No application or hooks are configured; these files are fixtures for your own hook tests.
