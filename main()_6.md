---
source_file: "harvester\scripts\test_single_game.py"
type: "code"
community: "Single-Game Test Pipeline"
location: "L255"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Single-Game_Test_Pipeline
---

# main()

## Connections
- [[step1_init()]] - `calls` [EXTRACTED]
- [[step2_collect()]] - `calls` [EXTRACTED]
- [[step3_transform()]] - `calls` [EXTRACTED]
- [[step4_quality_and_chunk()]] - `calls` [EXTRACTED]
- [[step5_embed()]] - `calls` [EXTRACTED]
- [[step6_upsert()]] - `calls` [EXTRACTED]
- [[step7_insert_embeddings()]] - `calls` [EXTRACTED]
- [[step8_pgvector_search()]] - `calls` [EXTRACTED]
- [[test_single_game.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Single-Game_Test_Pipeline