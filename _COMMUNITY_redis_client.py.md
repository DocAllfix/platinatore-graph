---
type: community
cohesion: 0.40
members: 5
---

# redis_client.py

**Cohesion:** 0.40 - moderately connected
**Members:** 5 nodes

## Members
- [[Chiude la connessione Redis. Da chiamare allo shutdown.]] - rationale - harvester\src\config\redis_client.py
- [[Verifica la connessione Redis con PING.]] - rationale - harvester\src\config\redis_client.py
- [[close_redis()]] - code - harvester\src\config\redis_client.py
- [[redis_client.py]] - code - harvester\src\config\redis_client.py
- [[test_redis_connection()]] - code - harvester\src\config\redis_client.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/redis_client.py
SORT file.name ASC
```
