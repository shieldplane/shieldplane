# Public Release Notes

This file carries concise public-facing release notes for Shieldplane.

## 2026-04

### Product maturity

- UI-first governed workflow validated end to end in local product labs
- Postgres established as the authoritative source of truth for incidents, events, workflow state, and worker tasks
- OIDC and ingress/TLS validation added to the supported evaluation path

### Operability

- Worker task visibility improved with explicit task states, retry policy, failure summaries, and operational drill-down
- Failure and retry paths exercised for evidence, delivery, verification, and inference scenarios
- Canonical workflow authority clarified in the UI/API, with external channels treated as notification, context, and deep-link surfaces

### Packaging and install

- Shieldplane chart source consolidated under `charts/shieldplane`
- OCI chart distribution prepared and published to GHCR for authorized customers and evaluators
- Public installation docs aligned to the current Helm/OCI distribution model
