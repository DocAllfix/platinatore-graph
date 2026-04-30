---
type: community
cohesion: 0.15
members: 19
---

# YouTube Collector

**Cohesion:** 0.15 - loosely connected
**Members:** 19 nodes

## Members
- [[.__init__()_4]] - code - harvester\src\collectors\youtube.py
- [[.collect()_2]] - code - harvester\src\collectors\youtube.py
- [[.extract()_12]] - code - harvester\src\collectors\youtube.py
- [[.fetch()_2]] - code - harvester\src\collectors\youtube.py
- [[.get_transcript()]] - code - harvester\src\collectors\youtube.py
- [[.search_videos()]] - code - harvester\src\collectors\youtube.py
- [[Cerca video su YouTube e ritorna quelli che passano i filtri qualità.          O]] - rationale - harvester\src\collectors\youtube.py
- [[Collector per guide video da YouTube via Data API v3 + transcript.]] - rationale - harvester\src\collectors\youtube.py
- [[Converte durata ISO 8601 in secondi totali. Es 'PT4M13S' → 253.]] - rationale - harvester\src\collectors\youtube.py
- [[Fetch con redazione di `key=...` nei log.]] - rationale - harvester\src\collectors\youtube.py
- [[Parsa transcript + URL e ritorna dict standard collector.          `extra` opzio]] - rationale - harvester\src\collectors\youtube.py
- [[Ritorna il testo del transcript EN, o None se non disponibile.          youtube-]] - rationale - harvester\src\collectors\youtube.py
- [[Supporta dispatch da seed file con URL youtube.comwatchv=VIDEO_ID.]] - rationale - harvester\src\collectors\youtube.py
- [[YouTubeCollector]] - code - harvester\src\collectors\youtube.py
- [[YouTubeCollector — guide video via YouTube Data API v3 + transcript.  Architettu]] - rationale - harvester\src\collectors\youtube.py
- [[_parse_duration()]] - code - harvester\src\collectors\youtube.py
- [[_title_from_extra()]] - code - harvester\src\collectors\youtube.py
- [[youtube.py]] - code - harvester\src\collectors\youtube.py
- [[youtube.py_1]] - code - il-platinatore-ai\harvester\src\collectors\youtube.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/YouTube_Collector
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Fextralife Collector]]

## Top bridge nodes
- [[YouTubeCollector]] - degree 10, connects to 1 community