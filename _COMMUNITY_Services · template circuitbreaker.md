---
type: community
cohesion: 0.09
members: 46
---

# Services · template circuitbreaker

**Cohesion:** 0.09 - loosely connected
**Members:** 46 nodes

## Members
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - code - backend/src/services/llm.circuitBreaker.ts
- [[CircuitBreaker Vitest suite]] - code - backend/src/services/llm.circuitBreaker.test.ts
- [[CircuitOpenError_1]] - code - backend/src/services/llm.circuitBreaker.ts
- [[DB_CANONICAL_LANGUAGE ('en')]] - code - backend/src/services/orchestrator.shared.ts
- [[Env Zod Schema]] - code - backend/src/config/env.ts
- [[GET apiguidestream (dual-response JSONSSE)]] - code - backend/src/routes/guide.routes.ts
- [[GuideCache (Redis getset)]] - code - backend/src/services/guide.cache.ts
- [[GuideRequestTrackerModel.upsertTrophyRequest]] - code - backend/src/models/guideRequestTracker.model.ts
- [[POST apiguide (JSON)]] - code - backend/src/routes/guide.routes.ts
- [[RetrievalBundle (shared shape)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[SYSTEM_CORE fence (invariant rules)]] - code - backend/src/services/prompt.builder.ts
- [[assembleUserContext (ragâ†’scrapingâ†’empty)]] - code - backend/src/services/prompt.builder.ts
- [[buildCacheKeyParams]] - code - backend/src/services/orchestrator.shared.ts
- [[buildChallenge template]] - code - backend/src/services/prompt.builder.ts
- [[buildCollectible template]] - code - backend/src/services/prompt.builder.ts
- [[buildPlatinum template]] - code - backend/src/services/prompt.builder.ts
- [[buildPrompt (template dispatcher)]] - code - backend/src/services/prompt.builder.ts
- [[buildPrompt Vitest suite]] - code - backend/src/services/prompt.builder.test.ts
- [[buildPromptContext]] - code - backend/src/services/orchestrator.shared.ts
- [[buildTrophy template]] - code - backend/src/services/prompt.builder.ts
- [[buildWalkthrough template]] - code - backend/src/services/prompt.builder.ts
- [[computeKey (guide{gameSlug}{target}{lang})]] - code - backend/src/services/guide.cache.ts
- [[detectLanguage (ITEN heuristic)]] - code - backend/src/services/query.normalizer.ts
- [[detectLanguage Vitest suite]] - code - backend/src/services/query.normalizer.test.ts
- [[enrichWithScraping (fallback when RAG empty)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[extractGame (321-gram fuzzy)]] - code - backend/src/services/query.normalizer.ts
- [[extractTopicHint (keyword regex map)]] - code - backend/src/services/query.normalizer.ts
- [[extractTrophy (TrophyLookupService)]] - code - backend/src/services/query.normalizer.ts
- [[fetchScrapedContext (Fase 16 stub)]] - code - backend/src/services/scraper.client.ts
- [[formatPsnAnchor (anti-hallucination)]] - code - backend/src/services/prompt.builder.ts
- [[gemini-chat CircuitBreaker instance]] - code - backend/src/services/llm.service.ts
- [[generateGuide (Gemini non-streaming)]] - code - backend/src/services/llm.service.ts
- [[generateGuideStream (Gemini SSE)]] - code - backend/src/services/llm.service.ts
- [[guideRequestSchema  guideStreamQuerySchema (zod)]] - code - backend/src/routes/guide.routes.ts
- [[handleGuideRequest (non-streaming 7-step)]] - code - backend/src/services/orchestrator.service.ts
- [[handleGuideStream (SSE 7-step generator)]] - code - backend/src/services/orchestrator.stream.ts
- [[loadEnv() â€” boot-time env validator]] - code - backend/src/config/env.ts
- [[logAndTrack (query_log + tracker upsert)]] - code - backend/src/services/orchestrator.shared.ts
- [[looksLikeTrophyQuery]] - code - backend/src/services/query.normalizer.ts
- [[normalizeQuery (main entry)]] - code - backend/src/services/query.normalizer.ts
- [[primaryModel (GoogleGenerativeAI client)]] - code - backend/src/services/llm.service.ts
- [[retrieveContext (trophyâ†’topicâ†’RAG dispatch)]] - code - backend/src/services/orchestrator.retrieval.ts
- [[rootRouter (routes index)]] - code - backend/src/routes/index.ts
- [[slugify (NFD + URL-safe normaliser)]] - code - backend/src/services/guide.cache.ts
- [[translateGuide (ENâ†’lang via Gemini)]] - code - backend/src/services/llm.service.ts
- [[tryCacheHit (SSE route dual-response gate)]] - code - backend/src/services/orchestrator.service.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Services_·_template_circuitbreaker
SORT file.name ASC
```
