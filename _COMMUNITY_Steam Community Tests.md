---
type: community
cohesion: 0.13
members: 18
---

# Steam Community Tests

**Cohesion:** 0.13 - loosely connected
**Members:** 18 nodes

## Members
- [[Test SteamCommunityGuidesCollector — JSON inventato, zero rete reale.]] - rationale - harvester\tests\test_steam_community_collector.py
- [[_details_payload()]] - code - harvester\tests\test_steam_community_collector.py
- [[steam()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_extract_empty_response_returns_none()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_extract_invalid_json_returns_none()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_extract_result_not_ok_returns_none()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_extract_too_short_returns_none()_1]] - code - harvester\tests\test_steam_community_collector.py
- [[test_extract_valid_guide()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_guide_type_achievements_to_trophy()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_guide_type_default_walkthrough()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_guide_type_strategy_to_meta()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_guide_type_walkthrough()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_key_redact_regex()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_steam_community_collector.py]] - code - harvester\tests\test_steam_community_collector.py
- [[test_strip_bbcode_empty()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_strip_bbcode_generic_tags()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_strip_bbcode_img_removes_entirely()]] - code - harvester\tests\test_steam_community_collector.py
- [[test_strip_bbcode_url_keeps_label()]] - code - harvester\tests\test_steam_community_collector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Steam_Community_Tests
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[Test SteamCommunityGuidesCollector — JSON inventato, zero rete reale.]] - degree 2, connects to 1 community