---
type: community
cohesion: 0.02
members: 126
---

# PSN/Steam Discovery Scripts

**Cohesion:** 0.02 - loosely connected
**Members:** 126 nodes

## Members
- [[.__init__()_6]] - code - harvester\src\discovery\psn_game_finder.py
- [[.__init__()_7]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.__init__()_8]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._extract_title_id()]] - code - harvester\src\discovery\psn_game_finder.py
- [[._fetch_global_percentages()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._fetch_lang()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[._fetch_schema()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._find_comm_id_sync()]] - code - harvester\src\discovery\psn_game_finder.py
- [[._get_platform()]] - code - harvester\src\discovery\psn_game_finder.py
- [[._resolve_comm_id()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.authenticate()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.close()_2]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.close()_3]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_all_missing()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_and_store_for_game()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.fetch_and_store_for_game()_1]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_game_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_game_trophies()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[.find_comm_id()]] - code - harvester\src\discovery\psn_game_finder.py
- [[.populate_all_games()]] - code - harvester\src\discovery\psn_game_finder.py
- [[.test_calls_execute_for_each()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_calls_execute_for_each_trophy()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_empty_game_returns_empty()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_empty_list_returns_zero()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_empty_list_returns_zero()_1]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_failed_lang_skipped()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_failed_language_is_skipped()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_multilang_fields_mapped_correctly()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_multilang_merge()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_parses_response_correctly()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_parses_single_lang_correctly()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_returns_false_when_npsso_empty()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_returns_true_from_redis_cache()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_upsert_uses_name_en_as_name()]] - code - harvester\tests\test_psn_fetcher.py
- [[.upsert_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.upsert_trophies()]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[Achievement fixture con tutti i campi Steam.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Achievement multilingua vengono mergiati correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Async wrapper attorno a _find_comm_id_sync.]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[Autentica con PSN via NPSSO. Cacha il token in Redis.          Ritorna False e l]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Carica checkpoint esistente o restituisce struttura vuota.]] - rationale - harvester\scripts\run_psn_trophies_all.py
- [[Cerca il gioco su PSN e ritorna il np_communication_id.          Sincrono — da c]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[Cerca il psn_communication_id per un gioco.          Strategia         1. games]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Chiude il client httpx._2]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Chiude il client httpx. Da chiamare allo shutdown.]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Crea una mock httpx.Response con la struttura PSN Trophy API.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Crea una mock httpx.Response con la struttura Steam GetSchemaForGame.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Crea una mock httpx.Response per GetGlobalAchievementPercentagesForApp.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._1]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._2]] - rationale - harvester\src\orchestrator\psn_seed.py
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale.]] - rationale - harvester\scripts\run_psn_trophies_all.py
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Estrae il title_id dal product_id PSN (parte centrale).]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[Fetch + store per un singolo gioco. Entry point ad alto livello.          Richie]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Fetch + store per un singolo gioco. Ritorna count o 0 su errore.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha achievement Steam per giochi con steam_appid senza achievement.]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[Fetcha achievement per tutti i giochi con steam_appid ma senza         achieveme]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha le percentuali globali di completamento per achievement.          Ritorna]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha lo schema achievement per una lingua.          Ritorna (lang, lista_achie]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha nomi trofei per una singola lingua.          Ritorna (lang, {trophy_id {]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Fetcha tutti gli achievement in 10 lingue + rarity %.          Ritorna lista di]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha tutti i trofei del gioco in 10 lingue in parallelo.          Ritorna list]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Gioco senza achievement ritorna lista vuota.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[I nomi multilingua sono mappati ai campi name_XX corretti.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Inserisce o aggiorna achievement Steam nel DB.          ON CONFLICT sull'indice]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Inserisce o aggiorna i trofei nel DB con nomi multilingua.          ON CONFLICT]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Mappa il prefisso del title_id alla piattaforma psnawp.]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[Popola games.metadata'psn_communication_id' per tutti i giochi del DB.]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[PsnGameFinder]] - code - harvester\src\discovery\psn_game_finder.py
- [[PsnGameFinder — scopre il psn_communication_id per ogni gioco del seed.  Usa psn]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[PsnTrophyFetcher]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[PsnTrophyFetcher — recupera nomi ufficiali PSN trofei in 10 lingue.  Autenticazi]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Recupera achievement Steam con nomi multilingua e li salva nel DB.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Recupera trofei PSN (con descrizioni) per tutti i giochi PS4PS5 nel DB.  Pipeli]] - rationale - harvester\scripts\run_psn_trophies_all.py
- [[Recupera trofei ufficiali PSN con nomi multilingua e li salva nel DB.]] - rationale - harvester\src\discovery\psn_trophy_fetcher.py
- [[Salva checkpoint su disco (atomico via tmp file).]] - rationale - harvester\scripts\run_psn_trophies_all.py
- [[Scopre il np_communication_id PSN per ogni gioco e lo salva in DB.]] - rationale - harvester\src\discovery\psn_game_finder.py
- [[SteamAchievementFetcher]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[SteamAchievementFetcher — recupera achievement Steam in 10 lingue.  Endpoint pri]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Test per PsnTrophyFetcher — tutto mockato, zero chiamate PSN reali.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Test per SteamAchievementFetcher — tutto mockato, zero chiamate Steam reali.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[TestAuthenticate]] - code - harvester\tests\test_psn_fetcher.py
- [[TestFetchGameAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[TestFetchGameTrophies]] - code - harvester\tests\test_psn_fetcher.py
- [[TestUpsertAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[TestUpsertTrophies]] - code - harvester\tests\test_psn_fetcher.py
- [[Trophy fixture con tutti i campi PSN.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Una lingua che fallisce non blocca le altre.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Una lingua che fallisce non blocca le altre._1]] - rationale - harvester\tests\test_steam_fetcher.py
- [[_is_name_match()]] - code - harvester\src\discovery\psn_game_finder.py
- [[_load_checkpoint()]] - code - harvester\scripts\run_psn_trophies_all.py
- [[_make_pct_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_make_psn_response()]] - code - harvester\tests\test_psn_fetcher.py
- [[_make_schema_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_normalize()]] - code - harvester\src\discovery\psn_game_finder.py
- [[_parse_args()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run()_3]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run()_4]] - code - harvester\src\orchestrator\psn_seed.py
- [[_run()]] - code - harvester\scripts\run_psn_trophies_all.py
- [[_run_psn_trophies()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_run_steam_achievements()]] - code - harvester\src\orchestrator\igdb_seed.py
- [[_sample_achievement()]] - code - harvester\tests\test_steam_fetcher.py
- [[_sample_trophy()]] - code - harvester\tests\test_psn_fetcher.py
- [[_save_checkpoint()]] - code - harvester\scripts\run_psn_trophies_all.py
- [[authenticate() ritorna False e logga warning se PSN_NPSSO è vuoto.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[authenticate() ritorna True usando il token cachato in Redis.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[fetch_game_achievements() parsa la risposta Steam correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[fetch_game_trophies() parsa la risposta PSN e mergia le 10 lingue.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - rationale - harvester\src\orchestrator\igdb_seed.py
- [[igdb_seed.py]] - code - harvester\src\orchestrator\igdb_seed.py
- [[main()_7]] - code - harvester\src\orchestrator\igdb_seed.py
- [[main()_9]] - code - harvester\src\orchestrator\psn_seed.py
- [[main()_3]] - code - harvester\scripts\run_psn_trophies_all.py
- [[psn_game_finder.py]] - code - harvester\src\discovery\psn_game_finder.py
- [[psn_seed — pipeline completa trofei PSN comm_id discovery + fetch multilingua.]] - rationale - harvester\src\orchestrator\psn_seed.py
- [[psn_seed.py]] - code - harvester\src\orchestrator\psn_seed.py
- [[psn_trophy_fetcher.py]] - code - harvester\src\discovery\psn_trophy_fetcher.py
- [[run_psn_trophies_all.py]] - code - harvester\scripts\run_psn_trophies_all.py
- [[steam_achievement_fetcher.py]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[test_psn_fetcher.py]] - code - harvester\tests\test_psn_fetcher.py
- [[test_steam_fetcher.py]] - code - harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() chiama execute() una volta per achievement.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() con lista vuota ritorna 0.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[upsert_trophies() chiama execute() una volta per trofeo.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[upsert_trophies() con lista vuota ritorna 0 senza chiamare execute.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[upsert_trophies() usa name_en come valore per la colonna name (NOT NULL).]] - rationale - harvester\tests\test_psn_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PSN/Steam_Discovery_Scripts
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_IGDB Discovery Scripts]]

## Top bridge nodes
- [[SteamAchievementFetcher]] - degree 27, connects to 1 community
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - degree 5, connects to 1 community
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - degree 5, connects to 1 community
- [[Fetcha achievement Steam per giochi con steam_appid senza achievement.]] - degree 5, connects to 1 community
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._1]] - degree 5, connects to 1 community