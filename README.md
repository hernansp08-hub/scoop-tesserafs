# TesseraFS for Scoop

[Scoop](https://scoop.sh) bucket for [TesseraFS](https://github.com/hernansp08-hub/TesseraFS), an open-source disk space analyzer: a treemap of your disk, duplicates, scan history and explained cleanup suggestions. Everything stays local.

```powershell
scoop bucket add tesserafs https://github.com/hernansp08-hub/scoop-tesserafs
scoop install tesserafs
```

It installs the desktop edition (`tesserafs-desktop.exe`, with a Start menu shortcut) and puts `tessera-cli` on your PATH. Update with `scoop update tesserafs`.

*Bucket de Scoop para TesseraFS: `scoop bucket add tesserafs https://github.com/hernansp08-hub/scoop-tesserafs` y `scoop install tesserafs`.*

The manifest in `bucket/` is generated for each release by `bun run manifests` in the main repository. License: MIT OR Apache-2.0.
