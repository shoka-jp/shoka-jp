# Hi, I'm shoka 👋

**I build open-source tools that connect AI with automotive diagnostics and maintenance.**

Software engineer based in Shizuoka, Japan. My projects help you explore vehicle data, structure diagnostic questions, and try automotive AI workflows — including a mock vehicle you can use without hardware.

[Follow my work](https://github.com/shoka-jp) · [Sponsor my open source](https://github.com/sponsors/shoka-jp) · [Technical notes on Qiita](https://qiita.com/shoka-jp)

## Start here: automotive × AI

| Project | What you can try |
| --- | --- |
| [**obd2-mcp**](https://github.com/shoka-jp/obd2-mcp) | Connect an AI assistant to OBD-II trouble codes, live sensors, freeze frames, and VIN data. Start with the built-in mock vehicle; no adapter required. |
| [**automotive-ai-skills**](https://github.com/shoka-jp/automotive-ai-skills) | Explore 16 AI skills for diagnostics, maintenance, used-car inspection, EVs, and more, with English and Japanese documentation. |

### Try the mock vehicle

With Claude Code installed, add the MCP server:

```bash
claude mcp add obd2 -- npx -y obd2-mcp
```

Then ask: **"Read the mock vehicle's trouble codes and freeze frame. What should I check before replacing parts?"**

The default connection is a simulated vehicle. See the [setup and safety notes](https://github.com/shoka-jp/obd2-mcp#quick-start-mock-mode--no-hardware) before connecting real hardware. Diagnostic output supports investigation; verify findings and vehicle specifications before acting.

## Follow, contribute, or support

[What your sponsorship supports / 支援対象について](./SPONSORING.md)

- **Follow** if you are interested in automotive AI, MCP tools, and practical open-source development.
- **Try a project** and share reproducible feedback in its issues: what you tried, what happened, and what you expected. Remove VINs and other personal information from logs.
- **Contribute** documentation fixes, translations, or examples through [automotive-ai-skills](https://github.com/shoka-jp/automotive-ai-skills/blob/main/CONTRIBUTING.md).
- **[Become a sponsor](https://github.com/sponsors/shoka-jp)** if these projects are useful to you and you would like to support my open-source work.

## Other projects and contributions

| Project | What it does |
| --- | --- |
| [PostOne docs](https://github.com/shoka-jp/PostOne-docs) | Public documentation for a social publishing and scheduling service. |
| [SellOne docs](https://github.com/shoka-jp/SellOne-docs) | User documentation for a Windows app that helps prepare marketplace listings. |

I also contribute documentation, reproducible examples, and focused improvements to other open-source projects:

[pytest contributions](https://github.com/pytest-dev/pytest/pulls?q=is%3Apr+author%3Ashoka-jp) · [VS Code Docs contributions](https://github.com/microsoft/vscode-docs/pulls?q=is%3Apr+author%3Ashoka-jp)

## 日本語

静岡を拠点に、**自動車 × AIのオープンソース**を開発しています。

- **[obd2-mcp](https://github.com/shoka-jp/obd2-mcp/blob/main/README.ja.md)**：AIから車両の故障コードやセンサーデータを読み取るMCPサーバー。機器なしで試せる模擬車両を同梱しています。
- **[automotive-ai-skills](https://github.com/shoka-jp/automotive-ai-skills/blob/main/README.ja.md)**：故障診断・整備・中古車チェックなどを支援する16種類のAIスキル集。

開発を追いたい方はフォロー、使ってみた感想や改善案は各リポジトリのIssueへ。活動を応援していただける方は、[GitHub Sponsors](https://github.com/sponsors/shoka-jp)からご支援いただけます。

[Qiitaの技術メモ](https://qiita.com/shoka-jp)
