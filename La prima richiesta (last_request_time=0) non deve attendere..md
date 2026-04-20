---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "BaseCollector Interface"
location: "L91"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/BaseCollector_Interface
---

# La prima richiesta (last_request_time=0) non deve attendere.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/BaseCollector_Interface