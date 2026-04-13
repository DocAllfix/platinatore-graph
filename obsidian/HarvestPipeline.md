---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "code"
community: "Embedding Service"
location: "L30"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Embedding_Service
---

# HarvestPipeline

## Connections
- [[.__init__()_6]] - `method` [EXTRACTED]
- [[._get_last_processed_slug()]] - `method` [EXTRACTED]
- [[._reset_progress()]] - `method` [EXTRACTED]
- [[._save_progress()]] - `method` [EXTRACTED]
- [[.cleanup()]] - `method` [EXTRACTED]
- [[.process_single_guide()]] - `method` [EXTRACTED]
- [[.run_seed_batch()]] - `method` [EXTRACTED]
- [[Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.]] - `uses` [INFERRED]
- [[Crea una pipeline con tutti i componenti mockati.]] - `uses` [INFERRED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Embedder]] - `uses` [INFERRED]
- [[Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `rationale_for` [EXTRACTED]
- [[Pipeline completa collect → transform → quality OK → upsert.]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[Se advisory lock non acquisito → ritorna subito con skipped_reason.]] - `uses` [INFERRED]
- [[Se quality_score  0.4 → skip.]] - `uses` [INFERRED]
- [[Se tutte le sorgenti sono già processate → skip.]] - `uses` [INFERRED]
- [[Se tutti i collect ritornano None → False.]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[Test per HarvestPipeline — tutto mockato, zero connessioni reali.]] - `uses` [INFERRED]
- [[TestCleanup]] - `uses` [INFERRED]
- [[TestProcessSingleGuide]] - `uses` [INFERRED]
- [[TestRunSeedBatch]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[cleanup() chiama collector.close().]] - `uses` [INFERRED]
- [[pipeline.py]] - `contains` [EXTRACTED]
- [[run_seed_batch ritorna dizionario con tutte le statistiche.]] - `uses` [INFERRED]

#graphify/code #graphify/INFERRED #community/Embedding_Service