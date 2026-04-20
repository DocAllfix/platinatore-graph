---
source_file: "harvester\src\discovery\steam_achievement_fetcher.py"
type: "rationale"
community: "PSN/Steam Discovery Scripts"
location: "L197"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/PSN/Steam_Discovery_Scripts
---

# Inserisce o aggiorna achievement Steam nel DB.          ON CONFLICT sull'indice

## Connections
- [[.upsert_achievements()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/PSN/Steam_Discovery_Scripts