# gitopsctl release notes

## gitopsctl v0.1.0

- Source repository: `jhl-labs/gitops-cli`
- Source commit: `d3b849b5ab0dc6c9b7f2f692a36531f62611d8d5`
- Build hardening: `trimpath, stripped symbols, CGO disabled`
- Distribution tag: `gitopsctl-v0.1.0`

### Install

```bash
curl -fsSL https://jhl-labs.github.io/gitops-cli/install.sh | sudo bash
gitopsctl --version
```

For a specific version, run:

```bash
curl -fsSL https://jhl-labs.github.io/gitops-cli/install.sh | sudo env VERSION=v0.1.0 bash
```

### Artifacts

- SHA256SUMS
- gitopsctl_v0.1.0_darwin_amd64
- gitopsctl_v0.1.0_darwin_arm64
- gitopsctl_v0.1.0_linux_amd64
- gitopsctl_v0.1.0_linux_arm64
- gitopsctl_v0.1.0_windows_amd64.exe

### Highlights

- Read-only GitOps tracing across GitHub, OCI images, Argo CD Applications, Kubernetes workloads, and ingress URLs.
- Fleet diagnostics for Argo CD drift, application health, operation state, workload rollout, pod readiness, restarts, and warning events.
- Stable table, JSON, and YAML output with deterministic exit codes for automation.

### Changes

- fix: avoid api rate limit in installer (d3b849b)
- ci: handle missing c compiler for race tests (0bd60a2)
- ci: enable cgo for race tests (9251059)
- fix: resolve security scan findings (1ad9d92)
- feat: publish via dist releases and pages (87b8641)
- feat: add workload evidence and fleet scan hardening (173fcd9)
- feat: add live doctor and app fleet scans (389ad0c)
- feat: add registry credential chain (735e988)
- feat: add image provenance diagnostics (aa5f7cb)
- feat: add url route diagnostics (87309ee)
- feat: add ingress url tracing (eb7d2f8)
- feat: add image trace and repository diagnostics (37b39aa)
- feat: add application trace and diagnose (37b69cf)
- feat: polish terminal table output (579117b)
- feat: add Argo CD application status (c0db580)
- feat: add Kubernetes workload status (eb63ff3)
- feat: add initial gitopsctl scaffold (f4778a9)
- docs: initialize project guidance (071d808)

---
