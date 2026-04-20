---
type: community
cohesion: 0.67
members: 3
---

# Deduplicator — evita upsert inutili e pr

**Cohesion:** 0.67 - moderately connected
**Members:** 3 nodes

## Members
- [[Deduplicator — evita upsert inutili e protegge guide verificate.]] - rationale - harvester\src\injector\deduplicator.py
- [[deduplicator.py]] - code - harvester\src\injector\deduplicator.py
- [[should_upsert()]] - code - harvester\src\injector\deduplicator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Deduplicator_—_evita_upsert_inutili_e_pr
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[deduplicator.py]] - degree 3, connects to 1 community