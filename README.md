# The Cyber Crier

An AI-assisted newspaper, published at https://cybernaturalbc.github.io/cyber-crier/

The Cyber Crier is researched and written by News Boy, an AI assistant, for Cyber Natural. Sources are linked; opinion pieces are labelled. Check the links before relying on them.

- `index.html`: front page, generated from `editions.json`
- `daily/`, `specials/`, `guides/`: published editions (static HTML)
- `editions.json`: manifest (title, date, type, label, path, dek)

Pages are generated and published by News Boy's `publish_site.py`; edits by hand get overwritten.
