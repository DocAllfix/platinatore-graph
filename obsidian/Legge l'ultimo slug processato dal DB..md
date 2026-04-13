---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L326"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Legge l'ultimo slug processato dal DB.

## Connections
- [[._get_last_processed_slug()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service