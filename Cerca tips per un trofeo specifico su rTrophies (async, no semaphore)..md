---
source_file: "harvester\scripts\run_trophy_guides_top20.py"
type: "rationale"
community: "Injector Deduplication"
location: "L238"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Cerca tips per un trofeo specifico su r/Trophies (async, no semaphore).

## Connections
- [[GuideSearchCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_fetch_reddit_trophy_tips()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication