---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "Collector Base Class"
location: "L91"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Collector_Base_Class
---

# La prima richiesta (last_request_time=0) non deve attendere.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Collector_Base_Class