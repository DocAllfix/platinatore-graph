# Graph Report - .  (2026-04-20)

## Corpus Check
- Corpus is ~49,386 words - fits in a single context window. You may not need a graph.

## Summary
- 957 nodes · 1689 edges · 80 communities detected
- Extraction: 59% EXTRACTED · 41% INFERRED · 0% AMBIGUOUS · INFERRED: 685 edges (avg confidence: 0.51)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_BaseCollector Interface|BaseCollector Interface]]
- [[_COMMUNITY_PSNSteam Discovery Scripts|PSN/Steam Discovery Scripts]]
- [[_COMMUNITY_Injector Deduplication|Injector Deduplication]]
- [[_COMMUNITY_IGDB Discovery Scripts|IGDB Discovery Scripts]]
- [[_COMMUNITY_Orchestrator Pipeline|Orchestrator Pipeline]]
- [[_COMMUNITY_Fandom Collector Tests|Fandom Collector Tests]]
- [[_COMMUNITY_Project Architecture Overview|Project Architecture Overview]]
- [[_COMMUNITY_YouTube Collector Tests|YouTube Collector Tests]]
- [[_COMMUNITY_Injector Integration Tests|Injector Integration Tests]]
- [[_COMMUNITY_Trophy Section Extractor|Trophy Section Extractor]]
- [[_COMMUNITY_Steam Community Tests|Steam Community Tests]]
- [[_COMMUNITY_PSNProfilesTrueAchievements Tests|PSNProfiles/TrueAchievements Tests]]
- [[_COMMUNITY_Backend Error Hierarchy|Backend Error Hierarchy]]
- [[_COMMUNITY_YouTube Collector|YouTube Collector]]
- [[_COMMUNITY_DB Pool Infrastructure|DB Pool Infrastructure]]
- [[_COMMUNITY_Upserter Transaction Logic|Upserter Transaction Logic]]
- [[_COMMUNITY_Guide Synthesizer|Guide Synthesizer]]
- [[_COMMUNITY_Single-Game Test Pipeline|Single-Game Test Pipeline]]
- [[_COMMUNITY_Reddit Collector|Reddit Collector]]
- [[_COMMUNITY_Trophy Guides Discovery Script|Trophy Guides Discovery Script]]
- [[_COMMUNITY_PSTrophies Collector|PSTrophies Collector]]
- [[_COMMUNITY_Exophase Collector|Exophase Collector]]
- [[_COMMUNITY_TrueTrophies Collector|TrueTrophies Collector]]
- [[_COMMUNITY_Transformer Tests|Transformer Tests]]
- [[_COMMUNITY_PSNProfiles Collector|PSNProfiles Collector]]
- [[_COMMUNITY_FextralifeIGNReddit Tests|Fextralife/IGN/Reddit Tests]]
- [[_COMMUNITY_Gemini Embedder|Gemini Embedder]]
- [[_COMMUNITY_PowerPyx Collector Tests|PowerPyx Collector Tests]]
- [[_COMMUNITY_Steam Community Collector|Steam Community Collector]]
- [[_COMMUNITY_Fextralife Collector|Fextralife Collector]]
- [[_COMMUNITY_ign.py|ign.py]]
- [[_COMMUNITY_BaseSettings|BaseSettings]]
- [[_COMMUNITY_._call_deepseek()|._call_deepseek()]]
- [[_COMMUNITY_logger.py|logger.py]]
- [[_COMMUNITY_redis_client.py|redis_client.py]]
- [[_COMMUNITY_chunk_content()|chunk_content()]]
- [[_COMMUNITY_database.ts|database.ts]]
- [[_COMMUNITY_games.routes.ts|games.routes.ts]]
- [[_COMMUNITY_quality.py|quality.py]]
- [[_COMMUNITY_GRAPH_REPORT|GRAPH_REPORT.md]]
- [[_COMMUNITY_rateLimiter.ts|rateLimiter.ts]]
- [[_COMMUNITY_embedding.service.test.ts|embedding.service.test.ts]]
- [[_COMMUNITY_embedding.worker.ts|embedding.worker.ts]]
- [[_COMMUNITY_main()|main()]]
- [[_COMMUNITY_Deduplicator — evita upsert inutili e pr|Deduplicator — evita upsert inutili e pr]]
- [[_COMMUNITY_run-migrations.ts|run-migrations.ts]]
- [[_COMMUNITY_env.ts|env.ts]]
- [[_COMMUNITY_redis.ts|redis.ts]]
- [[_COMMUNITY_errorHandler.ts|errorHandler.ts]]
- [[_COMMUNITY_requestLogger.ts|requestLogger.ts]]
- [[_COMMUNITY_validate.ts|validate.ts]]
- [[_COMMUNITY_embeddings.model.ts|embeddings.model.ts]]
- [[_COMMUNITY_games.model.ts|games.model.ts]]
- [[_COMMUNITY_guides.model.ts|guides.model.ts]]
- [[_COMMUNITY_embedding.queue.ts|embedding.queue.ts]]
- [[_COMMUNITY_embedding.scheduler.ts|embedding.scheduler.ts]]
- [[_COMMUNITY_asyncHandler()|asyncHandler()]]
- [[_COMMUNITY_prompts.py|prompts.py]]
- [[_COMMUNITY_vitest.config.ts|vitest.config.ts]]
- [[_COMMUNITY_index.ts|index.ts]]
- [[_COMMUNITY_queryLog.model.ts|queryLog.model.ts]]
- [[_COMMUNITY_ratings.model.ts|ratings.model.ts]]
- [[_COMMUNITY_systemConfig.model.ts|systemConfig.model.ts]]
- [[_COMMUNITY_users.model.ts|users.model.ts]]
- [[_COMMUNITY_express.d.ts|express.d.ts]]
- [[_COMMUNITY_logger.ts|logger.ts]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY_Estrae dati strutturati dall'HTML.  Da i|Estrae dati strutturati dall'HTML.  Da i]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY_Normalizza stringa per confronto minusc|Normalizza stringa per confronto: minusc]]
- [[_COMMUNITY_Verifica se il nome PSN corrisponde alla|Verifica se il nome PSN corrisponde alla]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY_Decide se sovrascrivere una guida esiste|Decide se sovrascrivere una guida esiste]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY___init__.py|__init__.py]]
- [[_COMMUNITY_index.ts|index.ts]]

