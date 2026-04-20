---
source_file: "harvester\src\orchestrator\psn_seed.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L35"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSN/Steam_Discovery_Scripts
---

# Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale.

## Connections
- [[PsnGameFinder]] - `uses` [INFERRED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]
- [[_run()_4]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/PSN/Steam_Discovery_Scripts