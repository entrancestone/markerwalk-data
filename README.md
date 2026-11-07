# markerwalk-data

Per-state place downloads for the Marker Walk iOS app, served with GitHub Pages at
`https://entrancestone.github.io/markerwalk-data/packs/`.

- `packs/manifest.json`: every state, with file name, place count, sizes and SHA-256.
- `packs/<st>.sqlite.deflate`: one SQLite database per state, raw DEFLATE compressed.

Data: Wikidata (CC0) and Wikipedia text (CC BY-SA 4.0), for places listed on the
National Register of Historic Places.
