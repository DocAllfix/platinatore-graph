---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L378"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Heartbeat file per Docker healthcheck (W-ARCH-2).

## Connections
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_touch_heartbeat()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service