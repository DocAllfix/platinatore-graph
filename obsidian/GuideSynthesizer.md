---
source_file: "harvester\src\transformer\synthesizer.py"
type: "code"
community: "Embedding Service"
location: "L33"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/Embedding_Service
---

# GuideSynthesizer

## Connections
- [[.__init__()_7]] - `method` [EXTRACTED]
- [[._call_gemini()]] - `method` [EXTRACTED]
- [[._check_daily_limit()_1]] - `method` [EXTRACTED]
- [[.extract_facts()]] - `method` [EXTRACTED]
- [[.synthesize_guide()]] - `method` [EXTRACTED]
- [[.transform()]] - `method` [EXTRACTED]
- [[Chiude tutti i client HTTP.]] - `uses` [INFERRED]
- [[HarvestPipeline]] - `uses` [INFERRED]
- [[HarvestPipeline — orchestratore che connette collector → transformer → injector.]] - `uses` [INFERRED]
- [[Heartbeat file per Docker healthcheck (W-ARCH-2).]] - `uses` [INFERRED]
- [[Legge l'ultimo slug processato dal DB.]] - `uses` [INFERRED]
- [[Orchestra la pipeline completa collect → transform → inject.]] - `uses` [INFERRED]
- [[Processa tutti i giochi del seed file con advisory lock singleton.          Rito]] - `uses` [INFERRED]
- [[Processa una singola guida end-to-end. Ritorna True se iniettata.]] - `uses` [INFERRED]
- [[Resetta il progresso dopo un batch completato con successo.]] - `uses` [INFERRED]
- [[Salva il progresso corrente nel DB.]] - `uses` [INFERRED]
- [[Se _gemini_calls_today = settings.daily_gemini_limit → False.]] - `uses` [INFERRED]
- [[Test per il modulo Transformer — prompts, quality score, daily limit.  NON chiam]] - `uses` [INFERRED]
- [[TestDailyLimit]] - `uses` [INFERRED]
- [[TestPrompts]] - `uses` [INFERRED]
- [[TestQualityScore]] - `uses` [INFERRED]
- [[Wrapper Gemini per estrazione fatti + sintesi guide.]] - `rationale_for` [EXTRACTED]
- [[synthesizer.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/Embedding_Service