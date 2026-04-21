---
source_file: "backend/src/services/orchestrator.service.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# tryCacheHit (SSE route dual-response gate)

## Connections
- [[GET apiguidestream (dual-response JSONSSE)]] - `calls` [EXTRACTED]
- [[GuideCache (Redis getset)]] - `calls` [EXTRACTED]
- [[handleGuideRequest (non-streaming 7-step)]] - `semantically_similar_to` [INFERRED]
- [[logAndTrack (query_log + tracker upsert)]] - `calls` [EXTRACTED]
- [[normalizeQuery (main entry)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker