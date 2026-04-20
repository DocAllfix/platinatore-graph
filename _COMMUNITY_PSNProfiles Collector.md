---
type: community
cohesion: 0.24
members: 11
---

# PSNProfiles Collector

**Cohesion:** 0.24 - loosely connected
**Members:** 11 nodes

## Members
- [[.extract()_6]] - code - harvester\src\collectors\psnprofiles.py
- [[Collassa spazi multipli e normalizza newline._1]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Converte tabelle table class=zebra in testo strutturato pipe-delimited.]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Estrae game_name dall'URL PSNProfiles.      Formati tipici       - guide12345]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Estrae titolo, tabelle trofei e testo dalla guida PSNProfiles.          Ritorna]] - rationale - harvester\src\collectors\psnprofiles.py
- [[PSNProfilesCollector — collector per psnprofiles.com.  Guide trophy nella sezion]] - rationale - harvester\src\collectors\psnprofiles.py
- [[_convert_tables_to_text()]] - code - harvester\src\collectors\psnprofiles.py
- [[_extract_title()_4]] - code - harvester\src\collectors\psnprofiles.py
- [[_normalize_whitespace()_4]] - code - harvester\src\collectors\psnprofiles.py
- [[_parse_url_slug()_3]] - code - harvester\src\collectors\psnprofiles.py
- [[psnprofiles.py]] - code - harvester\src\collectors\psnprofiles.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PSNProfiles_Collector
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_BaseCollector Interface]]
- 2 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[psnprofiles.py]] - degree 6, connects to 1 community
- [[.extract()_6]] - degree 6, connects to 1 community
- [[PSNProfilesCollector — collector per psnprofiles.com.  Guide trophy nella sezion]] - degree 2, connects to 1 community
- [[Converte tabelle table class=zebra in testo strutturato pipe-delimited.]] - degree 2, connects to 1 community
- [[Collassa spazi multipli e normalizza newline._1]] - degree 2, connects to 1 community