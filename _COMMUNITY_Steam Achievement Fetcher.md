---
type: community
cohesion: 0.13
members: 20
---

# Steam Achievement Fetcher

**Cohesion:** 0.13 - loosely connected
**Members:** 20 nodes

## Members
- [[.__init__()_8]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._fetch_global_percentages()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[._fetch_schema()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.close()_3]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_all_missing()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_and_store_for_game()_1]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.fetch_game_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[.upsert_achievements()]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[Chiude il client httpx._2]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetch + store per un singolo gioco. Ritorna count o 0 su errore.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha achievement per tutti i giochi con steam_appid ma senza         achieveme]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha le percentuali globali di completamento per achievement.          Ritorna]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha lo schema achievement per una lingua.          Ritorna (lang, lista_achie]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Fetcha tutti gli achievement in 10 lingue + rarity %.          Ritorna lista di]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Inserisce o aggiorna achievement Steam nel DB.          ON CONFLICT sull'indice]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[Recupera achievement Steam con nomi multilingua e li salva nel DB.]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[SteamAchievementFetcher]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[SteamAchievementFetcher — recupera achievement Steam in 10 lingue.  Endpoint pri]] - rationale - harvester\src\discovery\steam_achievement_fetcher.py
- [[steam_achievement_fetcher.py]] - code - harvester\src\discovery\steam_achievement_fetcher.py
- [[steam_achievement_fetcher.py_1]] - code - il-platinatore-ai\harvester\src\discovery\steam_achievement_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Steam_Achievement_Fetcher
SORT file.name ASC
```
