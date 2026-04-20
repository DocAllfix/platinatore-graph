---
source_file: "harvester\src\orchestrator\main.py"
type: "rationale"
community: "Orchestrator Pipeline"
location: "L25"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Orchestrator_Pipeline
---

# Aggiorna il timestamp del heartbeat file per segnalare che il processo è vivo.

## Connections
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[touch_heartbeat()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Orchestrator_Pipeline