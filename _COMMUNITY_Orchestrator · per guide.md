---
type: community
cohesion: 0.05
members: 122
---

# Orchestrator · per guide

**Cohesion:** 0.05 - loosely connected
**Members:** 122 nodes

## Members
- [[.__init__()_9]] - code - harvester\src\injector\deduplicator.py
- [[.__init__()_2]] - code - harvester\src\collectors\guide_search.py
- [[.__init__()_12]] - code - harvester\src\orchestrator\pipeline.py
- [[.__init__()_3]] - code - harvester\src\collectors\reddit.py
- [[.__init__()_13]] - code - harvester\src\transformer\synthesizer.py
- [[.__init__()_11]] - code - harvester\src\injector\upserter.py
- [[.__init__()_4]] - code - harvester\src\collectors\youtube.py
- [[._call_deepseek()]] - code - harvester\src\transformer\synthesizer.py
- [[._call_gemini()]] - code - harvester\src\transformer\synthesizer.py
- [[._call_llm()]] - code - harvester\src\transformer\synthesizer.py
- [[._find_or_create_game_tx()]] - code - harvester\src\injector\upserter.py
- [[._find_or_create_trophy_tx()]] - code - harvester\src\injector\upserter.py
- [[._get_collector_for_url()]] - code - harvester\src\orchestrator\pipeline.py
- [[._get_last_processed_slug()]] - code - harvester\src\orchestrator\pipeline.py
- [[._inject_synthetic()]] - code - harvester\src\orchestrator\pipeline.py
- [[._reset_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[._save_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[.cleanup()]] - code - harvester\src\orchestrator\pipeline.py
- [[.find_or_create_game()]] - code - harvester\src\injector\upserter.py
- [[.find_or_create_trophy()]] - code - harvester\src\injector\upserter.py
- [[.guide_exists()]] - code - harvester\src\injector\deduplicator.py
- [[.load_seed_file()]] - code - harvester\src\discovery\seed_loader.py
- [[.process_boss_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_fandom_content()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_single_guide()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_steam_community_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_with_reddit()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_youtube_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.run_seed_batch()]] - code - harvester\src\orchestrator\pipeline.py
- [[.seed_database()]] - code - harvester\src\discovery\seed_loader.py
- [[.source_already_processed()]] - code - harvester\src\injector\deduplicator.py
- [[.upsert_guide()]] - code - harvester\src\injector\upserter.py
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - rationale - harvester\src\orchestrator\pipeline.py
- [[BaseCollector_1]] - code
- [[Cerca guide via DDG e fetcha tutti gli URL IN PARALLELO.      Ritorna {trophy_na]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Cerca tips per un trofeo specifico su rTrophies (async, no semaphore).]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Chiamata DeepSeek sincrona via OpenAI-compatible SDK.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Chiamata Gemini sincrona via google-genai SDK.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Chiude tutti i client HTTP.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Converte una lista float nel literal pgvector 'f1,f2,...'.      Usato per INSE]] - rationale - harvester\scripts\test_single_game.py
- [[Deduplicator]] - code - harvester\src\injector\deduplicator.py
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Dispatch al provider configurato.]] - rationale - harvester\src\transformer\synthesizer.py
- [[End-to-end pipeline test — UN singolo gioco reale.  Valida l'intera pipeline co]] - rationale - harvester\scripts\test_single_game.py
- [[FandomCollector]] - code - harvester\src\collectors\fandom.py
- [[Fetch generico con browser UA e semaphore globale.      Usato per URL di guida s]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Fetch un URL guida ed estrae le sezioni trophy matchate.      Ritorna (url, {tro]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[FextralifeCollector]] - code - harvester\src\collectors\fextralife.py
- [[Genera e salva la guida per un singolo trofeo. Ritorna status string.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Genera guide boss per un gioco usando Fextralife + IGN.          Se boss_names è]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Genera guide per i trofei platgold di un gioco.      Trofei processati in batch]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - rationale - harvester\src\injector\upserter.py
- [[GuideSearchCollector]] - code - harvester\src\collectors\guide_search.py
- [[GuideSynthesizer]] - code - harvester\src\transformer\synthesizer.py
- [[HTML con contenuto  200 char → None.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[HTML valido → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[HarvestPipeline]] - code - harvester\src\orchestrator\pipeline.py
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[I tag script, style, nav non devono comparire nel raw_content.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[IGNCollector]] - code - harvester\src\collectors\ign.py
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Inserisce righe in guide_embeddings. TEST-ONLY bypassa il worker Node.js.]] - rationale - harvester\scripts\test_single_game.py
- [[Legge e valida un file JSON seed. Ritorna la lista di giochi.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Legge file JSON seed e upserta giochi nel DB con alias.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Legge l'ultimo slug processato dal DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Logica di deduplicazione basata su DB lookup.]] - rationale - harvester\src\injector\deduplicator.py
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - rationale - harvester\src\injector\upserter.py
- [[Mappa gli ID piattaforma IGDB ai nomi leggibili.]] - rationale - harvester\src\discovery\igdb.py
- [[Orchestra la pipeline completa collect → transform → inject.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Peak hour CET 1800-2359.]] - rationale - harvester\src\injector\upserter.py
- [[Pipeline completa collect → transform → quality OK → upsert.]] - rationale - harvester\tests\test_pipeline.py
- [[PowerPyxCollector]] - code - harvester\src\collectors\powerpyx.py
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Raccoglie contenuti wiki da Fandom per un gioco.          Se `wiki_subdomain` è]] - rationale - harvester\src\orchestrator\pipeline.py
- [[RedditCollector]] - code - harvester\src\collectors\reddit.py
- [[Resetta il progresso dopo un batch completato con successo.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Ricerca coseno su guide_embeddings. Ritorna le righe più simili.]] - rationale - harvester\scripts\test_single_game.py
- [[Ritorna la guida esistente (idconfidencequality) se presente, altrimenti None.]] - rationale - harvester\src\injector\deduplicator.py
- [[SHA256 di url+extra, troncato a 64 char per content_hash NOT NULL.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Salva il progresso corrente nel DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Se _gemini_calls_today = settings.daily_gemini_limit → False.]] - rationale - harvester\tests\test_transformer.py
- [[Se advisory lock non acquisito → ritorna subito con skipped_reason.]] - rationale - harvester\tests\test_pipeline.py
- [[Se quality_score  0.4 → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutte le sorgenti sono già processate → skip.]] - rationale - harvester\tests\test_pipeline.py
- [[Se tutti i collect ritornano None → False.]] - rationale - harvester\tests\test_pipeline.py
- [[SeedLoader]] - code - harvester\src\discovery\seed_loader.py
- [[SeedLoader — carica un file JSON seed e popola il catalogo giochi nel DB.  Forma]] - rationale - harvester\src\discovery\seed_loader.py
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - rationale - harvester\src\injector\upserter.py
- [[Slug URL-safe NFKD + minuscolo + solo alfanum e trattini.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[SteamCommunityGuidesCollector]] - code - harvester\src\collectors\steam_community.py
- [[Stesso URL + stesso hash → True (già processato).]] - rationale - harvester\tests\test_injector.py
- [[Stesso input HTML+URL → stesso content_hash.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[Test per i nuovi collector Fextralife, IGN, Reddit.  HTMLJSON tutti inventati,]] - rationale - harvester\tests\test_new_collectors.py
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - rationale - harvester\src\injector\upserter.py
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - rationale - harvester\src\injector\upserter.py
- [[True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato).]] - rationale - harvester\src\injector\deduplicator.py
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - rationale - harvester\src\injector\upserter.py
- [[Upserta tutti i giochi del seed file nel DB.          Per ogni gioco         -]] - rationale - harvester\src\discovery\seed_loader.py
- [[Upserter]] - code - harvester\src\injector\upserter.py
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - rationale - harvester\src\injector\upserter.py
- [[Verdetto di ammissibilità per un gioco IGDB.          Ritorna 'ok'  'mobile']] - rationale - harvester\src\discovery\igdb.py
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - rationale - harvester\src\injector\upserter.py
- [[Wrapper multi-provider per estrazione fatti + sintesi guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[YouTubeCollector]] - code - harvester\src\collectors\youtube.py
- [[_is_peak_hour()]] - code - harvester\src\injector\upserter.py
- [[_slugify()_3]] - code - harvester\src\orchestrator\pipeline.py
- [[_slugify()_2]] - code - harvester\src\injector\upserter.py
- [[_touch_heartbeat()]] - code - harvester\src\orchestrator\pipeline.py
- [[cleanup() chiama close() su tutti i collector.]] - rationale - harvester\tests\test_pipeline.py
- [[game_name estratto correttamente dallo slug URL.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[generate_slug()]] - code - harvester\src\injector\upserter.py
- [[guide_type_override deve sovrascrivere quello del synthesizer.]] - rationale - harvester\tests\test_pipeline.py
- [[pipeline.py]] - code - harvester\src\orchestrator\pipeline.py
- [[run_seed_batch ritorna dizionario con tutte le statistiche.]] - rationale - harvester\tests\test_pipeline.py
- [[seed_loader.py]] - code - harvester\src\discovery\seed_loader.py
- [[upserter.py]] - code - harvester\src\injector\upserter.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Orchestrator_·_per_guide
SORT file.name ASC
```

## Connections to other communities
- 86 edges to [[_COMMUNITY_Collectors · per collector]]
- 32 edges to [[_COMMUNITY_Discovery · giochi igdb]]
- 9 edges to [[_COMMUNITY_Run Trophy Guides Top20 · trophy fetch]]
- 8 edges to [[_COMMUNITY_Test Injector · quality contenuto]]
- 6 edges to [[_COMMUNITY_Collectors · youtube transcript]]
- 5 edges to [[_COMMUNITY_Collectors · json post]]
- 5 edges to [[_COMMUNITY_Test Pipeline · when returns]]
- 5 edges to [[_COMMUNITY_Transformer · extract synthesize]]
- 4 edges to [[_COMMUNITY_Test Single Game · insert embeddings()]]
- 4 edges to [[_COMMUNITY_Injector · embedder embed]]
- 4 edges to [[_COMMUNITY_Collectors · guide mediawiki]]
- 4 edges to [[_COMMUNITY_Collectors · ddg guide]]
- 4 edges to [[_COMMUNITY_Test Transformer · returns transformer]]
- 2 edges to [[_COMMUNITY_Collectors · fextralife wiki]]
- 2 edges to [[_COMMUNITY_Collectors · ign com]]
- 2 edges to [[_COMMUNITY_Collectors · powerpyx url]]
- 2 edges to [[_COMMUNITY_Test Powerpyx Collector · html content]]
- 2 edges to [[_COMMUNITY_Collectors · steam guide]]
- 2 edges to [[_COMMUNITY_Test Youtube Collector · returns duration]]
- 2 edges to [[_COMMUNITY_Orchestrator · main main()]]
- 1 edge to [[_COMMUNITY_Collectors · exophase per]]
- 1 edge to [[_COMMUNITY_Collectors · org per]]
- 1 edge to [[_COMMUNITY_Collectors · truetrophies per]]
- 1 edge to [[_COMMUNITY_Test Fandom Collector · returns infer]]
- 1 edge to [[_COMMUNITY_Test Steam Community Collector · extract returns]]
- 1 edge to [[_COMMUNITY_Injector · deduplicator evita]]
- 1 edge to [[_COMMUNITY_Test New Collectors · extract returns]]

## Top bridge nodes
- [[BaseCollector_1]] - degree 14, connects to 4 communities
- [[HarvestPipeline]] - degree 45, connects to 3 communities
- [[PowerPyxCollector]] - degree 34, connects to 3 communities
- [[YouTubeCollector]] - degree 30, connects to 3 communities
- [[FandomCollector]] - degree 27, connects to 3 communities