# install-claude-workflow-v2

Install the Claude Code workflow plugin with a single command.

## Usage

```bash
npm exec install-claude-workflow-v2@latest
```

Or with npx:
```bash
npx --yes install-claude-workflow-v2@latest
```

That's it. Run `claude` to start.

## What Gets Installed

```
.claude/
├── agents/      # 7 specialized subagents
├── skills/      # 10 knowledge domains
├── commands/    # 17 slash commands
└── hooks/       # 9 automation scripts
```

## Features

- **Additive install** - Preserves your existing `.claude/` files
- **No git history** - Downloads clean tarball, not full repo
- **Single command** - No configuration needed

## Requirements

- Node.js 16+
- [Claude Code CLI](https://claude.ai/code)

## Repository

https://github.com/CloudAI-X/claude-workflow

## License

MIT
