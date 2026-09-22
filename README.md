# Sofia public transport — map

Generated output. This site is built and force-pushed by
`scripts/publish_web.py` in the project repository; it holds a single commit
and is rewritten on every publish, so nothing here is edited by hand.

It publishes a rolling window of the most recent observed days plus the
typical-weekday medians for every schedule period in the archive. The
complete archive is published as a dataset record with a DOI.

- Code and methodology: https://github.com/StasSuslov/sofia-pt-data
- Code DOI (concept): 10.5281/zenodo.22256653
- Dataset DOI (concept): 10.5281/zenodo.22285128

Transit data: urbandata.sofia.bg (CGM Sofia GTFS/GTFS-RT),
operated by CGM Sofia.
https://urbandata.sofia.bg

The feeds do not share one licence, so they are named apart:
- vehicle positions: CC BY 4.0
- static: CC BY-SA 4.0

Licences: code MIT, everything published here CC BY-SA 4.0, because the
segment geometry is derived from the schedule feed.
