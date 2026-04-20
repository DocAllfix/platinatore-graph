---
source_file: "harvester\tests\test_psn_fetcher.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L166"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/PSN/Steam_Discovery_Scripts
---

# upsert_trophies() chiama execute() una volta per trofeo.

## Connections
- [[.test_calls_execute_for_each_trophy()]] - `rationale_for` [EXTRACTED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/PSN/Steam_Discovery_Scripts