---
source_file: "harvester\src\orchestrator\igdb_seed.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L39"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSN/Steam_Discovery_Scripts
---

# Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale.

## Connections
- [[IGDBDiscovery]] - `uses` [INFERRED]
- [[PsnGameFinder]] - `uses` [INFERRED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]
- [[SteamAchievementFetcher]] - `uses` [INFERRED]
- [[_run()_3]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/PSN/Steam_Discovery_Scripts