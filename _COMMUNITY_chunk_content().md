---
type: community
cohesion: 0.50
members: 5
---

# chunk_content()

**Cohesion:** 0.50 - moderately connected
**Members:** 5 nodes

## Members
- [[Chunker — split di una guida in chunk da max_tokens con overlap.  Stima token =]] - rationale - harvester\src\injector\chunker.py
- [[Split markdown guide in chunk con prefisso titolo e overlap tra chunk consecutiv]] - rationale - harvester\src\injector\chunker.py
- [[_estimate_tokens()]] - code - harvester\src\injector\chunker.py
- [[chunk_content()]] - code - harvester\src\injector\chunker.py
- [[chunker.py]] - code - harvester\src\injector\chunker.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/chunk_content()
SORT file.name ASC
```
