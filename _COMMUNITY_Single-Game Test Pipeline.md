---
type: community
cohesion: 0.31
members: 13
---

# Single-Game Test Pipeline

**Cohesion:** 0.31 - loosely connected
**Members:** 13 nodes

## Members
- [[_insert_embeddings()]] - code - harvester\scripts\test_single_game.py
- [[_pgvector_search()]] - code - harvester\scripts\test_single_game.py
- [[_vec_to_pg()]] - code - harvester\scripts\test_single_game.py
- [[main()_6]] - code - harvester\scripts\test_single_game.py
- [[step1_init()]] - code - harvester\scripts\test_single_game.py
- [[step2_collect()]] - code - harvester\scripts\test_single_game.py
- [[step3_transform()]] - code - harvester\scripts\test_single_game.py
- [[step4_quality_and_chunk()]] - code - harvester\scripts\test_single_game.py
- [[step5_embed()]] - code - harvester\scripts\test_single_game.py
- [[step6_upsert()]] - code - harvester\scripts\test_single_game.py
- [[step7_insert_embeddings()]] - code - harvester\scripts\test_single_game.py
- [[step8_pgvector_search()]] - code - harvester\scripts\test_single_game.py
- [[test_single_game.py]] - code - harvester\scripts\test_single_game.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Single-Game_Test_Pipeline
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[test_single_game.py]] - degree 13, connects to 1 community
- [[_insert_embeddings()]] - degree 4, connects to 1 community
- [[_pgvector_search()]] - degree 4, connects to 1 community
- [[_vec_to_pg()]] - degree 4, connects to 1 community