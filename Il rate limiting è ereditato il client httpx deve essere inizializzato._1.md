---
source_file: "harvester\tests\test_collectors.py"
type: "rationale"
community: "PSNProfiles/TrueAchievements Tests"
location: "L337"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/PSNProfiles/TrueAchievements_Tests
---

# Il rate limiting è ereditato: il client httpx deve essere inizializzato.

## Connections
- [[.test_has_http_client()_1]] - `rationale_for` [EXTRACTED]
- [[BaseCollector]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/PSNProfiles/TrueAchievements_Tests