---
type: community
cohesion: 0.07
members: 39
---

# RAG Architecture Concepts

**Cohesion:** 0.07 - loosely connected
**Members:** 39 nodes

## Members
- [[Chat page (SSE streaming)]] - code - il-platinatore-ai/frontend/src/pages/Chat.jsx
- [[Chat.handleSend (api.guideStream)]] - code - il-platinatore-ai/frontend/src/pages/Chat.jsx
- [[DB canonically English (harvester rule)]] - document - il-platinatore-ai/backend/src/services/orchestrator.shared.ts
- [[DB_CANONICAL_LANGUAGE constant (en)]] - code - il-platinatore-ai/backend/src/services/orchestrator.shared.ts
- [[Frontend App.jsx router]] - code - il-platinatore-ai/frontend/src/App.jsx
- [[Frontend README (Vite+React)]] - document - il-platinatore-ai/frontend/README.md
- [[GuideType taxonomy (5 fissi migration 004)]] - document - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[Harvester README]] - document - il-platinatore-ai/harvester/README.md
- [[Login page]] - code - il-platinatore-ai/frontend/src/pages/Login.jsx
- [[PSN anchor anti-hallucination pattern]] - document - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[PasswordStrength component]] - code - il-platinatore-ai/frontend/src/pages/Register.jsx
- [[Project README]] - document - il-platinatore-ai/README.md
- [[Prompt injection sanitization defense]] - document - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[RAG hybrid pipeline (HNSW + RRF)]] - document - il-platinatore-ai/README.md
- [[Register page]] - code - il-platinatore-ai/frontend/src/pages/Register.jsx
- [[SSE streaming chat UX (chunked bubble)]] - document - il-platinatore-ai/frontend/src/pages/Chat.jsx
- [[SYSTEM_CORE invariants prompt fence]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[TRUSTED_DOMAINS allowlist]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[Tavily daily request cap (Redis incr)]] - document - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[Vitest setup ioredis-mock]] - code - il-platinatore-ai/backend/tests/setup.ts
- [[assembleUserContext]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildCacheKeyParams]] - code - il-platinatore-ai/backend/src/services/orchestrator.shared.ts
- [[buildChallenge template]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildCollectible template]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildPlatinum template]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildPrompt dispatcher]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildPromptContext]] - code - il-platinatore-ai/backend/src/services/orchestrator.shared.ts
- [[buildTrophy template]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[buildWalkthrough template]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[callTavily]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[checkDailyLimit (Redis daily cap)]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[fetchScrapedContext (Tavily)]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[formatPsnAnchor]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[formatPsnOfficial]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts
- [[il-platinatore-ai CLAUDE.md (graphify rules)]] - document - il-platinatore-ai/CLAUDE.md
- [[isTrusted domain check]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[logAndTrack]] - code - il-platinatore-ai/backend/src/services/orchestrator.shared.ts
- [[reliabilityScore]] - code - il-platinatore-ai/backend/src/services/scraper.client.ts
- [[sanitizeUserQuery (anti-injection)]] - code - il-platinatore-ai/backend/src/services/prompt.builder.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/RAG_Architecture_Concepts
SORT file.name ASC
```
