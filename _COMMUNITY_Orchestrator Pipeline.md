---
type: community
cohesion: 0.07
members: 47
---

# Orchestrator Pipeline

**Cohesion:** 0.07 - loosely connected
**Members:** 47 nodes

## Members
- [[.__init__()_12]] - code - harvester\src\orchestrator\pipeline.py
- [[._get_collector_for_url()]] - code - harvester\src\orchestrator\pipeline.py
- [[._get_last_processed_slug()]] - code - harvester\src\orchestrator\pipeline.py
- [[._inject_synthetic()]] - code - harvester\src\orchestrator\pipeline.py
- [[._reset_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[._save_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[.cleanup()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_boss_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_fandom_content()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_single_guide()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_steam_community_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_with_reddit()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_youtube_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.run_seed_batch()]] - code - harvester\src\orchestrator\pipeline.py
- [[Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.]] - rationale - harvester\src\orchestrator\main.py
- [[Crea una pipeline con tutti i componenti mockati.]] - rationale - harvester\tests\test_pipeline.py
- [[Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è]] - rationale - harvester\src\orchestrator\main.py
- [[HarvestPipeline]] - code - harvester\src\orchestrator\pipeline.py
- [[Pipeline completa collect → transform → quality OK → upsert.]] - rationale - harvester\tests\test_pipeline.py
- [[Se advisory lock non acquisito → ritorna subito con skipped_reason.]] - rationale - harvester\tests\test_pipeline.py
- [[Se quality_score  0.4 → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutte le sorgenti sono già processate → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutti i collect ritornano None → False.]] - rationale - harvester\tests\test_pipeline.py
- [[Test per HarvestPipeline — tutto mockato, zero connessioni reali.]] - rationale - harvester\tests\test_pipeline.py
- [[TestCleanup]] - code - harvester\tests\test_pipeline.py
- [[TestProcessSingleGuide]] - code - harvester\tests\test_pipeline.py
- [[TestRunSeedBatch]] - code - harvester\tests\test_pipeline.py
- [[_make_pipeline()]] - code - harvester\tests\test_pipeline.py
- [[_parse_args()_1]] - code - harvester\src\orchestrator\main.py
- [[_slugify()_3]] - code - harvester\src\orchestrator\pipeline.py
- [[_touch_heartbeat()]] - code - harvester\src\orchestrator\pipeline.py
- [[cleanup() chiama close() su tutti i collector.]] - rationale - harvester\tests\test_pipeline.py
- [[guide_type_override deve sovrascrivere quello del synthesizer.]] - rationale - harvester\tests\test_pipeline.py
- [[main()_8]] - code - harvester\src\orchestrator\main.py
- [[main.py]] - code - harvester\src\orchestrator\main.py
- [[pipeline.py]] - code - harvester\src\orchestrator\pipeline.py
- [[run_seed_batch ritorna dizionario con tutte le statistiche.]] - rationale - harvester\tests\test_pipeline.py
- [[test_calls_upsert_on_success()]] - code - harvester\tests\test_pipeline.py
- [[test_closes_collector()]] - code - harvester\tests\test_pipeline.py
- [[test_exits_gracefully_when_lock_busy()]] - code - harvester\tests\test_pipeline.py
- [[test_guide_type_override_applies()]] - code - harvester\tests\test_pipeline.py
- [[test_pipeline.py]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_all_collectors_return_none()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_already_processed()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_false_when_quality_below_threshold()]] - code - harvester\tests\test_pipeline.py
- [[test_returns_stats_dict()]] - code - harvester\tests\test_pipeline.py
- [[touch_heartbeat()]] - code - harvester\src\orchestrator\main.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Orchestrator_Pipeline
SORT file.name ASC
```

## Connections to other communities
- 30 edges to [[_COMMUNITY_Injector Deduplication]]
- 1 edge to [[_COMMUNITY_BaseCollector Interface]]

## Top bridge nodes
- [[HarvestPipeline]] - degree 45, connects to 2 communities
- [[.run_seed_batch()]] - degree 7, connects to 1 community
- [[._inject_synthetic()]] - degree 6, connects to 1 community
- [[.process_single_guide()]] - degree 5, connects to 1 community
- [[pipeline.py]] - degree 4, connects to 1 community