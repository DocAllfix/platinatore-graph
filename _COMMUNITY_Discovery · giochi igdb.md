---
type: community
cohesion: 0.02
members: 123
---

# Discovery · giochi igdb

**Cohesion:** 0.02 - loosely connected
**Members:** 123 nodes

## Members
- [[.__init__()_5]] - code - harvester\src\discovery\igdb.py
- [[.__init__()_8]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._fetch_global_percentages()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._fetch_schema()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._get_token()]] - code - harvester\src\discovery\igdb.py
- [[._ingest_game()]] - code - harvester\src\discovery\igdb.py
- [[._insert_aliases()]] - code - harvester\src\discovery\igdb.py
- [[._query()]] - code - harvester\src\discovery\igdb.py
- [[.check_released_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.close()_1]] - code - harvester\src\discovery\igdb.py
- [[.close()_3]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.discover_all_games()]] - code - harvester\src\discovery\igdb.py
- [[.discover_popular_and_new()]] - code - harvester\src\discovery\igdb.py
- [[.discover_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_all_missing()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_and_store_for_game()_1]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_game_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_game_details()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_games()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_new_releases()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_popular()]] - code - harvester\src\discovery\igdb.py
- [[.fetch_upcoming()]] - code - harvester\src\discovery\igdb.py
- [[.resolve_steam_appids()]] - code - harvester\src\discovery\igdb.py
- [[.test_calls_execute_for_each()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_contains_at_least_20_games()]] - code - harvester\tests\test_discovery.py
- [[.test_empty_game_returns_empty()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_empty_list_returns_zero()_1]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_every_game_has_required_fields()]] - code - harvester\tests\test_discovery.py
- [[.test_failed_lang_skipped()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_multilang_merge()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_parses_single_lang_correctly()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_parses_valid_json()]] - code - harvester\tests\test_discovery.py
- [[.test_priority_values_are_valid()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_missing_file()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_non_list_json()]] - code - harvester\tests\test_discovery.py
- [[.test_seed_file_exists()]] - code - harvester\tests\test_discovery.py
- [[.upsert_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[Achievement fixture con tutti i campi Steam.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Achievement multilingua vengono mergiati correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Chiude il client httpx._1]] - rationale - harvester\src\discovery\igdb.py
- [[Chiude il client httpx._2]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Client IGDB per discovery automatica giochi e popolamento catalogo DB.]] - rationale - harvester\src\discovery\igdb.py
- [[Controlla se giochi in upcoming_games sono stati rilasciati.          Per ogni u]] - rationale - harvester\src\discovery\igdb.py
- [[Crea una mock httpx.Response con la struttura Steam GetSchemaForGame.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Crea una mock httpx.Response per GetGlobalAchievementPercentagesForApp.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._1]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Esegue una query POST su un endpoint IGDB e ritorna la risposta JSON.]] - rationale - harvester\src\discovery\igdb.py
- [[Fetch + store per un singolo gioco. Ritorna count o 0 su errore.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha achievement Steam per giochi con steam_appid senza achievement.]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Fetcha achievement per tutti i giochi con steam_appid ma senza         achieveme]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha le percentuali globali di completamento per achievement.          Ritorna]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha lo schema achievement per una lingua.          Ritorna (lang, lista_achie]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha tutti gli achievement in 10 lingue + rarity %.          Ritorna lista di]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[FileNotFoundError se il file non esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Gioco senza achievement ritorna lista vuota.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[IGDBDiscovery]] - code - harvester\src\discovery\igdb.py
- [[IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione Twit]] - rationale - harvester\src\discovery\igdb.py
- [[Il file seedstop_games.json esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Il seed ha almeno 20 giochi.]] - rationale - harvester\tests\test_discovery.py
- [[Inserisce alias per il gioco titolo completo + slug IGDB.]] - rationale - harvester\src\discovery\igdb.py
- [[Inserisce o aggiorna achievement Steam nel DB.          ON CONFLICT sull'indice]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Inserisce un gioco da dati IGDB se non già presente.          Salva igdb_id sia]] - rationale - harvester\src\discovery\igdb.py
- [[Ogni gioco ha title, slug, platforms e priority.]] - rationale - harvester\tests\test_discovery.py
- [[Priority deve essere un intero ≥ 1.]] - rationale - harvester\tests\test_discovery.py
- [[Recupera achievement Steam (con descrizioni) per tutti i giochi PC nel DB.  Pipe]] - rationale - harvester\scripts\run_steam_achievements_all.py
- [[Recupera achievement Steam con nomi multilingua e li salva nel DB.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
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
- [[Script discovery massiva giochi PS5+PS4 via IGDB fetch_games paginato.  Strateg]] - rationale - harvester\scripts\run_igdb_full_discovery.py
- [[Script espande il catalogo giochi via IGDB, poi fetch trophy PSN.]] - rationale - harvester\scripts\run_igdb_discovery.py
- [[SteamAchievementFetcher]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[SteamAchievementFetcher — recupera achievement Steam in 10 lingue.  Endpoint pri]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Test per SteamAchievementFetcher — tutto mockato, zero chiamate Steam reali.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Test per il modulo Discovery SeedLoader + IGDBDiscovery — zero HTTP reali.]] - rationale - harvester\tests\test_discovery.py
- [[TestFetchGameAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[TestIGDBDiscovery]] - code - harvester\tests\test_discovery.py
- [[TestLoadSeedFile]] - code - harvester\tests\test_discovery.py
- [[TestTopGamesSeedFile]] - code - harvester\tests\test_discovery.py
- [[TestUpsertAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[Una lingua che fallisce non blocca le altre._1]] - rationale - harvester\tests\test_steam_fetcher.py
- [[ValueError se il JSON non è una lista.]] - rationale - harvester\tests\test_discovery.py
- [[_accept_game()]] - code - harvester\src\discovery\igdb.py
- [[_get_token chiama POST una volta sola se il token è ancora valido.]] - rationale - harvester\tests\test_discovery.py
- [[_make_pct_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_make_schema_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_map_platform_ids()]] - code - harvester\src\discovery\igdb.py
- [[_parse_args()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run()_3]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run()_1]] - code - harvester\scripts\run_steam_achievements_all.py
- [[_run_psn_trophies()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run_steam_achievements()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_sample_achievement()]] - code - harvester\tests\test_steam_fetcher.py
- [[discover_all_games si ferma quando fetch_games ritorna lista vuota.]] - rationale - harvester\tests\test_discovery.py
- [[fetch_game_achievements() parsa la risposta Steam correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[fetch_games ritorna la lista di giochi parsata dal JSON IGDB.]] - rationale - harvester\tests\test_discovery.py
- [[igdb.py]] - code - harvester\src\discovery\igdb.py
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[igdb_seed.py]] - code - harvester\src\orchestrator\igdb_seed.py
- [[load_seed_file restituisce lista di dict da JSON valido.]] - rationale - harvester\tests\test_discovery.py
- [[main()_7]] - code - harvester\src\orchestrator\igdb_seed.py
- [[main()_1]] - code - harvester\scripts\run_igdb_discovery.py
- [[main()_2]] - code - harvester\scripts\run_igdb_full_discovery.py
- [[main()_4]] - code - harvester\scripts\run_steam_achievements_all.py
- [[run_igdb_discovery.py]] - code - harvester\scripts\run_igdb_discovery.py
- [[run_igdb_full_discovery.py]] - code - harvester\scripts\run_igdb_full_discovery.py
- [[run_steam_achievements_all.py]] - code - harvester\scripts\run_steam_achievements_all.py
- [[steam_achievement_fetcher.py]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[test_discover_all_games_stops_on_empty()]] - code - harvester\tests\test_discovery.py
- [[test_discovery.py]] - code - harvester\tests\test_discovery.py
- [[test_fetch_games_returns_list()]] - code - harvester\tests\test_discovery.py
- [[test_get_token_caches_result()]] - code - harvester\tests\test_discovery.py
- [[test_steam_fetcher.py]] - code - harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() chiama execute() una volta per achievement.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() con lista vuota ritorna 0.]] - rationale - harvester\tests\test_steam_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Discovery_·_giochi_igdb
SORT file.name ASC
```

## Connections to other communities
- 32 edges to [[_COMMUNITY_Orchestrator · per guide]]
- 8 edges to [[_COMMUNITY_Discovery · psn per]]

## Top bridge nodes
- [[IGDBDiscovery]] - degree 40, connects to 1 community
- [[TestTopGamesSeedFile]] - degree 7, connects to 1 community
- [[TestLoadSeedFile]] - degree 6, connects to 1 community
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - degree 5, connects to 1 community
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - degree 5, connects to 1 community