---
type: community
cohesion: 0.18
members: 12
---

# Guide Synthesizer

**Cohesion:** 0.18 - loosely connected
**Members:** 12 nodes

## Members
- [[._check_daily_limit()_1]] - code - harvester\src\transformer\synthesizer.py
- [[.extract_facts()]] - code - harvester\src\transformer\synthesizer.py
- [[.synthesize_guide()]] - code - harvester\src\transformer\synthesizer.py
- [[.transform()]] - code - harvester\src\transformer\synthesizer.py
- [[Estrae fatti atomici dai testi grezzi via Gemini.  None se quota o parsing KO.]] - rationale - harvester\src\transformer\synthesizer.py
- [[GuideSynthesizer — pipeline Gemini 2.5 Flash extract_facts → synthesize_guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Pipeline completa extract_facts → synthesize_guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Reset del contatore se cambia giorno; False se limite superato.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Rimuove eventuali ```json ... ``` fences che Gemini potrebbe aggiungere.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Sintetizza una guida markdown dai fatti.  None se quota o formato KO.]] - rationale - harvester\src\transformer\synthesizer.py
- [[_strip_json_fences()]] - code - harvester\src\transformer\synthesizer.py
- [[synthesizer.py]] - code - harvester\src\transformer\synthesizer.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Guide_Synthesizer
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_Embedding Service]]

## Top bridge nodes
- [[.extract_facts()]] - degree 5, connects to 1 community
- [[._check_daily_limit()_1]] - degree 4, connects to 1 community
- [[.synthesize_guide()]] - degree 4, connects to 1 community
- [[.transform()]] - degree 4, connects to 1 community
- [[synthesizer.py]] - degree 3, connects to 1 community