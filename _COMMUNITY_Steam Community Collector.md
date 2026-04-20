---
type: community
cohesion: 0.29
members: 8
---

# Steam Community Collector

**Cohesion:** 0.29 - loosely connected
**Members:** 8 nodes

## Members
- [[.extract()_9]] - code - harvester\src\collectors\steam_community.py
- [[Mappa tag Steam a guide_type DB. Default 'walkthrough' (sempre in CHECK).]] - rationale - harvester\src\collectors\steam_community.py
- [[Parsa una risposta GetDetails.  `html` qui è JSON text.          Ritorna dict st]] - rationale - harvester\src\collectors\steam_community.py
- [[Rimuove BBCode Steam preservando il testo leggibile.]] - rationale - harvester\src\collectors\steam_community.py
- [[SteamCommunityGuidesCollector — guide user-generated via API Steam ufficiale.  E]] - rationale - harvester\src\collectors\steam_community.py
- [[_guide_type_from_tags()]] - code - harvester\src\collectors\steam_community.py
- [[_strip_steam_bbcode()]] - code - harvester\src\collectors\steam_community.py
- [[steam_community.py]] - code - harvester\src\collectors\steam_community.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Steam_Community_Collector
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_BaseCollector Interface]]
- 2 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[steam_community.py]] - degree 4, connects to 1 community
- [[.extract()_9]] - degree 4, connects to 1 community
- [[SteamCommunityGuidesCollector — guide user-generated via API Steam ufficiale.  E]] - degree 2, connects to 1 community
- [[Parsa una risposta GetDetails.  `html` qui è JSON text.          Ritorna dict st]] - degree 2, connects to 1 community
- [[Rimuove BBCode Steam preservando il testo leggibile.]] - degree 2, connects to 1 community