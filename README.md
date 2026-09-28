# deen-assets

Downloadable content for the **Quran & Deen** section of the Azaan Live app (built by BizCor India).
Nothing here is sold, and the app shows no ads. Each pack is published as its own GitHub **release**;
`catalog.json` lists every pack so the app can offer it for download without an app update.

Every pack keeps the licence of its source and is shown **unaltered**. If you are the rights holder of
any item here and want it removed or credited differently, please open an issue — it will be done promptly.

## Packs

| Pack | What | Source | Licence |
|---|---|---|---|
| `tajweed13-v1` | Al Quran 13 Lines Tajweedi — colour-coded tajweed, Taj Company 13-line edition (847 Quran pages + 34 opening pages on the adab of recitation, makharij and tajweed rules) | Maktaba Yasin, via [archive.org/details/AlQuran13LinesTajweedi](https://archive.org/details/AlQuran13LinesTajweedi) | [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/) |

### tajweed13-v1 files

- `p001.jpg` … `p847.jpg` — Quran pages; `pNNN` is page NNN of the QUL "IndoPak 13 lines (Taj Company)"
  layout (checked line-by-line), so every page's ayahs are known.
- `i00.jpg` … `i33.jpg` — the opening pages, in book order.
- `files.json` — size and SHA-256 of every file.

The pages are the archive.org scans re-encoded from JPEG 2000 to JPEG (quality 70) at their original
size (1065×1425); nothing on any page is changed.
