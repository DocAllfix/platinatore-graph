---
source_file: "harvester\tests\test_collectors.py"
type: "rationale"
community: "Collectors · per collector"
location: "L229"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Collectors_·_per_collector
---

# Il rate limiting è ereditato: il client httpx deve essere inizializzato.

## Connections
- [[.test_has_http_client()]] - `rationale_for` [EXTRACTED]
- [[BaseCollector]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Collectors_·_per_collector