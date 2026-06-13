# jam release notes

## JAM v0.19.0

- Source commit: `6d05ec6712bf0bba62eb087f17b3ce1b8676ff09`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.19.0`
- Metrics spec: `v8.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.19.0_darwin_amd64
- jam_v0.19.0_darwin_amd64.tar.gz
- jam_v0.19.0_darwin_arm64
- jam_v0.19.0_darwin_arm64.tar.gz
- jam_v0.19.0_linux_amd64
- jam_v0.19.0_linux_amd64.tar.gz
- jam_v0.19.0_linux_arm64
- jam_v0.19.0_linux_arm64.tar.gz
- jam_v0.19.0_windows_amd64.exe
- jam_v0.19.0_windows_amd64.tar.gz
- jam_v0.19.0_windows_arm64.exe
- jam_v0.19.0_windows_arm64.tar.gz

### Changes

- JAM v0.19.0 / metrics v8.0.0: SIG risk-profile diagnostic + concentration guard (6d05ec6)
- Refine scoring model evidence notes (340460c)
- Use stable setup-go action in workflows (d2b56aa)
- Use local Go before setup-go on self-hosted runners (9f77e60)
- Harden workflow Go setup and scoring evidence docs (d286967)
- Document evidence requirements for metrics (5534bd2)

---

## JAM v0.18.0

- Source commit: `ae2b92c4bfd39aaab024bf8dbfc817a1cccc319c`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.18.0`
- Metrics spec: `v7.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.18.0_darwin_amd64
- jam_v0.18.0_darwin_amd64.tar.gz
- jam_v0.18.0_darwin_arm64
- jam_v0.18.0_darwin_arm64.tar.gz
- jam_v0.18.0_linux_amd64
- jam_v0.18.0_linux_amd64.tar.gz
- jam_v0.18.0_linux_arm64
- jam_v0.18.0_linux_arm64.tar.gz
- jam_v0.18.0_windows_amd64.exe
- jam_v0.18.0_windows_amd64.tar.gz
- jam_v0.18.0_windows_arm64.exe
- jam_v0.18.0_windows_arm64.tar.gz

### Changes

- JAM v0.18.0: SEC score caps and release guards (ae2b92c)
- Baseline legacy Sonar sort findings (59518b9)
- Limit SonarQube scope to source code (ad9837c)
- Baseline legacy Sonar maintainability rules (c0830e1)
- Tighten SonarQube analysis scope (8e98e35)
- Run JAM v0.17.0 in quality workflow (c7eeef9)
- Document JAM exceptions for scanner orchestration (56529f8)

---

## JAM v0.17.0

