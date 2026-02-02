# Omni Ecosystem

A modular suite of terminal-first tools built in bash.

## Tools

| Tool | Description |
|------|-------------|
| **omni-cli** | Workspace manager with tmux integration for smart pane layouts and session control |
| **omni-secrets** | Encrypted secrets and vault management with age + gocryptfs |

### Libraries

These are internal libraries used by the tools above, but can be integrated into other projects:

| Library | Description |
|---------|-------------|
| **omni-ui-kit** | Shared UI components and helpers |
| **omni-navigator** | File browser and navigation utilities |

## Dependencies

Core: `bash`, `tmux`, `jq`

Optional: `git`, `age`, `gocryptfs`

## Installation

Each tool installs independently and pulls its own dependencies:
```bash
git clone https://github.com/omni-ecosystem/omni-cli.git
cd omni-cli
./install.sh
```

Tools install to `~/.omni-ecosystem/`. Add to your PATH:
```bash
export PATH="$HOME/.omni-ecosystem/bin:$PATH"
```

## Docs

[omni-cli-docs.vercel.app](https://omni-cli-docs.vercel.app/) - Note: It is deprecated at the moment I'm writing this (02/02/2026). I'm working in a new documentation site, in order to cover **all** omni apps and installation processes.
