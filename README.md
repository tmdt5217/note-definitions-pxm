# note-definitions_PXM 0.39.0

- Two-tier dictionary: core library and external library.
- Core library: full editor features, including underlines, click definitions, autocomplete, and reading view.
- External library: search/cards/term manager/review only; no editor decorations.
- Promote selected terms or the first 5,000/10,000 to the core library.
- Base index provider now scans only the core library; the custom index scans both.
- High Performance Mode keeps core-library editor features while suppressing the external library.
- Persistent IndexedDB index and 100k-term pagination remain.