## God Nodes (most connected - your core abstractions)
1. `BaseCollector` - 162 edges
2. `Upserter` - 60 edges
3. `PSNProfilesCollector` - 51 edges
4. `GuideSynthesizer` - 46 edges
5. `HarvestPipeline` - 45 edges
6. `TrueAchievementsCollector` - 42 edges
7. `Deduplicator` - 42 edges
8. `IGDBDiscovery` - 40 edges
9. `RedditCollector` - 37 edges
10. `SeedLoader` - 36 edges

## Surprising Connections (you probably didn't know these)
- `ExophaseCollector — collector per exophase.com.  Exophase è un aggregatore di ac` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\exophase.py → harvester\src\collectors\base.py
- `Slug per Exophase: lowercase + trattini, apostrofi rimossi.` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\exophase.py → harvester\src\collectors\base.py
- `Collector per trofei/achievement su exophase.com.` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\exophase.py → harvester\src\collectors\base.py
- `Costruisce l'URL della pagina trofei per un gioco.` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\exophase.py → harvester\src\collectors\base.py
- `Estrae trofei e descrizioni dall'HTML di Exophase.          Ritorna None se la p` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\exophase.py → harvester\src\collectors\base.py

## Hyperedges (group relationships)
- **Hybrid Retrieval Strategy** — readme_hnsw_vector_search, readme_full_text_search, readme_rrf [EXTRACTED 1.00]
- **RAG Three-Stage Pipeline** — readme_retrieval_stage, readme_augmentation_stage, readme_generation_stage [EXTRACTED 1.00]
- **Ingestion Pipeline** — harvester_readme_scraping, harvester_readme_llm_transform, harvester_readme_vectorization [EXTRACTED 1.00]

## Communities

### Community 0 - "BaseCollector Interface"
Cohesion: 0.02
Nodes (92): ABC, BaseCollector, compute_hash(), extract(), PerHostTokenBucket, BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En, Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile., Chiude il client httpx. (+84 more)

