# Changelog

See https://crew.studiomeyer.io/health for current server version.

## Connector

- 2026-07-16 — v2.7.1: security hardening wave (S1578). Server-side email validation + normalization on the magic-link path, js-yaml JSON_SCHEMA parsing (merge-key DoS mitigation), persona file size cap, and OAuth redirect_uri exact-match. No feature/tool change — 16 tools, 13 personas, 3 workflows unchanged. Manifest version synced.
- 2026-07-11 — v2.7.0: hardening wave (S1512). /ready DB-roundtrip healthcheck, stateless-transport feedback/status fixes, social-login email-verified enforcement, refresh-token reuse detection, rate-limit + Sentry capture. No feature change.
- 2026-06-20 — v2.5.0: 12 tools (added `crew_council` for blind-vote councils/debates + `crew_ensemble` for standing teams), 13 personas (+5 Pro: Legal Advisor, Sales Engineer, Data Scientist, UX Researcher, DevRel), MCP **resources** (`crew://persona/{name}` + `crew://workflow/{name}` + `resources/templates/list`), bidirectional memory write-back, structured tool output (`structuredContent`), and opt-in `crmBrief` + `pdf` flags. README + manifest synced.
- 2026-04-26 — Initial public connector. Pattern-A docs-only repository for MCP listings (Glama, MCPize, MCP Registry).
