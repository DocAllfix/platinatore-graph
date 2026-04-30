---
type: community
cohesion: 0.08
members: 36
---

# Harvester Pipeline

**Cohesion:** 0.08 - loosely connected
**Members:** 36 nodes

## Members
- [[.__init__()_12]] - code - harvester\src\orchestrator\pipeline.py
- [[._get_collector_for_url()]] - code - harvester\src\orchestrator\pipeline.py
- [[._get_last_processed_slug()]] - code - harvester\src\orchestrator\pipeline.py
- [[._inject_synthetic()]] - code - harvester\src\orchestrator\pipeline.py
- [[._reset_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[._save_progress()]] - code - harvester\src\orchestrator\pipeline.py
- [[.cleanup()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_boss_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_fandom_content()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_single_guide()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_steam_community_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_with_reddit()]] - code - harvester\src\orchestrator\pipeline.py
- [[.process_youtube_guides()]] - code - harvester\src\orchestrator\pipeline.py
- [[.run_seed_batch()]] - code - harvester\src\orchestrator\pipeline.py
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Chiude tutti i client HTTP.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Genera guide boss per un gioco usando Fextralife + IGN.          Se boss_names è]] - rationale - harvester\src\orchestrator\pipeline.py
- [[HarvestPipeline]] - code - harvester\src\orchestrator\pipeline.py
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Legge l'ultimo slug processato dal DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Orchestra la pipeline completa collect → transform → inject.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Raccoglie contenuti wiki da Fandom per un gioco.          Se `wiki_subdomain` è]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Resetta il progresso dopo un batch completato con successo.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Salva il progresso corrente nel DB.]] - rationale - harvester\src\orchestrator\pipeline.py
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - rationale - harvester\src\orchestrator\pipeline.py
- [[_slugify()_3]] - code - harvester\src\orchestrator\pipeline.py
- [[_touch_heartbeat()]] - code - harvester\src\orchestrator\pipeline.py
- [[pipeline.py]] - code - harvester\src\orchestrator\pipeline.py
- [[pipeline.py_1]] - code - il-platinatore-ai\harvester\src\orchestrator\pipeline.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Harvester_Pipeline
SORT file.name ASC
```
