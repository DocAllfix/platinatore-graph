---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Injector Deduplication"
location: "L40"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Orchestra la pipeline completa: collect → transform → inject.

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[FandomCollector]] - `uses` [INFERRED]
- [[FextralifeCollector]] - `uses` [INFERRED]
- [[GuideSynthesizer]] - `uses` [INFERRED]
- [[HarvestPipeline]] - `rationale_for` [EXTRACTED]
- [[IGNCollector]] - `uses` [INFERRED]
- [[PSNProfilesCollector]] - `uses` [INFERRED]
- [[PowerPyxCollector]] - `uses` [INFERRED]
- [[RedditCollector]] - `uses` [INFERRED]
- [[SeedLoader]] - `uses` [INFERRED]
- [[SteamCommunityGuidesCollector]] - `uses` [INFERRED]
- [[TrueAchievementsCollector]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[YouTubeCollector]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication