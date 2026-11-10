# expat

Expat 2.6.4 XML parser library and xmlwf

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install expat
```

| | |
|---|---|
| Version | 2.6.4 |
| Licence | MIT |
| Upstream | https://libexpat.github.io |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc) |
| Needs tOS build | 615 or newer |
| Size | 275302 bytes (836573 unpacked) |
| SHA-256 of the `.tpkg` | `d1c86d99d421a0f9d21a61f6bc55b2424451b9a4de400129f368e6aa7f92cd97` |

## Commands it adds

| Command | Runs |
|---|---|
| `xmlwf` | `bin/xmlwf` |

## Download

The package file (`expat-2.6.4.tpkg`) and the sources it was built from are the assets of the
[v2.6.4 release](https://github.com/Artfical/tpkg-expat/releases/tag/v2.6.4).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `expat-2.6.4.tar.xz`

Check a download: `sha256sum expat-2.6.4.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
