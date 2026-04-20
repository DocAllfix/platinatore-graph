---
source_file: "harvester\scripts\run_psn_trophies_all.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L67"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSN/Steam_Discovery_Scripts
---

# Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale.

## Connections
- [[PsnGameFinder]] - `uses` [INFERRED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]
- [[_run()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/PSN/Steam_Discovery_Scripts