---
type: community
cohesion: 0.10
members: 30
---

# Test: Base Collector

**Cohesion:** 0.10 - loosely connected
**Members:** 30 nodes

## Members
- [[.__init__()_9]] - code - harvester\src\injector\deduplicator.py
- [[.__init__()_11]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[._find_or_create_game_tx()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[._find_or_create_trophy_tx()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[.find_or_create_game()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[.find_or_create_trophy()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[.guide_exists()]] - code - harvester\src\injector\deduplicator.py
- [[.source_already_processed()]] - code - harvester\src\injector\deduplicator.py
- [[.upsert_guide()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Deduplicator]] - code - harvester\src\injector\deduplicator.py
- [[Deduplicator — evita upsert inutili e protegge guide verificate.]] - rationale - harvester\src\injector\deduplicator.py
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Logica di deduplicazione basata su DB lookup.]] - rationale - harvester\src\injector\deduplicator.py
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Peak hour CET 1800-2359.]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Ritorna la guida esistente (idconfidencequality) se presente, altrimenti None.]] - rationale - harvester\src\injector\deduplicator.py
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato).]] - rationale - harvester\src\injector\deduplicator.py
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Upserter]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - rationale - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[_is_peak_hour()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[_slugify()_2]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[deduplicator.py]] - code - harvester\src\injector\deduplicator.py
- [[generate_slug()]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py
- [[should_upsert()]] - code - harvester\src\injector\deduplicator.py
- [[upserter.py]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\injector\upserter.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Test:_Base_Collector
SORT file.name ASC
```
