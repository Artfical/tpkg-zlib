# zlib

zlib 1.2.11 compression library (libz.so.1; for curl and git, 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install zlib
```

| | |
|---|---|
| Version | 1.2.11 |
| Licence | zlib |
| Upstream | https://zlib.net |
| Needs | none |
| Needs tOS build | 608 or newer |
| Size | 58335 bytes (108936 unpacked) |
| SHA-256 of the `.tpkg` | `7d257c6e8839719bd1e8071c67ba8a86f29e9f2b7da197603c0549180802f2c3` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`zlib-1.2.11.tpkg`) and the sources it was built from are the assets of the
[v1.2.11 release](https://github.com/Artfical/tpkg-zlib/releases/tag/v1.2.11).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- (none: see the upstream page above)

Check a download: `sha256sum zlib-1.2.11.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: zlib. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
