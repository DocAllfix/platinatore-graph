# Graph Report - .  (2026-04-14)

## Corpus Check
- 39 files · ~24,120 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 362 nodes · 534 edges · 41 communities detected
- Extraction: 63% EXTRACTED · 37% INFERRED · 0% AMBIGUOUS · INFERRED: 195 edges (avg confidence: 0.5)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]

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
- `BaseCollector` --uses--> `PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di`  [INFERRED]
  harvester\src\collectors\base.py → harvester\src\collectors\powerpyx.py
- `BaseCollector` --uses--> `Collector per guide trofei su powerpyx.com.`  [INFERRED]
  harvester\src\collectors\base.py → harvester\src\collectors\powerpyx.py
- `BaseCollector` --uses--> `Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor`  [INFERRED]
  harvester\src\collectors\base.py → harvester\src\collectors\powerpyx.py
- `BaseCollector` --uses--> `Collassa spazi multipli e normalizza newline.`  [INFERRED]
  harvester\src\collectors\base.py → harvester\src\collectors\powerpyx.py
- `BaseCollector` --uses--> `Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici:`  [INFERRED]
  harvester\src\collectors\base.py → harvester\src\collectors\powerpyx.py

## Communities

### Community 0 - "Community 0"
Cohesion: 0.05
Nodes (41): ABC, BaseCollector, compute_hash(), extract(), PerHostTokenBucket, BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En, Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile., Chiude il client httpx. (+33 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (38): Embedder, Embedder — wrapper Gemini text-embedding-004 con batching e quota giornaliera., Wrapper Gemini embedding con quota e batching automatico., Embedding in batch (max 100/call).  Splitta in sotto-batch se necessario., main(), _parse_args(), Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è, Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo. (+30 more)

### Community 2 - "Community 2"
Cohesion: 0.08
Nodes (23): IGDBDiscovery, IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione: Twit, Chiude il client httpx., Client IGDB per discovery automatica giochi e popolamento catalogo DB., SeedLoader — carica un file JSON seed e popola il catalogo giochi nel DB.  Forma, Legge file JSON seed e upserta giochi nel DB con alias., Legge e valida un file JSON seed. Ritorna la lista di giochi., Upserta tutti i giochi del seed file nel DB.          Per ogni gioco:         - (+15 more)

### Community 3 - "Community 3"
Cohesion: 0.08
Nodes (13): Deduplicator, Deduplicator — evita upsert inutili e protegge guide verificate., Logica di deduplicazione basata su DB lookup., Ritorna la guida esistente (id/confidence/quality) se presente, altrimenti None., True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato)., Test per Injector: chunker, slug, deduplicator — DB mockato, zero connessioni re, Contenuto breve → un solo chunk con prefisso titolo., Contenuto lungo con heading ## → multi chunk. (+5 more)

### Community 4 - "Community 4"
Cohesion: 0.1
Nodes (16): Scarica tutti i giochi IGDB per le piattaforme e li inserisce nel DB.          P, Inserisce alias per il gioco: titolo completo + slug IGDB., Ritorna il token Twitch OAuth, richiedendolo/rinnovandolo se scaduto., Recupera giochi IGDB per le piattaforme indicate.          IGDB usa POST con bod, generate_slug(), _is_peak_hour(), Upserter — transazione atomica: game → trophy → guide → harvest_sources.  **FF-N, Trova il trofeo per game_id + nome; None se trophy_name non è dato. (+8 more)

### Community 5 - "Community 5"
Cohesion: 0.2
Nodes (14): close_pool(), execute(), fetch_all(), fetch_one(), _get_pool(), init_pool(), Verifica la connessione al DB con SELECT NOW(). Logga il risultato., Apre il connection pool. Da chiamare all'avvio dell'orchestratore. (+6 more)

### Community 6 - "Community 6"
Cohesion: 0.22
Nodes (13): _make_pipeline(), Test per HarvestPipeline — tutto mockato, zero connessioni reali., Crea una pipeline con tutti i componenti mockati., test_calls_upsert_on_success(), test_closes_collector(), test_exits_gracefully_when_lock_busy(), test_returns_false_when_all_collectors_return_none(), test_returns_false_when_already_processed() (+5 more)

### Community 7 - "Community 7"
Cohesion: 0.17
Nodes (4): Test per il modulo Transformer — prompts, quality score, daily limit.  NON chiam, TestDailyLimit, TestPrompts, TestQualityScore

### Community 8 - "Community 8"
Cohesion: 0.18
Nodes (7): GuideSynthesizer — pipeline Gemini 2.5 Flash: extract_facts → synthesize_guide., Sintetizza una guida markdown dai fatti.  None se quota o formato KO., Pipeline completa: extract_facts → synthesize_guide., Rimuove eventuali ```json ... ``` fences che Gemini potrebbe aggiungere., Reset del contatore se cambia giorno; False se limite superato., Estrae fatti atomici dai testi grezzi via Gemini.  None se quota o parsing KO., _strip_json_fences()

### Community 9 - "Community 9"
Cohesion: 0.27
Nodes (11): Harvester - Infinite Ingestion Engine, Backend API (Node.js + TypeScript + Express), Google Gemini 2.5 Flash (LLM), Google Embedding API (768 dim), HNSW + Reciprocal Rank Fusion (RRF) Retrieval, Il Platinatore AI â€” Gaming Guide Chatbot, PgBouncer (Connection Pooling), PostgreSQL + pgvector (Semantic Search) (+3 more)

### Community 10 - "Community 10"
Cohesion: 0.28
Nodes (7): _extract_title(), _normalize_whitespace(), _parse_url_slug(), PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di, Collassa spazi multipli e normalizza newline., Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici:, Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor

### Community 11 - "Community 11"
Cohesion: 0.22
Nodes (2): Test per PowerPyxCollector — extract, URL slug parsing, pulizia HTML., TestExtract

### Community 12 - "Community 12"
Cohesion: 0.33
Nodes (4): BaseSettings, mock_settings(), Settings con valori di test, senza connessioni reali a DB o Redis.     Utile per, Settings

### Community 13 - "Community 13"
Cohesion: 0.4
Nodes (4): get_logger(), Restituisce un logger con il campo 'logger' già bindato al nome del modulo., Configura structlog: JSON in prod, console colorata in dev (DEBUG)., setup_logging()

### Community 14 - "Community 14"
Cohesion: 0.4
Nodes (4): close_redis(), Chiude la connessione Redis. Da chiamare allo shutdown., Verifica la connessione Redis con PING., test_redis_connection()

### Community 15 - "Community 15"
Cohesion: 0.5
Nodes (4): chunk_content(), _estimate_tokens(), Chunker — split di una guida in chunk da max_tokens con overlap.  Stima token =, Split markdown guide in chunk con prefisso titolo e overlap tra chunk consecutiv

### Community 16 - "Community 16"
Cohesion: 0.5
Nodes (0): 

### Community 17 - "Community 17"
Cohesion: 0.5
Nodes (3): calculate_quality_score(), Quality scoring per guide sintetizzate dal Transformer.  Algoritmo Masterplan:, Calcola un quality score in [0.0, 1.0] arrotondato a 2 decimali.

### Community 18 - "Community 18"
Cohesion: 0.5
Nodes (4): Rule: Routes -> Services -> Models Architecture, Rule: Always Connect via PgBouncer (port 6432), CLAUDE.md Project Rules, Rule: Zod Input Validation + Prepared Statements

### Community 19 - "Community 19"
Cohesion: 1.0
Nodes (0): 

### Community 20 - "Community 20"
Cohesion: 1.0
Nodes (0): 

### Community 21 - "Community 21"
Cohesion: 1.0
Nodes (0): 

### Community 22 - "Community 22"
Cohesion: 1.0
Nodes (1): System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz

### Community 23 - "Community 23"
Cohesion: 1.0
Nodes (2): RAG Pipeline Architecture (Hybrid HNSW + RRF), Technology Stack Overview

### Community 24 - "Community 24"
Cohesion: 1.0
Nodes (0): 

### Community 25 - "Community 25"
Cohesion: 1.0
Nodes (0): 

### Community 26 - "Community 26"
Cohesion: 1.0
Nodes (0): 

### Community 27 - "Community 27"
Cohesion: 1.0
Nodes (1): Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.

### Community 28 - "Community 28"
Cohesion: 1.0
Nodes (0): 

### Community 29 - "Community 29"
Cohesion: 1.0
Nodes (0): 

### Community 30 - "Community 30"
Cohesion: 1.0
Nodes (0): 

### Community 31 - "Community 31"
Cohesion: 1.0
Nodes (1): Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui

### Community 32 - "Community 32"
Cohesion: 1.0
Nodes (0): 

### Community 33 - "Community 33"
Cohesion: 1.0
Nodes (0): 

### Community 34 - "Community 34"
Cohesion: 1.0
Nodes (0): 

### Community 35 - "Community 35"
Cohesion: 1.0
Nodes (0): 

### Community 36 - "Community 36"
Cohesion: 1.0
Nodes (0): 

### Community 37 - "Community 37"
Cohesion: 1.0
Nodes (1): Rationale: Migrations Use Direct Postgres (DDL + PgBouncer incompatibility)

### Community 38 - "Community 38"
Cohesion: 1.0
Nodes (1): Il Platinatore AI â€” Gaming Guide Chatbot

### Community 39 - "Community 39"
Cohesion: 1.0
Nodes (1): test

### Community 40 - "Community 40"
Cohesion: 1.0
Nodes (1): Graphify Knowledge Graph Instructions

## Knowledge Gaps
- **75 isolated node(s):** `BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En`, `Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi`, `Attende fino a quando un token è disponibile per *host*.`, `Calcola SHA-256 di *text* e ritorna l'hash esadecimale.`, `Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi` (+70 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 19`** (2 nodes): `run-migrations.ts`, `runMigrations()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 20`** (2 nodes): `env.ts`, `loadEnv()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 21`** (2 nodes): `redis.ts`, `testRedisConnection()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 22`** (2 nodes): `prompts.py`, `System prompt per Gemini: estrazione fatti + sintesi guide.  NON modificare senz`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 23`** (2 nodes): `RAG Pipeline Architecture (Hybrid HNSW + RRF)`, `Technology Stack Overview`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 24`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 25`** (1 nodes): `logger.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 26`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 27`** (1 nodes): `Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 28`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 29`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 30`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 31`** (1 nodes): `Decide se sovrascrivere una guida esistente.          - None → upsert (nuova gui`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 32`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 33`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 34`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 35`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 36`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 37`** (1 nodes): `Rationale: Migrations Use Direct Postgres (DDL + PgBouncer incompatibility)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 38`** (1 nodes): `Il Platinatore AI â€” Gaming Guide Chatbot`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 39`** (1 nodes): `test`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 40`** (1 nodes): `Graphify Knowledge Graph Instructions`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `PowerPyxCollector` connect `Community 1` to `Community 0`, `Community 10`, `Community 11`?**
  _High betweenness centrality (0.281) - this node is a cross-community bridge._
- **Why does `BaseCollector` connect `Community 0` to `Community 1`, `Community 10`?**
  _High betweenness centrality (0.232) - this node is a cross-community bridge._
- **Why does `HarvestPipeline` connect `Community 1` to `Community 2`, `Community 3`, `Community 4`, `Community 6`?**
  _High betweenness centrality (0.152) - this node is a cross-community bridge._
- **Are the 29 inferred relationships involving `BaseCollector` (e.g. with `PowerPyxCollector` and `PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di`) actually correct?**
  _`BaseCollector` has 29 INFERRED edges - model-reasoned connections that need verification._
- **Are the 27 inferred relationships involving `Deduplicator` (e.g. with `Upserter` and `Upserter — transazione atomica: game → trophy → guide → harvest_sources.  **FF-N`) actually correct?**
  _`Deduplicator` has 27 INFERRED edges - model-reasoned connections that need verification._
- **Are the 20 inferred relationships involving `HarvestPipeline` (e.g. with `Entry point dell'harvester — avvia la pipeline in modalità seed o update.  Non è` and `Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.`) actually correct?**
  _`HarvestPipeline` has 20 INFERRED edges - model-reasoned connections that need verification._
- **Are the 24 inferred relationships involving `SeedLoader` (e.g. with `HarvestPipeline` and `HarvestPipeline — orchestratore che connette collector → transformer → injector.`) actually correct?**
  _`SeedLoader` has 24 INFERRED edges - model-reasoned connections that need verification._