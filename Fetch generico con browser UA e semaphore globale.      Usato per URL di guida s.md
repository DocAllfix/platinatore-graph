---
source_file: "harvester\scripts\run_trophy_guides_top20.py"
type: "rationale"
community: "Injector Deduplication"
location: "L106"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Fetch generico con browser UA e semaphore globale.      Usato per URL di guida s

## Connections
- [[GuideSearchCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_generic_fetch()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication