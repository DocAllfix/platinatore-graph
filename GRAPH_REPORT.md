# Graph Report - .  (2026-04-13)

## Corpus Check
- 22 files · ~15,091 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 143 nodes · 169 edges · 31 communities detected
- Extraction: 70% EXTRACTED · 30% INFERRED · 0% AMBIGUOUS · INFERRED: 50 edges (avg confidence: 0.52)
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

## God Nodes (most connected - your core abstractions)
1. `BaseCollector` - 33 edges
2. `PerHostTokenBucket` - 27 edges
3. `Il Platinatore AI â€” Gaming Guide Chatbot` - 9 edges
4. `_get_pool()` - 6 edges
5. `_StubCollector` - 6 edges
6. `TestComputeHash` - 6 edges
7. `execute()` - 5 edges
8. `fetch_one()` - 5 edges
9. `RAG Pipeline (Hybrid HNSW + RRF)` - 5 edges
10. `fetch_all()` - 4 edges

## Surprising Connections (you probably didn't know these)
- `_StubCollector` --uses--> `PerHostTokenBucket`  [INFERRED]
  harvester\tests\test_base_collector.py → harvester\src\collectors\base.py
- `Se l'ultima richiesta è recente, _respect_delay aspetta la differenza.` --uses--> `PerHostTokenBucket`  [INFERRED]
  harvester\tests\test_base_collector.py → harvester\src\collectors\base.py
- `La prima richiesta (last_request_time=0) non deve attendere.` --uses--> `PerHostTokenBucket`  [INFERRED]
  harvester\tests\test_base_collector.py → harvester\src\collectors\base.py
- `fetch() ritorna None se il server risponde 403.` --uses--> `PerHostTokenBucket`  [INFERRED]
  harvester\tests\test_base_collector.py → harvester\src\collectors\base.py
- `fetch() ritorna None se il server risponde 429 (rate limited).` --uses--> `PerHostTokenBucket`  [INFERRED]
  harvester\tests\test_base_collector.py → harvester\src\collectors\base.py

## Communities

### Community 0 - "Community 0"
Cohesion: 0.1
Nodes (27): BaseCollector, PerHostTokenBucket, Chiude il client httpx., Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi, Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi, Test per BaseCollector — rate limiting, robots.txt, fetch, hash., fetch() ritorna None se il server risponde 403., fetch() ritorna None se il server risponde 429 (rate limited). (+19 more)

### Community 1 - "Community 1"
Cohesion: 0.12
Nodes (3): BaseCollector, collector(), _StubCollector

### Community 2 - "Community 2"
Cohesion: 0.2
Nodes (14): close_pool(), execute(), fetch_all(), fetch_one(), _get_pool(), init_pool(), Verifica la connessione al DB con SELECT NOW(). Logga il risultato., Apre il connection pool. Da chiamare all'avvio dell'orchestratore. (+6 more)

### Community 3 - "Community 3"
Cohesion: 0.27
Nodes (11): Harvester - Infinite Ingestion Engine, Backend API (Node.js + TypeScript + Express), Google Gemini 2.5 Flash (LLM), Google Embedding API (768 dim), HNSW + Reciprocal Rank Fusion (RRF) Retrieval, Il Platinatore AI â€” Gaming Guide Chatbot, PgBouncer (Connection Pooling), PostgreSQL + pgvector (Semantic Search) (+3 more)

### Community 4 - "Community 4"
Cohesion: 0.2
Nodes (5): Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile., Aspetta almeno settings.scrape_delay_seconds tra richieste allo stesso dominio., Verifica se *url* è permesso da robots.txt.  Fail-open se non caricato., Scarica una pagina rispettando rate limit globale e per-host.          Ritorna i, Attende fino a quando un token è disponibile per *host*.

### Community 5 - "Community 5"
Cohesion: 0.25
Nodes (6): ABC, compute_hash(), extract(), BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En, Pipeline completa: fetch → extract.  Ritorna i dati strutturati o None., Calcola SHA-256 di *text* e ritorna l'hash esadecimale.

### Community 6 - "Community 6"
Cohesion: 0.33
Nodes (4): BaseSettings, mock_settings(), Settings con valori di test, senza connessioni reali a DB o Redis.     Utile per, Settings

### Community 7 - "Community 7"
Cohesion: 0.4
Nodes (4): get_logger(), Restituisce un logger con il campo 'logger' già bindato al nome del modulo., Configura structlog: JSON in prod, console colorata in dev (DEBUG)., setup_logging()

### Community 8 - "Community 8"
Cohesion: 0.4
Nodes (4): close_redis(), Chiude la connessione Redis. Da chiamare allo shutdown., Verifica la connessione Redis con PING., test_redis_connection()

### Community 9 - "Community 9"
Cohesion: 0.5
Nodes (0): 

### Community 10 - "Community 10"
Cohesion: 0.5
Nodes (4): Rule: Routes -> Services -> Models Architecture, Rule: Always Connect via PgBouncer (port 6432), CLAUDE.md Project Rules, Rule: Zod Input Validation + Prepared Statements

### Community 11 - "Community 11"
Cohesion: 1.0
Nodes (0): 

### Community 12 - "Community 12"
Cohesion: 1.0
Nodes (0): 

### Community 13 - "Community 13"
Cohesion: 1.0
Nodes (0): 

### Community 14 - "Community 14"
Cohesion: 1.0
Nodes (2): RAG Pipeline Architecture (Hybrid HNSW + RRF), Technology Stack Overview

### Community 15 - "Community 15"
Cohesion: 1.0
Nodes (0): 

### Community 16 - "Community 16"
Cohesion: 1.0
Nodes (0): 

### Community 17 - "Community 17"
Cohesion: 1.0
Nodes (0): 

### Community 18 - "Community 18"
Cohesion: 1.0
Nodes (1): Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.

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
Nodes (0): 

### Community 23 - "Community 23"
Cohesion: 1.0
Nodes (0): 

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
Nodes (1): Rationale: Migrations Use Direct Postgres (DDL + PgBouncer incompatibility)

### Community 28 - "Community 28"
Cohesion: 1.0
Nodes (1): Il Platinatore AI â€” Gaming Guide Chatbot

### Community 29 - "Community 29"
Cohesion: 1.0
Nodes (1): test

### Community 30 - "Community 30"
Cohesion: 1.0
Nodes (1): Graphify Knowledge Graph Instructions

## Knowledge Gaps
- **36 isolated node(s):** `BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En`, `Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi`, `Attende fino a quando un token è disponibile per *host*.`, `Calcola SHA-256 di *text* e ritorna l'hash esadecimale.`, `Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi` (+31 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 11`** (2 nodes): `run-migrations.ts`, `runMigrations()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 12`** (2 nodes): `env.ts`, `loadEnv()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 13`** (2 nodes): `redis.ts`, `testRedisConnection()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 14`** (2 nodes): `RAG Pipeline Architecture (Hybrid HNSW + RRF)`, `Technology Stack Overview`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 15`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 16`** (1 nodes): `logger.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 17`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 18`** (1 nodes): `Estrae dati strutturati dall'HTML.  Da implementare nelle sottoclassi.`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 19`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 20`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 21`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 22`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 23`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 24`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 25`** (1 nodes): `__init__.py`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 26`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 27`** (1 nodes): `Rationale: Migrations Use Direct Postgres (DDL + PgBouncer incompatibility)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 28`** (1 nodes): `Il Platinatore AI â€” Gaming Guide Chatbot`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 29`** (1 nodes): `test`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 30`** (1 nodes): `Graphify Knowledge Graph Instructions`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `BaseCollector` connect `Community 0` to `Community 1`, `Community 4`, `Community 5`?**
  _High betweenness centrality (0.122) - this node is a cross-community bridge._
- **Why does `PerHostTokenBucket` connect `Community 0` to `Community 1`, `Community 4`, `Community 5`?**
  _High betweenness centrality (0.062) - this node is a cross-community bridge._
- **Why does `_StubCollector` connect `Community 1` to `Community 0`?**
  _High betweenness centrality (0.024) - this node is a cross-community bridge._
- **Are the 23 inferred relationships involving `BaseCollector` (e.g. with `_StubCollector` and `TestComputeHash`) actually correct?**
  _`BaseCollector` has 23 INFERRED edges - model-reasoned connections that need verification._
- **Are the 23 inferred relationships involving `PerHostTokenBucket` (e.g. with `_StubCollector` and `TestComputeHash`) actually correct?**
  _`PerHostTokenBucket` has 23 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `_StubCollector` (e.g. with `BaseCollector` and `PerHostTokenBucket`) actually correct?**
  _`_StubCollector` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En`, `Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi`, `Attende fino a quando un token è disponibile per *host*.` to the rest of the system?**
  _36 weakly-connected nodes found - possible documentation gaps or missing edges._