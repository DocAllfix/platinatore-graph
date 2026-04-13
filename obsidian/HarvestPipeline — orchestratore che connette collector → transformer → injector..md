---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L1"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# HarvestPipeline — orchestratore che connette collector → transformer → injector.

## Connections
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[pipeline.py]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service