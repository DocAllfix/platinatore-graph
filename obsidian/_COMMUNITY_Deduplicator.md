---
type: community
cohesion: 0.06
members: 44
---

# Deduplicator

**Cohesion:** 0.06 - loosely connected
**Members:** 44 nodes

## Members
- [[.__init__()_3]] - code - harvester\src\injector\deduplicator.py
- [[._find_or_create_game_tx()]] - code - harvester\src\injector\upserter.py
- [[._find_or_create_trophy_tx()]] - code - harvester\src\injector\upserter.py
- [[.find_or_create_game()]] - code - harvester\src\injector\upserter.py
- [[.guide_exists()]] - code - harvester\src\injector\deduplicator.py
- [[.source_already_processed()]] - code - harvester\src\injector\deduplicator.py
- [[.test_higher_quality_overwrites()]] - code - harvester\tests\test_injector.py
- [[.test_lower_quality_skips()]] - code - harvester\tests\test_injector.py
- [[.test_new_guide_upserts()]] - code - harvester\tests\test_injector.py
- [[.test_no_special_chars()]] - code - harvester\tests\test_injector.py
- [[.test_short_content_single_chunk()]] - code - harvester\tests\test_injector.py
- [[.test_splits_on_markdown_headings()]] - code - harvester\tests\test_injector.py
- [[.test_title_prefix_on_every_chunk()]] - code - harvester\tests\test_injector.py
- [[.test_verified_never_overwritten()]] - code - harvester\tests\test_injector.py
- [[.test_without_trophy()]] - code - harvester\tests\test_injector.py
- [[.upsert_guide()]] - code - harvester\src\injector\upserter.py
- [[Contenuto breve → un solo chunk con prefisso titolo.]] - rationale - harvester\tests\test_injector.py
- [[Contenuto lungo con heading  → multi chunk.]] - rationale - harvester\tests\test_injector.py
- [[Deduplicator]] - code - harvester\src\injector\deduplicator.py
- [[Deduplicator — evita upsert inutili e protegge guide verificate.]] - rationale - harvester\src\injector\deduplicator.py
- [[Logica di deduplicazione basata su DB lookup.]] - rationale - harvester\src\injector\deduplicator.py
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - rationale - harvester\src\injector\upserter.py
- [[Peak hour CET 1800-2359.]] - rationale - harvester\src\injector\upserter.py
- [[Ritorna la guida esistente (idconfidencequality) se presente, altrimenti None.]] - rationale - harvester\src\injector\deduplicator.py
- [[Slug URL-safe per la guida `guida-{game}-{trophy}-{type}`.]] - rationale - harvester\src\injector\upserter.py
- [[Stesso URL + stesso hash → True (già processato).]] - rationale - harvester\tests\test_injector.py
- [[Test per Injector chunker, slug, deduplicator — DB mockato, zero connessioni re]] - rationale - harvester\tests\test_injector.py
- [[TestChunker]] - code - harvester\tests\test_injector.py
- [[TestShouldUpsert]] - code - harvester\tests\test_injector.py
- [[TestSlug]] - code - harvester\tests\test_injector.py
- [[TestSourceAlreadyProcessed]] - code - harvester\tests\test_injector.py
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.]] - rationale - harvester\src\injector\upserter.py
- [[True se esiste harvest_sources con stessa URL e stesso hash (nulla è cambiato).]] - rationale - harvester\src\injector\deduplicator.py
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - rationale - harvester\src\injector\upserter.py
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - rationale - harvester\src\injector\upserter.py
- [[_is_peak_hour()]] - code - harvester\src\injector\upserter.py
- [[_slugify()]] - code - harvester\src\injector\upserter.py
- [[deduplicator.py]] - code - harvester\src\injector\deduplicator.py
- [[generate_slug()]] - code - harvester\src\injector\upserter.py
- [[should_upsert()]] - code - harvester\src\injector\deduplicator.py
- [[test_injector.py]] - code - harvester\tests\test_injector.py
- [[test_returns_false_on_no_match()]] - code - harvester\tests\test_injector.py
- [[test_returns_true_on_hash_match()]] - code - harvester\tests\test_injector.py
- [[upserter.py]] - code - harvester\src\injector\upserter.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Deduplicator
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_Embedding Service]]
- 8 edges to [[_COMMUNITY_IGDB Discovery & Seeds]]

## Top bridge nodes
- [[Deduplicator]] - degree 32, connects to 2 communities
- [[.upsert_guide()]] - degree 6, connects to 1 community
- [[upserter.py]] - degree 5, connects to 1 community
- [[.find_or_create_game()]] - degree 3, connects to 1 community
- [[._find_or_create_game_tx()]] - degree 3, connects to 1 community