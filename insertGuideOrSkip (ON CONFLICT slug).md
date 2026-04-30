---
source_file: "il-platinatore-ai/backend/src/scripts/bulk-seed.ts"
type: "code"
community: "Fextralife Collector"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Fextralife_Collector
---

# insertGuideOrSkip (ON CONFLICT slug)

## Connections
- [[Idempotency via ON CONFLICT DO NOTHING]] - `implements` [EXTRACTED]
- [[enqueuePendingGuides (cursor pagination)]] - `shares_data_with` [INFERRED]
- [[seedBatch (batch insert + fail-open)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Fextralife_Collector