---
type: community
cohesion: 0.13
members: 18
---

# Collectors · ddg guide

**Cohesion:** 0.13 - loosely connected
**Members:** 18 nodes

## Members
- [[._ddg_fetch()]] - code - harvester\src\collectors\guide_search.py
- [[.search_guide_urls()]] - code - harvester\src\collectors\guide_search.py
- [[.search_guide_urls_multi()]] - code - harvester\src\collectors\guide_search.py
- [[Cerca guide per una singola query e ritorna URL filtrati.          Args]] - rationale - harvester\src\collectors\guide_search.py
- [[Costruisce URL deterministici per i siti più affidabili.      Usato quando DDG è]] - rationale - harvester\src\collectors\guide_search.py
- [[Estrae gli URL dai risultati HTML di DuckDuckGo.      DuckDuckGo HTML (html.duck]] - rationale - harvester\src\collectors\guide_search.py
- [[Estrae il dominio di un URL.]] - rationale - harvester\src\collectors\guide_search.py
- [[Fetch diretto a DDG accettando sia 200 che 202.          DDG restituisce 202 com]] - rationale - harvester\src\collectors\guide_search.py
- [[GuideSearchCollector — scoperta fonti guide via DuckDuckGo HTML.  Invece di cost]] - rationale - harvester\src\collectors\guide_search.py
- [[Lancia _QUERY_TEMPLATES sequenzialmente e aggrega i risultati.          Le query]] - rationale - harvester\src\collectors\guide_search.py
- [[Slug URL-safe per costruzione URL fallback.]] - rationale - harvester\src\collectors\guide_search.py
- [[True se l'URL appartiene a un dominio di fiducia.]] - rationale - harvester\src\collectors\guide_search.py
- [[_domain_of()]] - code - harvester\src\collectors\guide_search.py
- [[_is_trusted()]] - code - harvester\src\collectors\guide_search.py
- [[_parse_ddg_results()]] - code - harvester\src\collectors\guide_search.py
- [[_slugify()_1]] - code - harvester\src\collectors\guide_search.py
- [[build_fallback_urls()]] - code - harvester\src\collectors\guide_search.py
- [[guide_search.py]] - code - harvester\src\collectors\guide_search.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Collectors_·_ddg_guide
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_Collectors · per collector]]
- 4 edges to [[_COMMUNITY_Orchestrator · per guide]]

## Top bridge nodes
- [[guide_search.py]] - degree 7, connects to 1 community
- [[.search_guide_urls()]] - degree 6, connects to 1 community
- [[._ddg_fetch()]] - degree 3, connects to 1 community
- [[.search_guide_urls_multi()]] - degree 3, connects to 1 community
- [[GuideSearchCollector — scoperta fonti guide via DuckDuckGo HTML.  Invece di cost]] - degree 2, connects to 1 community