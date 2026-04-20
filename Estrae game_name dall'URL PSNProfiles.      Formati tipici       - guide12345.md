---
source_file: "harvester\src\collectors\psnprofiles.py"
type: "rationale"
community: "PSNProfiles Collector"
location: "L150"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/PSNProfiles_Collector
---

# Estrae game_name dall'URL PSNProfiles.      Formati tipici:       - /guide/12345

## Connections
- [[BaseCollector]] - `uses` [INFERRED]
- [[_parse_url_slug()_3]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/PSNProfiles_Collector