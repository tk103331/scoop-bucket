# Oni3 Scoop Bucket

[Scoop](https://scoop.sh) bucket for [Oni3](https://github.com/tk103331/oni3) — an AI
Agent TUI with tools, MCP and ACP support, built on
[CloudWeGo Eino](https://github.com/cloudwego/eino).

## Install

```powershell
scoop bucket add oni3 https://github.com/tk103331/scoop-bucket
scoop install oni3
```

## Update

```powershell
scoop update
scoop update oni3
```

The manifest follows the GitHub releases, so `scoop update oni3` picks up new
versions on its own. The published hash is read from the release's
`checksums.txt`.

## Uninstall

```powershell
scoop uninstall oni3
```

## Notes

The Windows build is a static binary and needs no extra runtime. Oni3 is a
terminal UI: run it from Windows Terminal or PowerShell 7 for the best
experience.