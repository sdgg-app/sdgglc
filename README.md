# sdgglc

Signed SDGG language packs, published as GitHub releases only. This repository holds no source.

Each release is one version of one pack:

| Item | Name |
|---|---|
| Tag | `<packId>-r<version>`, for example `sdgg-ko-r13` |
| Archive | `<packId>-r<version>.sdgglc` |
| Descriptor | `<packId>-r<version>.manifest.json` |
| Signature | `<packId>-r<version>.manifest.json.sig` |

The release body holds member-facing notes, with optional `[en]`, `[ko]` and `[zh-CN]` sections.

Prepare a release with `sdgglc prepare-release` and an SDGG release key, then upload the three files by hand. Never
replace an uploaded tag; publish a fix as a new version. A release reaches members only after an operator assigns it in
the SDGG operator console.
