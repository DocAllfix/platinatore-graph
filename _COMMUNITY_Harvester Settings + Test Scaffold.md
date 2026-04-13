---
type: community
cohesion: 0.29
members: 7
---

# Harvester Settings + Test Scaffold

**Cohesion:** 0.29 - loosely connected
**Members:** 7 nodes

## Members
- [[BaseSettings]] - code
- [[Settings]] - code - harvester\src\config\settings.py
- [[Settings con valori di test, senza connessioni reali a DB o Redis.     Utile per]] - rationale - harvester\tests\conftest.py
- [[conftest.py_1]] - code - harvester\tests\conftest.py
- [[mock_settings()]] - code - harvester\tests\conftest.py
- [[settings.py]] - code - c:\Users\user\PlatinatoreAI\il-platinatore-ai\harvester\src\config\settings.py
- [[settings.py_1]] - code - harvester\src\config\settings.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Harvester_Settings_+_Test_Scaffold
SORT file.name ASC
```
