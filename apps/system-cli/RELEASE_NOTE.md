# system-cli release notes

## system-cli v0.1.0

- Source commit: `6db972b7c0dbba956ce390a5346c039ba6869c33`
- Build hardening: `trimpath, stripped symbols, CGO disabled`
- Distribution tag: `system-cli-v0.1.0`

### Artifacts

- SHA256SUMS
- system-cli_v0.1.0_linux_amd64.tar.gz
- system-cli_v0.1.0_linux_arm64.tar.gz

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
