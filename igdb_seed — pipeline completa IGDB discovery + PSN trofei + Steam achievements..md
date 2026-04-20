---
source_file: "harvester\src\orchestrator\igdb_seed.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L1"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSN/Steam_Discovery_Scripts
---

# igdb_seed — pipeline completa: IGDB discovery + PSN trofei + Steam achievements.

## Connections
- [[IGDBDiscovery]] - `uses` [INFERRED]
- [[PsnGameFinder]] - `uses` [INFERRED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]
- [[SteamAchievementFetcher]] - `uses` [INFERRED]
- [[igdb_seed.py]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/PSN/Steam_Discovery_Scripts