# storage-cli release notes

## storage-cli v0.2.0

- Source commit: `dcdf5d67bd3f65cb557320962fb99644d880a70b`
- Build hardening: `trimpath, stripped symbols`
- Distribution tag: `storage-cli-v0.2.0`

### Install

```bash
curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo bash
storage-cli --version
sudo storage-cli --update
```

To pin this release, run `curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo env VERSION=v0.2.0 bash`.
For manual Linux downloads, use the direct executable assets below.

### Artifacts

- SHA256SUMS
- storage-cli_v0.2.0_linux_amd64
- storage-cli_v0.2.0_linux_arm64

### Changes

- Stabilize benchmark with time-based runs and ramp time (dcdf5d6)
- Warn when benchmarking under WSL or 9P/drvfs targets (2bea05c)
- Benchmark at max performance with io_uring and high queue depth (d3eb38f)
- Add --bench disk benchmark via fio (Linux) (f324829)
- Add NVMe vendor, remaining life, and estimated endurance (c5c96b7)
- Show NVMe Written/Read in decimal TB to match TBW ratings (8a2cc8f)
- Hide k8s/portal mounts by default and improve Device Health layout (6ff07b7)
- Add NVMe Device Health section (model, temp, wear, TBW) (7580c54)
- Redesign text output with section headers and semantic color (ebf0d8c)
- Suppress statfs warnings unless --all is set (21ed41b)
- Hide gvfs and /boot mounts from default output (3ac165a)
- Exclude snap/loop squashfs mounts from default output (86c6022)
- Baseline legacy Sonar sort findings (069ac7d)
- Limit SonarQube scope to source code (4da05f4)
- Baseline legacy Sonar maintainability rules (cc79a37)
- Tighten SonarQube analysis scope (5df98ee)
- Run JAM v0.17.0 in quality workflow (272dfd8)
- Use validated literal lsblk command (a277636)
- Raise storage CLI coverage (82beece)
- Set up Go before GitOps test scan (0f47b61)
- Add coverage for storage CLI helpers (6ff0a26)
- Install project dependencies before GitOps test scan (8b75118)
- Update GitOps quality workflow (932392e)
- Retry transient SonarQube scan failures (27f0968)
- Harden GitOps quality metrics reporting (dfd6f9e)
- Stop reporting smoke test coverage (8ed244c)
- Harden GitOps quality workflow payloads (686737e)
- Fix coverage webhook JSON payload (b2bb270)
- Add SonarQube and smoke test quality checks (2a6d679)
- Fix GitOps quality workflow run URLs (2dad6cf)
- Report empty test summaries to GitOps Console (ac3a857)
- Add GitOps quality metrics workflow (66bccc5)

---

## storage-cli v0.1.3

- Source commit: `17c3c678ec64930f1955ad0aefa49498f6f2224c`
- Build hardening: `trimpath, stripped symbols`
- Distribution tag: `storage-cli-v0.1.3`

### Install

```bash
curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo bash
storage-cli --version
sudo storage-cli --update
```

To pin this release, run `curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo env VERSION=v0.1.3 bash`.
For manual Linux downloads, use the direct executable assets below.

### Artifacts

- SHA256SUMS
- storage-cli_v0.1.3_linux_amd64
- storage-cli_v0.1.3_linux_arm64

### Changes

- Stabilize release binary build (17c3c67)

---

## storage-cli v0.1.2

- Source commit: `fb0ffa552a2564260d6b58032727ba38454e9448`
- Build hardening: `trimpath, stripped symbols, garble -tiny`
- Distribution tag: `storage-cli-v0.1.2`

### Install

```bash
curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo bash
storage-cli --version
sudo storage-cli --update
```

To pin this release, run `curl -fsSL https://jhl-labs.github.io/storage-cli/install.sh | sudo env VERSION=v0.1.2 bash`.
For manual Linux downloads, use the direct executable assets below.

### Artifacts

- SHA256SUMS
- storage-cli_v0.1.2_linux_amd64
- storage-cli_v0.1.2_linux_arm64

### Changes

- Add self update command (fb0ffa5)
- Add latest install script (ccef02f)

---

## storage-cli v0.1.1

- Source commit: `b96ddd4657ab5a32c5ccc601b38022feb14a1e9a`
- Build hardening: `trimpath, stripped symbols, garble -tiny`
- Distribution tag: `storage-cli-v0.1.1`

### Install

```bash
curl -fL -o storage-cli https://github.com/jhl-labs/dist/releases/download/storage-cli-v0.1.1/storage-cli_v0.1.1_linux_amd64
chmod +x storage-cli
sudo install -m 0755 storage-cli /usr/local/bin/storage-cli
storage-cli --version
```

For Linux arm64, use `storage-cli_v0.1.1_linux_arm64` in the download URL.

### Artifacts

- SHA256SUMS
- storage-cli_v0.1.1_linux_amd64
- storage-cli_v0.1.1_linux_arm64

### Changes

- Update distribution links for v0.1.1 (b96ddd4)
- Improve storage reclaim recommendations (522bc5f)
- Point distribution docs to public dist release (c518a27)
- Refine docs feature messaging (2a29e5e)
- Publish dist binaries directly (1f61efe)

---

## storage-cli v0.1.0

- Source commit: `1f61efe7fd1671c035ab47fca6148f28f2e554b2`
- Build hardening: `trimpath, stripped symbols, garble -tiny`
- Distribution tag: `storage-cli-v0.1.0`

### Install

```bash
curl -fL -o storage-cli https://github.com/jhl-labs/dist/releases/download/storage-cli-v0.1.0/storage-cli_v0.1.0_linux_amd64
chmod +x storage-cli
sudo install -m 0755 storage-cli /usr/local/bin/storage-cli
storage-cli --version
```

For Linux arm64, use `storage-cli_v0.1.0_linux_arm64` in the download URL.

### Artifacts

- SHA256SUMS
- storage-cli_v0.1.0_linux_amd64
- storage-cli_v0.1.0_linux_arm64

### Changes

- Publish dist binaries directly (1f61efe)

---

