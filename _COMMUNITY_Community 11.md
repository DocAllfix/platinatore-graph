---
type: community
cohesion: 0.09
members: 22
---

# Community 11

**Cohesion:** 0.09 - loosely connected
**Members:** 22 nodes

## Members
- [[.test_contains_at_least_20_games()]] - code - harvester\tests\test_discovery.py
- [[.test_every_game_has_required_fields()]] - code - harvester\tests\test_discovery.py
- [[.test_parses_valid_json()]] - code - harvester\tests\test_discovery.py
- [[.test_priority_values_are_valid()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_missing_file()]] - code - harvester\tests\test_discovery.py
- [[.test_raises_on_non_list_json()]] - code - harvester\tests\test_discovery.py
- [[.test_seed_file_exists()]] - code - harvester\tests\test_discovery.py
- [[FileNotFoundError se il file non esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Il file seedstop_games.json esiste.]] - rationale - harvester\tests\test_discovery.py
- [[Il seed ha almeno 20 giochi.]] - rationale - harvester\tests\test_discovery.py
- [[Ogni gioco ha title, slug, platforms e priority.]] - rationale - harvester\tests\test_discovery.py
- [[Priority deve essere un intero ≥ 1.]] - rationale - harvester\tests\test_discovery.py
- [[Test per il modulo Discovery SeedLoader + IGDBDiscovery — zero HTTP reali.]] - rationale - harvester\tests\test_discovery.py
- [[TestIGDBDiscovery]] - code - harvester\tests\test_discovery.py
- [[TestLoadSeedFile]] - code - harvester\tests\test_discovery.py
- [[TestTopGamesSeedFile]] - code - harvester\tests\test_discovery.py
- [[ValueError se il JSON non è una lista.]] - rationale - harvester\tests\test_discovery.py
- [[load_seed_file restituisce lista di dict da JSON valido.]] - rationale - harvester\tests\test_discovery.py
- [[test_discover_all_games_stops_on_empty()]] - code - harvester\tests\test_discovery.py
- [[test_discovery.py]] - code - harvester\tests\test_discovery.py
- [[test_fetch_games_returns_list()]] - code - harvester\tests\test_discovery.py
- [[test_get_token_caches_result()]] - code - harvester\tests\test_discovery.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Community_11
SORT file.name ASC
```