### Community 1 - "PSN/Steam Discovery Scripts"
Cohesion: 0.02
Nodes (82): main(), _parse_args(), igdb_seed — pipeline completa: IGDB discovery + PSN trofei + Steam achievements., Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi, Fetcha achievement Steam per giochi con steam_appid senza achievement., Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale., _run(), _run_psn_trophies() (+74 more)

### Community 2 - "Injector Deduplication"
Cohesion: 0.08
Nodes (80): BaseCollector, Deduplicator, Logica di deduplicazione basata su DB lookup., Ritorna la guida esistente (id/confidence/quality) se presente, altrimenti None., True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato)., FandomCollector, FextralifeCollector, GuideSearchCollector (+72 more)

### Community 3 - "IGDB Discovery Scripts"
Cohesion: 0.04
Nodes (39): _accept_game(), IGDBDiscovery, _map_platform_ids(), IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione: Twit, Esegue una query POST su un endpoint IGDB e ritorna la risposta JSON., Recupera i giochi più giocati via popularity_primitives.          popularity_typ, Recupera i dettagli dei giochi per una lista di IGDB IDs., Recupera giochi usciti negli ultimi N giorni per piattaforma.          Usa l'end (+31 more)

### Community 4 - "Orchestrator Pipeline"
Cohesion: 0.07
Nodes (30): main(), _parse_args(), Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è, Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo., touch_heartbeat(), HarvestPipeline, _slugify(), _touch_heartbeat() (+22 more)

### Community 5 - "Fandom Collector Tests"
Cohesion: 0.07
Nodes (1): Test FandomCollector — tutto mockato, zero rete reale.  Copre: HTML stripping, g

### Community 6 - "Project Architecture Overview"
Cohesion: 0.11
Nodes (29): Infinite Ingestion Engine, LLM Transformation, Scraping, Vectorization, Augmentation Stage, Backend API (Node.js + TypeScript + Express), backend/, Base44 Frontend (+21 more)

### Community 7 - "YouTube Collector Tests"
Cohesion: 0.09
Nodes (3): Test YouTubeCollector — tutto mockato, zero rete reale, zero API key.  I JSON/tr, search_videos deve filtrare per view count e duration., test_search_videos_returns_filtered_results()

### Community 8 - "Injector Integration Tests"
Cohesion: 0.1
Nodes (8): Test per Injector: chunker, slug, deduplicator — DB mockato, zero connessioni re, Contenuto breve → un solo chunk con prefisso titolo., Contenuto lungo con heading ## → multi chunk., Qualità uguale → upsert consentito.          Necessario perché il LLM produce se, TestChunker, TestShouldUpsert, TestSlug, TestSourceAlreadyProcessed

### Community 9 - "Trophy Section Extractor"
Cohesion: 0.15
Nodes (17): _anchor_id_to_name(), _extract_sections_by_anchors(), _extract_sections_by_headings(), extract_trophy_sections(), _is_trophy_anchor(), match_trophies_to_sections(), _normalize_name(), TrophySectionExtractor — estrae sezioni per-trofeo da HTML di guide.  Supporta d (+9 more)

### Community 10 - "Steam Community Tests"
Cohesion: 0.13
Nodes (5): _details_payload(), Test SteamCommunityGuidesCollector — JSON inventato, zero rete reale., test_extract_result_not_ok_returns_none(), test_extract_too_short_returns_none(), test_extract_valid_guide()

### Community 11 - "PSNProfiles/TrueAchievements Tests"
Cohesion: 0.12
Nodes (4): Test per PSNProfilesCollector e TrueAchievementsCollector.  HTML di esempio inve, TrueAchievementsCollector deve ereditare da BaseCollector., Il rate limiting è ereditato: il client httpx deve essere inizializzato., TestTrueAchievementsCollector

### Community 12 - "Backend Error Hierarchy"
Cohesion: 0.13
Nodes (7): AppError, AuthenticationError, ForbiddenError, InternalError, NotFoundError, RateLimitError, ValidationError

### Community 13 - "YouTube Collector"
Cohesion: 0.13
Nodes (9): _parse_duration(), YouTubeCollector — guide video via YouTube Data API v3 + transcript.  Architettu, Fetch con redazione di `key=...` nei log., Cerca video su YouTube e ritorna quelli che passano i filtri qualità.          O, Ritorna il testo del transcript EN, o None se non disponibile.          youtube-, Supporta dispatch da seed file con URL youtube.com/watch?v=VIDEO_ID., Parsa transcript + URL e ritorna dict standard collector.          `extra` opzio, Converte durata ISO 8601 in secondi totali. Es: 'PT4M13S' → 253. (+1 more)

### Community 14 - "DB Pool Infrastructure"
Cohesion: 0.2
Nodes (14): close_pool(), execute(), fetch_all(), fetch_one(), _get_pool(), init_pool(), Verifica la connessione al DB con SELECT NOW(). Logga il risultato., Apre il connection pool. Da chiamare all'avvio dell'orchestratore. (+6 more)

### Community 15 - "Upserter Transaction Logic"
Cohesion: 0.16
Nodes (10): generate_slug(), _is_peak_hour(), Upserter — transazione atomica: game → trophy → guide → harvest_sources.  **FF-N, UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`, Lowercase + rimozione accenti base + non-alfanumerici → trattini., Slug URL-safe per la guida: `guida-{game}-{trophy_or_topic?}-{type}`.      `topi, Versione TX-scoped di find_or_create_game — stessa logica a 4 step., Peak hour CET: 18:00-23:59. (+2 more)

### Community 16 - "Guide Synthesizer"
Cohesion: 0.16
Nodes (9): GuideSynthesizer — pipeline multi-provider: extract_facts → synthesize_guide.  P, Estrae fatti atomici dai testi grezzi. None se quota o parsing KO., Sintetizza una guida markdown dai fatti. None se quota o formato KO., Pipeline completa: extract_facts → synthesize_guide., Rimuove eventuali ```markdown ... ``` fences dal testo sintetizzato., Rimuove eventuali ```json ... ``` fences.      Usa search() invece di match() pe, Reset del contatore se cambia giorno; False se limite superato., _strip_json_fences() (+1 more)

### Community 17 - "Single-Game Test Pipeline"
Cohesion: 0.31
Nodes (12): _insert_embeddings(), main(), _pgvector_search(), step1_init(), step2_collect(), step3_transform(), step4_quality_and_chunk(), step5_embed() (+4 more)

### Community 18 - "Reddit Collector"
Cohesion: 0.17
Nodes (7): _clean_post(), format_for_llm(), RedditCollector — community meta/build/tips via API JSON pubblica.  Nessuna API, Cerca post in un subreddit.  Ritorna lista di dict filtrati., Fetcha un post + top commenti via /comments/{id}.json., Estrae post filtrati da un Listing search.json., Parsa un payload search.json o comments.json di Reddit.          `html` qui è il

### Community 19 - "Trophy Guides Discovery Script"
Cohesion: 0.32
Nodes (11): _discover_guide_sources(), _fetch_and_extract(), _fetch_reddit_trophy_tips(), _generic_fetch(), main(), _process_game(), _process_trophy(), _psnprofiles_trophy_url() (+3 more)

### Community 20 - "PSTrophies Collector"
Cohesion: 0.21
Nodes (9): _extract_title(), _normalize_whitespace(), PSTrophiesOrgCollector, PSTrophiesOrgCollector — collector per playstationtrophies.org.  PlaystationTrop, Slug per playstationtrophies.org: lowercase + trattini, no caratteri speciali., Collector per guide trofei su playstationtrophies.org., Costruisce l'URL della guida per un gioco., Estrae titolo e contenuto pulito dall'HTML di PlaystationTrophies.org. (+1 more)

### Community 21 - "Exophase Collector"
Cohesion: 0.21
Nodes (9): ExophaseCollector, _extract_title(), _normalize_whitespace(), ExophaseCollector — collector per exophase.com.  Exophase è un aggregatore di ac, Slug per Exophase: lowercase + trattini, apostrofi rimossi., Collector per trofei/achievement su exophase.com., Costruisce l'URL della pagina trofei per un gioco., Estrae trofei e descrizioni dall'HTML di Exophase.          Ritorna None se la p (+1 more)

### Community 22 - "TrueTrophies Collector"
Cohesion: 0.21
Nodes (9): _extract_title(), _normalize_whitespace(), TrueTrophiesCollector — collector per truetrophies.com.  TrueTrophies è una comm, Slug per TrueTrophies: NFKD + lowercase + trattini come separatori.      Esempi:, Collector per guide trofei su truetrophies.com., Costruisce l'URL della pagina trofei per un gioco., Estrae titolo e contenuto pulito dall'HTML di TrueTrophies.          Ritorna Non, _slugify_truetrophies() (+1 more)

### Community 23 - "Transformer Tests"
Cohesion: 0.17
Nodes (4): Test per il modulo Transformer — prompts, quality score, daily limit.  NON chiam, TestDailyLimit, TestPrompts, TestQualityScore

### Community 24 - "PSNProfiles Collector"
Cohesion: 0.24
Nodes (9): _convert_tables_to_text(), _extract_title(), _normalize_whitespace(), _parse_url_slug(), PSNProfilesCollector — collector per psnprofiles.com.  Guide trophy nella sezion, Converte tabelle <table class="zebra"> in testo strutturato pipe-delimited., Collassa spazi multipli e normalizza newline., Estrae game_name dall'URL PSNProfiles.      Formati tipici:       - /guide/12345 (+1 more)

### Community 25 - "Fextralife/IGN/Reddit Tests"
Cohesion: 0.18
Nodes (0): 

### Community 26 - "Gemini Embedder"
Cohesion: 0.25
Nodes (4): Embedder, Embedder — wrapper Gemini text-embedding-004 con batching e quota giornaliera., Wrapper Gemini embedding con quota e batching automatico., Embedding in batch (max 100/call).  Splitta in sotto-batch se necessario.

### Community 27 - "PowerPyx Collector Tests"
Cohesion: 0.22
Nodes (2): Test per PowerPyxCollector — extract, URL slug parsing, pulizia HTML., TestExtract

### Community 28 - "Steam Community Collector"
Cohesion: 0.29
Nodes (6): _guide_type_from_tags(), SteamCommunityGuidesCollector — guide user-generated via API Steam ufficiale.  E, Parsa una risposta GetDetails.  `html` qui è JSON text.          Ritorna dict st, Rimuove BBCode Steam preservando il testo leggibile., Mappa tag Steam a guide_type DB. Default 'walkthrough' (sempre in CHECK)., _strip_steam_bbcode()

### Community 29 - "Fextralife Collector"
Cohesion: 0.38
Nodes (5): _extract_title(), _normalize_whitespace(), _parse_url_slug(), FextralifeCollector — guide wiki Soulslike/Metroidvania.  Fextralife usa renderi, Estrae game_name e topic dallo slug Fextralife.      Pattern: wiki.fextralife.co

### Community 30 - "ign.py"
Cohesion: 0.38
Nodes (5): _extract_title(), _normalize_whitespace(), _parse_url_slug(), IGNCollector — guide wiki professionali su ign.com.  Pattern URL: ign.com/wikis/, Estrae game_name e topic da URL ign.com/wikis/{game}/{topic}.

### Community 31 - "BaseSettings"
Cohesion: 0.33
Nodes (4): BaseSettings, mock_settings(), Settings con valori di test, senza connessioni reali a DB o Redis.     Utile per, Settings

### Community 32 - "._call_deepseek()"
Cohesion: 0.33
Nodes (3): Chiamata Gemini sincrona via google-genai SDK., Dispatch al provider configurato., Chiamata DeepSeek sincrona via OpenAI-compatible SDK.

### Community 33 - "logger.py"
Cohesion: 0.4
Nodes (4): get_logger(), Restituisce un logger con il campo 'logger' già bindato al nome del modulo., Configura structlog: JSON in prod, console colorata in dev (DEBUG)., setup_logging()

### Community 34 - "redis_client.py"
Cohesion: 0.4
Nodes (4): close_redis(), Chiude la connessione Redis. Da chiamare allo shutdown., Verifica la connessione Redis con PING., test_redis_connection()

### Community 35 - "chunk_content()"
Cohesion: 0.5
Nodes (4): chunk_content(), _estimate_tokens(), Chunker — split di una guida in chunk da max_tokens con overlap.  Stima token =, Split markdown guide in chunk con prefisso titolo e overlap tra chunk consecutiv

