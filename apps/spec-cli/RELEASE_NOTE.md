# spec-cli release notes

## spec-cli v0.2.0

- Source commit: `726ca1a145ddd7e7e0d7e4cea0fa2957af745b29`
- Build runner: `jhl-space`
- Distribution tag: `spec-cli-v0.2.0`

### Artifacts

- SHA256SUMS
- spec-cli_v0.2.0_darwin_amd64
- spec-cli_v0.2.0_darwin_amd64.tar.gz
- spec-cli_v0.2.0_darwin_arm64
- spec-cli_v0.2.0_darwin_arm64.tar.gz
- spec-cli_v0.2.0_linux_amd64
- spec-cli_v0.2.0_linux_amd64.tar.gz
- spec-cli_v0.2.0_linux_arm64
- spec-cli_v0.2.0_linux_arm64.tar.gz
- spec-cli_v0.2.0_windows_amd64.exe
- spec-cli_v0.2.0_windows_amd64.tar.gz
- spec-cli_v0.2.0_windows_arm64.exe
- spec-cli_v0.2.0_windows_arm64.tar.gz

### Changes

- ci: provision release race toolchain (726ca1a)
- ci: isolate release quality gate (ff88615)
- ci: enable cgo for release race tests (137921c)
- docs: prepare v0.2.0 release metadata (469f0ac)
- build: align release version metadata (a07176f)
- feat: integrate trace reports and quality gates (5301fe6)
- feat: add summary and SARIF renderers (b2b1b97)
- feat: add requirement trace diagnostics (e0cedf7)
- fix: harden requirement evidence pipeline (e793da6)
- build: go 1.26 (garble v0.16.0 요구, security-cli와 일치) (d65c165)

---

## spec-cli v0.1.0

- Source commit: `e4cd775be08bd7f954e963c6e5525061bacd6a9d`
- Build runner: `local`
- Distribution tag: `spec-cli-v0.1.0`

### Artifacts

- SHA256SUMS
- spec-cli_v0.1.0_darwin_amd64
- spec-cli_v0.1.0_darwin_amd64.tar.gz
- spec-cli_v0.1.0_darwin_arm64
- spec-cli_v0.1.0_darwin_arm64.tar.gz
- spec-cli_v0.1.0_linux_amd64
- spec-cli_v0.1.0_linux_amd64.tar.gz
- spec-cli_v0.1.0_linux_arm64
- spec-cli_v0.1.0_linux_arm64.tar.gz
- spec-cli_v0.1.0_windows_amd64.exe
- spec-cli_v0.1.0_windows_amd64.tar.gz
- spec-cli_v0.1.0_windows_arm64.exe
- spec-cli_v0.1.0_windows_arm64.tar.gz

### Changes

- build: jhl-labs/dist 릴리스 인프라 (workflow·artifacts·install.sh) (e4cd775)
- fix(verify): Go 스타일 케이스 이름(REQ002) 정규화 매칭 — 실패 테스트 오판(verified) 수정 (fefd8ec)
- fix(cli): 실행 초입에 이전 리포트 제거 — exit 3 시 낡은 리포트 잔존 방지 (cd2e415)
- docs: README + Makefile; jam spec 컴포넌트 계약 스모크 확인 (9b92ab6)
- feat(cli): run/init 명령 + exit code 계약 + 통합 테스트 (285a8a5)
- feat(report): spec-report.json(jam 계약) / Markdown 렌더 (2331d40)
- feat(verify): 요구사항 판정 규칙 (추적 + 테스트 결과 결합) (9d255f4)
- feat(testreport): test-cli report@1 서브셋 리더 (7a835ec)
- feat(scan): 테스트 파일 발견 + REQ ID 참조 스캔 (434f675)
- feat(require): 요구사항 Markdown 파서 (6b80216)
- feat: 스캐폴드 + version 명령 (c478c74)
- docs: spec-cli 구현 계획 (a3faee7)
- docs: spec-cli 설계 스펙 (bb9e509)

---
