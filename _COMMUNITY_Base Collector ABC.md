---
type: community
cohesion: 0.11
members: 27
---

# Base Collector ABC

**Cohesion:** 0.11 - loosely connected
**Members:** 27 nodes

## Members
- [[.__init__()_1]] - code - harvester\src\collectors\base.py
- [[.__init__()]] - code - harvester\src\collectors\base.py
- [[._is_allowed()]] - code - harvester\src\collectors\base.py
- [[._load_robots()]] - code - harvester\src\collectors\base.py
- [[._respect_delay()]] - code - harvester\src\collectors\base.py
- [[.acquire()]] - code - harvester\src\collectors\base.py
- [[.close()]] - code - harvester\src\collectors\base.py
- [[.collect()]] - code - harvester\src\collectors\base.py
- [[.fetch()]] - code - harvester\src\collectors\base.py
- [[ABC]] - code
- [[Aspetta almeno settings.scrape_delay_seconds tra richieste allo stesso dominio.]] - rationale - harvester\src\collectors\base.py
- [[Attende fino a quando un token è disponibile per host.]] - rationale - harvester\src\collectors\base.py
- [[BaseCollector]] - code - harvester\src\collectors\base.py
- [[BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En]] - rationale - harvester\src\collectors\base.py
- [[Calcola SHA-256 di text e ritorna l'hash esadecimale.]] - rationale - harvester\src\collectors\base.py
- [[Chiude il client httpx.]] - rationale - harvester\src\collectors\base.py
- [[Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi]] - rationale - harvester\src\collectors\base.py
- [[PerHostTokenBucket]] - code - harvester\src\collectors\base.py
- [[Pipeline completa fetch → extract.  Ritorna i dati strutturati o None.]] - rationale - harvester\src\collectors\base.py
- [[Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi]] - rationale - harvester\src\collectors\base.py
- [[Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile.]] - rationale - harvester\src\collectors\base.py
- [[Scarica una pagina rispettando rate limit globale e per-host.          Ritorna i]] - rationale - harvester\src\collectors\base.py
- [[Verifica se url è permesso da robots.txt.  Fail-open se non caricato.]] - rationale - harvester\src\collectors\base.py
- [[base.py]] - code - harvester\src\collectors\base.py
- [[base.py_1]] - code - il-platinatore-ai\harvester\src\collectors\base.py
- [[compute_hash()]] - code - harvester\src\collectors\base.py
- [[extract()]] - code - harvester\src\collectors\base.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Base_Collector_ABC
SORT file.name ASC
```
