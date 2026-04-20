---
type: community
cohesion: 0.18
members: 11
---

# Fextralife/IGN/Reddit Tests

**Cohesion:** 0.18 - loosely connected
**Members:** 11 nodes

## Members
- [[fextra()]] - code - harvester\tests\test_new_collectors.py
- [[ign()]] - code - harvester\tests\test_new_collectors.py
- [[reddit()]] - code - harvester\tests\test_new_collectors.py
- [[test_fextralife_extract_valid()]] - code - harvester\tests\test_new_collectors.py
- [[test_fextralife_js_only_returns_none()]] - code - harvester\tests\test_new_collectors.py
- [[test_ign_empty_returns_none()]] - code - harvester\tests\test_new_collectors.py
- [[test_ign_extract_valid()]] - code - harvester\tests\test_new_collectors.py
- [[test_new_collectors.py]] - code - harvester\tests\test_new_collectors.py
- [[test_reddit_extract_filters_and_anonymizes()]] - code - harvester\tests\test_new_collectors.py
- [[test_reddit_extract_invalid_json_returns_none()]] - code - harvester\tests\test_new_collectors.py
- [[test_reddit_format_for_llm_no_username()]] - code - harvester\tests\test_new_collectors.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Fextralife/IGN/Reddit_Tests
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[test_new_collectors.py]] - degree 11, connects to 1 community