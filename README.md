# xom11 Scoop bucket

Bucket for [xom11](https://github.com/xom11) tools.

## Usage

```powershell
scoop bucket add xom11 https://github.com/xom11/scoop-bucket
scoop install beckon
# or:
scoop install xom11/beckon
```

## Available manifests

- [beckon](https://github.com/xom11/beckon) — cross-platform focus-or-launch app switcher (x86_64 + arm64)

## Auto-generated

This repo is updated automatically by the
[`bump-packagers.yml`](https://github.com/xom11/beckon/blob/main/.github/workflows/bump-packagers.yml)
workflow in `xom11/beckon` on every release. Do not hand-edit `bucket/*.json`
— changes will be overwritten by the next release.

The workflow authenticates via the fine-grained PAT stored in repo secret
`PACKAGER_TOKEN` on `xom11/beckon`. Scope: `Contents: write` on this repo
and `xom11/homebrew-tap` only. Renew before expiry (default 90 days).
