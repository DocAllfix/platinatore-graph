---
type: community
cohesion: 0.10
members: 26
---

# Guide Search Collector

**Cohesion:** 0.10 - loosely connected
**Members:** 26 nodes

## Members
- [[.test_calls_execute_for_each_trophy()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_empty_list_returns_zero()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_failed_language_is_skipped()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_multilang_fields_mapped_correctly()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_parses_response_correctly()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_returns_false_when_npsso_empty()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_returns_true_from_redis_cache()]] - code - harvester\tests\test_psn_fetcher.py
- [[.test_upsert_uses_name_en_as_name()]] - code - harvester\tests\test_psn_fetcher.py
- [[Crea una mock httpx.Response con la struttura PSN Trophy API.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[I nomi multilingua sono mappati ai campi name_XX corretti.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Test per PsnTrophyFetcher — tutto mockato, zero chiamate PSN reali.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[TestAuthenticate]] - code - harvester\tests\test_psn_fetcher.py
- [[TestFetchGameTrophies]] - code - harvester\tests\test_psn_fetcher.py
- [[TestUpsertTrophies]] - code - harvester\tests\test_psn_fetcher.py
- [[Trophy fixture con tutti i campi PSN.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[Una lingua che fallisce non blocca le altre.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[_make_psn_response()]] - code - harvester\tests\test_psn_fetcher.py
- [[_sample_trophy()]] - code - harvester\tests\test_psn_fetcher.py
- [[authenticate() ritorna False e logga warning se PSN_NPSSO è vuoto.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[authenticate() ritorna True usando il token cachato in Redis.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[fetch_game_trophies() parsa la risposta PSN e mergia le 10 lingue.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[test_psn_fetcher.py]] - code - harvester\tests\test_psn_fetcher.py
- [[test_psn_fetcher.py_1]] - code - il-platinatore-ai\harvester\tests\test_psn_fetcher.py
- [[upsert_trophies() chiama execute() una volta per trofeo.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[upsert_trophies() con lista vuota ritorna 0 senza chiamare execute.]] - rationale - harvester\tests\test_psn_fetcher.py
- [[upsert_trophies() usa name_en come valore per la colonna name (NOT NULL).]] - rationale - harvester\tests\test_psn_fetcher.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Guide_Search_Collector
SORT file.name ASC
```
