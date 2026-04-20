---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "BaseCollector Interface"
location: "L201"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/BaseCollector_Interface
---

# La prima fetch() triggera _load_robots(); le successive no.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/BaseCollector_Interface