---
type: community
cohesion: 0.05
members: 69
---

# Collector Base Class

**Cohesion:** 0.05 - loosely connected
**Members:** 69 nodes

## Members
- [[.__init__()_1]] - code - harvester\src\collectors\base.py
- [[.__init__()]] - code - harvester\src\collectors\base.py
- [[._is_allowed()]] - code - harvester\src\collectors\base.py
- [[._load_robots()]] - code - harvester\src\collectors\base.py
- [[._respect_delay()]] - code - harvester\src\collectors\base.py
- [[.acquire()]] - code - harvester\src\collectors\base.py
- [[.close()]] - code - harvester\src\collectors\base.py
- [[.collect()]] - code - harvester\src\collectors\base.py
- [[.extract()_1]] - code - harvester\tests\test_base_collector.py
- [[.fetch()]] - code - harvester\src\collectors\base.py
- [[.test_deterministic()]] - code - harvester\tests\test_base_collector.py
- [[.test_different_input_different_hash()]] - code - harvester\tests\test_base_collector.py
- [[.test_hex_format()]] - code - harvester\tests\test_base_collector.py
- [[.test_user_agent_from_settings()]] - code - harvester\tests\test_base_collector.py
- [[ABC]] - code
- [[Aspetta almeno settings.scrape_delay_seconds tra richieste allo stesso dominio.]] - rationale - harvester\src\collectors\base.py
- [[Attende fino a quando un token è disponibile per host.]] - rationale - harvester\src\collectors\base.py
- [[BaseCollector]] - code - harvester\src\collectors\base.py
- [[BaseCollector_1]] - code
- [[BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En]] - rationale - harvester\src\collectors\base.py
- [[Calcola SHA-256 di text e ritorna l'hash esadecimale.]] - rationale - harvester\src\collectors\base.py
- [[Chiude il client httpx.]] - rationale - harvester\src\collectors\base.py
- [[Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi]] - rationale - harvester\src\collectors\base.py
- [[Il client httpx usa lo User-Agent configurato in settings.]] - rationale - harvester\tests\test_base_collector.py
- [[Input diversi producono hash diversi.]] - rationale - harvester\tests\test_base_collector.py
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - rationale - harvester\tests\test_base_collector.py
- [[La prima acquire per un host non deve aspettare.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima fetch() triggera _load_robots(); le successive no.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima richiesta (last_request_time=0) non deve attendere.]] - rationale - harvester\tests\test_base_collector.py
- [[La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).]] - rationale - harvester\tests\test_base_collector.py
- [[Lo stesso input produce sempre lo stesso hash.]] - rationale - harvester\tests\test_base_collector.py
- [[PerHostTokenBucket]] - code - harvester\src\collectors\base.py
- [[Pipeline completa fetch → extract.  Ritorna i dati strutturati o None.]] - rationale - harvester\src\collectors\base.py
- [[Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi]] - rationale - harvester\src\collectors\base.py
- [[Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile.]] - rationale - harvester\src\collectors\base.py
- [[Scarica una pagina rispettando rate limit globale e per-host.          Ritorna i]] - rationale - harvester\src\collectors\base.py
- [[Se l'ultima richiesta è recente, _respect_delay aspetta la differenza.]] - rationale - harvester\tests\test_base_collector.py
- [[Test per BaseCollector — rate limiting, robots.txt, fetch, hash.]] - rationale - harvester\tests\test_base_collector.py
- [[TestComputeHash]] - code - harvester\tests\test_base_collector.py
- [[TestFetch]] - code - harvester\tests\test_base_collector.py
- [[TestPerHostTokenBucket]] - code - harvester\tests\test_base_collector.py
- [[TestRespectDelay]] - code - harvester\tests\test_base_collector.py
- [[TestRobotsTxt]] - code - harvester\tests\test_base_collector.py
- [[TestUserAgent]] - code - harvester\tests\test_base_collector.py
- [[Verifica se url è permesso da robots.txt.  Fail-open se non caricato.]] - rationale - harvester\src\collectors\base.py
- [[_StubCollector]] - code - harvester\tests\test_base_collector.py
- [[_is_allowed ritorna True se robots.txt non è stato caricato (fail-open).]] - rationale - harvester\tests\test_base_collector.py
- [[base.py]] - code - harvester\src\collectors\base.py
- [[collector()]] - code - harvester\tests\test_base_collector.py
- [[compute_hash()]] - code - harvester\src\collectors\base.py
- [[extract()]] - code - harvester\src\collectors\base.py
- [[fetch() ritorna None se il server risponde 403.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se il server risponde 429 (rate limited).]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se robots.txt vieta l'URL.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None su timeout.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna il body HTML su status 200.]] - rationale - harvester\tests\test_base_collector.py
- [[semaphore()]] - code - harvester\tests\test_base_collector.py
- [[test_allowed_when_no_robots()]] - code - harvester\tests\test_base_collector.py
- [[test_base_collector.py]] - code - harvester\tests\test_base_collector.py
- [[test_first_acquire_no_wait()]] - code - harvester\tests\test_base_collector.py
- [[test_lazy_load_robots_on_first_fetch()]] - code - harvester\tests\test_base_collector.py
- [[test_no_wait_first_request()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_html_on_200()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_403()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_429()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_timeout()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_when_disallowed()]] - code - harvester\tests\test_base_collector.py
- [[test_second_acquire_waits()]] - code - harvester\tests\test_base_collector.py
- [[test_waits_correct_time()]] - code - harvester\tests\test_base_collector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Collector_Base_Class
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_PowerPyx Collector]]
- 3 edges to [[_COMMUNITY_Embedding Service]]

## Top bridge nodes
- [[BaseCollector]] - degree 39, connects to 2 communities
- [[BaseCollector_1]] - degree 2, connects to 1 community