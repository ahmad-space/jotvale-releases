# JotVale releases

Signed JotVale installers for the Microsoft Store and direct download.
Source code is developed privately; this repo only publishes release binaries.

## 0.3.13 — 18 November 2026

Fixes six data-safety issues: renamed files keep following external changes,
failed saves no longer leave outdated recovery prompts, image links cannot make
the preview contact a network location, clearing recovery data no longer drops
another window's crash protection, Auto Save pauses during a "Save changes?"
prompt, and merging no longer repeats a line added on both sides. Signed package
for the Microsoft Store update and direct download.

- Package: `v0.3.13/JotVale_0.3.13_x64-setup.exe`
- Download: [JotVale 0.3.13 Windows installer](https://ahmad-space.github.io/jotvale-releases/v0.3.13/JotVale_0.3.13_x64-setup.exe)
- Version: 0.3.13; Windows x64 application, current-user NSIS installer.
- Size: 7,486,424 bytes.
- SHA-256: `d7a4eccee7be03592c4444602a79822c6be986998f2ec29b8d1427ab72f9d868`
- Authenticode: Valid, publisher `CN=JotVale`, SHA-256 with a DigiCert timestamp.
- Integrity: actual executable bytes, not a Git LFS pointer; matches the signed
  source bundle and the source repository's installer copy byte for byte.

## 0.3.12 — 7 October 2026

Fixes save/undo/close protection, reconciliation of recreated files, and Save As
creation races. Signed package for the Microsoft Store update and direct download.

- Package: `v0.3.12/JotVale_0.3.12_x64-setup.exe`
- Download: [JotVale 0.3.12 Windows installer](https://ahmad-space.github.io/jotvale-releases/v0.3.12/JotVale_0.3.12_x64-setup.exe)
- Version: 0.3.12; Windows x64 application, current-user NSIS installer.
- Size: 7,478,384 bytes.
- SHA-256: `815ee0943367be0653542f23dfa03e475fda5c199abd75858bc503d9dd242480`
- Authenticode: Valid, publisher `CN=JotVale`, SHA-256 with a DigiCert timestamp.
- Integrity: actual executable bytes, not a Git LFS pointer; matches the signed
  source bundle and the source repository's installer copy byte for byte.

All previous version directories are preserved. Package URLs are versioned;
existing submitted binaries must not be replaced. Microsoft Store certification
and publication status are managed separately in Partner Center.
