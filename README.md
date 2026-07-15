# scoop-bucket

[Scoop](https://scoop.sh) bucket for [**spxrogers**](https://github.com/spxrogers)'
projects — install command-line tools on Windows with `scoop`.

## Install

```powershell
scoop bucket add spxrogers https://github.com/spxrogers/scoop-bucket
scoop install <project>
```

## What's in the bucket

| Project | Install | Description |
| --- | --- | --- |
| [agentsync](https://github.com/spxrogers/agentsync) | `scoop install agentsync` | Centrally manage AI coding-agent configurations (Claude Code, OpenCode, Codex, and more) from one canonical, committable source. |

## How this bucket is maintained

The manifests under [`bucket/`](bucket/) are **generated** and updated
automatically by each project's release pipeline
([GoReleaser](https://goreleaser.com) on every tagged release). Don't edit them
by hand — they're overwritten on the next release.

## License

[MIT](LICENSE). Each project is licensed by its upstream repository.
