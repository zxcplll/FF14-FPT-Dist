# Integrated Third-Party Modules

FPT contains modified builds of the following AGPL-3.0 projects:

- PalacePal, upstream commit `021636c14ef59c0310139959cb829d11c484cf68`
- Splatoon, upstream commit `d21b92aef821ac86dc2297788c05898914929391`

The corresponding FPT changes are stored in `PalacePal-FPT.patch` and
`Splatoon-FPT.patch`. The original license text is preserved in
`LICENSE-PalacePal.txt` and `LICENSE-Splatoon.txt` and inside each embedded
runtime bundle.

Run `scripts/prepare-integrated-sources.ps1` to obtain the exact upstream
sources and apply the patches, then run `scripts/build-integrated-modules.ps1`
to rebuild both embedded bundles.
