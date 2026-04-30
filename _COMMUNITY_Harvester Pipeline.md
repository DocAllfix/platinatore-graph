---
type: community
cohesion: 0.08
members: 38
---

# Harvester Pipeline

**Cohesion:** 0.08 - loosely connected
**Members:** 38 nodes

## Members
- [[.__init__()_5]] - code - harvester\src\discovery\igdb.py
- [[._get_token()]] - code - harvester\src\discovery\igdb.py
- [[._ingest_game()]] - code - harvester\src\discovery\igdb.py
- [[._insert_aliases()]] - code - harvester\src\discovery\igdb.py
- [[._query()]] - code - harvester\src\discovery\igdb.py
- [[.check_released_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.close()_1]] - code - harvester\src\discovery\igdb.py
- [[.discover_all_games()]] - code - harvester\src\discovery\igdb.py
- [[.discover_popular_and_new()]] - code - harvester\src\discovery\igdb.py
- [[.discover_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_game_details()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_games()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_new_releases()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_popular()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.resolve_steam_appids()]] - code - harvester\src\discovery\igdb.py
- [[Chiude il client httpx._1]] - rationale - harvester\src\discovery\igdb.py
- [[Client IGDB per discovery automatica giochi e popolamento catalogo DB.]] - rationale - harvester\src\discovery\igdb.py
- [[Controlla se giochi in upcoming_games sono stati rilasciati.          Per ogni u]] - rationale - harvester\src\discovery\igdb.py
- [[Esegue una query POST su un endpoint IGDB e ritorna la risposta JSON.]] - rationale - harvester\src\discovery\igdb.py
- [[IGDBDiscovery]] - code - harvester\src\discovery\igdb.py
- [[IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione Twit]] - rationale - harvester\src\discovery\igdb.py
- [[Inserisce alias per il gioco titolo completo + slug IGDB.]] - rationale - harvester\src\discovery\igdb.py
- [[Inserisce un gioco da dati IGDB se non già presente.          Salva igdb_id sia]] - rationale - harvester\src\discovery\igdb.py
- [[Recupera giochi IGDB per le piattaforme indicate.          IGDB usa POST con bod]] - rationale - harvester\src\discovery\igdb.py
- [[Recupera giochi upcoming con alto hypefollowing.          status=2 = alpha, 3]] - rationale - harvester\src\discovery\igdb.py
- [[Recupera giochi usciti negli ultimi N giorni per piattaforma.          Usa l'end]] - rationale - harvester\src\discovery\igdb.py
- [[Recupera i dettagli dei giochi per una lista di IGDB IDs.]] - rationale - harvester\src\discovery\igdb.py
- [[Recupera i giochi più giocati via popularity_primitives.          popularity_typ]] - rationale - harvester\src\discovery\igdb.py
- [[Risolve steam_appid per giochi con igdb_id ma senza steam_appid.          Usa l']] - rationale - harvester\src\discovery\igdb.py
- [[Ritorna il token Twitch OAuth, richiedendolorinnovandolo se scaduto.]] - rationale - harvester\src\discovery\igdb.py
- [[Scarica tutti i giochi IGDB per le piattaforme e li inserisce nel DB.          P]] - rationale - harvester\src\discovery\igdb.py
- [[Scopre giochi popolari e nuove uscite, li inserisce in games.          Ritorna s]] - rationale - harvester\src\discovery\igdb.py
- [[Scopre giochi upcoming e li salva in upcoming_games.          Non li mette in ga]] - rationale - harvester\src\discovery\igdb.py
- [[_accept_game()]] - code - harvester\src\discovery\igdb.py
- [[_map_platform_ids()]] - code - harvester\src\discovery\igdb.py
- [[igdb.py]] - code - harvester\src\discovery\igdb.py
- [[igdb.py_1]] - code - il-platinatore-ai\harvester\src\discovery\igdb.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Harvester_Pipeline
SORT file.name ASC
```
