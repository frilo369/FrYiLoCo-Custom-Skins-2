# FrYiLoCo Custom Skins 2

Additional champion skins for FrYiLoCo's **Update Custom Skins**. The app reads this repository together with [the first collection](https://github.com/frilo369/FrYiLoCo-Custom-Skins).

Skins live in `Custom Skins/<champion>/<skin>.fantome`. A matching Divine Skins thumbnail beside each Fantome supplies its catalogue artwork; the app identifies skins by their contents, so renamed local copies retain their artwork. See [ARTWORK.md](ARTWORK.md) for source pages.

Keep files in ordinary Git, below 100 MB each. Do not use Git LFS. Updates add missing skins without replacing a player's own files.

The optimized Zilean VU package removes 14 redundant shared game assets that caused unnecessarily large overlays. Its original package is listed in `removed.json` by exact Git blob hash and size; the updater downloads the optimized package first, then moves matching old copies to the Recycle Bin. User-edited copies are preserved.

## Custom Mods

`Custom Mods/` holds standalone packages offered by **Update Custom Mods**, separately from champion skins. Updates download them without enabling them automatically.

`FriloSoundPack1.0.fantome` is an **Arena voice and sound pack for en_US**. Download it through Update Custom Mods and enable it in the Custom Mods dialog. Shared Common-bank replacements can also affect other modes using those sounds. Import, overlay construction and offline audio decoding were checked; live-match playback is not verified.
