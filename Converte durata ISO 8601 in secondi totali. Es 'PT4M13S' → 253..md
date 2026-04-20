---
source_file: "harvester\src\collectors\youtube.py"
type: "rationale"
community: "YouTube Collector"
location: "L85"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/YouTube_Collector
---

# Converte durata ISO 8601 in secondi totali. Es: 'PT4M13S' → 253.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[_parse_duration()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/YouTube_Collector