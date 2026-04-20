---
source_file: "harvester\scripts\run_trophy_guides_top20.py"
type: "rationale"
community: "Injector Deduplication"
location: "L267"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Genera e salva la guida per un singolo trofeo. Ritorna status string.

## Connections
- [[GuideSearchCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_process_trophy()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication