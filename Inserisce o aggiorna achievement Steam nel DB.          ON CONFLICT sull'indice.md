---
source_file: "harvester\src\discovery\steam_achievement_fetcher.py"
type: "rationale"
community: "Steam Achievement Fetcher"
location: "L197"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Steam_Achievement_Fetcher
---

# Inserisce o aggiorna achievement Steam nel DB.          ON CONFLICT sull'indice

## Connections
- [[.upsert_achievements()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Steam_Achievement_Fetcher