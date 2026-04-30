---
type: community
cohesion: 0.07
members: 31
---

# Fextralife Collector

**Cohesion:** 0.07 - loosely connected
**Members:** 31 nodes

## Members
- [[.extract()_13]] - code - harvester\tests\test_base_collector.py
- [[.test_deterministic()]] - code - harvester\tests\test_base_collector.py
- [[.test_different_input_different_hash()]] - code - harvester\tests\test_base_collector.py
- [[.test_hex_format()]] - code - harvester\tests\test_base_collector.py
- [[.test_user_agent_from_settings()]] - code - harvester\tests\test_base_collector.py
- [[Il client httpx usa lo User-Agent configurato in settings.]] - rationale - harvester\tests\test_base_collector.py
- [[Input diversi producono hash diversi.]] - rationale - harvester\tests\test_base_collector.py
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - rationale - harvester\tests\test_base_collector.py
- [[Lo stesso input produce sempre lo stesso hash.]] - rationale - harvester\tests\test_base_collector.py
- [[Test per BaseCollector — rate limiting, robots.txt, fetch, hash.]] - rationale - harvester\tests\test_base_collector.py
- [[TestComputeHash]] - code - harvester\tests\test_base_collector.py
- [[TestFetch]] - code - harvester\tests\test_base_collector.py
- [[TestPerHostTokenBucket]] - code - harvester\tests\test_base_collector.py
- [[TestRespectDelay]] - code - harvester\tests\test_base_collector.py
- [[TestRobotsTxt]] - code - harvester\tests\test_base_collector.py
- [[TestUserAgent]] - code - harvester\tests\test_base_collector.py
- [[_StubCollector]] - code - harvester\tests\test_base_collector.py
- [[collector()]] - code - harvester\tests\test_base_collector.py
- [[semaphore()]] - code - harvester\tests\test_base_collector.py
- [[test_allowed_when_no_robots()]] - code - harvester\tests\test_base_collector.py
- [[test_base_collector.py]] - code - harvester\tests\test_base_collector.py
- [[test_first_acquire_no_wait()]] - code - harvester\tests\test_base_collector.py
- [[test_lazy_load_robots_on_first_fetch()]] - code - harvester\tests\test_base_collector.py
- [[test_no_wait_first_request()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_html_on_200()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_403()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_429()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_timeout()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_when_disallowed()]] - code - harvester\tests\test_base_collector.py
- [[test_second_acquire_waits()]] - code - harvester\tests\test_base_collector.py
- [[test_waits_correct_time()]] - code - harvester\tests\test_base_collector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Fextralife_Collector
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Pre-Beta architecture concepts]]

## Top bridge nodes
- [[_StubCollector]] - degree 4, connects to 1 community