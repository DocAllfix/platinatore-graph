---
source_file: "il-platinatore-ai/backend/src/services/orchestrator.service.ts"
type: "code"
community: "Bulk Seed CLI"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Bulk_Seed_CLI
---

# Fail-open pattern (degrade graceful)

## Connections
- [[appendConvStategetConvHistory (Redis TTL)]] - `implements` [INFERRED]
- [[handleGuideRequest (8-step pipeline)]] - `implements` [EXTRACTED]
- [[notifyNewDraft (fail-open webhook)]] - `implements` [EXTRACTED]
- [[seedBatch (batch insert + fail-open)]] - `implements` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Bulk_Seed_CLI