---
type: community
cohesion: 0.22
members: 9
---

# PowerPyx Collector Tests

**Cohesion:** 0.22 - loosely connected
**Members:** 9 nodes

## Members
- [[Test per PowerPyxCollector — extract, URL slug parsing, pulizia HTML.]] - rationale - harvester\tests\test_powerpyx_collector.py
- [[TestExtract]] - code - harvester\tests\test_powerpyx_collector.py
- [[collector()_1]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_content_hash_deterministic()]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_empty_content_returns_none()_1]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_game_name_from_url()_1]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_powerpyx_collector.py]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_script_style_nav_removed()]] - code - harvester\tests\test_powerpyx_collector.py
- [[test_valid_html_returns_full_dict()_1]] - code - harvester\tests\test_powerpyx_collector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/PowerPyx_Collector_Tests
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[Test per PowerPyxCollector — extract, URL slug parsing, pulizia HTML.]] - degree 2, connects to 1 community
- [[TestExtract]] - degree 2, connects to 1 community