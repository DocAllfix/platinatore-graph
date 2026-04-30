---
type: community
cohesion: 0.15
members: 21
---

# Injector Upserter

**Cohesion:** 0.15 - loosely connected
**Members:** 21 nodes

## Members
- [[.__init__()_11]] - code - harvester\src\injector\upserter.py
- [[._find_or_create_game_tx()]] - code - harvester\src\injector\upserter.py
- [[._find_or_create_trophy_tx()]] - code - harvester\src\injector\upserter.py
- [[.find_or_create_game()]] - code - harvester\src\injector\upserter.py
- [[.find_or_create_trophy()]] - code - harvester\src\injector\upserter.py
- [[.upsert_guide()]] - code - harvester\src\injector\upserter.py
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - rationale - harvester\src\injector\upserter.py
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - rationale - harvester\src\injector\upserter.py
- [[Peak hour CET 1800-2359.]] - rationale - harvester\src\injector\upserter.py
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - rationale - harvester\src\injector\upserter.py
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - rationale - harvester\src\injector\upserter.py
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - rationale - harvester\src\injector\upserter.py
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - rationale - harvester\src\injector\upserter.py
- [[Upserter]] - code - harvester\src\injector\upserter.py
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - rationale - harvester\src\injector\upserter.py
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - rationale - harvester\src\injector\upserter.py
- [[_is_peak_hour()]] - code - harvester\src\injector\upserter.py
- [[_slugify()_2]] - code - harvester\src\injector\upserter.py
- [[generate_slug()]] - code - harvester\src\injector\upserter.py
- [[upserter.py]] - code - harvester\src\injector\upserter.py
- [[upserter.py_1]] - code - il-platinatore-ai\harvester\src\injector\upserter.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Injector_Upserter
SORT file.name ASC
```
