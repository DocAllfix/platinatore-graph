---
type: community
cohesion: 0.40
members: 5
---

# Structured Logger

**Cohesion:** 0.40 - moderately connected
**Members:** 5 nodes

## Members
- [[Configura structlog JSON in prod, console colorata in dev (DEBUG).]] - rationale - harvester\src\config\logger.py
- [[Restituisce un logger con il campo 'logger' già bindato al nome del modulo.]] - rationale - harvester\src\config\logger.py
- [[get_logger()]] - code - harvester\src\config\logger.py
- [[logger.py]] - code - harvester\src\config\logger.py
- [[setup_logging()]] - code - harvester\src\config\logger.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Structured_Logger
SORT file.name ASC
```
