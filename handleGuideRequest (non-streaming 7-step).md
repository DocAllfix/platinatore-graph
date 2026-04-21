---
source_file: "backend/src/services/orchestrator.service.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# handleGuideRequest (non-streaming 7-step)

## Connections
- [[DB_CANONICAL_LANGUAGE ('en')]] - `references` [EXTRACTED]
- [[GuideCache (Redis getset)]] - `calls` [EXTRACTED]
- [[POST apiguide (JSON)]] - `calls` [EXTRACTED]
- [[buildCacheKeyParams]] - `calls` [EXTRACTED]
- [[buildPromptContext]] - `calls` [EXTRACTED]
- [[enrichWithScraping (fallback when RAG empty)]] - `calls` [EXTRACTED]
- [[generateGuide (Gemini non-streaming)]] - `calls` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `semantically_similar_to` [INFERRED]
- [[logAndTrack (query_log + tracker upsert)]] - `calls` [EXTRACTED]
- [[normalizeQuery (main entry)]] - `calls` [EXTRACTED]
- [[retrieveContext (trophyâ†’topicâ†’RAG dispatch)]] - `calls` [EXTRACTED]
- [[translateGuide (ENâ†’lang via Gemini)]] - `calls` [EXTRACTED]
- [[tryCacheHit (SSE route dual-response gate)]] - `semantically_similar_to` [INFERRED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker