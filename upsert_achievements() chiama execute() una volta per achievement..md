---
source_file: "harvester\tests\test_steam_fetcher.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L178"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/PSN/Steam_Discovery_Scripts
---

# upsert_achievements() chiama execute() una volta per achievement.

## Connections
- [[.test_calls_execute_for_each()]] - `rationale_for` [EXTRACTED]
- [[SteamAchievementFetcher]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/PSN/Steam_Discovery_Scripts