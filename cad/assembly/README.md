# Complete CATIA assembly

Four shaft subassembly products are included in `../native/`. No complete launcher `.CATProduct` is present in the supplied folder. The final assembly drawing is available on page 26 of [the drawing package](../../docs/PDF%202D%20COMPLET.pdf); page 33 is the chassis assembly.

When the original full assembly becomes available, add its root product and all dependencies, preserve component references, and verify that it opens without missing links in a compatible CATIA installation. Record the CATIA version and root filename here after that check. Preserve any necessary original relative layout and update repository navigation accordingly.

Some supplied shaft products name catalogue components absent from the folder (for example `FL606ZZ.catpart` and `KESF5_26.catpart`). Text inspection does not establish whether geometry is embedded or whether each reference is required at opening. Native links and constraints have not been validated in CATIA.

This directory is a documented placeholder, not a replacement assembly.
