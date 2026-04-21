---
source_file: "harvester\src\transformer\synthesizer.py"
type: "code"
community: "Orchestrator · per guide"
location: "L41"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Orchestrator_·_per_guide
---

# GuideSynthesizer

## Connections
- [[.__init__()_13]] - `method` [EXTRACTED]
- [[._call_deepseek()]] - `method` [EXTRACTED]
- [[._call_gemini()]] - `method` [EXTRACTED]
- [[._call_llm()]] - `method` [EXTRACTED]
- [[._check_daily_limit()_1]] - `method` [EXTRACTED]
- [[.extract_facts()]] - `method` [EXTRACTED]
- [[.synthesize_guide()]] - `method` [EXTRACTED]
- [[.transform()]] - `method` [EXTRACTED]
- [[Arricchisce guide con community tips da Reddit.          Per ogni query (default]] - `uses` [INFERRED]
- [[Cerca guide via DDG e fetcha tutti gli URL IN PARALLELO.      Ritorna {trophy_na]] - `uses` [INFERRED]
- [[Cerca tips per un trofeo specifico su rTrophies (async, no semaphore).]] - `uses` [INFERRED]
- [[Chiude tutti i client HTTP.]] - `uses` [INFERRED]
- [[Converte 'Elden Ring' → 'elden-ring' (URL slug conservativo).]] - `uses` [INFERRED]
- [[Converte una lista float nel literal pgvector 'f1,f2,...'.      Usato per INSE]] - `uses` [INFERRED]
- [[Discovery + collect di Steam Community Guides per un gioco.          Richiede `g]] - `uses` [INFERRED]
- [[Discovery + inject di guide video YouTube per un gioco.          Per ogni query]] - `uses` [INFERRED]
- [[End-to-end pipeline test — UN singolo gioco reale.  Valida l'intera pipeline co]] - `uses` [INFERRED]
- [[Fetch generico con browser UA e semaphore globale.      Usato per URL di guida s]] - `uses` [INFERRED]
- [[Fetch un URL guida ed estrae le sezioni trophy matchate.      Ritorna (url, {tro]] - `uses` [INFERRED]
- [[Genera e salva la guida per un singolo trofeo. Ritorna status string.]] - `uses` [INFERRED]
- [[Genera guide boss per un gioco usando Fextralife + IGN.          Se boss_names è]] - `uses` [INFERRED]
- [[Genera guide per i trofei platgold di un gioco.      Trofei processati in batch]] - `uses` [INFERRED]
- [[Genera guide per-trofeo (platinum + gold) per i top 20 giochi con trofei PSN.  P]] - `uses` [INFERRED]
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - `uses` [INFERRED]
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - `uses` [INFERRED]
- [[Inietta un contenuto già raccolto (bypass collect step).          Include dedup]] - `uses` [INFERRED]
- [[Inserisce righe in guide_embeddings. TEST-ONLY bypassa il worker Node.js.]] - `uses` [INFERRED]
- [[Legge l'ultimo slug processato dal DB.]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `uses` [INFERRED]
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - `uses` [INFERRED]
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - `uses` [INFERRED]
- [[Raccoglie contenuti wiki da Fandom per un gioco.          Se `wiki_subdomain` è]] - `uses` [INFERRED]
- [[Resetta il progresso dopo un batch completato con successo.]] - `uses` [INFERRED]
- [[Ricerca coseno su guide_embeddings. Ritorna le righe più simili.]] - `uses` [INFERRED]
- [[SHA256 di url+extra, troncato a 64 char per content_hash NOT NULL.]] - `uses` [INFERRED]
- [[Salva il progresso corrente nel DB.]] - `uses` [INFERRED]
- [[Se _gemini_calls_today = settings.daily_gemini_limit → False.]] - `uses` [INFERRED]
- [[Seleziona il collector corretto in base al dominio dell'URL.          Usa match]] - `uses` [INFERRED]
- [[Slug URL-safe NFKD + minuscolo + solo alfanum e trattini.]] - `uses` [INFERRED]
- [[Test per il modulo Transformer — prompts, quality score, daily limit.  NON chiam]] - `uses` [INFERRED]
- [[TestDailyLimit]] - `uses` [INFERRED]
- [[TestPrompts]] - `uses` [INFERRED]
- [[TestQualityScore]] - `uses` [INFERRED]
- [[Wrapper multi-provider per estrazione fatti + sintesi guide.]] - `rationale_for` [EXTRACTED]
- [[synthesizer.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/Orchestrator_·_per_guide