---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Embedding Service"
location: "L340"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Embedding_Service
---

# Salva il progresso corrente nel DB.

## Connections
- [[._save_progress()]] - `rationale_for` [EXTRACTED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Embedding_Service