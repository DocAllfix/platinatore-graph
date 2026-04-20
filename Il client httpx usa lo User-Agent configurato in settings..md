---
source_file: "harvester\tests\test_base_collector.py"
type: "rationale"
community: "BaseCollector Interface"
location: "L236"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/BaseCollector_Interface
---

# Il client httpx usa lo User-Agent configurato in settings.

## Connections
- [[.test_user_agent_from_settings()]] - `rationale_for` [EXTRACTED]
- [[BaseCollector]] - `uses` [INFERRED]
- [[PerHostTokenBucket]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/BaseCollector_Interface