---
source_file: "harvester\src\injector\upserter.py"
type: "rationale"
community: "Injector Deduplication"
location: "L138"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Injector_Deduplication
---

# Trova il trofeo per game_id + nome; None se trophy_name non è dato.

## Connections
- [[.find_or_create_trophy()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/Injector_Deduplication