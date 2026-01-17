# Contributing to Awesome Finance MCP

Thank you for your interest in contributing to this list! This document provides guidelines for adding new MCP servers.

## Adding a New MCP Server

### Requirements

Your MCP server must:

1. **Be finance-related** - Trading, payments, banking, crypto, DeFi, personal finance, or financial data
2. **Have a working GitHub repository** - With clear documentation on how to install and use it
3. **Be an actual MCP server** - Following the [Model Context Protocol specification](https://modelcontextprotocol.io/)
4. **Be functional** - We may test submissions before merging

### How to Submit

1. **Fork this repository**

2. **Add your MCP to the appropriate section** in `README.md`

3. **Follow this format:**

```markdown
| [Name](https://github.com/org/repo) | Brief description (under 60 chars) | Pricing model | ![GitHub stars](https://img.shields.io/github/stars/org/repo?style=flat) |
```

4. **Pricing options:**
   - `Free` - Completely free to use
   - `Freemium` - Has a free tier with paid upgrades
   - `Requires API key` - Free with registration
   - `Paid API key` - Requires paid subscription
   - `Requires credentials` - Needs account credentials
   - `Requires wallet` - Needs crypto wallet connection
   - `Free (x402)` - Uses x402 micropayments
   - `Free (self-hosted)` - Free but requires self-hosting

5. **Submit a Pull Request** with:
   - Clear title: `Add [MCP Name]`
   - Brief description of what the MCP does
   - Which category it belongs to

### Quality Guidelines

**Do:**
- Keep descriptions concise and informative
- Use proper capitalization
- Link directly to the GitHub repository
- Ensure all links work

**Don't:**
- Add MCPs that are abandonware or broken
- Submit duplicate entries
- Add promotional language
- Include personal API keys or credentials in examples

### Creating a New Category

If your MCP doesn't fit existing categories:

1. Propose the new category in your PR description
2. Include at least 2-3 MCPs for the category
3. Place it in logical order within the document

## Updating Existing Entries

To update information about an existing MCP:

1. Fork the repository
2. Make your changes
3. Submit a PR explaining what changed and why

## Reporting Issues

Found a broken link or incorrect information?

1. Open an issue with the `bug` label
2. Include which MCP has the problem
3. Describe what's wrong

## Code of Conduct

- Be respectful and constructive
- No spam or self-promotion beyond legitimate MCP submissions
- Help maintain a useful resource for the community

## Questions?

Open an issue with the `question` label or reach out to [@blockrunai](https://twitter.com/blockrunai) on Twitter.

---

Thank you for helping make this list better!
