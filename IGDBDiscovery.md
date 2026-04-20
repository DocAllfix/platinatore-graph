---
source_file: "harvester\src\discovery\igdb.py"
type: "code"
community: "IGDB Discovery Scripts"
location: "L63"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/IGDB_Discovery_Scripts
---

# IGDBDiscovery

## Connections
- [[.__init__()_5]] - `method` [EXTRACTED]
- [[._get_token()]] - `method` [EXTRACTED]
- [[._ingest_game()]] - `method` [EXTRACTED]
- [[._insert_aliases()]] - `method` [EXTRACTED]
- [[._query()]] - `method` [EXTRACTED]
- [[.check_released_upcoming()]] - `method` [EXTRACTED]
- [[.close()_1]] - `method` [EXTRACTED]
- [[.discover_all_games()]] - `method` [EXTRACTED]
- [[.discover_popular_and_new()]] - `method` [EXTRACTED]
- [[.discover_upcoming()]] - `method` [EXTRACTED]
- [[.fetch_game_details()]] - `method` [EXTRACTED]
- [[.fetch_games()]] - `method` [EXTRACTED]
- [[.fetch_new_releases()]] - `method` [EXTRACTED]
- [[.fetch_popular()]] - `method` [EXTRACTED]
- [[.fetch_upcoming()]] - `method` [EXTRACTED]
- [[.resolve_steam_appids()]] - `method` [EXTRACTED]
- [[Client IGDB per discovery automatica giochi e popolamento catalogo DB.]] - `rationale_for` [EXTRACTED]
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._1]] - `uses` [INFERRED]
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - `uses` [INFERRED]
- [[Fetcha achievement Steam per giochi con steam_appid senza achievement.]] - `uses` [INFERRED]
- [[FileNotFoundError se il file non esiste.]] - `uses` [INFERRED]
- [[Il file seedstop_games.json esiste.]] - `uses` [INFERRED]
- [[Il seed ha almeno 20 giochi.]] - `uses` [INFERRED]
- [[Ogni gioco ha title, slug, platforms e priority.]] - `uses` [INFERRED]
- [[Priority deve essere un intero ≥ 1.]] - `uses` [INFERRED]
- [[Recupera achievement Steam (con descrizioni) per tutti i giochi PC nel DB.  Pipe]] - `uses` [INFERRED]
- [[Script discovery massiva giochi PS5+PS4 via IGDB fetch_games paginato.  Strateg]] - `uses` [INFERRED]
- [[Script espande il catalogo giochi via IGDB, poi fetch trophy PSN.]] - `uses` [INFERRED]
- [[Test per il modulo Discovery SeedLoader + IGDBDiscovery — zero HTTP reali.]] - `uses` [INFERRED]
- [[TestIGDBDiscovery]] - `uses` [INFERRED]
- [[TestLoadSeedFile]] - `uses` [INFERRED]
- [[TestTopGamesSeedFile]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[ValueError se il JSON non è una lista.]] - `uses` [INFERRED]
- [[_get_token chiama POST una volta sola se il token è ancora valido.]] - `uses` [INFERRED]
- [[discover_all_games si ferma quando fetch_games ritorna lista vuota.]] - `uses` [INFERRED]
- [[fetch_games ritorna la lista di giochi parsata dal JSON IGDB.]] - `uses` [INFERRED]
- [[igdb.py]] - `contains` [EXTRACTED]
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - `uses` [INFERRED]
- [[load_seed_file restituisce lista di dict da JSON valido.]] - `uses` [INFERRED]

#graphify/code #graphify/INFERRED #community/IGDB_Discovery_Scripts