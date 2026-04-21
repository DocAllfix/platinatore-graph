---
type: community
cohesion: 0.18
members: 12
---

# Collectors · guide mediawiki

**Cohesion:** 0.18 - loosely connected
**Members:** 12 nodes

## Members
- [[.collect()_1]] - code - harvester\src\collectors\fandom.py
- [[.extract()_1]] - code - harvester\src\collectors\fandom.py
- [[.fetch_page()]] - code - harvester\src\collectors\fandom.py
- [[FandomCollector — guide wiki via MediaWiki API (api.php).  Architettura --------]] - rationale - harvester\src\collectors\fandom.py
- [[Inferisce guide_type da categorie MediaWiki e titolo pagina.]] - rationale - harvester\src\collectors\fandom.py
- [[Parsa HTML MediaWiki e ritorna dict standard collector.          `categories` e]] - rationale - harvester\src\collectors\fandom.py
- [[Rimuove tag HTML e decodifica entità HTML. Normalizza whitespace.]] - rationale - harvester\src\collectors\fandom.py
- [[Ritorna {html_text, categories, page_url} per una pagina Fandom.          Usa ac]] - rationale - harvester\src\collectors\fandom.py
- [[Supporta dispatch da seed file con URL fandom.comwikiPAGE.]] - rationale - harvester\src\collectors\fandom.py
- [[_infer_guide_type()]] - code - harvester\src\collectors\fandom.py
- [[_strip_html()]] - code - harvester\src\collectors\fandom.py
- [[fandom.py]] - code - harvester\src\collectors\fandom.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Collectors_·_guide_mediawiki
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_Collectors · per collector]]
- 4 edges to [[_COMMUNITY_Orchestrator · per guide]]

## Top bridge nodes
- [[.extract()_1]] - degree 5, connects to 1 community
- [[.collect()_1]] - degree 4, connects to 1 community
- [[fandom.py]] - degree 4, connects to 1 community
- [[.fetch_page()]] - degree 3, connects to 1 community
- [[FandomCollector — guide wiki via MediaWiki API (api.php).  Architettura --------]] - degree 2, connects to 1 community