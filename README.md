# EUDR & DPP-textiles document library

Two public document collections, each with the original PDFs and machine-readable
markdown conversions (produced with [marker](https://github.com/datalab-to/marker)).

| Folder | PDFs | Markdown | Source |
|---|---|---|---|
| [`eudr/`](eudr/) | 294 | 161 | [Zero Deforestation Hub library](https://zerodeforestationhub.eu/library/) |
| [`dpp/`](dpp/) | 99 | 99 | [Ecosystex publications](https://www.ecosystex.eu/publications) |

- `<collection>/pdf/` — source PDFs as published.
- `<collection>/markdown/` — one folder per document: the `.md`, images extracted from
  the PDF, and `_meta.json`.
- `dpp/INDEX.md` maps publication titles and project tags to filenames.

The EUDR library is multilingual; only its 161 English documents were converted to
markdown (all 294 PDFs are here). Conversions are automated OCR — verify figures,
tables and legal citations against the source PDF.

All documents remain the work and property of their original authors and publishers.
