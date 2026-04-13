---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L231"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Processa tutti i giochi del seed file con advisory lock singleton.          Rito

## Connections
- [[.run_seed_batch()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service