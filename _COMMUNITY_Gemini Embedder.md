---
type: community
cohesion: 0.25
members: 9
---

# Gemini Embedder

**Cohesion:** 0.25 - loosely connected
**Members:** 9 nodes

## Members
- [[.__init__()_10]] - code - harvester\src\injector\embedder.py
- [[._check_daily_limit()]] - code - harvester\src\injector\embedder.py
- [[._embed_sync()]] - code - harvester\src\injector\embedder.py
- [[.embed_batch()]] - code - harvester\src\injector\embedder.py
- [[Embedder]] - code - harvester\src\injector\embedder.py
- [[Embedder — wrapper Gemini text-embedding-004 con batching e quota giornaliera.]] - rationale - harvester\src\injector\embedder.py
- [[Embedding in batch (max 100call).  Splitta in sotto-batch se necessario.]] - rationale - harvester\src\injector\embedder.py
- [[Wrapper Gemini embedding con quota e batching automatico.]] - rationale - harvester\src\injector\embedder.py
- [[embedder.py]] - code - harvester\src\injector\embedder.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Gemini_Embedder
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[Embedder]] - degree 10, connects to 1 community