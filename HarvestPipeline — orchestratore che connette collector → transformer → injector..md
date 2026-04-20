---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Injector Deduplication"
location: "L1"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# HarvestPipeline — orchestratore che connette collector → transformer → injector.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[FandomCollector]] - `uses` [INFERRED]
- [[FextralifeCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[IGNCollector]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[SteamCommunityGuidesCollector]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[YouTubeCollector]] - `uses` [INFERRED]
- [[pipeline.py]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication