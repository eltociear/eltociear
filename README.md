

[🌊 Explore top tech opportunities on WAVEE — a place to connect, build, and grow.
Get access 🎟️](https://wavee.world/en/invitation/b96d00e6-b802-4a1b-8a66-2e3854a01ffd)


<!-- ### 🤖🤖🗼 -->

## ⚡ Pay-per-call APIs for AI agents

**148 paid routes across three services.** x402 micropayments in USDC on Base —
no account, no API key, no signup. Every route publishes its price, input schema and a
worked example in its own `402` response, so an agent can discover and use it unattended.

| Service | Routes | What it covers |
|---|---|---|
| [**tokenguard**](https://eltociear-tokenguard.hf.space) | 132 | crypto & DeFi, plus weather, stocks, FX, air quality, earthquakes, holidays, world-bank indicators |
| [**skill-audit**](https://eltociear-skill-audit.hf.space) | 15 | web read/crawl/search, MCP and agent-skill security scanning |
| [**contract-guard**](https://eltociear-contract-guard.hf.space) | 1 | pre-interaction EVM contract and token risk check |

Each service also speaks **MCP** at `/mcp` with free tools alongside the paid ones —
usable directly from Claude, Cursor or any MCP client.
Route list and prices: `GET /.well-known/x402` on any of the three.

**Published to the official MCP registry** (6 servers): `contract-guard-mcp` ·
`repo-security-scanner` · `secrets-audit-mcp` · `skill-audit-mcp` · `tokenguard-mcp` ·
`url-to-markdown-for-llms`

## 🔒 Security tooling

[**MCP Security Audit**](https://skill-audit-api.eltociear.workers.dev) — a scanner for MCP
servers and agent skill files: **17 named patterns / 60 regex signatures** across 4 severity
levels.

The number worth quoting is not the pattern count, it is the calibration: a false-positive
pass took the rate from **14.8% to 1.0%** across **196 public MCP servers**, of which **194
came back clean**. Most scanners in this space are tuned to find something. This one is tuned
to be believed when it does.

- [mcp-audit](https://github.com/eltociear/mcp-audit) — zero-dependency scanner, CLI / GitHub Action / Docker / MCP / x402
- [pypi-supply-scan](https://github.com/eltociear/pypi-supply-scan) — zero-dependency PyPI supply-chain inspector

## 📊 Awesome lists

- [**AI-Driven Development**](https://github.com/eltociear/awesome-AI-driven-development) — AI駆動開発ツールのまとめ
- [**Molt Ecosystem**](https://github.com/eltociear/awesome-molt-ecosystem) — a brutally honest guide to 200+ AI agent platforms

## ✍️ Writing

Engineering notes from running a long-lived autonomous agent — monitoring, scheduling,
measurement, and the numbers that turned out to be wrong:
**[eltociear.github.io](https://eltociear.github.io/)**

- [A green test is a claim about a sample](https://eltociear.github.io/posts/a-green-test-is-a-claim-about-a-sample/)
- [Count the silence: three green monitors that were lying](https://eltociear.github.io/posts/count-the-silence/)
- [Measure it to the payout address](https://eltociear.github.io/posts/measure-to-the-payout-address/)
- [Your cron expression is not your schedule](https://eltociear.github.io/posts/your-cron-expression-is-not-your-schedule/)

## 💰 Work with me

- **MCP server / agent-skill security audits** — 17 patterns, calibrated to a 1% false-positive rate over 196 public servers
- **Agent-economy research** — measured to the payout address, not to the marketing page

Email **eltociear@gmail.com**

**USDC / ETH on Base:** `0x5bCDA55247B238a573A968B234F788a2D35664Dd`
**Lightning:** `eltociear@coinos.io`
**Nostr:** `npub15e4nss9atrl9mzna8xwwsp58v64c822uklscp6k75hw2ly2amh6q7ck488`
