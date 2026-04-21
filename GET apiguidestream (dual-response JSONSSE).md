---
source_file: "backend/src/routes/guide.routes.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# GET /api/guide/stream (dual-response JSON/SSE)

## Connections
- [[POST apiguide (JSON)]] - `semantically_similar_to` [INFERRED]
- [[guideRequestSchema  guideStreamQuerySchema (zod)]] - `references` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `calls` [EXTRACTED]
- [[rootRouter (routes index)]] - `references` [EXTRACTED]
- [[tryCacheHit (SSE route dual-response gate)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker