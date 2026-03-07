<div align="center">

<img src="https://openpump.io/logo-icon.png" alt="OpenPump" width="120" />

# OpenPump

**MCP-native Solana trading infrastructure.**

22 MCP tools for pump.fun automation. Token launches, Jito bundles, curve sniping — one config away.

[![Website](https://img.shields.io/badge/openpump.io-F07A20?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyMCIvPjxwYXRoIGQ9Ik0xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweiIvPjwvc3ZnPg==&logoColor=white)](https://openpump.io)
[![X](https://img.shields.io/badge/@openpumpio-000?style=flat&logo=x&logoColor=white)](https://x.com/openpumpio)
[![npm](https://img.shields.io/badge/npm-@openpump-CB3837?style=flat&logo=npm&logoColor=white)](https://www.npmjs.com/org/openpump)

</div>

---

## Packages

| Package | Description | Install |
|---------|-------------|---------|
| [`@openpump/mcp`](https://www.npmjs.com/package/@openpump/mcp) | MCP server for Claude, Cursor & any MCP client | `npx @openpump/mcp init` |
| [`@openpump/sdk`](https://www.npmjs.com/package/@openpump/sdk) | Type-safe TypeScript client for every API endpoint | `npm i @openpump/sdk` |
| [`@openpump/solana-agent-kit`](https://www.npmjs.com/package/@openpump/solana-agent-kit) | Plug-in for Solana Agent Kit v2 | `npm i @openpump/solana-agent-kit` |
| [`@openpump/eliza-plugin`](https://www.npmjs.com/package/@openpump/eliza-plugin) | ElizaOS plugin with actions, evaluators & providers | `npm i @openpump/eliza-plugin` |

## Quick Start

```json
{
  "mcpServers": {
    "openpump": {
      "command": "npx",
      "args": ["-y", "@openpump/mcp"],
      "env": {
        "OPENPUMP_API_KEY": "op_sk_live_..."
      }
    }
  }
}
```

Get your API key at [openpump.io](https://openpump.io).

## What You Can Do

- **Launch tokens** on pump.fun with full metadata
- **Bundle buys** with Jito MEV protection
- **Snipe curves** with configurable slippage
- **Manage wallets** with HD-derived key pairs
- **Track positions** across all your tokens
- **Automate trading** via X/Twitter mentions

## Links

- [Documentation](https://openpump.io/docs)
- [Get Started](https://openpump.io/get-started)
- [API Reference](https://openpump.io/docs)
