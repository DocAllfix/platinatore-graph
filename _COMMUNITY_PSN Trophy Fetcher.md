---
type: community
cohesion: 0.13
members: 20
---

# PSN Trophy Fetcher

**Cohesion:** 0.13 - loosely connected
**Members:** 20 nodes

## Members
- [[.__init__()_7]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[._fetch_lang()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[._resolve_comm_id()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.authenticate()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.close()_2]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.fetch_and_store_for_game()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.fetch_game_trophies()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.upsert_trophies()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[Autentica con PSN via NPSSO. Cacha il token in Redis.          Ritorna False e l]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Cerca il psn_communication_id per un gioco.          Strategia         1. games]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Chiude il client httpx. Da chiamare allo shutdown.]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Fetch + store per un singolo gioco. Entry point ad alto livello.          Richie]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Fetcha nomi trofei per una singola lingua.          Ritorna (lang, {trophy_id {]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Fetcha tutti i trofei del gioco in 10 lingue in parallelo.          Ritorna list]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Inserisce o aggiorna i trofei nel DB con nomi multilingua.          ON CONFLICT]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[PsnTrophyFetcher]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[PsnTrophyFetcher — recupera nomi ufficiali PSN trofei in 10 lingue.  Autenticazi]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Recupera trofei ufficiali PSN con nomi multilingua e li salva nel DB.]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[psn_trophy_fetcher.py]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[psn_trophy_fetcher.py_1]] - code - il-platinatore-ai\harvester\src\discovery\psn_trophy_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PSN_Trophy_Fetcher
SORT file.name ASC
```
