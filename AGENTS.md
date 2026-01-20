# AGENTS.md

This file provides guidance for AI coding agents working with this repository.

## Project Overview

**Awesome Finance MCP** is a curated list of MCP (Model Context Protocol) servers and AI skills for finance, trading, and crypto. It follows the [awesome-list](https://github.com/sindresorhus/awesome) format.

**This is a documentation-only repository** - it contains no code to build or test. The primary file is `README.md`.

## Repository Structure

```
awesome-finance-mcp/
├── README.md           # Main list (this is what contributors edit)
├── CONTRIBUTING.md     # Human contributor guidelines
├── AGENTS.md           # This file (AI agent guidelines)
└── assets/             # Images and logos
```

## Adding a New MCP Server

### Entry Format

All entries must follow this exact markdown table format:

```markdown
| [Name](https://github.com/org/repo) | Brief description (under 60 chars) | Pricing | ![GitHub stars](https://img.shields.io/github/stars/org/repo?style=flat) |
```

### Valid Pricing Values

Use one of these exact values:
- `Free` - Completely free
- `Freemium` - Free tier with paid upgrades
- `Requires API key` - Free with registration
- `Paid API key` - Requires paid subscription
- `Requires credentials` - Needs account credentials
- `Requires wallet` - Needs crypto wallet
- `Free (x402)` - Uses x402 micropayments
- `Free (self-hosted)` - Requires self-hosting

### Categories

Add entries to the appropriate section in README.md:

**MCP Servers:**
- Stock Market → Data Providers, Trading Execution
- Cryptocurrency → Crypto Data Providers, Crypto Trading Execution, On-Chain Analytics
- DeFi & Swaps
- Personal Finance
- Payments & Banking
- Blockchain & Web3
- Financial Intelligence

**Community Contributions:** For user-submitted MCPs (includes contributor attribution)

**Skills:** For task-level workflows built on MCP servers

### Community Contribution Format

```markdown
| [Name](https://github.com/org/repo) | Description | Pricing | ![stars](https://img.shields.io/github/stars/org/repo?style=flat) | *[@username](https://github.com/username)* |
```

### Skill Entry Format

```markdown
| [Name](https://github.com/org/repo) | Description | Built On | ![GitHub stars](https://img.shields.io/github/stars/org/repo?style=flat) |
```

## Validation Checklist

Before submitting changes:

- [ ] Entry is finance/trading/crypto related
- [ ] GitHub link is valid and repository exists
- [ ] Description is under 60 characters
- [ ] Pricing value matches one of the valid options
- [ ] Stars badge URL matches the repository URL
- [ ] Entry is placed in the correct category
- [ ] Table alignment is preserved (use spaces, not tabs)
- [ ] No duplicate entries exist

## Style Conventions

- Keep descriptions concise and factual
- Use proper capitalization (not ALL CAPS)
- No promotional language or superlatives
- Link directly to GitHub repositories (not landing pages)
- Maintain alphabetical order within subsections when possible

## Common Tasks

### Verify a GitHub link works
Check that `https://github.com/org/repo` returns 200.

### Update star counts
Star badges auto-update via shields.io - no manual updates needed.

### Add a new category
New categories require at least 2-3 entries to justify creation. Add to the Table of Contents and create a new `## Section` with appropriate `###` subsections.

## Maintainer

This list is maintained by [BlockRun](https://blockrun.ai). For questions, open an issue or contact [@blockrunai](https://twitter.com/blockrunai).
