# Native CAD archive

The `native/` directory preserves all 85 files supplied in the original CATIA folder, with original filenames and a flat directory layout. Numbered variants have been kept rather than guessed to be obsolete.

## Contents

- 65 CATIA part files (`.CATPart` / `.catpart`).
- 4 CATIA products: `ASSArbre1.CATProduct`, `ASSARBRE2.CATProduct`, `ASSArbre3.CATProduct`, `ASSARBR4.CATProduct`.
- 8 CATIA drawing files.
- 7 PNG reference images and `Nomenclature.pdf`.

The products correspond to shaft subassemblies. No complete launcher product was found. See [assembly status](assembly/README.md).

Download the entire repository before opening native documents in a compatible CATIA installation. Keep the files together: separating parts, products and drawings can break relative links. External references to supplier components or the original authoring computer may still need to be resolved. Native geometry, product constraints and link completeness have not been tested in CATIA on this Mac.

[manifest.csv](manifest.csv) records filenames, sizes and SHA-256 hashes for the supplied archive. The PDF drawing package in `docs/` provides a software-independent review path.
