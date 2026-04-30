---
type: community
cohesion: 0.20
members: 11
---

# Community 42

**Cohesion:** 0.20 - loosely connected
**Members:** 11 nodes

## Members
- [[BENCH_RESULT.md (load test + verifica Pre-Beta thresholds)]] - document - BENCH_RESULT.md
- [[CLAUDE.md (regole progetto + invariant)]] - document - CLAUDE.md
- [[CLAUDE.md regola 11 — backend single replica (rate limit Gemini per-worker)]] - document - CLAUDE.md
- [[Cache HIT latency 29ms (target 100ms)]] - document - BENCH_RESULT.md
- [[DB canonicalmente inglese (post-T1.2 default 'en')]] - document - CLAUDE.md
- [[Rate limit free tier 5min (sliding window Redis Lua)]] - document - BENCH_RESULT.md
- [[T1.2 — Migration 028 multilang embeddings]] - document - EXECUTION_TRACKER.md
- [[T1.5 — embedding.queue race condition fix (state=active)]] - document - EXECUTION_TRACKER.md
- [[T1.6 — Embedding chunk_hash idempotency]] - document - EXECUTION_TRACKER.md
- [[T2.6 — tierRateLimiter (freeregisteredproplatinum)]] - document - EXECUTION_TRACKER.md
- [[T4.2 — Load test script Node nativo (multi-lang, p953s)]] - document - BENCH_RESULT.md

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Community_42
SORT file.name ASC
```
