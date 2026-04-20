---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "BaseCollector Interface"
location: "L195"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/BaseCollector_Interface
---

# _is_allowed ritorna True se robots.txt non è stato caricato (fail-open).

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/BaseCollector_Interface