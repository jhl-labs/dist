# storage-cli release notes

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

