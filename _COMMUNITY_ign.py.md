---
type: community
cohesion: 0.38
members: 7
---

# ign.py

**Cohesion:** 0.38 - loosely connected
**Members:** 7 nodes

## Members
- [[.extract()_4]] - code - harvester\src\collectors\ign.py
- [[Estrae game_name e topic da URL ign.comwikis{game}{topic}.]] - rationale - harvester\src\collectors\ign.py
- [[IGNCollector — guide wiki professionali su ign.com.  Pattern URL ign.comwikis]] - rationale - harvester\src\collectors\ign.py
- [[_extract_title()_2]] - code - harvester\src\collectors\ign.py
- [[_normalize_whitespace()_2]] - code - harvester\src\collectors\ign.py
- [[_parse_url_slug()_1]] - code - harvester\src\collectors\ign.py
- [[ign.py]] - code - harvester\src\collectors\ign.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/ign.py
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_BaseCollector Interface]]
- 2 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[ign.py]] - degree 5, connects to 1 community
- [[.extract()_4]] - degree 4, connects to 1 community
- [[IGNCollector — guide wiki professionali su ign.com.  Pattern URL ign.comwikis]] - degree 2, connects to 1 community
- [[Estrae game_name e topic da URL ign.comwikis{game}{topic}.]] - degree 2, connects to 1 community