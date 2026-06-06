# system-cli release notes

## system-cli v0.1.2

- Source commit: `f65af56d88660ffacf7219595ddc636e0b8b73d5`
- Build hardening: `trimpath, stripped symbols, CGO disabled`
- Distribution tag: `system-cli-v0.1.2`

### Install

```bash
curl -fsSL -o system-cli https://github.com/jhl-labs/dist/releases/download/system-cli-v0.1.2/system-cli_v0.1.2_linux_amd64
chmod +x system-cli
sudo install -m 0755 system-cli /usr/local/bin/system-cli
system-cli --version
```

For Linux arm64, use `system-cli_v0.1.2_linux_arm64` in the download URL.

### Artifacts

- SHA256SUMS
- system-cli_v0.1.2_linux_amd64
- system-cli_v0.1.2_linux_arm64

### Highlights

- Agent-ready Linux host diagnostics for packages, updates, services, unit files, ports, SSH/sudo posture, hardening, containers, YAML manifests, and OSV advisories.
- Baseline drift detection with approval and ignore policy controls.
- Text reports, remediation context, JSON output, strict exit codes, and run history for periodic agent execution.

### Changes

- Add self update command (f65af56)
- Improve docs install command copy UI (8973cfc)
- Add one-line install script (0509fdc)

---

## system-cli v0.1.1

- Source commit: `2c09ba3962c938ed6d47817f5513a225480b714b`
- Build hardening: `trimpath, stripped symbols, CGO disabled`
- Distribution tag: `system-cli-v0.1.1`

### Install

```bash
curl -fsSL -o system-cli https://github.com/jhl-labs/dist/releases/download/system-cli-v0.1.1/system-cli_v0.1.1_linux_amd64
chmod +x system-cli
sudo install -m 0755 system-cli /usr/local/bin/system-cli
system-cli --version
```

For Linux arm64, use `system-cli_v0.1.1_linux_arm64` in the download URL.

### Artifacts

- SHA256SUMS
- system-cli_v0.1.1_linux_amd64
- system-cli_v0.1.1_linux_arm64

### Highlights

- Agent-ready Linux host diagnostics for packages, updates, services, unit files, ports, SSH/sudo posture, hardening, containers, YAML manifests, and OSV advisories.
- Baseline drift detection with approval and ignore policy controls.
- Text reports, remediation context, JSON output, strict exit codes, and run history for periodic agent execution.

### Changes

- Ensure gh is available in release workflow (2c09ba3)
- Update release links to v0.1.1 (9bb3930)
- Improve public listener evidence output (8f98083)
- Publish releases to public dist repo (c225f21)
- Refocus docs on agent diagnostics (364495f)
- Align workflows with jhl-space runner (b2536d4)
- Document direct binary install (c11c555)
- Refine docs product copy (6db972b)
- Add docs theme switcher (a42fc4e)
- Match docs demo to CLI text output (0cbb255)
- Improve docs demo capture (bc6a2c2)
- Show version in text scan output (7d38bc8)
- Make docs page more compact and usage-focused (758d809)
- Add colorized CLI output and bilingual docs (4a7b76c)
- Add sanitized CLI demo to docs hero (e90ed8f)
- Remove terminal ghost from docs hero (6f9d0a0)
- Fix docs hero layout overlap (7d48d48)
- Enable Pages deployment from workflow (4986800)
- Add docs site and deployment workflows (d75725b)
- Make install deploy to configured bindir (8adb8a1)
- Support Docker fallback builds (462ecce)
- Add OSV vulnerability database checks (d480637)
- Use available self-hosted runner labels (c20423d)
- Fix runner group workflow syntax (7d2f744)
- Harden production diagnostics (af83426)
- Add package update and manifest checks (b1f6664)
- Clarify approved baseline output (ed3a397)
- Initial system diagnostic CLI (02d3030)

---

## system-cli v0.1.0

- Source commit: `6db972b7c0dbba956ce390a5346c039ba6869c33`
- Build hardening: `trimpath, stripped symbols, CGO disabled`
- Distribution tag: `system-cli-v0.1.0`

### Artifacts

- SHA256SUMS
- system-cli_v0.1.0_linux_amd64
- system-cli_v0.1.0_linux_arm64

### Install

```sh
curl -fsSL -o system-cli \
  https://github.com/jhl-labs/dist/releases/download/system-cli-v0.1.0/system-cli_v0.1.0_linux_amd64
chmod +x system-cli
sudo install -m 0755 system-cli /usr/local/bin/system-cli
system-cli --version
```

### Highlights

- Linux host diagnostics for packages, package updates, services, unit files,
  public listeners, SSH/sudo posture, accounts, containers, and YAML manifests.
- Local OSV advisory cache update, status, and installed package matching.
- Approved baseline drift detection for packages, services, units, and ports.
- Approval and ignore policy controls with reason, approver, and expiry fields.
- Text reports, remediation output, JSON output, and strict exit codes for
  runners and agents.
- GitHub Pages documentation with sanitized CLI demo, Korean/English language
  support, and light/dark/system themes.

### Changes

- docs: refine docs product copy (6db972b)
- docs: add theme switcher (a42fc4e)
- docs: match docs demo to CLI text output (0cbb255)
- docs: improve docs demo capture (bc6a2c2)
- feat: show version in text scan output (7d38bc8)
- docs: make docs page more compact and usage-focused (758d809)
- docs: add colorized CLI output and bilingual docs (4a7b76c)
- docs: add sanitized CLI demo to docs hero (e90ed8f)
- docs: remove terminal ghost from docs hero (6f9d0a0)
- docs: fix docs hero layout overlap (7d48d48)
- ci: enable Pages deployment from workflow (4986800)
- docs: add docs site and deployment workflows (d75725b)
- build: make install deploy to configured bindir (8adb8a1)
- build: support Docker fallback builds (462ecce)
- feat: add OSV vulnerability database checks (d480637)
- ci: use available self-hosted runner labels (c20423d)
- ci: fix runner group workflow syntax (7d2f744)
- feat: harden production diagnostics (af83426)
- feat: add package update and manifest checks (b1f6664)
- docs: clarify approved baseline output (ed3a397)
- feat: initial system diagnostic CLI (02d3030)

---
