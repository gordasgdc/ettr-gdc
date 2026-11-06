# Provenance

Copyright © 2026 Dumitru Cristinel Gordas. Licence of the distributed files: see `../LICENSE`.

## What is distributed
- The pre-generated `.cube` LUTs, `INDEX.*`, `STATS.json`, `catalog.json`, `audit.json`, `oracle_colour.json` (measurement results), documentation and folder icons. The tools used to produce them are not part of this distribution.
- Folder icons: own typographic design. **No manufacturer logo or brand asset is used**; brand names appear only as plain text identifying the format. No affiliation or endorsement is implied.
- No third-party footage or images. Example images use synthetic charts only.

## Formulas and constants (published by the format owners)
Each curve is implemented from the owner's public document; the constants are numbers published there (facts, not creative expression). Sources:
DaVinci Intermediate (Blackmagic Design), ACEScct (Academy S-2016-001), Sony S-Log2/S-Log3 technical summaries, Canon Log/Log2/Log3 white papers, Panasonic V-Log/V-Gamut reference manual, ARRI LogC3 (SUP 3.x, 11 EI table) and LogC4 specification, RED Log3G10 (REDWideGamutRGB v3), Blackmagic Film Gen5, Nikon N-Log specification, GoPro Protune (Flat), Fujifilm F-Log/F-Log2 data sheets, FilmLight T-Log, Apple Log profile white paper. Gamut names in file names are labels only: a log→log exposure LUT is independent of the gamut.

## Validation
- The results were checked against anchor values from manufacturer documents (e.g. Blackmagic Gen5 0.18→0.38356164, Apple Log 0.18→0.48827246, DaVinci Intermediate 0.336), a round-trip test, an exposure-ladder test and an independent oracle (`Colour` 0.4.7, BSD-3-Clause, used offline only; nothing from it is included). Results per file: `audit.json`, `oracle_colour.json`, `INDEX.md`.

## Third-party material
- Inter typeface (SIL Open Font License 1.1, https://rsms.me/inter/): used only to render the folder-icon images; the font files are not distributed.

## Known limits
Blackmagic Film Gen4, GoPro GP-Log, DJI D-Log and Apple Log 2 are not included (no verifiable public specification used here). See README, “Precision and limits”.
