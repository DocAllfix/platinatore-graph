---
source_file: "harvester\src\orchestrator\main.py"
type: "rationale"
community: "Harvester Entry Point"
location: "L25"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Harvester_Entry_Point
---

# Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.

## Connections
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[touch_heartbeat()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Harvester_Entry_Point