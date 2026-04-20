---
type: community
cohesion: 0.07
members: 48
---

# Embedding Service

**Cohesion:** 0.07 - loosely connected
**Members:** 48 nodes

## Members
- [[.__init__()_4]] - code - harvester\src\injector\embedder.py
- [[.__init__()_6]] - code - harvester\src\orchestrator\pipeline.py
- [[.__init__()_7]] - code - harvester\src\transformer\synthesizer.py
- [[._call_gemini()]] - code - harvester\src\transformer\synthesizer.py
- [[._check_daily_limit()]] - code - harvester\src\injector\embedder.py
- [[._embed_sync()]] - code - harvester\src\injector\embedder.py
- [[._get_last_processed_slug()]] - code - harvester\src\orchestrator\pipeline.py
- [[._reset_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[._save_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[.cleanup()]] - code - harvester\src\orchestrator\pipeline.py
- [[.embed_batch()]] - code - harvester\src\injector\embedder.py
- [[.process_single_guide()]] - code - harvester\src\orchestrator\pipeline.py
- [[.run_seed_batch()]] - code - harvester\src\orchestrator\pipeline.py
- [[Chiamata Gemini sincrona (SDK è sync).  Ritorna response.text.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Chiude tutti i client HTTP.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Collector per guide trofei su powerpyx.com.]] - rationale - harvester\src\collectors\powerpyx.py
- [[Embedder]] - code - harvester\src\injector\embedder.py
- [[Embedder — wrapper Gemini text-embedding-004 con batching e quota giornaliera.]] - rationale - harvester\src\injector\embedder.py
- [[Embedding in batch (max 100call).  Splitta in sotto-batch se necessario.]] - rationale - harvester\src\injector\embedder.py
- [[GuideSynthesizer]] - code - harvester\src\transformer\synthesizer.py
- [[HTML con contenuto  200 char → None.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[HTML valido → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[HarvestPipeline]] - code - harvester\src\orchestrator\pipeline.py
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[I tag script, style, nav non devono comparire nel raw_content.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[Legge l'ultimo slug processato dal DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Orchestra la pipeline completa collect → transform → inject.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Pipeline completa collect → transform → quality OK → upsert.]] - rationale - harvester\tests\test_pipeline.py
- [[PowerPyxCollector]] - code - harvester\src\collectors\powerpyx.py
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Resetta il progresso dopo un batch completato con successo.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Salva il progresso corrente nel DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Se _gemini_calls_today = settings.daily_gemini_limit → False.]] - rationale - harvester\tests\test_transformer.py
- [[Se advisory lock non acquisito → ritorna subito con skipped_reason.]] - rationale - harvester\tests\test_pipeline.py
- [[Se quality_score  0.4 → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutte le sorgenti sono già processate → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutti i collect ritornano None → False.]] - rationale - harvester\tests\test_pipeline.py
- [[Stesso input HTML+URL → stesso content_hash.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[Wrapper Gemini embedding con quota e batching automatico.]] - rationale - harvester\src\injector\embedder.py
- [[Wrapper Gemini per estrazione fatti + sintesi guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[_touch_heartbeat()]] - code - harvester\src\orchestrator\pipeline.py
- [[cleanup() chiama collector.close().]] - rationale - harvester\tests\test_pipeline.py
- [[embedder.py]] - code - harvester\src\injector\embedder.py
- [[game_name estratto correttamente dallo slug URL.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[pipeline.py]] - code - harvester\src\orchestrator\pipeline.py
- [[run_seed_batch ritorna dizionario con tutte le statistiche.]] - rationale - harvester\tests\test_pipeline.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Embedding_Service
SORT file.name ASC
```

## Connections to other communities
- 20 edges to [[_COMMUNITY_IGDB Discovery & Seeds]]
- 10 edges to [[_COMMUNITY_Deduplicator]]
- 5 edges to [[_COMMUNITY_Pipeline Tests]]
- 5 edges to [[_COMMUNITY_Guide Synthesizer]]
- 4 edges to [[_COMMUNITY_Transformer Tests]]
- 3 edges to [[_COMMUNITY_Collector Base Class]]
- 2 edges to [[_COMMUNITY_PowerPyx Collector]]
- 2 edges to [[_COMMUNITY_PowerPyx Collector Tests]]
- 2 edges to [[_COMMUNITY_Harvester Entry Point]]

## Top bridge nodes
- [[HarvestPipeline]] - degree 29, connects to 4 communities
- [[PowerPyxCollector]] - degree 22, connects to 3 communities
- [[GuideSynthesizer]] - degree 23, connects to 2 communities
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - degree 7, connects to 2 communities
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - degree 7, connects to 2 communities