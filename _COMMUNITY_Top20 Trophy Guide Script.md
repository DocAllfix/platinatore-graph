---
type: community
cohesion: 0.18
members: 22
---

# Top20 Trophy Guide Script

**Cohesion:** 0.18 - loosely connected
**Members:** 22 nodes

## Members
- [[Cerca guide via DDG e fetcha tutti gli URL IN PARALLELO.      Ritorna {trophy_na]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Cerca tips per un trofeo specifico su rTrophies (async, no semaphore).]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Fetch generico con browser UA e semaphore globale.      Usato per URL di guida s]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Fetch un URL guida ed estrae le sezioni trophy matchate.      Ritorna (url, {tro]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Genera e salva la guida per un singolo trofeo. Ritorna status string.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Genera guide per i trofei platgold di un gioco.      Trofei processati in batch]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[SHA256 di url+extra, troncato a 64 char per content_hash NOT NULL.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[Slug URL-safe NFKD + minuscolo + solo alfanum e trattini.]] - rationale - harvester\scripts\run_trophy_guides_top20.py
- [[_discover_guide_sources()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_fetch_and_extract()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_fetch_reddit_trophy_tips()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_generic_fetch()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_process_game()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_process_trophy()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_psnprofiles_trophy_url()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_run()_2]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_slugify()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[_url_hash()]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[main()_7]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[run_trophy_guides_top20.py]] - code - harvester\scripts\run_trophy_guides_top20.py
- [[run_trophy_guides_top20.py_1]] - code - il-platinatore-ai\harvester\scripts\run_trophy_guides_top20.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Top20_Trophy_Guide_Script
SORT file.name ASC
```
