---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L56"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Processa una singola guida end-to-end. Ritorna True se iniettata.

## Connections
- [[.process_single_guide()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service