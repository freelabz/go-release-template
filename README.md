# go-release-template
Go release template containing:
- `.goreleaser.yml` configuration (edit the `cmd:` attribute)
- `.github/workflows/release-test.yml`: run release tests on `.go` / `.mod` updates
- `.github/workflows/release-binary.yml`: run binary release on tag publish
