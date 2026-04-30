---
type: community
cohesion: 0.17
members: 17
---

# Fandom Collector

**Cohesion:** 0.17 - loosely connected
**Members:** 17 nodes

## Members
- [[.collect()_1]] - code - harvester\src\collectors\fandom.py
- [[.extract()_1]] - code - harvester\src\collectors\fandom.py
- [[.fetch_page()]] - code - harvester\src\collectors\fandom.py
- [[.search_wiki()]] - code - harvester\src\collectors\fandom.py
- [[Cerca pagine nel wiki Fandom e ritorna lista di titoli.          Usa action=quer]] - rationale - harvester\src\collectors\fandom.py
- [[Collector per guide wiki da Fandom via MediaWiki API.]] - rationale - harvester\src\collectors\fandom.py
- [[FandomCollector]] - code - harvester\src\collectors\fandom.py
- [[FandomCollector — guide wiki via MediaWiki API (api.php).  Architettura --------]] - rationale - harvester\src\collectors\fandom.py
- [[Inferisce guide_type da categorie MediaWiki e titolo pagina.]] - rationale - harvester\src\collectors\fandom.py
- [[Parsa HTML MediaWiki e ritorna dict standard collector.          `categories` e]] - rationale - harvester\src\collectors\fandom.py
- [[Rimuove tag HTML e decodifica entità HTML. Normalizza whitespace.]] - rationale - harvester\src\collectors\fandom.py
- [[Ritorna {html_text, categories, page_url} per una pagina Fandom.          Usa ac]] - rationale - harvester\src\collectors\fandom.py
- [[Supporta dispatch da seed file con URL fandom.comwikiPAGE.]] - rationale - harvester\src\collectors\fandom.py
- [[_infer_guide_type()]] - code - harvester\src\collectors\fandom.py
- [[_strip_html()]] - code - harvester\src\collectors\fandom.py
- [[fandom.py]] - code - harvester\src\collectors\fandom.py
- [[fandom.py_1]] - code - il-platinatore-ai\harvester\src\collectors\fandom.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Fandom_Collector
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Fextralife Collector]]

## Top bridge nodes
- [[FandomCollector]] - degree 8, connects to 1 community