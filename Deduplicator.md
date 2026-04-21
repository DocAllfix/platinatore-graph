---
source_file: "harvester\src\injector\deduplicator.py"
type: "code"
community: "Orchestrator · per guide"
location: "L9"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Orchestrator_·_per_guide
---

# Deduplicator

## Connections
- [[.__init__()_9]] - `method` [EXTRACTED]
- [[.guide_exists()]] - `method` [EXTRACTED]
- [[.source_already_processed()]] - `method` [EXTRACTED]
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - `uses` [INFERRED]
- [[Chiude tutti i client HTTP.]] - `uses` [INFERRED]
- [[Contenuto breve → un solo chunk con prefisso titolo.]] - `uses` [INFERRED]
- [[Contenuto lungo con heading  → multi chunk.]] - `uses` [INFERRED]
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - `uses` [INFERRED]
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - `uses` [INFERRED]
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - `uses` [INFERRED]
- [[Genera guide boss per un gioco usando Fextralife + IGN.          Se boss_names è]] - `uses` [INFERRED]
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - `uses` [INFERRED]
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - `uses` [INFERRED]
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - `uses` [INFERRED]
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - `uses` [INFERRED]
- [[Legge l'ultimo slug processato dal DB.]] - `uses` [INFERRED]
- [[Logica di deduplicazione basata su DB lookup.]] - `rationale_for` [EXTRACTED]
- [[Lowercase + rimozione accenti base + non-alfanumerici → trattini.]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `uses` [INFERRED]
- [[Peak hour CET 1800-2359.]] - `uses` [INFERRED]
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - `uses` [INFERRED]
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - `uses` [INFERRED]
- [[Qualità uguale → upsert consentito.          Necessario perché il LLM produce se]] - `uses` [INFERRED]
- [[Raccoglie contenuti wiki da Fandom per un gioco.          Se `wiki_subdomain` è]] - `uses` [INFERRED]
- [[Resetta il progresso dopo un batch completato con successo.]] - `uses` [INFERRED]
- [[Salva il progresso corrente nel DB.]] - `uses` [INFERRED]
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - `uses` [INFERRED]
- [[Slug URL-safe per la guida `guida-{game}-{trophy_or_topic}-{type}`.      `topi]] - `uses` [INFERRED]
- [[Stesso URL + stesso hash → True (già processato).]] - `uses` [INFERRED]
- [[Test per Injector chunker, slug, deduplicator — DB mockato, zero connessioni re]] - `uses` [INFERRED]
- [[TestChunker]] - `uses` [INFERRED]
- [[TestShouldUpsert]] - `uses` [INFERRED]
- [[TestSlug]] - `uses` [INFERRED]
- [[TestSourceAlreadyProcessed]] - `uses` [INFERRED]
- [[Trova il game per slug o alias; se non esiste, INSERT e ritorna l'id.          L]] - `uses` [INFERRED]
- [[Trova il trofeo per game_id + nome; None se trophy_name non è dato.]] - `uses` [INFERRED]
- [[UPSERT atomica di una guida con tracciabilità fonti.          Argomenti `chunks`]] - `uses` [INFERRED]
- [[Upserter]] - `uses` [INFERRED]
- [[Upserter — transazione atomica game → trophy → guide → harvest_sources.  FF-N]] - `uses` [INFERRED]
- [[Versione TX-scoped di find_or_create_game — stessa logica a 4 step.]] - `uses` [INFERRED]
- [[deduplicator.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/Orchestrator_·_per_guide