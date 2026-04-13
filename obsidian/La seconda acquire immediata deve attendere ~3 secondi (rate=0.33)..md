---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "Collector Base Class"
location: "L255"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Collector_Base_Class
---

# La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Collector_Base_Class