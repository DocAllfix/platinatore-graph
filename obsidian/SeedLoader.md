---
source_file: "harvester\src\discovery\seed_loader.py"
type: "code"
community: "IGDB Discovery & Seeds"
location: "L26"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/IGDB_Discovery_&_Seeds
---

# SeedLoader

## Connections
- [[.load_seed_file()]] - `method` [EXTRACTED]
- [[.seed_database()]] - `method` [EXTRACTED]
- [[Chiude tutti i client HTTP.]] - `uses` [INFERRED]
- [[FileNotFoundError se il file non esiste.]] - `uses` [INFERRED]
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - `uses` [INFERRED]
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - `uses` [INFERRED]
- [[Il file seedstop_games.json esiste.]] - `uses` [INFERRED]
- [[Il seed ha almeno 20 giochi.]] - `uses` [INFERRED]
- [[Legge file JSON seed e upserta giochi nel DB con alias.]] - `rationale_for` [EXTRACTED]
- [[Legge l'ultimo slug processato dal DB.]] - `uses` [INFERRED]
- [[Ogni gioco ha title, slug, platforms e priority.]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `uses` [INFERRED]
- [[Priority deve essere un intero ≥ 1.]] - `uses` [INFERRED]
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - `uses` [INFERRED]
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - `uses` [INFERRED]
- [[Resetta il progresso dopo un batch completato con successo.]] - `uses` [INFERRED]
- [[Salva il progresso corrente nel DB.]] - `uses` [INFERRED]
- [[Test per il modulo Discovery SeedLoader + IGDBDiscovery — zero HTTP reali.]] - `uses` [INFERRED]
- [[TestIGDBDiscovery]] - `uses` [INFERRED]
- [[TestLoadSeedFile]] - `uses` [INFERRED]
- [[TestTopGamesSeedFile]] - `uses` [INFERRED]
- [[ValueError se il JSON non è una lista.]] - `uses` [INFERRED]
- [[_get_token chiama POST una volta sola se il token è ancora valido.]] - `uses` [INFERRED]
- [[discover_all_games si ferma quando fetch_games ritorna lista vuota.]] - `uses` [INFERRED]
- [[fetch_games ritorna la lista di giochi parsata dal JSON IGDB.]] - `uses` [INFERRED]
- [[load_seed_file restituisce lista di dict da JSON valido.]] - `uses` [INFERRED]
- [[seed_loader.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/IGDB_Discovery_&_Seeds