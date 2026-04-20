---
type: community
cohesion: 0.22
members: 14
---

# Pipeline Tests

**Cohesion:** 0.22 - loosely connected
**Members:** 14 nodes

## Members
- [[Crea una pipeline con tutti i componenti mockati.]] - rationale - harvester\tests\test_pipeline.py
- [[Test per HarvestPipeline — tutto mockato, zero connessioni reali.]] - rationale - harvester\tests\test_pipeline.py
- [[TestCleanup]] - code - harvester\tests\test_pipeline.py
- [[TestProcessSingleGuide]] - code - harvester\tests\test_pipeline.py
- [[TestRunSeedBatch]] - code - harvester\tests\test_pipeline.py
- [[_make_pipeline()]] - code - harvester\tests\test_pipeline.py
- [[test_calls_upsert_on_success()]] - code - harvester\tests\test_pipeline.py
- [[test_closes_collector()]] - code - harvester\tests\test_pipeline.py
- [[test_exits_gracefully_when_lock_busy()]] - code - harvester\tests\test_pipeline.py
- [[test_pipeline.py]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_all_collectors_return_none()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_already_processed()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_quality_below_threshold()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_stats_dict()]] - code - harvester\tests\test_pipeline.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Pipeline_Tests
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_Embedding Service]]

## Top bridge nodes
- [[Test per HarvestPipeline — tutto mockato, zero connessioni reali.]] - degree 2, connects to 1 community
- [[Crea una pipeline con tutti i componenti mockati.]] - degree 2, connects to 1 community
- [[TestCleanup]] - degree 2, connects to 1 community
- [[TestProcessSingleGuide]] - degree 2, connects to 1 community
- [[TestRunSeedBatch]] - degree 2, connects to 1 community