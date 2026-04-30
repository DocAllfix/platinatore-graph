---
type: community
cohesion: 0.14
members: 22
---

# Circuit Breaker + Guide Cache

**Cohesion:** 0.14 - loosely connected
**Members:** 22 nodes

## Members
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - code - backend/src/services/llm.circuitBreaker.ts
- [[CircuitBreaker Vitest suite]] - code - backend/src/services/llm.circuitBreaker.test.ts
- [[CircuitOpenError]] - code - backend/src/services/llm.circuitBreaker.ts
- [[GuideCache (Redis getset)]] - code - backend/src/services/guide.cache.ts
- [[GuideRequestTrackerModel.upsertTrophyRequest]] - code - backend/src/models/guideRequestTracker.model.ts
- [[RetrievalBundle (shared shape)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[computeKey (guide{gameSlug}{target}{lang})]] - code - backend/src/services/guide.cache.ts
- [[detectLanguage (ITEN heuristic)]] - code - backend/src/services/query.normalizer.ts
- [[enrichWithScraping (fallback when RAG empty)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[extractGame (321-gram fuzzy)]] - code - backend/src/services/query.normalizer.ts
- [[extractTopicHint (keyword regex map)]] - code - backend/src/services/query.normalizer.ts
- [[extractTrophy (TrophyLookupService)]] - code - backend/src/services/query.normalizer.ts
- [[gemini-chat CircuitBreaker instance]] - code - backend/src/services/llm.service.ts
- [[generateGuide (Gemini non-streaming)]] - code - backend/src/services/llm.service.ts
- [[generateGuideStream (Gemini SSE)]] - code - backend/src/services/llm.service.ts
- [[handleGuideStream (SSE 7-step generator)]] - code - backend/src/services/orchestrator.stream.ts
- [[looksLikeTrophyQuery]] - code - backend/src/services/query.normalizer.ts
- [[normalizeQuery (main entry)]] - code - backend/src/services/query.normalizer.ts
- [[primaryModel (GoogleGenerativeAI client)]] - code - backend/src/services/llm.service.ts
- [[retrieveContext (trophyâ†’topicâ†’RAG dispatch)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[slugify (NFD + URL-safe normaliser)]] - code - backend/src/services/guide.cache.ts
- [[translateGuide (ENâ†’lang via Gemini)]] - code - backend/src/services/llm.service.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Circuit_Breaker_+_Guide_Cache
SORT file.name ASC
```
