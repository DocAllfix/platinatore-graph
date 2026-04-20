---
type: community
cohesion: 0.15
members: 18
---

# Trophy Section Extractor

**Cohesion:** 0.15 - loosely connected
**Members:** 18 nodes

## Members
- [[Associa ogni trophy_name alla sezione con heading più simile.      Ritorna dict]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Converte un id anchor in un nome leggibile underscoretrattini → spazi, title c]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Estrae sezioni per-trofeo da un HTML di guida.      Ritorna lista di dict]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Estrazione anchor-based per PowerPyx e strutture simili.      Cerca tutti i tag]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Estrazione heading-based h2h3h4 come delimitatori di sezione.]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Normalizza il nome per il confronto minuscolo, no accenti, solo alfanumspazi.]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[Similarity tra due stringhe normalizzate (0.0 – 1.0).]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[TrophySectionExtractor — estrae sezioni per-trofeo da HTML di guide.  Supporta d]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[True se il tag a id=... ha un id che assomiglia a un nome di trofeo.      Cr]] - rationale - harvester\src\collectors\trophy_section_extractor.py
- [[_anchor_id_to_name()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[_extract_sections_by_anchors()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[_extract_sections_by_headings()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[_is_trophy_anchor()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[_normalize_name()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[_similarity()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[extract_trophy_sections()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[match_trophies_to_sections()]] - code - harvester\src\collectors\trophy_section_extractor.py
- [[trophy_section_extractor.py]] - code - harvester\src\collectors\trophy_section_extractor.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Trophy_Section_Extractor
SORT file.name ASC
```
