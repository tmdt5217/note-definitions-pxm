# note-definitions_PXM 0.39.4

- Fix external definitions opening as “Definition is no longer indexed”.
- Render definitions from the search index when the original shard path is stale.
- Core terms win over duplicate external records.
- Core library capped at 10,000 terms with atomic writes.
