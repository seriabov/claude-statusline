# claude-statusline

Customized Claude Code statusline showing directory, context usage, git info, session duration, and rate limits in a compact single-line format.

Based on [@kamranahmedse/claude-statusline](https://github.com/kamranahmedse/claude-statusline).

## Install

```bash
npx github:seriabov/claude-statusline
```

This backs up your old statusline (if any), copies the script to `~/.claude/statusline.sh`, and configures your Claude Code settings.

## Requirements

- [jq](https://jqlang.github.io/jq/) — for parsing JSON
- curl — for fetching rate limit data
- git — for branch info

On macOS:

```bash
brew install jq
```

## Uninstall

```bash
npx github:seriabov/claude-statusline --uninstall
```

If you had a previous statusline, it restores it from the backup. Otherwise it removes the script and cleans up your settings.

## License

MIT
