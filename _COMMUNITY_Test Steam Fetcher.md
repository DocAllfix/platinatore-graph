---
type: community
cohesion: 0.11
members: 23
---

# Test: Steam Fetcher

**Cohesion:** 0.11 - loosely connected
**Members:** 23 nodes

## Members
- [[.test_calls_execute_for_each()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_empty_game_returns_empty()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_empty_list_returns_zero()_1]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_failed_lang_skipped()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_multilang_merge()]] - code - harvester\tests\test_steam_fetcher.py
- [[.test_parses_single_lang_correctly()]] - code - harvester\tests\test_steam_fetcher.py
- [[Achievement fixture con tutti i campi Steam.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Achievement multilingua vengono mergiati correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Crea una mock httpx.Response con la struttura Steam GetSchemaForGame.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Crea una mock httpx.Response per GetGlobalAchievementPercentagesForApp.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Gioco senza achievement ritorna lista vuota.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[Test per SteamAchievementFetcher — tutto mockato, zero chiamate Steam reali.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[TestFetchGameAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[TestUpsertAchievements]] - code - harvester\tests\test_steam_fetcher.py
- [[Una lingua che fallisce non blocca le altre._1]] - rationale - harvester\tests\test_steam_fetcher.py
- [[_make_pct_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_make_schema_response()]] - code - harvester\tests\test_steam_fetcher.py
- [[_sample_achievement()]] - code - harvester\tests\test_steam_fetcher.py
- [[fetch_game_achievements() parsa la risposta Steam correttamente.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[test_steam_fetcher.py]] - code - harvester\tests\test_steam_fetcher.py
- [[test_steam_fetcher.py_1]] - code - il-platinatore-ai\harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() chiama execute() una volta per achievement.]] - rationale - harvester\tests\test_steam_fetcher.py
- [[upsert_achievements() con lista vuota ritorna 0.]] - rationale - harvester\tests\test_steam_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Test:_Steam_Fetcher
SORT file.name ASC
```
