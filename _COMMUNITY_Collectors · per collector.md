---
type: community
cohesion: 0.02
members: 144
---

# Collectors · per collector

**Cohesion:** 0.02 - loosely connected
**Members:** 144 nodes

## Members
- [[.__init__()_1]] - code - harvester\src\collectors\base.py
- [[.__init__()]] - code - harvester\src\collectors\base.py
- [[._is_allowed()]] - code - harvester\src\collectors\base.py
- [[._load_robots()]] - code - harvester\src\collectors\base.py
- [[._respect_delay()]] - code - harvester\src\collectors\base.py
- [[.acquire()]] - code - harvester\src\collectors\base.py
- [[.close()]] - code - harvester\src\collectors\base.py
- [[.collect()]] - code - harvester\src\collectors\base.py
- [[.discover_guides()]] - code - harvester\src\collectors\steam_community.py
- [[.extract()_3]] - code - harvester\src\collectors\guide_search.py
- [[.extract()_6]] - code - harvester\src\collectors\psnprofiles.py
- [[.extract()_13]] - code - harvester\tests\test_base_collector.py
- [[.extract()_10]] - code - harvester\src\collectors\trueachievements.py
- [[.fetch()]] - code - harvester\src\collectors\base.py
- [[.fetch()_1]] - code - harvester\src\collectors\steam_community.py
- [[.search_wiki()]] - code - harvester\src\collectors\fandom.py
- [[.test_deterministic()]] - code - harvester\tests\test_base_collector.py
- [[.test_different_input_different_hash()]] - code - harvester\tests\test_base_collector.py
- [[.test_has_http_client()]] - code - harvester\tests\test_collectors.py
- [[.test_has_http_client()_1]] - code - harvester\tests\test_collectors.py
- [[.test_hex_format()]] - code - harvester\tests\test_base_collector.py
- [[.test_inherits_base_collector()]] - code - harvester\tests\test_collectors.py
- [[.test_inherits_base_collector()_1]] - code - harvester\tests\test_collectors.py
- [[.test_user_agent_from_settings()]] - code - harvester\tests\test_base_collector.py
- [[ABC]] - code
- [[Applica filtri qualità + anonimizza.  None se scartato.]] - rationale - harvester\src\collectors\reddit.py
- [[Aspetta almeno settings.scrape_delay_seconds tra richieste allo stesso dominio.]] - rationale - harvester\src\collectors\base.py
- [[Attende fino a quando un token è disponibile per host.]] - rationale - harvester\src\collectors\base.py
- [[BaseCollector]] - code - harvester\src\collectors\base.py
- [[BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En]] - rationale - harvester\src\collectors\base.py
- [[Calcola SHA-256 di text e ritorna l'hash esadecimale.]] - rationale - harvester\src\collectors\base.py
- [[Cerca pagine nel wiki Fandom e ritorna lista di titoli.          Usa action=quer]] - rationale - harvester\src\collectors\fandom.py
- [[Chiude il client httpx.]] - rationale - harvester\src\collectors\base.py
- [[Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi]] - rationale - harvester\src\collectors\base.py
- [[Collassa spazi multipli e normalizza newline._1]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Collassa spazi multipli e normalizza newline._2]] - rationale - harvester\src\collectors\trueachievements.py
- [[Collector per Steam Community Guides via API ufficiale.      Uso tipico (dal pip]] - rationale - harvester\src\collectors\steam_community.py
- [[Collector per guide achievement su trueachievements.com.]] - rationale - harvester\src\collectors\trueachievements.py
- [[Collector per guide trofei su powerpyx.com.]] - rationale - harvester\src\collectors\powerpyx.py
- [[Collector per guide trofei su psnprofiles.com.]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Collector per guide video da YouTube via Data API v3 + transcript.]] - rationale - harvester\src\collectors\youtube.py
- [[Collector per guide wiki da Fandom via MediaWiki API.]] - rationale - harvester\src\collectors\fandom.py
- [[Collector per post Reddit — aggrega titolo + selftext + top commenti.]] - rationale - harvester\src\collectors\reddit.py
- [[Collector per wiki IGN (boss, walkthrough, collectible).]] - rationale - harvester\src\collectors\ign.py
- [[Collector per wiki.fextralife.com (boss, build, lore).]] - rationale - harvester\src\collectors\fextralife.py
- [[Contenuto  200 char → None.]] - rationale - harvester\tests\test_collectors.py
- [[Contenuto  200 char → None._1]] - rationale - harvester\tests\test_collectors.py
- [[Converte tabelle table class=zebra in testo strutturato pipe-delimited.]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Estrae game_name dall'URL PSNProfiles.      Formati tipici       - guide12345]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Estrae game_name dall'URL TrueAchievements.      Formati tipici       - gamee]] - rationale - harvester\src\collectors\trueachievements.py
- [[Estrae titolo, lista achievement e testo da TrueAchievements.          Ritorna N]] - rationale - harvester\src\collectors\trueachievements.py
- [[Estrae titolo, tabelle trofei e testo dalla guida PSNProfiles.          Ritorna]] - rationale - harvester\src\collectors\psnprofiles.py
- [[Fetch con redazione di `key=...` nei log.          Implementazione ricalca Base]] - rationale - harvester\src\collectors\steam_community.py
- [[HTML valido con guide → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_collectors.py
- [[HTML valido con .wiki-article → dict con tutti i campi richiesti.]] - rationale - harvester\tests\test_collectors.py
- [[Il client httpx usa lo User-Agent configurato in settings.]] - rationale - harvester\tests\test_base_collector.py
- [[Il rate limiting è ereditato il client httpx deve essere inizializzato.]] - rationale - harvester\tests\test_collectors.py
- [[Il rate limiting è ereditato il client httpx deve essere inizializzato._1]] - rationale - harvester\tests\test_collectors.py
- [[Input diversi producono hash diversi.]] - rationale - harvester\tests\test_base_collector.py
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - rationale - harvester\tests\test_base_collector.py
- [[La lista achievement deve comparire nel raw_content.]] - rationale - harvester\tests\test_collectors.py
- [[La prima acquire per un host non deve aspettare.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima fetch() triggera _load_robots(); le successive no.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima richiesta (last_request_time=0) non deve attendere.]] - rationale - harvester\tests\test_base_collector.py
- [[La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).]] - rationale - harvester\tests\test_base_collector.py
- [[La tabella trofei deve comparire nel raw_content come testo pipe-delimited.]] - rationale - harvester\tests\test_collectors.py
- [[Lo stesso input produce sempre lo stesso hash.]] - rationale - harvester\tests\test_base_collector.py
- [[Non usato direttamente — GuideSearchCollector è solo per discovery.]] - rationale - harvester\src\collectors\guide_search.py
- [[PSNProfilesCollector]] - code - harvester\src\collectors\psnprofiles.py
- [[PSNProfilesCollector deve ereditare da BaseCollector.]] - rationale - harvester\tests\test_collectors.py
- [[PSNProfilesCollector — collector per psnprofiles.com.  Guide trophy nella sezion]] - rationale - harvester\src\collectors\psnprofiles.py
- [[PerHostTokenBucket]] - code - harvester\src\collectors\base.py
- [[Pipeline completa fetch → extract.  Ritorna i dati strutturati o None.]] - rationale - harvester\src\collectors\base.py
- [[Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi]] - rationale - harvester\src\collectors\base.py
- [[Ritorna top guide filtrate (EN, viewsvotes soglia minima).          Ogni elemen]] - rationale - harvester\src\collectors\steam_community.py
- [[Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile.]] - rationale - harvester\src\collectors\base.py
- [[Scarica una pagina rispettando rate limit globale e per-host.          Ritorna i]] - rationale - harvester\src\collectors\base.py
- [[Scopre URL di guide via DuckDuckGo per query libere.]] - rationale - harvester\src\collectors\guide_search.py
- [[Script, sidebar, footer, commenti non devono comparire nel testo.]] - rationale - harvester\tests\test_collectors.py
- [[Script, style, sidebar, footer, commenti non devono comparire nel testo.]] - rationale - harvester\tests\test_collectors.py
- [[Se l'ultima richiesta è recente, _respect_delay aspetta la differenza.]] - rationale - harvester\tests\test_base_collector.py
- [[Serializza un post+commenti in testo pulito, senza username.]] - rationale - harvester\src\collectors\reddit.py
- [[Stesso input → stesso content_hash.]] - rationale - harvester\tests\test_collectors.py
- [[Stesso input → stesso content_hash._1]] - rationale - harvester\tests\test_collectors.py
- [[Test per BaseCollector — rate limiting, robots.txt, fetch, hash.]] - rationale - harvester\tests\test_base_collector.py
- [[Test per PSNProfilesCollector e TrueAchievementsCollector.  HTML di esempio inve]] - rationale - harvester\tests\test_collectors.py
- [[TestComputeHash]] - code - harvester\tests\test_base_collector.py
- [[TestFetch]] - code - harvester\tests\test_base_collector.py
- [[TestPSNProfilesCollector]] - code - harvester\tests\test_collectors.py
- [[TestPerHostTokenBucket]] - code - harvester\tests\test_base_collector.py
- [[TestRespectDelay]] - code - harvester\tests\test_base_collector.py
- [[TestRobotsTxt]] - code - harvester\tests\test_base_collector.py
- [[TestTrueAchievementsCollector]] - code - harvester\tests\test_collectors.py
- [[TestUserAgent]] - code - harvester\tests\test_base_collector.py
- [[TrueAchievementsCollector]] - code - harvester\src\collectors\trueachievements.py
- [[TrueAchievementsCollector deve ereditare da BaseCollector.]] - rationale - harvester\tests\test_collectors.py
- [[TrueAchievementsCollector — collector per trueachievements.com.  Guide achieveme]] - rationale - harvester\src\collectors\trueachievements.py
- [[Verifica se url è permesso da robots.txt.  Fail-open se non caricato.]] - rationale - harvester\src\collectors\base.py
- [[_StubCollector]] - code - harvester\tests\test_base_collector.py
- [[_convert_tables_to_text()]] - code - harvester\src\collectors\psnprofiles.py
- [[_extract_title()_4]] - code - harvester\src\collectors\psnprofiles.py
- [[_extract_title()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_is_allowed ritorna True se robots.txt non è stato caricato (fail-open).]] - rationale - harvester\tests\test_base_collector.py
- [[_normalize_whitespace()_4]] - code - harvester\src\collectors\psnprofiles.py
- [[_normalize_whitespace()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_game_name_from_url()]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_url_slug()_3]] - code - harvester\src\collectors\psnprofiles.py
- [[base.py]] - code - harvester\src\collectors\base.py
- [[collector()]] - code - harvester\tests\test_base_collector.py
- [[compute_hash()]] - code - harvester\src\collectors\base.py
- [[extract()]] - code - harvester\src\collectors\base.py
- [[fetch() ritorna None se il server risponde 403.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se il server risponde 429 (rate limited).]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se robots.txt vieta l'URL.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None su timeout.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna il body HTML su status 200.]] - rationale - harvester\tests\test_base_collector.py
- [[game_name estratto dallo slug game{slug}.]] - rationale - harvester\tests\test_collectors.py
- [[game_name estratto rimuovendo il prefisso numerico dallo slug.]] - rationale - harvester\tests\test_collectors.py
- [[psn_collector()]] - code - harvester\tests\test_collectors.py
- [[psnprofiles.py]] - code - harvester\src\collectors\psnprofiles.py
- [[semaphore()]] - code - harvester\tests\test_base_collector.py
- [[ta_collector()]] - code - harvester\tests\test_collectors.py
- [[test_achievement_list_preserved()]] - code - harvester\tests\test_collectors.py
- [[test_allowed_when_no_robots()]] - code - harvester\tests\test_base_collector.py
- [[test_base_collector.py]] - code - harvester\tests\test_base_collector.py
- [[test_collectors.py]] - code - harvester\tests\test_collectors.py
- [[test_empty_content_returns_none()]] - code - harvester\tests\test_collectors.py
- [[test_first_acquire_no_wait()]] - code - harvester\tests\test_base_collector.py
- [[test_game_name_from_url()]] - code - harvester\tests\test_collectors.py
- [[test_game_name_stripped_from_url()]] - code - harvester\tests\test_collectors.py
- [[test_hash_deterministic()]] - code - harvester\tests\test_collectors.py
- [[test_junk_removed()]] - code - harvester\tests\test_collectors.py
- [[test_lazy_load_robots_on_first_fetch()]] - code - harvester\tests\test_base_collector.py
- [[test_no_wait_first_request()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_html_on_200()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_403()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_429()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_timeout()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_when_disallowed()]] - code - harvester\tests\test_base_collector.py
- [[test_second_acquire_waits()]] - code - harvester\tests\test_base_collector.py
- [[test_table_converted_to_text()]] - code - harvester\tests\test_collectors.py
- [[test_valid_html_returns_full_dict()]] - code - harvester\tests\test_collectors.py
- [[test_waits_correct_time()]] - code - harvester\tests\test_base_collector.py
- [[trueachievements.py]] - code - harvester\src\collectors\trueachievements.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Collectors_·_per_collector
SORT file.name ASC
```

## Connections to other communities
- 86 edges to [[_COMMUNITY_Orchestrator · per guide]]
- 9 edges to [[_COMMUNITY_Collectors · ddg guide]]
- 7 edges to [[_COMMUNITY_Collectors · youtube transcript]]
- 6 edges to [[_COMMUNITY_Collectors · exophase per]]
- 6 edges to [[_COMMUNITY_Collectors · guide mediawiki]]
- 6 edges to [[_COMMUNITY_Collectors · org per]]
- 6 edges to [[_COMMUNITY_Collectors · truetrophies per]]
- 5 edges to [[_COMMUNITY_Collectors · json post]]
- 4 edges to [[_COMMUNITY_Collectors · powerpyx url]]
- 4 edges to [[_COMMUNITY_Collectors · steam guide]]
- 2 edges to [[_COMMUNITY_Collectors · fextralife wiki]]
- 2 edges to [[_COMMUNITY_Collectors · ign com]]

## Top bridge nodes
- [[BaseCollector]] - degree 162, connects to 12 communities
- [[PSNProfilesCollector]] - degree 51, connects to 1 community
- [[TrueAchievementsCollector]] - degree 42, connects to 1 community
- [[_StubCollector]] - degree 6, connects to 1 community
- [[.discover_guides()]] - degree 3, connects to 1 community