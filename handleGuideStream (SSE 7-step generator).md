---
source_file: "backend/src/services/orchestrator.stream.ts"
type: "code"
community: "Circuit Breaker + Guide Cache"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Circuit_Breaker_+_Guide_Cache
---

# handleGuideStream (SSE 7-step generator)

## Connections
- [[GuideCache (Redis getset)]] - `calls` [EXTRACTED]
- [[enrichWithScraping (fallback when RAG empty)]] - `calls` [EXTRACTED]
- [[generateGuideStream (Gemini SSE)]] - `calls` [EXTRACTED]
- [[normalizeQuery (main entry)]] - `calls` [EXTRACTED]
- [[retrieveContext (trophyâ†’topicâ†’RAG dispatch)]] - `calls` [EXTRACTED]
- [[translateGuide (ENâ†’lang via Gemini)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Circuit_Breaker_+_Guide_Cache