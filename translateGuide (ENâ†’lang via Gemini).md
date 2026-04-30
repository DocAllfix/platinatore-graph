---
source_file: "backend/src/services/llm.service.ts"
type: "code"
community: "Circuit Breaker + Guide Cache"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Circuit_Breaker_+_Guide_Cache
---

# translateGuide (ENâ†’lang via Gemini)

## Connections
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - `shares_data_with` [INFERRED]
- [[gemini-chat CircuitBreaker instance]] - `calls` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `calls` [EXTRACTED]
- [[primaryModel (GoogleGenerativeAI client)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Circuit_Breaker_+_Guide_Cache