# wzcloud-build

Public GitHub Actions build repository for the private `zzx396/wzcloud` source repo.

This repository only contains workflow logic. Source code stays in the private repo and is fetched at build time through a read-only deploy key.

Current workflow:

- `Build wzcloud macOS`
  - Manual trigger only
  - Builds macOS `x64`, `arm64`, and `universal`
  - Uploads build artifacts instead of publishing a public release

