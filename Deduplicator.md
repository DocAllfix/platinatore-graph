---
source_file: "harvester\src\injector\deduplicator.py"
type: "code"
community: "Test: Base Collector"
location: "L9"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Test:_Base_Collector
---

# Deduplicator

## Connections
- [[.__init__()_9]] - `method` [EXTRACTED]
- [[.guide_exists()]] - `method` [EXTRACTED]
- [[.source_already_processed()]] - `method` [EXTRACTED]
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - `uses` [INFERRED]
- [[Logica di deduplicazione basata su DB lookup.]] - `rationale_for` [EXTRACTED]
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - `uses` [INFERRED]
- [[Peak hour CET 1800-2359.]] - `uses` [INFERRED]
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - `uses` [INFERRED]
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - `uses` [INFERRED]
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - `uses` [INFERRED]
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - `uses` [INFERRED]
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - `uses` [INFERRED]
- [[deduplicator.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/Test:_Base_Collector