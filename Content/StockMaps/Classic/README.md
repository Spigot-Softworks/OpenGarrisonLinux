# Original maps for the Practice and Last to Die browser edition

These assets have separate `gg2_` map identities, registered in `ClassicStockMapCatalog`, so a desktop guest and a browser host resolve the same background, collision, entities, and scale. The full desktop roster still defaults to the existing redrawn versions.

Local originals reused without conversion or artwork changes:

- `cp_coldfront_v7/`: manifest, background, and walkmask copied from `Maps/cp_coldfront_v7/`.
- `dkoth_kulay/`: manifest, background, and walkmask copied from `Maps/dkoth_kulay/`.
- `koth_harvest.png`: copied from `Maps/koth_harvest.png`. The PNG with the same name directly under `Core/Content/StockMaps/` is a redraw.

Missing originals retrieved from [Derpduck's GG2 Map Archive](https://github.com/Derpduck/GG2-Map-Archive), pinned to commit `bf858bec16fa3c06f3a898431e029b9c998d73bb`:

- [CP/cp_docking_v2.png](https://github.com/Derpduck/GG2-Map-Archive/blob/bf858bec16fa3c06f3a898431e029b9c998d73bb/CP/cp_docking_v2.png). The local `Maps/cp_docking_v2/` package also contains redrawn art.
- [CTF/ctf_conflict.png](https://github.com/Derpduck/GG2-Map-Archive/blob/bf858bec16fa3c06f3a898431e029b9c998d73bb/CTF/ctf_conflict.png). Local Conflict variants are redraws or modified layouts/parallax versions.

Map credits embedded in the original assets remain intact. The browser asset builder includes this directory's PNG and JSON data recursively in the runtime bundle.
