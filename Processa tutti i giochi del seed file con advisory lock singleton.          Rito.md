---
source_file: "harvester\src\orchestrator\pipeline.py"
type: "rationale"
community: "Injector Deduplication"
location: "L805"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Processa tutti i giochi del seed file con advisory lock singleton.          Rito

## Connections
- [[.run_seed_batch()]] - `rationale_for` [EXTRACTED]
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

#graphify/rationale #graphify/INFERRED #community/Injector_Deduplication