# at-spi2-atk

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/a/at-spi2-atk.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/at-spi2-atk-2.38.0-h0630a04_3.tar.bz2 | `26ab9386e80bf196e51ebe005da77d57decf6d989b4f34d96130560bc133479c` | conda-forge at-spi2-atk 2.38.0 h0630a04_3 (LGPL-2.1-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name at-spi2-atk \
    --version 2.38.0 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/at-spi2-atk-2.38.0-h0630a04_3.tar.bz2#26ab9386e80bf196e51ebe005da77d57decf6d989b4f34d96130560bc133479c \
    --require lib/libatk-bridge-2.0.so.0 \
    --require lib/gtk-2.0/modules/libatk-bridge.so
```

