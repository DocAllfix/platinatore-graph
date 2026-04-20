---
type: community
cohesion: 0.08
members: 94
---

# Injector Deduplication

**Cohesion:** 0.08 - loosely connected
**Members:** 94 nodes

## Members
- [[.__init__()_9]] - code - harvester\src\injector\deduplicator.py
- [[.__init__()_2]] - code - harvester\src\collectors\guide_search.py
- [[.__init__()_3]] - code - harvester\src\collectors\reddit.py
- [[.__init__()_13]] - code - harvester\src\transformer\synthesizer.py
- [[.__init__()_11]] - code - harvester\src\injector\upserter.py
- [[.__init__()_4]] - code - harvester\src\collectors\youtube.py
- [[.find_or_create_trophy()]] - code - harvester\src\injector\upserter.py
- [[.guide_exists()]] - code - harvester\src\injector\deduplicator.py
- [[.load_seed_file()]] - code - harvester\src\discovery\seed_loader.py
- [[.seed_database()]] - code - harvester\src\discovery\seed_loader.py
- [[.source_already_processed()]] - code - harvester\src\injector\deduplicator.py
- [[.test_has_http_client()]] - code - harvester\tests\test_collectors.py
- [[.test_inherits_base_collector()]] - code - harvester\tests\test_collectors.py
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - rationale - harvester\src\orchestrator\pipeline.py
- [[BaseCollector_1]] - code
- [[Cerca guide via DDG e fetcha tutti gli URL IN PARALLELO.      Ritorna {trophy_na]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Cerca tips per un trofeo specifico su rTrophies (async, no semaphore).]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Chiude tutti i client HTTP.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Contenuto  200 char → None.]] - rationale - harvester\tests\test_collectors.py
- [[Contenuto  200 char → None._1]] - rationale - harvester\tests\test_collectors.py
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Converte una lista float nel literal pgvector 'f1,f2,...'.      Usato per INSE]] - rationale - harvester\scripts\test_single_game.py
- [[Deduplicator]] - code - harvester\src\injector\deduplicator.py
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - rationale - harvester\src\orchestrator\pipeline.py
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
- [[HTML valido con guide → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_collectors.py
- [[HTML valido con .wiki-article → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_collectors.py
- [[HTML valido → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[I tag script, style, nav non devono comparire nel raw_content.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[IGNCollector]] - code - harvester\src\collectors\ign.py
- [[Il rate limiting è ereditato il client httpx deve essere inizializzato.]] - rationale - harvester\tests\test_collectors.py
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Inserisce righe in guide_embeddings. TEST-ONLY bypassa il worker Node.js.]] - rationale - harvester\scripts\test_single_game.py
- [[La lista achievement deve comparire nel raw_content.]] - rationale - harvester\tests\test_collectors.py
- [[La tabella trofei deve comparire nel raw_content come testo pipe-delimited.]] - rationale - harvester\tests\test_collectors.py
- [[Legge e valida un file JSON seed. Ritorna la lista di giochi.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Legge file JSON seed e upserta giochi nel DB con alias.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Legge l'ultimo slug processato dal DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Logica di deduplicazione basata su DB lookup.]] - rationale - harvester\src\injector\deduplicator.py
- [[Mappa gli ID piattaforma IGDB ai nomi leggibili.]] - rationale - harvester\src\discovery\igdb.py
- [[Orchestra la pipeline completa collect → transform → inject.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[PSNProfilesCollector]] - code - harvester\src\collectors\psnprofiles.py
- [[PSNProfilesCollector deve ereditare da BaseCollector.]] - rationale - harvester\tests\test_collectors.py
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
- [[Script, sidebar, footer, commenti non devono comparire nel testo.]] - rationale - harvester\tests\test_collectors.py
- [[Script, style, sidebar, footer, commenti non devono comparire nel testo.]] - rationale - harvester\tests\test_collectors.py
- [[Se _gemini_calls_today = settings.daily_gemini_limit → False.]] - rationale - harvester\tests\test_transformer.py
- [[SeedLoader]] - code - harvester\src\discovery\seed_loader.py
- [[SeedLoader — carica un file JSON seed e popola il catalogo giochi nel DB.  Forma]] - rationale - harvester\src\discovery\seed_loader.py
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Slug URL-safe NFKD + minuscolo + solo alfanum e trattini.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[SteamCommunityGuidesCollector]] - code - harvester\src\collectors\steam_community.py
- [[Stesso URL + stesso hash → True (già processato).]] - rationale - harvester\tests\test_injector.py
- [[Stesso input HTML+URL → stesso content_hash.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[Stesso input → stesso content_hash.]] - rationale - harvester\tests\test_collectors.py
- [[Stesso input → stesso content_hash._1]] - rationale - harvester\tests\test_collectors.py
- [[Test per i nuovi collector Fextralife, IGN, Reddit.  HTMLJSON tutti inventati,]] - rationale - harvester\tests\test_new_collectors.py
- [[TestPSNProfilesCollector]] - code - harvester\tests\test_collectors.py
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - rationale - harvester\src\injector\upserter.py
- [[True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato).]] - rationale - harvester\src\injector\deduplicator.py
- [[TrueAchievementsCollector]] - code - harvester\src\collectors\trueachievements.py
- [[Upserta tutti i giochi del seed file nel DB.          Per ogni gioco         -]] - rationale - harvester\src\discovery\seed_loader.py
- [[Upserter]] - code - harvester\src\injector\upserter.py
- [[Verdetto di ammissibilità per un gioco IGDB.          Ritorna 'ok'  'mobile']] - rationale - harvester\src\discovery\igdb.py
- [[Wrapper multi-provider per estrazione fatti + sintesi guide.]] - rationale - harvester\src\transformer\synthesizer.py
- [[YouTubeCollector]] - code - harvester\src\collectors\youtube.py
- [[game_name estratto correttamente dallo slug URL.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[game_name estratto dallo slug game{slug}.]] - rationale - harvester\tests\test_collectors.py
- [[game_name estratto rimuovendo il prefisso numerico dallo slug.]] - rationale - harvester\tests\test_collectors.py
- [[seed_loader.py]] - code - harvester\src\discovery\seed_loader.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Injector_Deduplication
SORT file.name ASC
```

## Connections to other communities
- 69 edges to [[_COMMUNITY_BaseCollector Interface]]
- 32 edges to [[_COMMUNITY_IGDB Discovery Scripts]]
- 30 edges to [[_COMMUNITY_Orchestrator Pipeline]]
- 12 edges to [[_COMMUNITY_Upserter Transaction Logic]]
- 9 edges to [[_COMMUNITY_Trophy Guides Discovery Script]]
- 9 edges to [[_COMMUNITY_PSNProfilesTrueAchievements Tests]]
- 8 edges to [[_COMMUNITY_Injector Integration Tests]]
- 6 edges to [[_COMMUNITY_YouTube Collector]]
- 5 edges to [[_COMMUNITY_Reddit Collector]]
- 5 edges to [[_COMMUNITY_Guide Synthesizer]]
- 4 edges to [[_COMMUNITY_Single-Game Test Pipeline]]
- 4 edges to [[_COMMUNITY_Gemini Embedder]]
- 4 edges to [[_COMMUNITY_Transformer Tests]]
- 3 edges to [[_COMMUNITY_._call_deepseek()]]
- 2 edges to [[_COMMUNITY_Fextralife Collector]]
- 2 edges to [[_COMMUNITY_ign.py]]
- 2 edges to [[_COMMUNITY_PowerPyx Collector Tests]]
- 2 edges to [[_COMMUNITY_PSNProfiles Collector]]
- 2 edges to [[_COMMUNITY_Steam Community Collector]]
- 2 edges to [[_COMMUNITY_YouTube Collector Tests]]
- 1 edge to [[_COMMUNITY_Exophase Collector]]
- 1 edge to [[_COMMUNITY_PSTrophies Collector]]
- 1 edge to [[_COMMUNITY_TrueTrophies Collector]]
- 1 edge to [[_COMMUNITY_Fandom Collector Tests]]
- 1 edge to [[_COMMUNITY_Steam Community Tests]]
- 1 edge to [[_COMMUNITY_Deduplicator — evita upsert inutili e pr]]
- 1 edge to [[_COMMUNITY_FextralifeIGNReddit Tests]]

## Top bridge nodes
- [[PSNProfilesCollector]] - degree 51, connects to 4 communities
- [[GuideSynthesizer]] - degree 46, connects to 4 communities
- [[Deduplicator]] - degree 42, connects to 4 communities
- [[YouTubeCollector]] - degree 30, connects to 4 communities
- [[SteamCommunityGuidesCollector]] - degree 26, connects to 4 communities