---
type: community
cohesion: 0.16
members: 15
---

# Upserter Transaction Logic

**Cohesion:** 0.16 - loosely connected
**Members:** 15 nodes

## Members
- [[._find_or_create_game_tx()]] - code - harvester\src\injector\upserter.py
- [[._find_or_create_trophy_tx()]] - code - harvester\src\injector\upserter.py
- [[.find_or_create_game()]] - code - harvester\src\injector\upserter.py
- [[.upsert_guide()]] - code - harvester\src\injector\upserter.py
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - rationale - harvester\src\injector\upserter.py
- [[Peak hour CET 1800-2359.]] - rationale - harvester\src\injector\upserter.py
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - rationale - harvester\src\injector\upserter.py
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - rationale - harvester\src\injector\upserter.py
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - rationale - harvester\src\injector\upserter.py
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - rationale - harvester\src\injector\upserter.py
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - rationale - harvester\src\injector\upserter.py
- [[_is_peak_hour()]] - code - harvester\src\injector\upserter.py
- [[_slugify()_2]] - code - harvester\src\injector\upserter.py
- [[generate_slug()]] - code - harvester\src\injector\upserter.py
- [[upserter.py]] - code - harvester\src\injector\upserter.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Upserter_Transaction_Logic
SORT file.name ASC
```

## Connections to other communities
- 12 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[.upsert_guide()]] - degree 6, connects to 1 community
- [[upserter.py]] - degree 5, connects to 1 community
- [[._find_or_create_game_tx()]] - degree 4, connects to 1 community
- [[.find_or_create_game()]] - degree 3, connects to 1 community
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - degree 2, connects to 1 community