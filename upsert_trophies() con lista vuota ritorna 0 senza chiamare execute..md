---
source_file: "harvester\tests\test_psn_fetcher.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L197"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/PSN/Steam_Discovery_Scripts
---

# upsert_trophies() con lista vuota ritorna 0 senza chiamare execute.

## Connections
- [[.test_empty_list_returns_zero()]] - `rationale_for` [EXTRACTED]
- [[PsnTrophyFetcher]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/PSN/Steam_Discovery_Scripts