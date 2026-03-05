# Ilshat Galimov Claude Code Plugins Marketplace

A curated collection of [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugins for Piano engineering teams.

## Available Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| [gitlab-review](https://github.com/ilshat-galimov/gitlab-review) | Code review automation | GitHub |

## Installation

1. Add the marketplace to Claude Code:
   ```
   /plugin marketplace add ilshat-galimov/marketplace
   ```

2. Install a plugin:
   ```
   /plugin install gitlab-review
   ```

## Marketplace Structure

```
.claude-plugin/
  marketplace.json    # Plugin registry with sources and metadata
```

The `marketplace.json` file defines all available plugins with their name, source repository, and branch reference.

