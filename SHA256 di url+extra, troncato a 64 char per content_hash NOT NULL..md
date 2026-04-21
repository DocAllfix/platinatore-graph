---
source_file: "harvester\scripts\run_trophy_guides_top20.py"
type: "rationale"
community: "Orchestrator · per guide"
location: "L85"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Orchestrator_·_per_guide
---

# SHA256 di url+extra, troncato a 64 char per content_hash NOT NULL.

## Connections
- [[GuideSearchCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[_url_hash()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Orchestrator_·_per_guide