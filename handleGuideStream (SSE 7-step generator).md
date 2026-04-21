---
source_file: "backend/src/services/orchestrator.stream.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# handleGuideStream (SSE 7-step generator)

## Connections
- [[DB_CANONICAL_LANGUAGE ('en')]] - `references` [EXTRACTED]
- [[GET apiguidestream (dual-response JSONSSE)]] - `calls` [EXTRACTED]
- [[GuideCache (Redis getset)]] - `calls` [EXTRACTED]
- [[buildCacheKeyParams]] - `calls` [EXTRACTED]
- [[buildPromptContext]] - `calls` [EXTRACTED]
- [[enrichWithScraping (fallback when RAG empty)]] - `calls` [EXTRACTED]
- [[generateGuideStream (Gemini SSE)]] - `calls` [EXTRACTED]
- [[handleGuideRequest (non-streaming 7-step)]] - `semantically_similar_to` [INFERRED]
- [[logAndTrack (query_log + tracker upsert)]] - `calls` [EXTRACTED]
- [[normalizeQuery (main entry)]] - `calls` [EXTRACTED]
- [[retrieveContext (trophyâ†’topicâ†’RAG dispatch)]] - `calls` [EXTRACTED]
- [[translateGuide (ENâ†’lang via Gemini)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker