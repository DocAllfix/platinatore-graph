# Graph Report - .  (2026-04-14)

## Corpus Check
- Corpus is ~12,190 words - fits in a single context window. You may not need a graph.

## Summary
- 374 nodes · 561 edges · 36 communities detected
- Extraction: 63% EXTRACTED · 37% INFERRED · 0% AMBIGUOUS · INFERRED: 209 edges (avg confidence: 0.53)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Collector Base Class|Collector Base Class]]
- [[_COMMUNITY_IGDB Discovery & Seeds|IGDB Discovery & Seeds]]
- [[_COMMUNITY_Embedding Service|Embedding Service]]
- [[_COMMUNITY_Deduplicator|Deduplicator]]
- [[_COMMUNITY_Architecture README|Architecture README]]
- [[_COMMUNITY_Postgres Pool|Postgres Pool]]
- [[_COMMUNITY_Pipeline Tests|Pipeline Tests]]
- [[_COMMUNITY_Transformer Tests|Transformer Tests]]
- [[_COMMUNITY_Guide Synthesizer|Guide Synthesizer]]
- [[_COMMUNITY_PowerPyx Collector|PowerPyx Collector]]
- [[_COMMUNITY_PowerPyx Collector Tests|PowerPyx Collector Tests]]
- [[_COMMUNITY_Harvester Entry Point|Harvester Entry Point]]
- [[_COMMUNITY_Settings & Conftest|Settings & Conftest]]
- [[_COMMUNITY_Structured Logger|Structured Logger]]
- [[_COMMUNITY_Redis Client|Redis Client]]
- [[_COMMUNITY_Content Chunker|Content Chunker]]
- [[_COMMUNITY_Backend Database|Backend Database]]
- [[_COMMUNITY_Quality Scorer|Quality Scorer]]
- [[_COMMUNITY_Graphify Integration|Graphify Integration]]
- [[_COMMUNITY_Migration Runner|Migration Runner]]
- [[_COMMUNITY_Backend Env Config|Backend Env Config]]
- [[_COMMUNITY_Backend Redis|Backend Redis]]
- [[_COMMUNITY_Prompt Templates|Prompt Templates]]
- [[_COMMUNITY_Backend Entry Point|Backend Entry Point]]
- [[_COMMUNITY_Backend Logger|Backend Logger]]
- [[_COMMUNITY_Harvester Package Root|Harvester Package Root]]
- [[_COMMUNITY_Base Rationale Orphan|Base Rationale Orphan]]
- [[_COMMUNITY_Collectors Package Root|Collectors Package Root]]
- [[_COMMUNITY_Config Package Root|Config Package Root]]
- [[_COMMUNITY_Discovery Package Root|Discovery Package Root]]
- [[_COMMUNITY_Dedup Rationale Orphan|Dedup Rationale Orphan]]
- [[_COMMUNITY_Injector Package Root|Injector Package Root]]
- [[_COMMUNITY_Orchestrator Package Root|Orchestrator Package Root]]
- [[_COMMUNITY_Transformer Package Root|Transformer Package Root]]
- [[_COMMUNITY_Tests Package Root|Tests Package Root]]
- [[_COMMUNITY_Scraper Entry Point|Scraper Entry Point]]

## God Nodes (most connected - your core abstractions)
1. `BaseCollector` - 39 edges
2. `Deduplicator` - 32 edges
3. `HarvestPipeline` - 29 edges
4. `SeedLoader` - 28 edges
5. `PerHostTokenBucket` - 27 edges
6. `Upserter` - 27 edges
7. `IGDBDiscovery` - 23 edges
8. `GuideSynthesizer` - 23 edges
9. `PowerPyxCollector` - 22 edges
10. `Embedder` - 16 edges

## Surprising Connections (you probably didn't know these)
- `PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\powerpyx.py → harvester\src\collectors\base.py
- `Collector per guide trofei su powerpyx.com.` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\powerpyx.py → harvester\src\collectors\base.py
- `Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\powerpyx.py → harvester\src\collectors\base.py
- `Collassa spazi multipli e normalizza newline.` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\powerpyx.py → harvester\src\collectors\base.py
- `Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici:` --uses--> `BaseCollector`  [INFERRED]
  harvester\src\collectors\powerpyx.py → harvester\src\collectors\base.py

## Hyperedges (group relationships)
- **Hybrid Retrieval Strategy** — readme_hnsw_vector_search, readme_full_text_search, readme_rrf [EXTRACTED 1.00]
- **Ingestion Pipeline** — harvester_readme_scraping, harvester_readme_llm_transform, harvester_readme_vectorization [EXTRACTED 1.00]
- **RAG Three-Stage Pipeline** — readme_retrieval_stage, readme_augmentation_stage, readme_generation_stage [EXTRACTED 1.00]

## Communities

### Community 0 - "Collector Base Class"
Cohesion: 0.05
Nodes (41): ABC, BaseCollector, compute_hash(), extract(), PerHostTokenBucket, BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En, Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile., Chiude il client httpx. (+33 more)

### Community 1 - "IGDB Discovery & Seeds"
Cohesion: 0.06
Nodes (30): IGDBDiscovery, IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione: Twit, Scarica tutti i giochi IGDB per le piattaforme e li inserisce nel DB.          P, Inserisce alias per il gioco: titolo completo + slug IGDB., Chiude il client httpx., Client IGDB per discovery automatica giochi e popolamento catalogo DB., Ritorna il token Twitch OAuth, richiedendolo/rinnovandolo se scaduto., Recupera giochi IGDB per le piattaforme indicate.          IGDB usa POST con bod (+22 more)

### Community 2 - "Embedding Service"
Cohesion: 0.07
Nodes (33): Embedder, Embedder — wrapper Gemini text-embedding-004 con batching e quota giornaliera., Wrapper Gemini embedding con quota e batching automatico., Embedding in batch (max 100/call).  Splitta in sotto-batch se necessario., HarvestPipeline, HarvestPipeline — orchestratore che connette collector → transformer → injector., Processa tutti i giochi del seed file con advisory lock singleton.          Rito, Orchestra la pipeline completa: collect → transform → inject. (+25 more)

### Community 3 - "Deduplicator"
Cohesion: 0.06
Nodes (22): Deduplicator, Deduplicator — evita upsert inutili e protegge guide verificate., Logica di deduplicazione basata su DB lookup., Ritorna la guida esistente (id/confidence/quality) se presente, altrimenti None., True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato)., Test per Injector: chunker, slug, deduplicator — DB mockato, zero connessioni re, Contenuto breve → un solo chunk con prefisso titolo., Contenuto lungo con heading ## → multi chunk. (+14 more)

### Community 4 - "Architecture README"
Cohesion: 0.11
Nodes (29): Infinite Ingestion Engine, LLM Transformation, Scraping, Vectorization, Augmentation Stage, Backend API (Node.js + TypeScript + Express), backend/, Base44 Frontend (+21 more)

### Community 5 - "Postgres Pool"
Cohesion: 0.2
Nodes (14): close_pool(), execute(), fetch_all(), fetch_one(), _get_pool(), init_pool(), Verifica la connessione al DB con SELECT NOW(). Logga il risultato., Apre il connection pool. Da chiamare all'avvio dell'orchestratore. (+6 more)

### Community 6 - "Pipeline Tests"
Cohesion: 0.22
Nodes (13): _make_pipeline(), Test per HarvestPipeline — tutto mockato, zero connessioni reali., Crea una pipeline con tutti i componenti mockati., test_calls_upsert_on_success(), test_closes_collector(), test_exits_gracefully_when_lock_busy(), test_returns_false_when_all_collectors_return_none(), test_returns_false_when_already_processed() (+5 more)

### Community 7 - "Transformer Tests"
Cohesion: 0.17
Nodes (4): Test per il modulo Transformer — prompts, quality score, daily limit.  NON chiam, TestDailyLimit, TestPrompts, TestQualityScore

### Community 8 - "Guide Synthesizer"
Cohesion: 0.18
Nodes (7): GuideSynthesizer — pipeline Gemini 2.5 Flash: extract_facts → synthesize_guide., Sintetizza una guida markdown dai fatti.  None se quota o formato KO., Pipeline completa: extract_facts → synthesize_guide., Rimuove eventuali ```json ... ``` fences che Gemini potrebbe aggiungere., Reset del contatore se cambia giorno; False se limite superato., Estrae fatti atomici dai testi grezzi via Gemini.  None se quota o parsing KO., _strip_json_fences()

### Community 9 - "PowerPyx Collector"
Cohesion: 0.28
Nodes (7): _extract_title(), _normalize_whitespace(), _parse_url_slug(), PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di, Collassa spazi multipli e normalizza newline., Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici:, Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor

### Community 10 - "PowerPyx Collector Tests"
Cohesion: 0.22
Nodes (2): Test per PowerPyxCollector — extract, URL slug parsing, pulizia HTML., TestExtract

### Community 11 - "Harvester Entry Point"
Cohesion: 0.47
Nodes (5): main(), _parse_args(), Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è, Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo., touch_heartbeat()

### Community 12 - "Settings & Conftest"
Cohesion: 0.33
Nodes (4): BaseSettings, mock_settings(), Settings con valori di test, senza connessioni reali a DB o Redis.     Utile per, Settings

### Community 13 - "Structured Logger"
Cohesion: 0.4
Nodes (4): get_logger(), Restituisce un logger con il campo 'logger' già bindato al nome del modulo., Configura structlog: JSON in prod, console colorata in dev (DEBUG)., setup_logging()