- Source commit: `cd1194caacd9c462d1bc762022eeb9d0c9e5e8db`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.17.0`
- Metrics spec: `v6.1.0`

### Artifacts

- SHA256SUMS
- jam_v0.17.0_darwin_amd64
- jam_v0.17.0_darwin_amd64.tar.gz
- jam_v0.17.0_darwin_arm64
- jam_v0.17.0_darwin_arm64.tar.gz
- jam_v0.17.0_linux_amd64
- jam_v0.17.0_linux_amd64.tar.gz
- jam_v0.17.0_linux_arm64
- jam_v0.17.0_linux_arm64.tar.gz
- jam_v0.17.0_windows_amd64.exe
- jam_v0.17.0_windows_amd64.tar.gz
- jam_v0.17.0_windows_arm64.exe
- jam_v0.17.0_windows_arm64.tar.gz

### Changes

- JAM v0.17.0 / metrics v6.1.0: ARCH-05 Hub-Like + ARCH-06 Propagation Cost (cd1194c)
- Set up Go before GitOps test scan (8118f4e)
- Install project dependencies before GitOps test scan (4f3719d)
- Run Go coverage in GitOps quality workflow (b3dc2f9)
- Exclude JAM testdata from Sonar scan (6c3f84a)
- Run GitOps quality workflow on master (47d8f10)
- Update GitOps quality workflow (5fb4564)
- Publish JAM v0.16.0 installer metadata (e607ada)
- Retry transient SonarQube scan failures (6f3697c)
- Harden GitOps quality metrics reporting (2e6dd5c)
- Stop reporting smoke test coverage (9e1476a)

---

## JAM v0.16.0

- Source commit: `bc2bbd5198a34ea3262881472d8b228e7c286fb9`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.16.0`
- Metrics spec: `v6.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.16.0_darwin_amd64
- jam_v0.16.0_darwin_amd64.tar.gz
- jam_v0.16.0_darwin_arm64
- jam_v0.16.0_darwin_arm64.tar.gz
- jam_v0.16.0_linux_amd64
- jam_v0.16.0_linux_amd64.tar.gz
- jam_v0.16.0_linux_arm64
- jam_v0.16.0_linux_arm64.tar.gz
- jam_v0.16.0_windows_amd64.exe
- jam_v0.16.0_windows_amd64.tar.gz
- jam_v0.16.0_windows_arm64.exe
- jam_v0.16.0_windows_arm64.tar.gz

### Changes

- JAM v0.16.0 / metrics v6.0.0: SEC-04 dynamic-execution critical escalation (bc2bbd5)

---

## JAM v0.15.0

- Source commit: `97ff7b44a76712edca7d2543a1e640264848c3d6`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.15.0`
- Metrics spec: `v5.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.15.0_darwin_amd64
- jam_v0.15.0_darwin_amd64.tar.gz
- jam_v0.15.0_darwin_arm64
- jam_v0.15.0_darwin_arm64.tar.gz
- jam_v0.15.0_linux_amd64
- jam_v0.15.0_linux_amd64.tar.gz
- jam_v0.15.0_linux_arm64
- jam_v0.15.0_linux_arm64.tar.gz
- jam_v0.15.0_windows_amd64.exe
- jam_v0.15.0_windows_amd64.tar.gz
- jam_v0.15.0_windows_arm64.exe
- jam_v0.15.0_windows_arm64.tar.gz

### Changes

- Prepare JAM v0.15.0 release (97ff7b4)
- Honor nested gitignore and dependency dirs (8b51798)
- docs: update for v0.14.0 / metrics v5.0.0 release (46e9925)

---

## JAM v0.14.0

- Source commit: `62a0a02943ead4582f5cb392ba46f4694d304dd7`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.14.0`
- Metrics spec: `v4.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.14.0_darwin_amd64
- jam_v0.14.0_darwin_amd64.tar.gz
- jam_v0.14.0_darwin_arm64
- jam_v0.14.0_darwin_arm64.tar.gz
- jam_v0.14.0_linux_amd64
- jam_v0.14.0_linux_amd64.tar.gz
- jam_v0.14.0_linux_arm64
- jam_v0.14.0_linux_arm64.tar.gz
- jam_v0.14.0_windows_amd64.exe
- jam_v0.14.0_windows_amd64.tar.gz
- jam_v0.14.0_windows_arm64.exe
- jam_v0.14.0_windows_arm64.tar.gz

### Changes

- JAM v0.14.0 / metrics v5.0.0: SEC-02 Java/C# + critical escalation (62a0a02)

---

## JAM v0.13.0

- Source commit: `56ac2e58e22c201d5ffd4acf8504ac6640f3f402`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.13.0`
- Metrics spec: `v4.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.13.0_darwin_amd64
- jam_v0.13.0_darwin_amd64.tar.gz
- jam_v0.13.0_darwin_arm64
- jam_v0.13.0_darwin_arm64.tar.gz
- jam_v0.13.0_linux_amd64
- jam_v0.13.0_linux_amd64.tar.gz
- jam_v0.13.0_linux_arm64
- jam_v0.13.0_linux_arm64.tar.gz
- jam_v0.13.0_windows_amd64.exe
- jam_v0.13.0_windows_amd64.tar.gz
- jam_v0.13.0_windows_arm64.exe
- jam_v0.13.0_windows_arm64.tar.gz

### Changes

- JAM v0.13.0 / metrics v4.0.0: TDRMax 0.20 -> 0.10 (de-leniency) (56ac2e5)
- Add SonarQube and smoke test quality checks (7b50d6b)
- Surface jam-full on homepage (bde5cf4)

---

## JAM v0.12.0

- Source commit: `68a9bf3e58f454bc763acec5a62db9e42e00910b`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.12.0`
- Metrics spec: `v3.0.0`

