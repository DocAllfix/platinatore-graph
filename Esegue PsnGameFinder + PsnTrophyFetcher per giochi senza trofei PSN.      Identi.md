---
source_file: "harvester\src\orchestrator\igdb_seed.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L112"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSN/Steam_Discovery_Scripts
---

# Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi

## Connections
- [[IGDBDiscovery]] - `uses` [INFERRED]
- [[PsnGameFinder]] - `uses` [INFERRED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]
- [[SteamAchievementFetcher]] - `uses` [INFERRED]
- [[_run_psn_trophies()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/PSN/Steam_Discovery_Scripts