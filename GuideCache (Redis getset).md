---
source_file: "backend/src/services/guide.cache.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# GuideCache (Redis get/set)

## Connections
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - `conceptually_related_to` [INFERRED]
- [[Env Zod Schema]] - `references` [EXTRACTED]
- [[computeKey (guide{gameSlug}{target}{lang})]] - `calls` [EXTRACTED]
- [[enrichWithScraping (fallback when RAG empty)]] - `conceptually_related_to` [INFERRED]
- [[handleGuideRequest (non-streaming 7-step)]] - `calls` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `calls` [EXTRACTED]
- [[tryCacheHit (SSE route dual-response gate)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker