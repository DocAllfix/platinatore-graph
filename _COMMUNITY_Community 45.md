---
type: community
cohesion: 0.22
members: 11
---

# Community 45

**Cohesion:** 0.22 - loosely connected
**Members:** 11 nodes

## Members
- [[.__init__()_9]] - code - harvester\src\injector\deduplicator.py
- [[.guide_exists()]] - code - harvester\src\injector\deduplicator.py
- [[.source_already_processed()]] - code - harvester\src\injector\deduplicator.py
- [[Deduplicator]] - code - harvester\src\injector\deduplicator.py
- [[Deduplicator — evita upsert inutili e protegge guide verificate.]] - rationale - harvester\src\injector\deduplicator.py
- [[Logica di deduplicazione basata su DB lookup.]] - rationale - harvester\src\injector\deduplicator.py
- [[Ritorna la guida esistente (idconfidencequality) se presente, altrimenti None.]] - rationale - harvester\src\injector\deduplicator.py
- [[True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato).]] - rationale - harvester\src\injector\deduplicator.py
- [[deduplicator.py]] - code - harvester\src\injector\deduplicator.py
- [[deduplicator.py_1]] - code - il-platinatore-ai\harvester\src\injector\deduplicator.py
- [[should_upsert()]] - code - harvester\src\injector\deduplicator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Community_45
SORT file.name ASC
```