### Community 36 - "database.ts"
Cohesion: 0.5
Nodes (0): 

### Community 37 - "games.routes.ts"
Cohesion: 0.5
Nodes (0): 

### Community 38 - "quality.py"
Cohesion: 0.5
Nodes (3): calculate_quality_score(), Quality scoring per guide sintetizzate dal Transformer.  Algoritmo Masterplan:, Calcola un quality score in [0.0, 1.0] arrotondato a 2 decimali.

### Community 39 - "GRAPH_REPORT.md"
Cohesion: 0.5
Nodes (4): GRAPH_REPORT.md, Graphify Knowledge Graph, graphify.watch._rebuild_code, Wiki Index

### Community 40 - "rateLimiter.ts"
Cohesion: 0.67
Nodes (0): 

### Community 41 - "embedding.service.test.ts"
Cohesion: 0.67
Nodes (0): 

### Community 42 - "embedding.worker.ts"
Cohesion: 0.67
Nodes (0): 

### Community 43 - "main()"
Cohesion: 0.67
Nodes (1): Genera expanded_seed.json dai giochi PS5/PS4 più rilevanti nel DB.  Criteri prio

### Community 44 - "Deduplicator — evita upsert inutili e pr"
Cohesion: 0.67
Nodes (1): Deduplicator — evita upsert inutili e protegge guide verificate.

### Community 45 - "run-migrations.ts"
Cohesion: 1.0
Nodes (0): 

### Community 46 - "env.ts"
Cohesion: 1.0
Nodes (0): 

### Community 47 - "redis.ts"
Cohesion: 1.0
Nodes (0): 

### Community 48 - "errorHandler.ts"
Cohesion: 1.0
Nodes (0): 

### Community 49 - "requestLogger.ts"
Cohesion: 1.0
Nodes (0): 

### Community 50 - "validate.ts"
Cohesion: 1.0
Nodes (0): 

### Community 51 - "embeddings.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 52 - "games.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 53 - "guides.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 54 - "embedding.queue.ts"
Cohesion: 1.0
Nodes (0): 

### Community 55 - "embedding.scheduler.ts"
Cohesion: 1.0
Nodes (0): 

### Community 56 - "asyncHandler()"
Cohesion: 1.0
Nodes (0): 

### Community 57 - "prompts.py"
Cohesion: 1.0
Nodes (1): System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz

### Community 58 - "vitest.config.ts"
Cohesion: 1.0
Nodes (0): 

### Community 59 - "index.ts"
Cohesion: 1.0
Nodes (0): 

### Community 60 - "queryLog.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 61 - "ratings.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 62 - "systemConfig.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 63 - "users.model.ts"
Cohesion: 1.0
Nodes (0): 

### Community 64 - "express.d.ts"
Cohesion: 1.0
Nodes (0): 

### Community 65 - "logger.ts"
Cohesion: 1.0
Nodes (0): 

### Community 66 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 67 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 68 - "Estrae dati strutturati dall'HTML.  Da i"
Cohesion: 1.0
Nodes (1): Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.

### Community 69 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 70 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 71 - "Normalizza stringa per confronto: minusc"
Cohesion: 1.0
Nodes (1): Normalizza stringa per confronto: minuscolo, senza accenti né punteggiatura.

### Community 72 - "Verifica se il nome PSN corrisponde alla"
Cohesion: 1.0
Nodes (1): Verifica se il nome PSN corrisponde alla query di ricerca.          Strategia a

### Community 73 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 74 - "Decide se sovrascrivere una guida esiste"
Cohesion: 1.0
Nodes (1): Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui

### Community 75 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 76 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 77 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 78 - "__init__.py"
Cohesion: 1.0
Nodes (0): 

### Community 79 - "index.ts"
Cohesion: 1.0
Nodes (0): 

