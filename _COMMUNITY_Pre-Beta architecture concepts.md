---
type: community
cohesion: 0.06
members: 41
---

# Pre-Beta architecture concepts

**Cohesion:** 0.06 - loosely connected
**Members:** 41 nodes

## Members
- [[.extract()_2]] - code - harvester\src\collectors\fextralife.py
- [[.extract()_4]] - code - harvester\src\collectors\ign.py
- [[.extract()_5]] - code - harvester\src\collectors\powerpyx.py
- [[.extract()_10]] - code - harvester\src\collectors\trueachievements.py
- [[BaseCollector_1]] - code
- [[Collassa spazi multipli e normalizza newline.]] - rationale - harvester\src\collectors\powerpyx.py
- [[Collassa spazi multipli e normalizza newline._2]] - rationale - harvester\src\collectors\trueachievements.py
- [[Collector per guide achievement su trueachievements.com.]] - rationale - harvester\src\collectors\trueachievements.py
- [[Collector per guide trofei su powerpyx.com.]] - rationale - harvester\src\collectors\powerpyx.py
- [[Collector per wiki IGN (boss, walkthrough, collectible).]] - rationale - harvester\src\collectors\ign.py
- [[Collector per wiki.fextralife.com (boss, build, lore).]] - rationale - harvester\src\collectors\fextralife.py
- [[Estrae game_name dall'URL TrueAchievements.      Formati tipici       - gamee]] - rationale - harvester\src\collectors\trueachievements.py
- [[Estrae game_name e topic da URL ign.comwikis{game}{topic}.]] - rationale - harvester\src\collectors\ign.py
- [[Estrae game_name e topic dallo slug Fextralife.      Pattern wiki.fextralife.co]] - rationale - harvester\src\collectors\fextralife.py
- [[Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae titolo, lista achievement e testo da TrueAchievements.          Ritorna N]] - rationale - harvester\src\collectors\trueachievements.py
- [[FextralifeCollector]] - code - harvester\src\collectors\fextralife.py
- [[FextralifeCollector — guide wiki SoulslikeMetroidvania.  Fextralife usa renderi]] - rationale - harvester\src\collectors\fextralife.py
- [[IGNCollector]] - code - harvester\src\collectors\ign.py
- [[IGNCollector — guide wiki professionali su ign.com.  Pattern URL ign.comwikis]] - rationale - harvester\src\collectors\ign.py
- [[PowerPyxCollector]] - code - harvester\src\collectors\powerpyx.py
- [[PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di]] - rationale - harvester\src\collectors\powerpyx.py
- [[TrueAchievementsCollector]] - code - harvester\src\collectors\trueachievements.py
- [[TrueAchievementsCollector — collector per trueachievements.com.  Guide achieveme]] - rationale - harvester\src\collectors\trueachievements.py
- [[_extract_title()_1]] - code - harvester\src\collectors\fextralife.py
- [[_extract_title()_2]] - code - harvester\src\collectors\ign.py
- [[_extract_title()_3]] - code - harvester\src\collectors\powerpyx.py
- [[_extract_title()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_normalize_whitespace()_1]] - code - harvester\src\collectors\fextralife.py
- [[_normalize_whitespace()_2]] - code - harvester\src\collectors\ign.py
- [[_normalize_whitespace()_3]] - code - harvester\src\collectors\powerpyx.py
- [[_normalize_whitespace()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_game_name_from_url()]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_url_slug()]] - code - harvester\src\collectors\fextralife.py
- [[_parse_url_slug()_1]] - code - harvester\src\collectors\ign.py
- [[_parse_url_slug()_2]] - code - harvester\src\collectors\powerpyx.py
- [[fextralife.py]] - code - harvester\src\collectors\fextralife.py
- [[ign.py]] - code - harvester\src\collectors\ign.py
- [[powerpyx.py]] - code - harvester\src\collectors\powerpyx.py
- [[trueachievements.py]] - code - harvester\src\collectors\trueachievements.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Pre-Beta_architecture_concepts
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_Community 35]]
- 1 edge to [[_COMMUNITY_Community 25]]
- 1 edge to [[_COMMUNITY_Community 8]]
- 1 edge to [[_COMMUNITY_Community 34]]
- 1 edge to [[_COMMUNITY_Community 36]]
- 1 edge to [[_COMMUNITY_Community 26]]
- 1 edge to [[_COMMUNITY_Community 33]]
- 1 edge to [[_COMMUNITY_Community 37]]
- 1 edge to [[_COMMUNITY_Community 21]]
- 1 edge to [[_COMMUNITY_Fextralife Collector]]

## Top bridge nodes
- [[BaseCollector_1]] - degree 14, connects to 10 communities