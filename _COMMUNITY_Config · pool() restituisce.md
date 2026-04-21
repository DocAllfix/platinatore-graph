---
type: community
cohesion: 0.20
members: 15
---

# Config · pool() restituisce

**Cohesion:** 0.20 - loosely connected
**Members:** 15 nodes

## Members
- [[Apre il connection pool. Da chiamare all'avvio dell'orchestratore.]] - rationale - harvester\src\config\db.py
- [[Chiude il connection pool. Da chiamare allo shutdown.]] - rationale - harvester\src\config\db.py
- [[Esegue una query e restituisce la prima riga come dict, o None se vuota.]] - rationale - harvester\src\config\db.py
- [[Esegue una query e restituisce tutte le righe come lista di dict.]] - rationale - harvester\src\config\db.py
- [[Esegue una query senza risultati (INSERT, UPDATE, DELETE).]] - rationale - harvester\src\config\db.py
- [[Restituisce il pool, inizializzandolo se necessario.]] - rationale - harvester\src\config\db.py
- [[Verifica la connessione al DB con SELECT NOW(). Logga il risultato.]] - rationale - harvester\src\config\db.py
- [[_get_pool()]] - code - harvester\src\config\db.py
- [[close_pool()]] - code - harvester\src\config\db.py
- [[db.py]] - code - harvester\src\config\db.py
- [[execute()]] - code - harvester\src\config\db.py
- [[fetch_all()]] - code - harvester\src\config\db.py
- [[fetch_one()]] - code - harvester\src\config\db.py
- [[init_pool()]] - code - harvester\src\config\db.py
- [[test_connection()]] - code - harvester\src\config\db.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Config_·_pool()_restituisce
SORT file.name ASC
```
