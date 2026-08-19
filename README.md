# Caprock — Scoop bucket

[Scoop](https://scoop.sh) bucket for [**Caprock**](https://github.com/dspv/caprock)
— mission control for Claude Code (Windows). Website:
[caprock.dev](https://caprock.dev).

```powershell
scoop bucket add dspv https://github.com/dspv/scoop-bucket
scoop install caprock
caprock up          # opens http://127.0.0.1:4173
```

On macOS or Linux? Use the [Homebrew tap](https://github.com/dspv/homebrew-tap)
instead (`brew install dspv/tap/caprock`). Everything else — docs, releases,
issues — is in the main repo, [**dspv/caprock**](https://github.com/dspv/caprock).

The `caprock.json` manifest is published here automatically by
[goreleaser](https://goreleaser.com) when a `v*` tag is cut in
[dspv/caprock](https://github.com/dspv/caprock). Do not edit it by hand — it is
generated.
