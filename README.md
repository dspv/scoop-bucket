# Caprock — Scoop bucket

[Scoop](https://scoop.sh) bucket for [Caprock](https://caprock.dev) — mission
control for Claude Code (Windows).

```powershell
scoop bucket add dspv https://github.com/dspv/scoop-bucket
scoop install caprock
caprock up          # opens http://127.0.0.1:4173
```

The `caprock.json` manifest is published here automatically by
[goreleaser](https://goreleaser.com) when a `v*` tag is cut in
[dspv/caprock](https://github.com/dspv/caprock). Do not edit it by hand — it is
generated.
