# scoop-bucket

Scoop bucket for Zesh-One tools.

## Install

```powershell
scoop bucket add zeshone https://github.com/zeshone/scoop-bucket
scoop install doc-agent-ai
```

Then:

```powershell
doc-agent-ai install
```

## Available manifests

- **doc-agent-ai** — Multi-platform documentation workflow agent installer ([source](https://github.com/zeshone/doc-agent-ai))

## Update

```powershell
scoop update
scoop update doc-agent-ai
```

## Uninstall

```powershell
scoop uninstall doc-agent-ai
scoop bucket rm zeshone
```

---

Manifests in this bucket are published automatically by [goreleaser](https://goreleaser.com) and a release hook on every tagged release of the upstream repo. Do not edit `bucket/*.json` by hand — changes will be overwritten by the next release.
