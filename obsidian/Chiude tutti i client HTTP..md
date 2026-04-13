---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L370"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Chiude tutti i client HTTP.

## Connections
- [[.cleanup()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service