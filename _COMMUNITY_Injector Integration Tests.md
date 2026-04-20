---
type: community
cohesion: 0.10
members: 21
---

# Injector Integration Tests

**Cohesion:** 0.10 - loosely connected
**Members:** 21 nodes

## Members
- [[.test_equal_quality_does_upsert()]] - code - harvester\tests\test_injector.py
- [[.test_higher_quality_overwrites()]] - code - harvester\tests\test_injector.py
- [[.test_lower_quality_skips()]] - code - harvester\tests\test_injector.py
- [[.test_new_guide_upserts()]] - code - harvester\tests\test_injector.py
- [[.test_no_special_chars()]] - code - harvester\tests\test_injector.py
- [[.test_short_content_single_chunk()]] - code - harvester\tests\test_injector.py
- [[.test_splits_on_markdown_headings()]] - code - harvester\tests\test_injector.py
- [[.test_title_prefix_on_every_chunk()]] - code - harvester\tests\test_injector.py
- [[.test_verified_never_overwritten()]] - code - harvester\tests\test_injector.py
- [[.test_without_trophy()]] - code - harvester\tests\test_injector.py
- [[Contenuto breve → un solo chunk con prefisso titolo.]] - rationale - harvester\tests\test_injector.py
- [[Contenuto lungo con heading  → multi chunk.]] - rationale - harvester\tests\test_injector.py
- [[Qualità uguale → upsert consentito.          Necessario perché il LLM produce se]] - rationale - harvester\tests\test_injector.py
- [[Test per Injector chunker, slug, deduplicator — DB mockato, zero connessioni re]] - rationale - harvester\tests\test_injector.py
- [[TestChunker]] - code - harvester\tests\test_injector.py
- [[TestShouldUpsert]] - code - harvester\tests\test_injector.py
- [[TestSlug]] - code - harvester\tests\test_injector.py
- [[TestSourceAlreadyProcessed]] - code - harvester\tests\test_injector.py
- [[test_injector.py]] - code - harvester\tests\test_injector.py
- [[test_returns_false_on_no_match()]] - code - harvester\tests\test_injector.py
- [[test_returns_true_on_hash_match()]] - code - harvester\tests\test_injector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Injector_Integration_Tests
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[TestShouldUpsert]] - degree 7, connects to 1 community
- [[TestChunker]] - degree 5, connects to 1 community
- [[TestSlug]] - degree 4, connects to 1 community
- [[Test per Injector chunker, slug, deduplicator — DB mockato, zero connessioni re]] - degree 2, connects to 1 community
- [[Contenuto breve → un solo chunk con prefisso titolo.]] - degree 2, connects to 1 community