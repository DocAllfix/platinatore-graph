---
source_file: "harvester\src\discovery\psn_trophy_fetcher.py"
type: "code"
community: "Discovery · psn per"
location: "L63"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Discovery_·_psn_per
---

# PsnTrophyFetcher

## Connections
- [[.__init__()_7]] - `method` [EXTRACTED]
- [[._fetch_lang()]] - `method` [EXTRACTED]
- [[._resolve_comm_id()]] - `method` [EXTRACTED]
- [[.authenticate()]] - `method` [EXTRACTED]
- [[.close()_2]] - `method` [EXTRACTED]
- [[.fetch_and_store_for_game()]] - `method` [EXTRACTED]
- [[.fetch_game_trophies()]] - `method` [EXTRACTED]
- [[.upsert_trophies()]] - `method` [EXTRACTED]
- [[Carica checkpoint esistente o restituisce struttura vuota.]] - `uses` [INFERRED]
- [[Crea una mock httpx.Response con la struttura PSN Trophy API.]] - `uses` [INFERRED]
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale.]] - `uses` [INFERRED]
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._1]] - `uses` [INFERRED]
- [[Entry point asincrono. Ritorna 0 su successo, 1 su errore fatale._2]] - `uses` [INFERRED]
- [[Esegue PsnGameFinder + PsnTrophyFetcher per giochi senza trofei PSN.      Identi]] - `uses` [INFERRED]
- [[Fetcha achievement Steam per giochi con steam_appid senza achievement.]] - `uses` [INFERRED]
- [[I nomi multilingua sono mappati ai campi name_XX corretti.]] - `uses` [INFERRED]
- [[Recupera trofei PSN (con descrizioni) per tutti i giochi PS4PS5 nel DB.  Pipeli]] - `uses` [INFERRED]
- [[Recupera trofei ufficiali PSN con nomi multilingua e li salva nel DB.]] - `rationale_for` [EXTRACTED]
- [[Salva checkpoint su disco (atomico via tmp file).]] - `uses` [INFERRED]
- [[Test per PsnTrophyFetcher — tutto mockato, zero chiamate PSN reali.]] - `uses` [INFERRED]
- [[TestAuthenticate]] - `uses` [INFERRED]
- [[TestFetchGameTrophies]] - `uses` [INFERRED]
- [[TestUpsertTrophies]] - `uses` [INFERRED]
- [[Trophy fixture con tutti i campi PSN.]] - `uses` [INFERRED]
- [[Una lingua che fallisce non blocca le altre.]] - `uses` [INFERRED]
- [[authenticate() ritorna False e logga warning se PSN_NPSSO è vuoto.]] - `uses` [INFERRED]
- [[authenticate() ritorna True usando il token cachato in Redis.]] - `uses` [INFERRED]
- [[fetch_game_trophies() parsa la risposta PSN e mergia le 10 lingue.]] - `uses` [INFERRED]
- [[igdb_seed — pipeline completa IGDB discovery + PSN trofei + Steam achievements.]] - `uses` [INFERRED]
- [[psn_seed — pipeline completa trofei PSN comm_id discovery + fetch multilingua.]] - `uses` [INFERRED]
- [[psn_trophy_fetcher.py]] - `contains` [EXTRACTED]
- [[upsert_trophies() chiama execute() una volta per trofeo.]] - `uses` [INFERRED]
- [[upsert_trophies() con lista vuota ritorna 0 senza chiamare execute.]] - `uses` [INFERRED]
- [[upsert_trophies() usa name_en come valore per la colonna name (NOT NULL).]] - `uses` [INFERRED]

#graphify/code #graphify/INFERRED #community/Discovery_·_psn_per