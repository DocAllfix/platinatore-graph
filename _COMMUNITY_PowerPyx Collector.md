---
type: community
cohesion: 0.28
members: 9
---

# PowerPyx Collector

**Cohesion:** 0.28 - loosely connected
**Members:** 9 nodes

## Members
- [[.extract()]] - code - harvester\src\collectors\powerpyx.py
- [[Collassa spazi multipli e normalizza newline.]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor]] - rationale - harvester\src\collectors\powerpyx.py
- [[PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di]] - rationale - harvester\src\collectors\powerpyx.py
- [[_extract_title()]] - code - harvester\src\collectors\powerpyx.py
- [[_normalize_whitespace()]] - code - harvester\src\collectors\powerpyx.py
- [[_parse_url_slug()]] - code - harvester\src\collectors\powerpyx.py
- [[powerpyx.py]] - code - harvester\src\collectors\powerpyx.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PowerPyx_Collector
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_Collector Base Class]]
- 2 edges to [[_COMMUNITY_Embedding Service]]

## Top bridge nodes
- [[powerpyx.py]] - degree 5, connects to 1 community
- [[.extract()]] - degree 5, connects to 1 community
- [[PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di]] - degree 2, connects to 1 community
- [[Collassa spazi multipli e normalizza newline.]] - degree 2, connects to 1 community
- [[Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici]] - degree 2, connects to 1 community