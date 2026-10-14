# abelland-lgtm/scoop-bucket

[Scoop](https://scoop.sh) manifests for [abelland-lgtm](https://github.com/abelland-lgtm)'s projects on Windows.

```powershell
scoop bucket add extras
scoop bucket add abelland https://github.com/abelland-lgtm/scoop-bucket
```

`extras` is needed for mpv, which tbard depends on.

## Apps

| App | Description | Install |
|---|---|---|
| [tbard](https://abelland-lgtm.github.io/tbard/) | Audiobook manager and listener for the terminal (installs mpv and ffmpeg too) | `scoop install abelland/tbard` |

Update with `scoop update *`.

## Maintenance

Each project's release workflow writes its manifest in `bucket/` automatically on every release. Change the
project's workflow rather than editing the manifests here by hand.
