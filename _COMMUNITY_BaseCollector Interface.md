---
type: community
cohesion: 0.02
members: 136
---

# BaseCollector Interface

**Cohesion:** 0.02 - loosely connected
**Members:** 136 nodes

## Members
- [[.__init__()_1]] - code - harvester\src\collectors\base.py
- [[.__init__()]] - code - harvester\src\collectors\base.py
- [[._ddg_fetch()]] - code - harvester\src\collectors\guide_search.py
- [[._is_allowed()]] - code - harvester\src\collectors\base.py
- [[._load_robots()]] - code - harvester\src\collectors\base.py
- [[._respect_delay()]] - code - harvester\src\collectors\base.py
- [[.acquire()]] - code - harvester\src\collectors\base.py
- [[.close()]] - code - harvester\src\collectors\base.py
- [[.collect()]] - code - harvester\src\collectors\base.py
- [[.collect()_1]] - code - harvester\src\collectors\fandom.py
- [[.discover_guides()]] - code - harvester\src\collectors\steam_community.py
- [[.extract()_1]] - code - harvester\src\collectors\fandom.py
- [[.extract()_3]] - code - harvester\src\collectors\guide_search.py
- [[.extract()_5]] - code - harvester\src\collectors\powerpyx.py
- [[.extract()_13]] - code - harvester\tests\test_base_collector.py
- [[.extract()_10]] - code - harvester\src\collectors\trueachievements.py
- [[.fetch()]] - code - harvester\src\collectors\base.py
- [[.fetch()_1]] - code - harvester\src\collectors\steam_community.py
- [[.fetch_page()]] - code - harvester\src\collectors\fandom.py
- [[.search_guide_urls()]] - code - harvester\src\collectors\guide_search.py
- [[.search_guide_urls_multi()]] - code - harvester\src\collectors\guide_search.py
- [[.search_wiki()]] - code - harvester\src\collectors\fandom.py
- [[.test_deterministic()]] - code - harvester\tests\test_base_collector.py
- [[.test_different_input_different_hash()]] - code - harvester\tests\test_base_collector.py
- [[.test_hex_format()]] - code - harvester\tests\test_base_collector.py
- [[.test_user_agent_from_settings()]] - code - harvester\tests\test_base_collector.py
- [[ABC]] - code
- [[Applica filtri qualità + anonimizza.  None se scartato.]] - rationale - harvester\src\collectors\reddit.py
- [[Aspetta almeno settings.scrape_delay_seconds tra richieste allo stesso dominio.]] - rationale - harvester\src\collectors\base.py
- [[Attende fino a quando un token è disponibile per host.]] - rationale - harvester\src\collectors\base.py
- [[BaseCollector]] - code - harvester\src\collectors\base.py
- [[BaseCollector — classe astratta per tutti i collector dell'Infinite Ingestion En]] - rationale - harvester\src\collectors\base.py
- [[Calcola SHA-256 di text e ritorna l'hash esadecimale.]] - rationale - harvester\src\collectors\base.py
- [[Cerca guide per una singola query e ritorna URL filtrati.          Args]] - rationale - harvester\src\collectors\guide_search.py
- [[Cerca pagine nel wiki Fandom e ritorna lista di titoli.          Usa action=quer]] - rationale - harvester\src\collectors\fandom.py
- [[Chiude il client httpx.]] - rationale - harvester\src\collectors\base.py
- [[Classe astratta da cui ereditano tutti i collector.      Sottoclassi DEVONO defi]] - rationale - harvester\src\collectors\base.py
- [[Collassa spazi multipli e normalizza newline.]] - rationale - harvester\src\collectors\powerpyx.py
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
- [[Costruisce URL deterministici per i siti più affidabili.      Usato quando DDG è]] - rationale - harvester\src\collectors\guide_search.py
- [[Estrae game_name dall'URL TrueAchievements.      Formati tipici       - gamee]] - rationale - harvester\src\collectors\trueachievements.py
- [[Estrae game_name e trophy_name dallo slug URL di PowerPyx.      Formati tipici]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae gli URL dai risultati HTML di DuckDuckGo.      DuckDuckGo HTML (html.duck]] - rationale - harvester\src\collectors\guide_search.py
- [[Estrae il dominio di un URL.]] - rationale - harvester\src\collectors\guide_search.py
- [[Estrae titolo, contenuto pulito e metadati dall'HTML di PowerPyx.          Ritor]] - rationale - harvester\src\collectors\powerpyx.py
- [[Estrae titolo, lista achievement e testo da TrueAchievements.          Ritorna N]] - rationale - harvester\src\collectors\trueachievements.py
- [[FandomCollector — guide wiki via MediaWiki API (api.php).  Architettura --------]] - rationale - harvester\src\collectors\fandom.py
- [[Fetch con redazione di `key=...` nei log.          Implementazione ricalca Base]] - rationale - harvester\src\collectors\steam_community.py
- [[Fetch diretto a DDG accettando sia 200 che 202.          DDG restituisce 202 com]] - rationale - harvester\src\collectors\guide_search.py
- [[GuideSearchCollector — scoperta fonti guide via DuckDuckGo HTML.  Invece di cost]] - rationale - harvester\src\collectors\guide_search.py
- [[Il client httpx usa lo User-Agent configurato in settings.]] - rationale - harvester\tests\test_base_collector.py
- [[Inferisce guide_type da categorie MediaWiki e titolo pagina.]] - rationale - harvester\src\collectors\fandom.py
- [[Input diversi producono hash diversi.]] - rationale - harvester\tests\test_base_collector.py
- [[L'hash è una stringa esadecimale di 64 caratteri (SHA-256).]] - rationale - harvester\tests\test_base_collector.py
- [[La prima acquire per un host non deve aspettare.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima fetch() triggera _load_robots(); le successive no.]] - rationale - harvester\tests\test_base_collector.py
- [[La prima richiesta (last_request_time=0) non deve attendere.]] - rationale - harvester\tests\test_base_collector.py
- [[La seconda acquire immediata deve attendere ~3 secondi (rate=0.33).]] - rationale - harvester\tests\test_base_collector.py
- [[Lancia _QUERY_TEMPLATES sequenzialmente e aggrega i risultati.          Le query]] - rationale - harvester\src\collectors\guide_search.py
- [[Lo stesso input produce sempre lo stesso hash.]] - rationale - harvester\tests\test_base_collector.py
- [[Non usato direttamente — GuideSearchCollector è solo per discovery.]] - rationale - harvester\src\collectors\guide_search.py
- [[Parsa HTML MediaWiki e ritorna dict standard collector.          `categories` e]] - rationale - harvester\src\collectors\fandom.py
- [[PerHostTokenBucket]] - code - harvester\src\collectors\base.py
- [[Pipeline completa fetch → extract.  Ritorna i dati strutturati o None.]] - rationale - harvester\src\collectors\base.py
- [[PowerPyxCollector — collector concreto per powerpyx.com.  PowerPyx è il sito di]] - rationale - harvester\src\collectors\powerpyx.py
- [[Rate limiter per-host con algoritmo token bucket.      rate = 0.33 → max 1 richi]] - rationale - harvester\src\collectors\base.py
- [[Rimuove tag HTML e decodifica entità HTML. Normalizza whitespace.]] - rationale - harvester\src\collectors\fandom.py
- [[Ritorna top guide filtrate (EN, viewsvotes soglia minima).          Ogni elemen]] - rationale - harvester\src\collectors\steam_community.py
- [[Ritorna {html_text, categories, page_url} per una pagina Fandom.          Usa ac]] - rationale - harvester\src\collectors\fandom.py
- [[Scarica e parsa robots.txt del dominio.  Fail-open se non raggiungibile.]] - rationale - harvester\src\collectors\base.py
- [[Scarica una pagina rispettando rate limit globale e per-host.          Ritorna i]] - rationale - harvester\src\collectors\base.py
- [[Scopre URL di guide via DuckDuckGo per query libere.]] - rationale - harvester\src\collectors\guide_search.py
- [[Se l'ultima richiesta è recente, _respect_delay aspetta la differenza.]] - rationale - harvester\tests\test_base_collector.py
- [[Serializza un post+commenti in testo pulito, senza username.]] - rationale - harvester\src\collectors\reddit.py
- [[Slug URL-safe per costruzione URL fallback.]] - rationale - harvester\src\collectors\guide_search.py
- [[Supporta dispatch da seed file con URL fandom.comwikiPAGE.]] - rationale - harvester\src\collectors\fandom.py
- [[Test per BaseCollector — rate limiting, robots.txt, fetch, hash.]] - rationale - harvester\tests\test_base_collector.py
- [[TestComputeHash]] - code - harvester\tests\test_base_collector.py
- [[TestFetch]] - code - harvester\tests\test_base_collector.py
- [[TestPerHostTokenBucket]] - code - harvester\tests\test_base_collector.py
- [[TestRespectDelay]] - code - harvester\tests\test_base_collector.py
- [[TestRobotsTxt]] - code - harvester\tests\test_base_collector.py
- [[TestUserAgent]] - code - harvester\tests\test_base_collector.py
- [[True se l'URL appartiene a un dominio di fiducia.]] - rationale - harvester\src\collectors\guide_search.py
- [[TrueAchievementsCollector — collector per trueachievements.com.  Guide achieveme]] - rationale - harvester\src\collectors\trueachievements.py
- [[Verifica se url è permesso da robots.txt.  Fail-open se non caricato.]] - rationale - harvester\src\collectors\base.py
- [[_StubCollector]] - code - harvester\tests\test_base_collector.py
- [[_domain_of()]] - code - harvester\src\collectors\guide_search.py
- [[_extract_title()_3]] - code - harvester\src\collectors\powerpyx.py
- [[_extract_title()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_infer_guide_type()]] - code - harvester\src\collectors\fandom.py
- [[_is_allowed ritorna True se robots.txt non è stato caricato (fail-open).]] - rationale - harvester\tests\test_base_collector.py
- [[_is_trusted()]] - code - harvester\src\collectors\guide_search.py
- [[_normalize_whitespace()_3]] - code - harvester\src\collectors\powerpyx.py
- [[_normalize_whitespace()_6]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_ddg_results()]] - code - harvester\src\collectors\guide_search.py
- [[_parse_game_name_from_url()]] - code - harvester\src\collectors\trueachievements.py
- [[_parse_url_slug()_2]] - code - harvester\src\collectors\powerpyx.py
- [[_slugify()_1]] - code - harvester\src\collectors\guide_search.py
- [[_strip_html()]] - code - harvester\src\collectors\fandom.py
- [[base.py]] - code - harvester\src\collectors\base.py
- [[build_fallback_urls()]] - code - harvester\src\collectors\guide_search.py
- [[collector()]] - code - harvester\tests\test_base_collector.py
- [[compute_hash()]] - code - harvester\src\collectors\base.py
- [[extract()]] - code - harvester\src\collectors\base.py
- [[fandom.py]] - code - harvester\src\collectors\fandom.py
- [[fetch() ritorna None se il server risponde 403.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se il server risponde 429 (rate limited).]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None se robots.txt vieta l'URL.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna None su timeout.]] - rationale - harvester\tests\test_base_collector.py
- [[fetch() ritorna il body HTML su status 200.]] - rationale - harvester\tests\test_base_collector.py
- [[guide_search.py]] - code - harvester\src\collectors\guide_search.py
- [[powerpyx.py]] - code - harvester\src\collectors\powerpyx.py
- [[semaphore()]] - code - harvester\tests\test_base_collector.py
- [[test_allowed_when_no_robots()]] - code - harvester\tests\test_base_collector.py
- [[test_base_collector.py]] - code - harvester\tests\test_base_collector.py
- [[test_first_acquire_no_wait()]] - code - harvester\tests\test_base_collector.py
- [[test_lazy_load_robots_on_first_fetch()]] - code - harvester\tests\test_base_collector.py
- [[test_no_wait_first_request()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_html_on_200()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_403()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_429()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_on_timeout()]] - code - harvester\tests\test_base_collector.py
- [[test_returns_none_when_disallowed()]] - code - harvester\tests\test_base_collector.py
- [[test_second_acquire_waits()]] - code - harvester\tests\test_base_collector.py
- [[test_waits_correct_time()]] - code - harvester\tests\test_base_collector.py
- [[trueachievements.py]] - code - harvester\src\collectors\trueachievements.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/BaseCollector_Interface
SORT file.name ASC
```

## Connections to other communities
- 69 edges to [[_COMMUNITY_Injector Deduplication]]
- 7 edges to [[_COMMUNITY_YouTube Collector]]
- 6 edges to [[_COMMUNITY_Exophase Collector]]
- 6 edges to [[_COMMUNITY_PSTrophies Collector]]
- 6 edges to [[_COMMUNITY_TrueTrophies Collector]]
- 5 edges to [[_COMMUNITY_PSNProfiles Collector]]
- 5 edges to [[_COMMUNITY_Reddit Collector]]
- 4 edges to [[_COMMUNITY_Steam Community Collector]]
- 4 edges to [[_COMMUNITY_PSNProfilesTrueAchievements Tests]]
- 2 edges to [[_COMMUNITY_Fextralife Collector]]
- 2 edges to [[_COMMUNITY_ign.py]]
- 1 edge to [[_COMMUNITY_Orchestrator Pipeline]]

## Top bridge nodes
- [[BaseCollector]] - degree 162, connects to 12 communities
- [[guide_search.py]] - degree 7, connects to 1 community
- [[.search_guide_urls()]] - degree 6, connects to 1 community
- [[_StubCollector]] - degree 6, connects to 1 community
- [[.extract()_1]] - degree 5, connects to 1 community