# Homebrew Tap for MeowPass

Official Homebrew tap for [MeowPass](https://meowpass.dev) — open-source, CLI-first, E2E encrypted secret management for developers.

## Install

```bash
brew install meowrithm/tap/meowpass
```

Or tap first, then install:

```bash
brew tap meowrithm/tap
brew install meowpass
```

## Upgrade

```bash
brew upgrade meowpass
```

## Verify

```bash
meowpass --version
```

## What is MeowPass?

MeowPass is a secret vault for developers. Store API keys, sync .env files, and share secrets with your team — all E2E encrypted with AES-256-GCM.

```bash
meowpass login
meowpass vault create my-project
meowpass set STRIPE_KEY sk_live_... --vault <id>
meowpass get STRIPE_KEY --vault <id>
meowpass pull --vault <id> --env production
```

## Ecosystem

| Tool | Link |
|------|------|
| **Website** | [meowpass.dev](https://meowpass.dev) |
| **CLI Source** | [meowrithm/meowpass-cli](https://github.com/meowrithm/meowpass-cli) |
| **Web App** | [app.meowpass.dev](https://app.meowpass.dev) |
| **Chrome Extension** | [meowrithm/meowpass-extension](https://github.com/meowrithm/meowpass-extension) |
| **MCP Server** | [@meowlabs/meowpass-mcp](https://www.npmjs.com/package/@meowlabs/meowpass-mcp) |
| **Claude Code Skill** | [meowrithm/meowpass-skill](https://github.com/meowrithm/meowpass-skill) |
| **Discord** | [Join community](https://discord.gg/GTZcZKRQu7) |

## License

MIT
