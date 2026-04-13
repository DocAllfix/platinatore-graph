---
type: community
cohesion: 0.06
members: 53
---

# IGDB Discovery & Seeds

**Cohesion:** 0.06 - loosely connected
**Members:** 53 nodes

## Members
- [[.__init__()_2]] - code - harvester\src\discovery\igdb.py
- [[.__init__()_5]] - code - harvester\src\injector\upserter.py
- [[._get_token()]] - code - harvester\src\discovery\igdb.py
- [[._insert_aliases()]] - code - harvester\src\discovery\igdb.py
- [[.close()_1]] - code - harvester\src\discovery\igdb.py
- [[.discover_all_games()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_games()]] - code - harvester\src\discovery\igdb.py
- [[.find_or_create_trophy()]] - code - harvester\src\injector\upserter.py
- [[.load_seed_file()]] - code - harvester\src\discovery\seed_loader.py
- [[.seed_database()]] - code - harvester\src\discovery\seed_loader.py
- [[.test_contains_at_least_20_games()]] - code - harvester\tests\test_discovery.py
- [[.test_every_game_has_required_fields()]] - code - harvester\tests\test_discovery.py
- [[.test_parses_valid_json()]] - code - harvester\tests\test_discovery.py
- [[.test_priority_values_are_valid()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_missing_file()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_non_list_json()]] - code - harvester\tests\test_discovery.py
- [[.test_seed_file_exists()]] - code - harvester\tests\test_discovery.py
- [[Chiude il client httpx._1]] - rationale - harvester\src\discovery\igdb.py
- [[Client IGDB per discovery automatica giochi e popolamento catalogo DB.]] - rationale - harvester\src\discovery\igdb.py
- [[FileNotFoundError se il file non esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - rationale - harvester\src\injector\upserter.py
- [[IGDBDiscovery]] - code - harvester\src\discovery\igdb.py
- [[IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione Twit]] - rationale - harvester\src\discovery\igdb.py
- [[Il file seedstop_games.json esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Il seed ha almeno 20 giochi.]] - rationale - harvester\tests\test_discovery.py
- [[Inserisce alias per il gioco titolo completo + slug IGDB.]] - rationale - harvester\src\discovery\igdb.py
- [[Legge e valida un file JSON seed. Ritorna la lista di giochi.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Legge file JSON seed e upserta giochi nel DB con alias.]] - rationale - harvester\src\discovery\seed_loader.py
- [[Ogni gioco ha title, slug, platforms e priority.]] - rationale - harvester\tests\test_discovery.py
- [[Priority deve essere un intero ≥ 1.]] - rationale - harvester\tests\test_discovery.py
- [[Recupera giochi IGDB per le piattaforme indicate.          IGDB usa POST con bod]] - rationale - harvester\src\discovery\igdb.py
- [[Ritorna il token Twitch OAuth, richiedendolorinnovandolo se scaduto.]] - rationale - harvester\src\discovery\igdb.py
- [[Scarica tutti i giochi IGDB per le piattaforme e li inserisce nel DB.          P]] - rationale - harvester\src\discovery\igdb.py
- [[SeedLoader]] - code - harvester\src\discovery\seed_loader.py
- [[SeedLoader — carica un file JSON seed e popola il catalogo giochi nel DB.  Forma]] - rationale - harvester\src\discovery\seed_loader.py
- [[Test per il modulo Discovery SeedLoader + IGDBDiscovery — zero HTTP reali.]] - rationale - harvester\tests\test_discovery.py
- [[TestIGDBDiscovery]] - code - harvester\tests\test_discovery.py
- [[TestLoadSeedFile]] - code - harvester\tests\test_discovery.py
- [[TestTopGamesSeedFile]] - code - harvester\tests\test_discovery.py
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - rationale - harvester\src\injector\upserter.py
- [[Upserta tutti i giochi del seed file nel DB.          Per ogni gioco         -]] - rationale - harvester\src\discovery\seed_loader.py
- [[Upserter]] - code - harvester\src\injector\upserter.py
- [[ValueError se il JSON non è una lista.]] - rationale - harvester\tests\test_discovery.py
- [[_get_token chiama POST una volta sola se il token è ancora valido.]] - rationale - harvester\tests\test_discovery.py
- [[discover_all_games si ferma quando fetch_games ritorna lista vuota.]] - rationale - harvester\tests\test_discovery.py
- [[fetch_games ritorna la lista di giochi parsata dal JSON IGDB.]] - rationale - harvester\tests\test_discovery.py
- [[igdb.py]] - code - harvester\src\discovery\igdb.py
- [[load_seed_file restituisce lista di dict da JSON valido.]] - rationale - harvester\tests\test_discovery.py
- [[seed_loader.py]] - code - harvester\src\discovery\seed_loader.py
- [[test_discover_all_games_stops_on_empty()]] - code - harvester\tests\test_discovery.py
- [[test_discovery.py]] - code - harvester\tests\test_discovery.py
- [[test_fetch_games_returns_list()]] - code - harvester\tests\test_discovery.py
- [[test_get_token_caches_result()]] - code - harvester\tests\test_discovery.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/IGDB_Discovery_&_Seeds
SORT file.name ASC
```

## Connections to other communities
- 20 edges to [[_COMMUNITY_Embedding Service]]
- 8 edges to [[_COMMUNITY_Deduplicator]]

## Top bridge nodes
- [[Upserter]] - degree 27, connects to 2 communities
- [[SeedLoader]] - degree 28, connects to 1 community
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - degree 2, connects to 1 community
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - degree 2, connects to 1 community