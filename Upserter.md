---
source_file: "harvester\src\injector\upserter.py"
type: "code"
community: "Injector Deduplication"
location: "L60"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Injector_Deduplication
---

# Upserter

## Connections
- [[.__init__()_11]] - `method` [EXTRACTED]
- [[._find_or_create_game_tx()]] - `method` [EXTRACTED]
- [[._find_or_create_trophy_tx()]] - `method` [EXTRACTED]
- [[.find_or_create_game()]] - `method` [EXTRACTED]
- [[.find_or_create_trophy()]] - `method` [EXTRACTED]
- [[.upsert_guide()]] - `method` [EXTRACTED]
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - `uses` [INFERRED]
- [[Cerca guide via DDG e fetcha tutti gli URL IN PARALLELO.      Ritorna {trophy_na]] - `uses` [INFERRED]
- [[Cerca tips per un trofeo specifico su rTrophies (async, no semaphore).]] - `uses` [INFERRED]
- [[Chiude il client httpx._1]] - `uses` [INFERRED]
- [[Chiude tutti i client HTTP.]] - `uses` [INFERRED]
- [[Client IGDB per discovery automatica giochi e popolamento catalogo DB.]] - `uses` [INFERRED]
- [[Controlla se giochi in upcoming_games sono stati rilasciati.          Per ogni u]] - `uses` [INFERRED]
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - `uses` [INFERRED]
- [[Converte una lista float nel literal pgvector 'f1,f2,...'.      Usato per INSE]] - `uses` [INFERRED]
- [[Deduplicator]] - `uses` [INFERRED]
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - `uses` [INFERRED]
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - `uses` [INFERRED]
- [[End-to-end pipeline test — UN singolo gioco reale.  Valida l'intera pipeline co]] - `uses` [INFERRED]
- [[Esegue una query POST su un endpoint IGDB e ritorna la risposta JSON.]] - `uses` [INFERRED]
- [[Fetch generico con browser UA e semaphore globale.      Usato per URL di guida s]] - `uses` [INFERRED]
- [[Fetch un URL guida ed estrae le sezioni trophy matchate.      Ritorna (url, {tro]] - `uses` [INFERRED]
- [[Genera e salva la guida per un singolo trofeo. Ritorna status string.]] - `uses` [INFERRED]
- [[Genera guide boss per un gioco usando Fextralife + IGN.          Se boss_names è]] - `uses` [INFERRED]
- [[Genera guide per i trofei platgold di un gioco.      Trofei processati in batch]] - `uses` [INFERRED]
- [[Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P]] - `uses` [INFERRED]
- [[Gestisce l'INSERT atomico di guida + fonti in una transazione.]] - `rationale_for` [EXTRACTED]
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - `uses` [INFERRED]
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - `uses` [INFERRED]
- [[IGDBDiscovery]] - `uses` [INFERRED]
- [[IGDBDiscovery — popola il catalogo giochi via IGDB API v4.  Autenticazione Twit]] - `uses` [INFERRED]
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - `uses` [INFERRED]
- [[Inserisce alias per il gioco titolo completo + slug IGDB.]] - `uses` [INFERRED]
- [[Inserisce righe in guide_embeddings. TEST-ONLY bypassa il worker Node.js.]] - `uses` [INFERRED]
- [[Inserisce un gioco da dati IGDB se non già presente.          Salva igdb_id sia]] - `uses` [INFERRED]
- [[Legge l'ultimo slug processato dal DB.]] - `uses` [INFERRED]
- [[Mappa gli ID piattaforma IGDB ai nomi leggibili.]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `uses` [INFERRED]
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - `uses` [INFERRED]
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - `uses` [INFERRED]
- [[Raccoglie contenuti wiki da Fandom per un gioco.          Se `wiki_subdomain` è]] - `uses` [INFERRED]
- [[Recupera giochi IGDB per le piattaforme indicate.          IGDB usa POST con bod]] - `uses` [INFERRED]
- [[Recupera giochi upcoming con alto hypefollowing.          status=2 = alpha, 3]] - `uses` [INFERRED]
- [[Recupera giochi usciti negli ultimi N giorni per piattaforma.          Usa l'end]] - `uses` [INFERRED]
- [[Recupera i dettagli dei giochi per una lista di IGDB IDs.]] - `uses` [INFERRED]
- [[Recupera i giochi più giocati via popularity_primitives.          popularity_typ]] - `uses` [INFERRED]
- [[Resetta il progresso dopo un batch completato con successo.]] - `uses` [INFERRED]
- [[Ricerca coseno su guide_embeddings. Ritorna le righe più simili.]] - `uses` [INFERRED]
- [[Risolve steam_appid per giochi con igdb_id ma senza steam_appid.          Usa l']] - `uses` [INFERRED]
- [[Ritorna il token Twitch OAuth, richiedendolorinnovandolo se scaduto.]] - `uses` [INFERRED]
- [[SHA256 di url+extra, troncato a 64 char per content_hash NOT NULL.]] - `uses` [INFERRED]
- [[Salva il progresso corrente nel DB.]] - `uses` [INFERRED]
- [[Scarica tutti i giochi IGDB per le piattaforme e li inserisce nel DB.          P]] - `uses` [INFERRED]
- [[Scopre giochi popolari e nuove uscite, li inserisce in games.          Ritorna s]] - `uses` [INFERRED]
- [[Scopre giochi upcoming e li salva in upcoming_games.          Non li mette in ga]] - `uses` [INFERRED]
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - `uses` [INFERRED]
- [[Slug URL-safe NFKD + minuscolo + solo alfanum e trattini.]] - `uses` [INFERRED]
- [[Verdetto di ammissibilità per un gioco IGDB.          Ritorna 'ok'  'mobile']] - `uses` [INFERRED]
- [[upserter.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/Injector_Deduplication