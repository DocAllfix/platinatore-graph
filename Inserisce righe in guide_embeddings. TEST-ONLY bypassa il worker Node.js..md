---
source_file: "harvester\scripts\test_single_game.py"
type: "rationale"
community: "Injector Deduplication"
location: "L58"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Inserisce righe in guide_embeddings. TEST-ONLY: bypassa il worker Node.js.

## Connections
- [[Embedder]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_insert_embeddings()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication