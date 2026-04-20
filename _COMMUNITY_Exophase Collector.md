---
type: community
cohesion: 0.21
members: 12
---

# Exophase Collector

**Cohesion:** 0.21 - loosely connected
**Members:** 12 nodes

## Members
- [[.extract()]] - code - harvester\src\collectors\exophase.py
- [[.guide_url()]] - code - harvester\src\collectors\exophase.py
- [[Collector per trofeiachievement su exophase.com.]] - rationale - harvester\src\collectors\exophase.py
- [[Costruisce l'URL della pagina trofei per un gioco.]] - rationale - harvester\src\collectors\exophase.py
- [[Estrae trofei e descrizioni dall'HTML di Exophase.          Ritorna None se la p]] - rationale - harvester\src\collectors\exophase.py
- [[ExophaseCollector]] - code - harvester\src\collectors\exophase.py
- [[ExophaseCollector — collector per exophase.com.  Exophase è un aggregatore di ac]] - rationale - harvester\src\collectors\exophase.py
- [[Slug per Exophase lowercase + trattini, apostrofi rimossi.]] - rationale - harvester\src\collectors\exophase.py
- [[_extract_title()]] - code - harvester\src\collectors\exophase.py
- [[_normalize_whitespace()]] - code - harvester\src\collectors\exophase.py
- [[_slugify_exophase()]] - code - harvester\src\collectors\exophase.py
- [[exophase.py]] - code - harvester\src\collectors\exophase.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Exophase_Collector
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_BaseCollector Interface]]
- 1 edge to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[ExophaseCollector]] - degree 6, connects to 2 communities
- [[ExophaseCollector — collector per exophase.com.  Exophase è un aggregatore di ac]] - degree 2, connects to 1 community
- [[Slug per Exophase lowercase + trattini, apostrofi rimossi.]] - degree 2, connects to 1 community
- [[Collector per trofeiachievement su exophase.com.]] - degree 2, connects to 1 community
- [[Costruisce l'URL della pagina trofei per un gioco.]] - degree 2, connects to 1 community