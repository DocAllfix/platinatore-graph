---
type: community
cohesion: 0.33
members: 6
---

# ._call_deepseek()

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[._call_deepseek()]] - code - harvester\src\transformer\synthesizer.py
- [[._call_gemini()]] - code - harvester\src\transformer\synthesizer.py
- [[._call_llm()]] - code - harvester\src\transformer\synthesizer.py
- [[Chiamata DeepSeek sincrona via OpenAI-compatible SDK.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Chiamata Gemini sincrona via google-genai SDK.]] - rationale - harvester\src\transformer\synthesizer.py
- [[Dispatch al provider configurato.]] - rationale - harvester\src\transformer\synthesizer.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/._call_deepseek()
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[._call_llm()]] - degree 4, connects to 1 community
- [[._call_deepseek()]] - degree 3, connects to 1 community
- [[._call_gemini()]] - degree 3, connects to 1 community