### Community 14 - "Redis Client"
Cohesion: 0.4
Nodes (4): close_redis(), Chiude la connessione Redis. Da chiamare allo shutdown., Verifica la connessione Redis con PING., test_redis_connection()

### Community 15 - "Content Chunker"
Cohesion: 0.5
Nodes (4): chunk_content(), _estimate_tokens(), Chunker — split di una guida in chunk da max_tokens con overlap.  Stima token =, Split markdown guide in chunk con prefisso titolo e overlap tra chunk consecutiv

### Community 16 - "Backend Database"
Cohesion: 0.5
Nodes (0): 

### Community 17 - "Quality Scorer"
Cohesion: 0.5
Nodes (3): calculate_quality_score(), Quality scoring per guide sintetizzate dal Transformer.  Algoritmo Masterplan:, Calcola un quality score in [0.0, 1.0] arrotondato a 2 decimali.

### Community 18 - "Graphify Integration"
Cohesion: 0.5
Nodes (4): GRAPH_REPORT.md, Graphify Knowledge Graph, graphify.watch._rebuild_code, Wiki Index

### Community 19 - "Migration Runner"
Cohesion: 1.0
Nodes (0): 

### Community 20 - "Backend Env Config"
Cohesion: 1.0
Nodes (0): 

### Community 21 - "Backend Redis"
Cohesion: 1.0
Nodes (0): 

### Community 22 - "Prompt Templates"
Cohesion: 1.0
Nodes (1): System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz

### Community 23 - "Backend Entry Point"
Cohesion: 1.0
Nodes (0): 

### Community 24 - "Backend Logger"
Cohesion: 1.0
Nodes (0): 

### Community 25 - "Harvester Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 26 - "Base Rationale Orphan"
Cohesion: 1.0
Nodes (1): Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.

### Community 27 - "Collectors Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 28 - "Config Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 29 - "Discovery Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 30 - "Dedup Rationale Orphan"
Cohesion: 1.0
Nodes (1): Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui

### Community 31 - "Injector Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 32 - "Orchestrator Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 33 - "Transformer Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 34 - "Tests Package Root"
Cohesion: 1.0
Nodes (0): 

### Community 35 - "Scraper Entry Point"
Cohesion: 1.0
Nodes (0): 

## Knowledge Gaps
- **71 isolated node(s):** `BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En`, `Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi`, `Attende fino a quando un token è disponibile per *host*.`, `Calcola SHA-256 di *text* e ritorna l'hash esadecimale.`, `Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi` (+66 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Migration Runner`** (2 nodes): `run-migrations.ts`, `runMigrations()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Backend Env Config`** (2 nodes): `env.ts`, `loadEnv()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Backend Redis`** (2 nodes): `redis.ts`, `testRedisConnection()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Prompt Templates`** (2 nodes): `prompts.py`, `System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Backend Entry Point`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Backend Logger`** (1 nodes): `logger.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Harvester Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Base Rationale Orphan`** (1 nodes): `Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Collectors Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Config Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Discovery Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dedup Rationale Orphan`** (1 nodes): `Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Injector Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Orchestrator Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Transformer Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Tests Package Root`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Scraper Entry Point`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `PowerPyxCollector` connect `Embedding Service` to `Collector Base Class`, `PowerPyx Collector`, `PowerPyx Collector Tests`?**
  _High betweenness centrality (0.263) - this node is a cross-community bridge._
- **Why does `BaseCollector` connect `Collector Base Class` to `PowerPyx Collector`, `Embedding Service`?**
  _High betweenness centrality (0.218) - this node is a cross-community bridge._
- **Why does `HarvestPipeline` connect `Embedding Service` to `Deduplicator`, `IGDB Discovery & Seeds`, `Harvester Entry Point`, `Pipeline Tests`?**
  _High betweenness centrality (0.142) - this node is a cross-community bridge._
- **Are the 29 inferred relationships involving `BaseCollector` (e.g. with `PowerPyxCollector` and `PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di`) actually correct?**
  _`BaseCollector` has 29 INFERRED edges - model-reasoned connections that need verification._
- **Are the 27 inferred relationships involving `Deduplicator` (e.g. with `Upserter` and `Upserter — transazione atomica: game → trophy → guide → harvest_sources.  **FF-N`) actually correct?**
  _`Deduplicator` has 27 INFERRED edges - model-reasoned connections that need verification._
- **Are the 20 inferred relationships involving `HarvestPipeline` (e.g. with `Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è` and `Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.`) actually correct?**
  _`HarvestPipeline` has 20 INFERRED edges - model-reasoned connections that need verification._
- **Are the 24 inferred relationships involving `SeedLoader` (e.g. with `HarvestPipeline` and `HarvestPipeline — orchestratore che connette collector → transformer → injector.`) actually correct?**
  _`SeedLoader` has 24 INFERRED edges - model-reasoned connections that need verification._