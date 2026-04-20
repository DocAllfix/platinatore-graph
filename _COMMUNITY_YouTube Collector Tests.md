---
type: community
cohesion: 0.09
members: 22
---

# YouTube Collector Tests

**Cohesion:** 0.09 - loosely connected
**Members:** 22 nodes

## Members
- [[Test YouTubeCollector — tutto mockato, zero rete reale, zero API key.  I JSONtr]] - rationale - harvester\tests\test_youtube_collector.py
- [[search_videos deve filtrare per view count e duration.]] - rationale - harvester\tests\test_youtube_collector.py
- [[test_collect_extracts_video_id_from_url()]] - code - harvester\tests\test_youtube_collector.py
- [[test_collect_invalid_url_returns_none()_1]] - code - harvester\tests\test_youtube_collector.py
- [[test_extract_empty_returns_none()_1]] - code - harvester\tests\test_youtube_collector.py
- [[test_extract_too_short_returns_none()_2]] - code - harvester\tests\test_youtube_collector.py
- [[test_extract_valid_transcript()]] - code - harvester\tests\test_youtube_collector.py
- [[test_get_transcript_returns_none_when_disabled()]] - code - harvester\tests\test_youtube_collector.py
- [[test_get_transcript_returns_text()]] - code - harvester\tests\test_youtube_collector.py
- [[test_parse_duration_empty()]] - code - harvester\tests\test_youtube_collector.py
- [[test_parse_duration_hours()]] - code - harvester\tests\test_youtube_collector.py
- [[test_parse_duration_minutes_only()]] - code - harvester\tests\test_youtube_collector.py
- [[test_parse_duration_minutes_seconds()]] - code - harvester\tests\test_youtube_collector.py
- [[test_parse_duration_seconds_only()]] - code - harvester\tests\test_youtube_collector.py
- [[test_search_videos_returns_empty_when_no_key()]] - code - harvester\tests\test_youtube_collector.py
- [[test_search_videos_returns_empty_when_quota_exceeded()]] - code - harvester\tests\test_youtube_collector.py
- [[test_search_videos_returns_filtered_results()]] - code - harvester\tests\test_youtube_collector.py
- [[test_title_from_extra_channel_fallback()]] - code - harvester\tests\test_youtube_collector.py
- [[test_title_from_extra_none()]] - code - harvester\tests\test_youtube_collector.py
- [[test_title_from_extra_with_title()]] - code - harvester\tests\test_youtube_collector.py
- [[test_youtube_collector.py]] - code - harvester\tests\test_youtube_collector.py
- [[yt()]] - code - harvester\tests\test_youtube_collector.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/YouTube_Collector_Tests
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_Injector Deduplication]]

## Top bridge nodes
- [[Test YouTubeCollector — tutto mockato, zero rete reale, zero API key.  I JSONtr]] - degree 2, connects to 1 community
- [[search_videos deve filtrare per view count e duration.]] - degree 2, connects to 1 community