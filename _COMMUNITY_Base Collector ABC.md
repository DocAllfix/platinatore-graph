---
type: community
cohesion: 0.10
members: 28
---

# Base Collector ABC

**Cohesion:** 0.10 - loosely connected
**Members:** 28 nodes

## Members
- [[Auth Routes]] - code - il-platinatore-ai/backend/src/routes/auth.routes.ts
- [[Draft FSM (draft-revision-pending-approved-published)]] - code - il-platinatore-ai/backend/src/models/guideDrafts.model.ts
- [[Draft Routes]] - code - il-platinatore-ai/backend/src/routes/draft.routes.ts
- [[Env Config Zod Schema]] - code - il-platinatore-ai/backend/src/config/env.ts
- [[Express App Bootstrap (index.ts)]] - code - il-platinatore-ai/backend/src/index.ts
- [[GameStats Routes]] - code - il-platinatore-ai/backend/src/routes/gameStats.routes.ts
- [[Guide Routes (RAG)]] - code - il-platinatore-ai/backend/src/routes/guide.routes.ts
- [[GuideDrafts Model]] - code - il-platinatore-ai/backend/src/models/guideDrafts.model.ts
- [[GuideDrafts Model Tests]] - code - il-platinatore-ai/backend/src/models/guideDrafts.model.test.ts
- [[IDOR Guard via WHERE user_id]] - code - il-platinatore-ai/backend/src/models/userGameStats.model.ts
- [[JWT + CSRF + Refresh Token Pair]] - code - il-platinatore-ai/backend/src/routes/auth.routes.ts
- [[PgBouncer Connection (port 6432)]] - code - il-platinatore-ai/backend/src/config/env.ts
- [[RateLimiter Tests]] - code - il-platinatore-ai/backend/src/middleware/rateLimiter.test.ts
- [[Ratings Model]] - code - il-platinatore-ai/backend/src/models/ratings.model.ts
- [[Ratings Model Tests]] - code - il-platinatore-ai/backend/src/models/ratings.model.test.ts
- [[Redis Lua Sliding Window Rate Limit]] - code - il-platinatore-ai/backend/src/middleware/rateLimiter.test.ts
- [[SSE Dual Response (cache HIT JSON  MISS SSE)]] - code - il-platinatore-ai/backend/src/routes/guide.routes.ts
- [[Section Admin endpoints HITL (Fase 24)]] - document - il-platinatore-ai/ARCHITECTURE.md
- [[Section Draft FSM (state machine)]] - document - il-platinatore-ai/ARCHITECTURE.md
- [[Section IDOR Guard via WHERE user_id]] - document - il-platinatore-ai/ARCHITECTURE.md
- [[Section SSE streaming chat UX]] - document - il-platinatore-ai/ARCHITECTURE.md
- [[UserGameStats Model]] - code - il-platinatore-ai/backend/src/models/userGameStats.model.ts
- [[UserGameStats Model Tests]] - code - il-platinatore-ai/backend/src/models/userGameStats.model.test.ts
- [[Users Model]] - code - il-platinatore-ai/backend/src/models/users.model.ts
- [[Users Model Tests]] - code - il-platinatore-ai/backend/src/models/users.model.test.ts
- [[Vitest Integration Test Config]] - code - il-platinatore-ai/backend/vitest.integration.config.ts
- [[Vitest Unit Test Config]] - code - il-platinatore-ai/backend/vitest.config.ts
- [[Zod Strict Schema Validation]] - code - il-platinatore-ai/backend/src/config/env.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Base_Collector_ABC
SORT file.name ASC
```
