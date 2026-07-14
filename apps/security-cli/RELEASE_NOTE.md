# security-cli release notes

## security-cli v0.2.0

- Source commit: `2106a82905a5263de91a9542221fa1efba4d3f88`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.2.0`

### Artifacts

- SHA256SUMS
- security-cli_v0.2.0_darwin_amd64
- security-cli_v0.2.0_darwin_amd64.tar.gz
- security-cli_v0.2.0_darwin_arm64
- security-cli_v0.2.0_darwin_arm64.tar.gz
- security-cli_v0.2.0_linux_amd64
- security-cli_v0.2.0_linux_amd64.tar.gz
- security-cli_v0.2.0_linux_arm64
- security-cli_v0.2.0_linux_arm64.tar.gz
- security-cli_v0.2.0_windows_amd64.exe
- security-cli_v0.2.0_windows_amd64.tar.gz
- security-cli_v0.2.0_windows_arm64.exe
- security-cli_v0.2.0_windows_arm64.tar.gz

### Changes

- fix: run database updates from installed tool paths (2106a82)
- docs: prepare v0.2.0 release (26003ef)
- docs: add portfolio security coverage guidance (51657c3)
- feat(report): expose scanner coverage in all formats (891e8e6)
- feat: add coverage-aware scan orchestration (73dd60a)
- Baseline legacy Sonar sort findings (c08fd3d)
- Limit SonarQube scope to source code (d8ba5a7)
- Baseline legacy Sonar maintainability rules (df5ed7c)
- Tighten SonarQube analysis scope (2262a65)
- Run JAM v0.17.0 in quality workflow (74fa235)
- Document JAM exceptions for CLI orchestration (8d9115c)
- Use literal updater command names (3a158fe)
- Set up Go before GitOps test scan (f8335fc)
- Raise security CLI coverage for GitOps quality (eeb08f6)
- Install project dependencies before GitOps test scan (910da69)
- Update GitOps quality workflow (3fe3929)
- Retry transient SonarQube scan failures (3143e3b)
- Harden GitOps quality metrics reporting (8544863)
- Stop reporting smoke test coverage (b962f7d)
- Harden GitOps quality workflow payloads (8671b5a)
- Fix coverage webhook JSON payload (1a9625a)
- Add SonarQube and smoke test quality checks (0cd0d45)
- Fix GitOps quality workflow run URLs (08ac9d2)
- Report empty test summaries to GitOps Console (91a5f73)
- Add GitOps quality metrics workflow (1921f9b)

---

## security-cli v0.1.8

- Source commit: `eeaf428897d4a747641b215b253ff3c8aba20056`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.8`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.8_darwin_amd64
- security-cli_v0.1.8_darwin_amd64.tar.gz
- security-cli_v0.1.8_darwin_arm64
- security-cli_v0.1.8_darwin_arm64.tar.gz
- security-cli_v0.1.8_linux_amd64
- security-cli_v0.1.8_linux_amd64.tar.gz
- security-cli_v0.1.8_linux_arm64
- security-cli_v0.1.8_linux_arm64.tar.gz
- security-cli_v0.1.8_windows_amd64.exe
- security-cli_v0.1.8_windows_amd64.tar.gz
- security-cli_v0.1.8_windows_arm64.exe
- security-cli_v0.1.8_windows_arm64.tar.gz

### Changes

- Run security gates with installed scanners (eeaf428)
- Avoid GitHub API dependency for self updates (6f09106)

---

## security-cli v0.1.7

- Source commit: `26b4291f332187f2e838b39bc635262ab409a76a`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.7`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.7_darwin_amd64
- security-cli_v0.1.7_darwin_amd64.tar.gz
- security-cli_v0.1.7_darwin_arm64
- security-cli_v0.1.7_darwin_arm64.tar.gz
- security-cli_v0.1.7_linux_amd64
- security-cli_v0.1.7_linux_amd64.tar.gz
- security-cli_v0.1.7_linux_arm64
- security-cli_v0.1.7_linux_arm64.tar.gz
- security-cli_v0.1.7_windows_amd64.exe
- security-cli_v0.1.7_windows_amd64.tar.gz
- security-cli_v0.1.7_windows_arm64.exe
- security-cli_v0.1.7_windows_arm64.tar.gz

### Changes

- Avoid GitHub API dependency for tool installs (26b4291)

---

## security-cli v0.1.6

- Source commit: `ade063394af897fb5d718ce1a8c911d50a8e692e`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.6`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.6_darwin_amd64
- security-cli_v0.1.6_darwin_amd64.tar.gz
- security-cli_v0.1.6_darwin_arm64
- security-cli_v0.1.6_darwin_arm64.tar.gz
- security-cli_v0.1.6_linux_amd64
- security-cli_v0.1.6_linux_amd64.tar.gz
- security-cli_v0.1.6_linux_arm64
- security-cli_v0.1.6_linux_arm64.tar.gz
- security-cli_v0.1.6_windows_amd64.exe
- security-cli_v0.1.6_windows_amd64.tar.gz
- security-cli_v0.1.6_windows_arm64.exe
- security-cli_v0.1.6_windows_arm64.tar.gz

### Changes

- Fix scanner tool manifest checksum verification (ade0633)

---

## security-cli v0.1.5

- Source commit: `b91d3818a249b6e7983862671e9cb3ff30259673`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.5`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.5_darwin_amd64
- security-cli_v0.1.5_darwin_amd64.tar.gz
- security-cli_v0.1.5_darwin_arm64
- security-cli_v0.1.5_darwin_arm64.tar.gz
- security-cli_v0.1.5_linux_amd64
- security-cli_v0.1.5_linux_amd64.tar.gz
- security-cli_v0.1.5_linux_arm64
- security-cli_v0.1.5_linux_arm64.tar.gz
- security-cli_v0.1.5_windows_amd64.exe
- security-cli_v0.1.5_windows_amd64.tar.gz
- security-cli_v0.1.5_windows_arm64.exe
- security-cli_v0.1.5_windows_arm64.tar.gz

### Changes

- Add self update command (b91d381)

---

## security-cli v0.1.4

- Source commit: `a424b8561a8fc543e12b5105a0d1d1ad995ff604`
- Build runner: `jhl-space`
- Distribution tag: `security-cli-v0.1.4`

### Artifacts

- SHA256SUMS
- security-cli_v0.1.4_darwin_amd64
- security-cli_v0.1.4_darwin_amd64.tar.gz
- security-cli_v0.1.4_darwin_arm64
- security-cli_v0.1.4_darwin_arm64.tar.gz
- security-cli_v0.1.4_linux_amd64
- security-cli_v0.1.4_linux_amd64.tar.gz
- security-cli_v0.1.4_linux_arm64
- security-cli_v0.1.4_linux_arm64.tar.gz
- security-cli_v0.1.4_windows_amd64.exe
- security-cli_v0.1.4_windows_amd64.tar.gz
- security-cli_v0.1.4_windows_arm64.exe
- security-cli_v0.1.4_windows_arm64.tar.gz

### Changes

- Update docs for security-cli v0.1.4 (a424b85)
- Improve human finding details in reports (b571e73)
- Document first-run scanner setup flow (62a2b15)

---

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
