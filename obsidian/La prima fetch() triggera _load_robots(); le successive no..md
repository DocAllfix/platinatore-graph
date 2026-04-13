---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "Collector Base Class"
location: "L201"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Collector_Base_Class
---

# La prima fetch() triggera _load_robots(); le successive no.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Collector_Base_Class