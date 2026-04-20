---
type: community
cohesion: 0.12
members: 17
---

# PSNProfiles/TrueAchievements Tests

**Cohesion:** 0.12 - loosely connected
**Members:** 17 nodes

## Members
- [[.test_has_http_client()_1]] - code - harvester\tests\test_collectors.py
- [[.test_inherits_base_collector()_1]] - code - harvester\tests\test_collectors.py
- [[Il rate limiting è ereditato il client httpx deve essere inizializzato._1]] - rationale - harvester\tests\test_collectors.py
- [[Test per PSNProfilesCollector e TrueAchievementsCollector.  HTML di esempio inve]] - rationale - harvester\tests\test_collectors.py
- [[TestTrueAchievementsCollector]] - code - harvester\tests\test_collectors.py
- [[TrueAchievementsCollector deve ereditare da BaseCollector.]] - rationale - harvester\tests\test_collectors.py
- [[psn_collector()]] - code - harvester\tests\test_collectors.py
- [[ta_collector()]] - code - harvester\tests\test_collectors.py
- [[test_achievement_list_preserved()]] - code - harvester\tests\test_collectors.py
- [[test_collectors.py]] - code - harvester\tests\test_collectors.py
- [[test_empty_content_returns_none()]] - code - harvester\tests\test_collectors.py
- [[test_game_name_from_url()]] - code - harvester\tests\test_collectors.py
- [[test_game_name_stripped_from_url()]] - code - harvester\tests\test_collectors.py
- [[test_hash_deterministic()]] - code - harvester\tests\test_collectors.py
- [[test_junk_removed()]] - code - harvester\tests\test_collectors.py
- [[test_table_converted_to_text()]] - code - harvester\tests\test_collectors.py
- [[test_valid_html_returns_full_dict()]] - code - harvester\tests\test_collectors.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PSNProfiles/TrueAchievements_Tests
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_Injector Deduplication]]
- 4 edges to [[_COMMUNITY_BaseCollector Interface]]

## Top bridge nodes
- [[TestTrueAchievementsCollector]] - degree 6, connects to 2 communities
- [[Test per PSNProfilesCollector e TrueAchievementsCollector.  HTML di esempio inve]] - degree 4, connects to 2 communities
- [[TrueAchievementsCollector deve ereditare da BaseCollector.]] - degree 4, connects to 2 communities
- [[Il rate limiting è ereditato il client httpx deve essere inizializzato._1]] - degree 4, connects to 2 communities
- [[test_collectors.py]] - degree 13, connects to 1 community