---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "BaseCollector Interface"
location: "L255"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/BaseCollector_Interface
---

# La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/BaseCollector_Interface