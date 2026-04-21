---
source_file: "backend/src/services/llm.service.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# translateGuide (ENâ†’lang via Gemini)

## Connections
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - `shares_data_with` [INFERRED]
- [[gemini-chat CircuitBreaker instance]] - `calls` [EXTRACTED]
- [[handleGuideRequest (non-streaming 7-step)]] - `calls` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `calls` [EXTRACTED]
- [[primaryModel (GoogleGenerativeAI client)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker