# Tibeuru Console — releases

Public installer downloads for **Tibeuru Console** — Flutter Windows GUI for the Tibeuru API + MCP servers.

**The source code is intentionally not here** — it lives in a private repo. This repo exists only so the GitHub Releases page is publicly browsable for downloads.

## Latest

[Download the latest `TibeuruConsole-Setup-*.exe`](https://github.com/Tibeuru/tibeuru-console-releases/releases/latest).

## Install

Per-user install by default — lands under `%LocalAppData%\Programs\Tibeuru Console\` with no admin prompt. Elevate during the installer if you'd rather land in `Program Files`.

## What it does

Two-pane GUI front-end for [api.tibeuru.com](https://api.tibeuru.com) and [mcp.tibeuru.com](https://mcp.tibeuru.com):

- **Run a tool** — invoke any API endpoint or MCP tool with form-driven inputs, results in a terminal-styled output pane.
- **Keys** — manage your `tbk_*` API keys (create, copy, revoke, hard-delete).

Same `tbk_*` token works against both `api.tibeuru.com` and `mcp.tibeuru.com` after the 2026-05-10 `checkMcpAuth` fall-through fix landed in the MCP worker.

## License

See [tibeuru.com](https://tibeuru.com) — proprietary.
