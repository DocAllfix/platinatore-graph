---
type: community
cohesion: 0.16
members: 14
---

# Transformer · extract synthesize

**Cohesion:** 0.16 - loosely connected
**Members:** 14 nodes

## Members
- [[._check_daily_limit()_1]] - code - harvester\src\transformer\synthesizer.py
- [[.extract_facts()]] - code - harvester\src\transformer\synthesizer.py
- [[.synthesize_guide()]] - code - harvester\src\transformer\synthesizer.py
- [[.transform()]] - code - harvester\src\transformer\synthesizer.py
- [[Estrae fatti atomici dai testi grezzi. None se quota o parsing KO.]] - rationale - harvester\src\transformer\synthesizer.py
- [[GuideSynthesizer — pipeline multi-provider extract_facts → synthesize_guide.  P]] - rationale - harvester\src\transformer\synthesizer.py
- [[Pipeline completa extract_facts → synthesize_guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Reset del contatore se cambia giorno; False se limite superato.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Rimuove eventuali ```json ... ``` fences.      Usa search() invece di match() pe]] - rationale - harvester\src\transformer\synthesizer.py
- [[Rimuove eventuali ```markdown ... ``` fences dal testo sintetizzato.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Sintetizza una guida markdown dai fatti. None se quota o formato KO.]] - rationale - harvester\src\transformer\synthesizer.py
- [[_strip_json_fences()]] - code - harvester\src\transformer\synthesizer.py
- [[_strip_markdown_fences()]] - code - harvester\src\transformer\synthesizer.py
- [[synthesizer.py]] - code - harvester\src\transformer\synthesizer.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Transformer_·_extract_synthesize
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_Orchestrator · per guide]]

## Top bridge nodes
- [[.extract_facts()]] - degree 5, connects to 1 community
- [[.synthesize_guide()]] - degree 5, connects to 1 community
- [[synthesizer.py]] - degree 4, connects to 1 community
- [[._check_daily_limit()_1]] - degree 4, connects to 1 community
- [[.transform()]] - degree 4, connects to 1 community