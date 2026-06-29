# scoop-xbrain

Scoop bucket for [**xbrain**](https://github.com/xsaven/xbrain) — the declarative AI agent compiler (compile YAML to Claude, Codex, Gemini, Qwen, OpenCode).

## Install

```powershell
scoop bucket add xbrain https://github.com/xsaven/scoop-xbrain
scoop install xbrain
```

This installs `xbrain.exe` plus an `xb` shim.

## Update

```powershell
scoop update xbrain
```

## Notes

- `xbrain.json` is generated and pushed automatically by [GoReleaser](https://goreleaser.com) on each tagged release of the main repo — do not edit it by hand.
- Stable releases only; pre-releases (`-rc.N`) skip the manifest update (`skip_upload: auto`).
