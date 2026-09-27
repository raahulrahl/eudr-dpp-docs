# EUDR & DPP-textiles document library

Machine-readable (markdown) conversions of two public document collections, produced with
[marker](https://github.com/datalab-to/marker). Each document lives in its own folder
containing the converted `.md` file, the images extracted from the PDF, and a
`_meta.json` with conversion metadata.

## Collections

| Folder | Documents | Source |
|---|---|---|
| [`eudr/`](eudr/) | 161 | [Zero Deforestation Hub library](https://zerodeforestationhub.eu/library/) — EU Deforestation Regulation guidance, country legality due-diligence tools, sector factsheets |
| [`dpp-textiles/`](dpp-textiles/) | 99 | [Ecosystex publications](https://www.ecosystex.eu/publications) — EU textile-circularity project deliverables, incl. Digital Product Passport governance and infrastructure |

`dpp-textiles/INDEX.md` maps each publication title and its EU project tags to the
filename on disk, and lists source entries that are interactive resources
(platforms, MOOCs, flip-books, video) rather than downloadable documents.

## Scope and provenance

- Only the **English-language** documents of the EUDR library were converted. The
  collection also contains Spanish, French, Portuguese, Vietnamese and German
  editions, which remain unconverted.
- Source PDFs are **not** included here (see `.gitignore`): they are large and remain
  available from the two sites linked above.
- Conversion is automated OCR/layout inference. Tables and figures in scanned
  documents are reconstructed heuristically, so **verify against the original PDF
  before relying on any specific figure, table or legal citation.**

## Copyright

All documents are the work of their respective authors and publishers and remain under
their original terms. This repository holds format conversions for research and search
purposes only; it claims no rights over the content.
