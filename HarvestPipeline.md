---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "code"
community: "Orchestrator Pipeline"
location: "L39"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Orchestrator_Pipeline
---

# HarvestPipeline

## Connections
- [[.__init__()_12]] - `method` [EXTRACTED]
- [[._get_collector_for_url()]] - `method` [EXTRACTED]
- [[._get_last_processed_slug()]] - `method` [EXTRACTED]
- [[._inject_synthetic()]] - `method` [EXTRACTED]
- [[._reset_progress()]] - `method` [EXTRACTED]
- [[._save_progress()]] - `method` [EXTRACTED]
- [[.cleanup()]] - `method` [EXTRACTED]
- [[.process_boss_guides()]] - `method` [EXTRACTED]
- [[.process_fandom_content()]] - `method` [EXTRACTED]
- [[.process_single_guide()]] - `method` [EXTRACTED]
- [[.process_steam_community_guides()]] - `method` [EXTRACTED]
- [[.process_with_reddit()]] - `method` [EXTRACTED]
- [[.process_youtube_guides()]] - `method` [EXTRACTED]
- [[.run_seed_batch()]] - `method` [EXTRACTED]
- [[Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.]] - `uses` [INFERRED]
- [[BaseCollector]] - `uses` [INFERRED]
- [[Crea una pipeline con tutti i componenti mockati.]] - `uses` [INFERRED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è]] - `uses` [INFERRED]
- [[FandomCollector]] - `uses` [INFERRED]
- [[FextralifeCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[IGNCollector]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `rationale_for` [EXTRACTED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[Pipeline completa collect → transform → quality OK → upsert.]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[Se advisory lock non acquisito → ritorna subito con skipped_reason.]] - `uses` [INFERRED]
- [[Se quality_score  0.4 → skip.]] - `uses` [INFERRED]
- [[Se tutte le sorgenti sono già processate → skip.]] - `uses` [INFERRED]
- [[Se tutti i collect ritornano None → False.]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[SteamCommunityGuidesCollector]] - `uses` [INFERRED]
- [[Test per HarvestPipeline — tutto mockato, zero connessioni reali.]] - `uses` [INFERRED]
- [[TestCleanup]] - `uses` [INFERRED]
- [[TestProcessSingleGuide]] - `uses` [INFERRED]
- [[TestRunSeedBatch]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[YouTubeCollector]] - `uses` [INFERRED]
- [[cleanup() chiama close() su tutti i collector.]] - `uses` [INFERRED]
- [[guide_type_override deve sovrascrivere quello del synthesizer.]] - `uses` [INFERRED]
- [[pipeline.py]] - `contains` [EXTRACTED]
- [[run_seed_batch ritorna dizionario con tutte le statistiche.]] - `uses` [INFERRED]

#graphify/code #graphify/INFERRED #community/Orchestrator_Pipeline