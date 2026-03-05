# Piano Claude Plugins Marketplace

A curated collection of [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugins for Piano engineering teams.

## Available Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| [gitlab-review](https://github.com/ilshat-galimov/gitlab-review) | Code review automation | GitHub |

## Installation

Install a plugin from this marketplace using the Claude Code CLI:

```bash
claude plugin install <plugin-name> --from marketplace
```

Or add the plugin source directly to your project's `.claude/plugins.json`.

## Marketplace Structure

```
.claude-plugin/
  marketplace.json    # Plugin registry with sources and metadata
```

The `marketplace.json` file defines all available plugins with their name, source repository, and branch reference.