### Artifacts

- SHA256SUMS
- jam_v0.12.0_darwin_amd64
- jam_v0.12.0_darwin_amd64.tar.gz
- jam_v0.12.0_darwin_arm64
- jam_v0.12.0_darwin_arm64.tar.gz
- jam_v0.12.0_linux_amd64
- jam_v0.12.0_linux_amd64.tar.gz
- jam_v0.12.0_linux_arm64
- jam_v0.12.0_linux_arm64.tar.gz
- jam_v0.12.0_windows_amd64.exe
- jam_v0.12.0_windows_amd64.tar.gz
- jam_v0.12.0_windows_arm64.exe
- jam_v0.12.0_windows_arm64.tar.gz

### Changes

- JAM v0.12.0 / metrics v3.0.0: exclude unassessable categories from score (68a9bf3)
- Fix GitOps quality workflow run URLs (31cdafe)
- Report empty test summaries to GitOps Console (9edbe91)

---

## JAM v0.11.0

- Source commit: `3697a51d60dbb2f3281e411ad7c5d2156dcf3dcf`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.11.0`
- Metrics spec: `v2.3.4`

### Artifacts

- SHA256SUMS
- jam_v0.11.0_darwin_amd64
- jam_v0.11.0_darwin_amd64.tar.gz
- jam_v0.11.0_darwin_arm64
- jam_v0.11.0_darwin_arm64.tar.gz
- jam_v0.11.0_linux_amd64
- jam_v0.11.0_linux_amd64.tar.gz
- jam_v0.11.0_linux_arm64
- jam_v0.11.0_linux_arm64.tar.gz
- jam_v0.11.0_windows_amd64.exe
- jam_v0.11.0_windows_amd64.tar.gz
- jam_v0.11.0_windows_arm64.exe
- jam_v0.11.0_windows_arm64.tar.gz

### Changes

- Format coverage test files with gofmt (3697a51)
- JAM v0.11.0: complexity refactor + coverage safety net (97dc966)
- Render homepage coverage summary as chart (f91d023)
- Add homepage metric coverage summary (348f0dd)
- Simplify homepage metric descriptions (f85277c)
- Improve Pages readability and responsive tables (f52fefe)
- Document metric formulas and category scores (65a3869)
- Fix Pages command layout overlap (a32bfb8)
- Fix Pages hero layout (ce95233)
- Improve GitHub Pages home content (82b8542)
- Render full docs in GitHub Pages (9f71146)

---

## JAM v0.10.7

- Source commit: `3cfe2874fee14eba6298fff41820c15764d8708f`
- Build runner: `jhl-space`
- Distribution tag: `jam-v0.10.7`
- Metrics spec: `v2.3.4`

### Artifacts

- SHA256SUMS
- jam_v0.10.7_darwin_amd64
- jam_v0.10.7_darwin_amd64.tar.gz
- jam_v0.10.7_darwin_arm64
- jam_v0.10.7_darwin_arm64.tar.gz
- jam_v0.10.7_linux_amd64
- jam_v0.10.7_linux_amd64.tar.gz
- jam_v0.10.7_linux_arm64
- jam_v0.10.7_linux_arm64.tar.gz
- jam_v0.10.7_windows_amd64.exe
- jam_v0.10.7_windows_amd64.tar.gz
- jam_v0.10.7_windows_arm64.exe
- jam_v0.10.7_windows_arm64.tar.gz

### Changes

- Enable race tests in CI (3cfe287)
- Prepare docs site and dist release (e35a509)
- Add jam-full partial component mode (bff5eb1)
- Classify missing test evidence in jam-full E2E (ff3f8c7)
- Run jam-full E2E and tune security scoring (a2471f8)
- Calibrate Rust architecture cycles and E2E corpus (1d8de8e)
- Document E2E language sample baseline (9263279)
- JAM v0.10.3: complete lite/full metrics calibration (d7c0d39)

---
