# security-cli release notes

## security-cli v0.1.3

- Source commit: `3d83625c169e8ca9cfc83c801980151ccc8d4e49`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.3`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.3_darwin_amd64
- security-cli_v0.1.3_darwin_amd64.tar.gz
- security-cli_v0.1.3_darwin_arm64
- security-cli_v0.1.3_darwin_arm64.tar.gz
- security-cli_v0.1.3_linux_amd64
- security-cli_v0.1.3_linux_amd64.tar.gz
- security-cli_v0.1.3_linux_arm64
- security-cli_v0.1.3_linux_arm64.tar.gz
- security-cli_v0.1.3_windows_amd64.exe
- security-cli_v0.1.3_windows_amd64.tar.gz
- security-cli_v0.1.3_windows_arm64.exe
- security-cli_v0.1.3_windows_arm64.tar.gz

### Changes

- Install scanner tools from GitHub releases (3d83625)
- Improve install command copy UI (41c4f4d)
- Add latest install script (1a2abbb)

---

## security-cli v0.1.2

- Source commit: `c7718ea491f479cc06f3908155022f92c6632e7e`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.2`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.2_darwin_amd64
- security-cli_v0.1.2_darwin_amd64.tar.gz
- security-cli_v0.1.2_darwin_arm64
- security-cli_v0.1.2_darwin_arm64.tar.gz
- security-cli_v0.1.2_linux_amd64
- security-cli_v0.1.2_linux_amd64.tar.gz
- security-cli_v0.1.2_linux_arm64
- security-cli_v0.1.2_linux_arm64.tar.gz
- security-cli_v0.1.2_windows_amd64.exe
- security-cli_v0.1.2_windows_amd64.tar.gz
- security-cli_v0.1.2_windows_arm64.exe
- security-cli_v0.1.2_windows_arm64.tar.gz

### Changes

- docs: point downloads to v0.1.2 (c7718ea)
- feat: deduplicate advisory findings (a2b31b7)
- feat: improve release diagnostics insight (cc7788f)
- docs: use cli name as page brand (d5342d3)

---

## security-cli v0.1.1

- Source commit: `897f6fd20e98d964201be3852e65557b528241b8`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.1`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.1_darwin_amd64
- security-cli_v0.1.1_darwin_amd64.tar.gz
- security-cli_v0.1.1_darwin_arm64
- security-cli_v0.1.1_darwin_arm64.tar.gz
- security-cli_v0.1.1_linux_amd64
- security-cli_v0.1.1_linux_amd64.tar.gz
- security-cli_v0.1.1_linux_arm64
- security-cli_v0.1.1_linux_arm64.tar.gz
- security-cli_v0.1.1_windows_amd64.exe
- security-cli_v0.1.1_windows_amd64.tar.gz
- security-cli_v0.1.1_windows_arm64.exe
- security-cli_v0.1.1_windows_arm64.tar.gz

### Changes

- docs: link downloads to public dist release (897f6fd)
- ci: update actions for node 24 (24533fd)
- ci: gate dist release with security diagnostics (e99f958)
- ci: warn when scanner toolchain is absent (d38d096)
- ci: build cli without make (41f8198)
- ci: use portable go test on runner (6a1003a)
- ci: add devsecops verification workflow (a2c8409)
- ci: publish direct release binaries (c2b4dba)
- ci: obfuscate public release binaries (38f4464)
- ci: set content length for release uploads (a5c397f)
- ci: publish dist releases through github api (1443416)
- docs: refine landing copy and dark buttons (705dfbb)
- docs: add theme and language switchers (6d365bd)

---

## security-cli v0.1.0

- Source commit: `f647788971b13d7f6890c6360d6e80118fb3c44d`
- Build hardening: `trimpath, stripped symbols, garble -tiny`
- Distribution tag: `security-cli-v0.1.0`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.0_darwin_amd64.tar.gz
- security-cli_v0.1.0_darwin_arm64.tar.gz
- security-cli_v0.1.0_linux_amd64.tar.gz
- security-cli_v0.1.0_linux_arm64.tar.gz
- security-cli_v0.1.0_windows_amd64.tar.gz
- security-cli_v0.1.0_windows_arm64.tar.gz

### Changes

- ci: publish security cli releases to dist (f647788)
- docs: align pages with system cli design (b120904)
- docs: publish internal pages for public docs (09d482f)
- docs: refocus pages on security cli value (14cf684)
- ci: enable github pages site (54dded3)
- ci: run pages deploy on github hosted runner (9c305ac)
- docs: add GitHub Pages landing page (116e4e7)
- feat: add one-shot production diagnostics (0659db5)
- feat: add attestations and runtime provenance (951bde4)
- feat: harden production security operations (1c9050a)
- feat: add production security scanners and policies (9c75dc1)
- chore: exclude generated scan outputs (9ab0a5d)
- feat: implement security cli mvp (2ca2ee3)
- docs: expand security cli specification (35dc30c)
- docs: add initial security cli requirements (5000d09)

---
