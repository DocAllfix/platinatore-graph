---
source_file: "backend/src/services/llm.service.ts"
type: "code"
community: "Services · template circuitbreaker"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Services_·_template_circuitbreaker
---

# generateGuideStream (Gemini SSE)

## Connections
- [[CircuitBreaker (CLOSEDOPENHALF_OPEN)]] - `shares_data_with` [INFERRED]
- [[CircuitOpenError_1]] - `references` [EXTRACTED]
- [[buildPrompt (template dispatcher)]] - `calls` [EXTRACTED]
- [[gemini-chat CircuitBreaker instance]] - `calls` [EXTRACTED]
- [[handleGuideStream (SSE 7-step generator)]] - `calls` [EXTRACTED]
- [[primaryModel (GoogleGenerativeAI client)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Services_·_template_circuitbreaker