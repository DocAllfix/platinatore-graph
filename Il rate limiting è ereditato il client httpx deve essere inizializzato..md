---
source_file: "harvester\tests\test_collectors.py"
type: "rationale"
community: "Injector Deduplication"
location: "L229"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Il rate limiting è ereditato: il client httpx deve essere inizializzato.

## Connections
- [[.test_has_http_client()]] - `rationale_for` [EXTRACTED]
- [[BaseCollector]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication