---
source_file: "harvester\src\collectors\base.py"
type: "code"
community: "Collectors · per collector"
location: "L29"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Collectors_·_per_collector
---

# PerHostTokenBucket

## Connections
- [[.__init__()]] - `method` [EXTRACTED]
- [[.acquire()]] - `method` [EXTRACTED]
- [[Il client httpx usa lo User-Agent configurato in settings.]] - `uses` [INFERRED]
- [[Input diversi producono hash diversi.]] - `uses` [INFERRED]
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - `uses` [INFERRED]
- [[La prima acquire per un host non deve aspettare.]] - `uses` [INFERRED]
- [[La prima fetch() triggera _load_robots(); le successive no.]] - `uses` [INFERRED]
- [[La prima richiesta (last_request_time=0) non deve attendere.]] - `uses` [INFERRED]
- [[La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).]] - `uses` [INFERRED]
- [[Lo stesso input produce sempre lo stesso hash.]] - `uses` [INFERRED]
- [[Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi]] - `rationale_for` [EXTRACTED]
- [[Se l'ultima richiesta è recente, _respect_delay aspetta la differenza.]] - `uses` [INFERRED]
- [[Test per BaseCollector — rate limiting, robots.txt, fetch, hash.]] - `uses` [INFERRED]
- [[TestComputeHash]] - `uses` [INFERRED]
- [[TestFetch]] - `uses` [INFERRED]
- [[TestPerHostTokenBucket]] - `uses` [INFERRED]
- [[TestRespectDelay]] - `uses` [INFERRED]
- [[TestRobotsTxt]] - `uses` [INFERRED]
- [[TestUserAgent]] - `uses` [INFERRED]
- [[_StubCollector]] - `uses` [INFERRED]
- [[_is_allowed ritorna True se robots.txt non è stato caricato (fail-open).]] - `uses` [INFERRED]
- [[base.py]] - `contains` [EXTRACTED]
- [[fetch() ritorna None se il server risponde 403.]] - `uses` [INFERRED]
- [[fetch() ritorna None se il server risponde 429 (rate limited).]] - `uses` [INFERRED]
- [[fetch() ritorna None se robots.txt vieta l'URL.]] - `uses` [INFERRED]
- [[fetch() ritorna None su timeout.]] - `uses` [INFERRED]
- [[fetch() ritorna il body HTML su status 200.]] - `uses` [INFERRED]

#graphify/code #graphify/INFERRED #community/Collectors_·_per_collector