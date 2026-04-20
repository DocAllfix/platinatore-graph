---
source_file: "harvester\src\injector\upserter.py"
type: "rationale"
community: "Deduplicator"
location: "L62"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Deduplicator
---

# Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.

## Connections
- [[.find_or_create_game()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/Deduplicator