## Knowledge Gaps
- **116 isolated node(s):** `Genera expanded_seed.json dai giochi PS5/PS4 più rilevanti nel DB.  Criteri prio`, `BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En`, `Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi`, `Attende fino a quando un token è disponibile per *host*.`, `Calcola SHA-256 di *text* e ritorna l'hash esadecimale.` (+111 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `run-migrations.ts`** (2 nodes): `run-migrations.ts`, `runMigrations()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `env.ts`** (2 nodes): `env.ts`, `loadEnv()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `redis.ts`** (2 nodes): `redis.ts`, `testRedisConnection()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `errorHandler.ts`** (2 nodes): `errorHandler.ts`, `errorHandler()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `requestLogger.ts`** (2 nodes): `requestLogger.ts`, `requestLogger()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `validate.ts`** (2 nodes): `validate.ts`, `validate()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `embeddings.model.ts`** (2 nodes): `embeddings.model.ts`, `runQuery()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `games.model.ts`** (2 nodes): `games.model.ts`, `buildSetClause()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `guides.model.ts`** (2 nodes): `guides.model.ts`, `buildSetClause()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `embedding.queue.ts`** (2 nodes): `embedding.queue.ts`, `enqueueLiveEmbedding()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `embedding.scheduler.ts`** (2 nodes): `embedding.scheduler.ts`, `startEmbeddingScheduler()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `asyncHandler()`** (2 nodes): `asyncHandler()`, `asyncHandler.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `prompts.py`** (2 nodes): `prompts.py`, `System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `vitest.config.ts`** (1 nodes): `vitest.config.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `index.ts`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `queryLog.model.ts`** (1 nodes): `queryLog.model.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `ratings.model.ts`** (1 nodes): `ratings.model.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `systemConfig.model.ts`** (1 nodes): `systemConfig.model.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `users.model.ts`** (1 nodes): `users.model.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `express.d.ts`** (1 nodes): `express.d.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `logger.ts`** (1 nodes): `logger.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Estrae dati strutturati dall'HTML.  Da i`** (1 nodes): `Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Normalizza stringa per confronto: minusc`** (1 nodes): `Normalizza stringa per confronto: minuscolo, senza accenti né punteggiatura.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Verifica se il nome PSN corrisponde alla`** (1 nodes): `Verifica se il nome PSN corrisponde alla query di ricerca.          Strategia a`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Decide se sovrascrivere una guida esiste`** (1 nodes): `Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `__init__.py`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `index.ts`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `BaseCollector` connect `BaseCollector Interface` to `Injector Deduplication`, `Orchestrator Pipeline`, `PSNProfiles/TrueAchievements Tests`, `YouTube Collector`, `Reddit Collector`, `PSTrophies Collector`, `Exophase Collector`, `TrueTrophies Collector`, `PSNProfiles Collector`, `Steam Community Collector`, `Fextralife Collector`, `ign.py`?**
  _High betweenness centrality (0.285) - this node is a cross-community bridge._
- **Why does `Upserter` connect `Injector Deduplication` to `IGDB Discovery Scripts`, `Orchestrator Pipeline`, `Upserter Transaction Logic`?**
  _High betweenness centrality (0.251) - this node is a cross-community bridge._
- **Why does `IGDBDiscovery` connect `IGDB Discovery Scripts` to `PSN/Steam Discovery Scripts`, `Injector Deduplication`?**
  _High betweenness centrality (0.214) - this node is a cross-community bridge._
- **Are the 152 inferred relationships involving `BaseCollector` (e.g. with `ExophaseCollector` and `ExophaseCollector — collector per exophase.com.  Exophase è un aggregatore di ac`) actually correct?**
  _`BaseCollector` has 152 INFERRED edges - model-reasoned connections that need verification._
- **Are the 52 inferred relationships involving `Upserter` (e.g. with `Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P` and `Slug URL-safe: NFKD + minuscolo + solo alfanum e trattini.`) actually correct?**
  _`Upserter` has 52 INFERRED edges - model-reasoned connections that need verification._
- **Are the 47 inferred relationships involving `PSNProfilesCollector` (e.g. with `Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P` and `Slug URL-safe: NFKD + minuscolo + solo alfanum e trattini.`) actually correct?**
  _`PSNProfilesCollector` has 47 INFERRED edges - model-reasoned connections that need verification._
- **Are the 36 inferred relationships involving `GuideSynthesizer` (e.g. with `Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P` and `Slug URL-safe: NFKD + minuscolo + solo alfanum e trattini.`) actually correct?**
  _`GuideSynthesizer` has 36 INFERRED edges - model-reasoned connections that need verification._