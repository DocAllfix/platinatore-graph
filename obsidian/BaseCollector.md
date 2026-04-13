---
source_file: "harvester\src\collectors\base.py"
type: "code"
community: "Collector Base Class"
location: "L70"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Collector_Base_Class
---

# BaseCollector

## Connections
- [[.__init__()_1]] - `method` [EXTRACTED]
- [[._is_allowed()]] - `method` [EXTRACTED]
- [[._load_robots()]] - `method` [EXTRACTED]
- [[._respect_delay()]] - `method` [EXTRACTED]
- [[.close()]] - `method` [EXTRACTED]
- [[.collect()]] - `method` [EXTRACTED]
- [[.fetch()]] - `method` [EXTRACTED]
- [[ABC]] - `inherits` [EXTRACTED]
- [[Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi]] - `rationale_for` [EXTRACTED]
- [[Collassa spazi multipli e normalizza newline.]] - `uses` [INFERRED]
- [[Collector per guide trofei su powerpyx.com.]] - `uses` [INFERRED]
- [[Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici]] - `uses` [INFERRED]
- [[Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor]] - `uses` [INFERRED]
- [[Il client httpx usa lo User-Agent configurato in settings.]] - `uses` [INFERRED]
- [[Input diversi producono hash diversi.]] - `uses` [INFERRED]
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - `uses` [INFERRED]
- [[La prima acquire per un host non deve aspettare.]] - `uses` [INFERRED]
- [[La prima fetch() triggera _load_robots(); le successive no.]] - `uses` [INFERRED]
- [[La prima richiesta (last_request_time=0) non deve attendere.]] - `uses` [INFERRED]
- [[La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).]] - `uses` [INFERRED]
- [[Lo stesso input produce sempre lo stesso hash.]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di]] - `uses` [INFERRED]
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

#graphify/code #graphify/INFERRED #community/Collector_Base_Class