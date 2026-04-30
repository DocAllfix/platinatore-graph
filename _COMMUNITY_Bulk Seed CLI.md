---
type: community
cohesion: 0.10
members: 29
---

# Bulk Seed CLI

**Cohesion:** 0.10 - loosely connected
**Members:** 29 nodes

## Members
- [[Checkpoint (resume on .checkpoint.json)]] - code - il-platinatore-ai/backend/src/scripts/bulk-seed.ts
- [[Fail-open pattern (degrade graceful)]] - code - il-platinatore-ai/backend/src/services/orchestrator.service.ts
- [[Idempotency via ON CONFLICT DO NOTHING]] - code - il-platinatore-ai/backend/src/scripts/bulk-seed.ts
- [[Phase 23 — HITL Self-Learning RAG]] - code - il-platinatore-ai/backend/src/services/draft.service.ts
- [[appendConvStategetConvHistory (Redis TTL)]] - code - il-platinatore-ai/backend/src/services/draft.service.ts
- [[approveDraft]] - code - il-platinatore-ai/backend/src/services/draft.service.ts
- [[buildGuideSlug (slug + UUID8 suffix)]] - code - il-platinatore-ai/backend/src/services/ingestion.service.ts
- [[buildSlug()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[bulk-seed.test.ts]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.test.ts
- [[bulk-seed.ts]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[clearCheckpoint()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[createDraft (HITL + Redis convo)]] - code - il-platinatore-ai/backend/src/services/draft.service.ts
- [[enqueuePendingGuides (cursor pagination)]] - code - il-platinatore-ai/backend/src/scripts/re-embed-pending.ts
- [[guideRecordSchema (Zod JSONL row)]] - code - il-platinatore-ai/backend/src/scripts/bulk-seed.ts
- [[handleGuideRequest (8-step pipeline)]] - code - il-platinatore-ai/backend/src/services/orchestrator.service.ts
- [[ingestApprovedDraft (publish pipeline)]] - code - il-platinatore-ai/backend/src/services/ingestion.service.ts
- [[insertGuideOrSkip (ON CONFLICT slug)]] - code - il-platinatore-ai/backend/src/scripts/bulk-seed.ts
- [[insertGuideOrSkip()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[main()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[notifyNewDraft (fail-open webhook)]] - code - il-platinatore-ai/backend/src/services/notification.service.ts
- [[parseArgs()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[readCheckpoint()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[reviseDraft (LLM iter, MAX=5)]] - code - il-platinatore-ai/backend/src/services/draft.service.ts
- [[seedBatch (batch insert + fail-open)]] - code - il-platinatore-ai/backend/src/scripts/bulk-seed.ts
- [[seedBatch()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[slugify()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts
- [[tryCacheHit (SSE precheck)]] - code - il-platinatore-ai/backend/src/services/orchestrator.service.ts
- [[validateDraft (5-layer validation)]] - code - il-platinatore-ai/backend/src/services/ingestion.service.ts
- [[writeCheckpoint()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\backend\src\scripts\bulk-seed.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Bulk_Seed_CLI
SORT file.name ASC
```
