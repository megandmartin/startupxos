<p align="center">
  <a href="https://www.startupxos.com/preview"><img src="assets/startupxos-tour.gif" alt="A six-second tour of the startupxOS desktop app: Today, the workspace hub, agent approvals and connections. Real screens from the public preview with a fictional demo company." width="100%"></a>
</p>

<h1 align="center">startupxOS</h1>
<p align="center"><strong>Your agents do the work. You run the company.</strong><br>The AI operating system for startups.</p>
<p align="center">
  <a href="https://www.startupxos.com/preview"><strong>Try the live preview</strong></a> ·
  <a href="https://www.startupxos.com/download">Download for Mac or Windows</a> ·
  <a href="#releases">Release notes</a> ·
  <a href="https://github.com/megandmartin/startupxos/issues/new/choose">Give feedback</a>
</p>

This is the public home for startupxOS **release notes, checksums and feedback**. The app's source is private.

## What it does

- **One company brain.** Capture company information with its source, and link decisions to their evidence and outcomes.
- **Agents draft, you approve.** Drafts pause in Approvals until you approve, edit or decline them. Nothing leaves without you.
- **Your AI tools, scoped.** Claude and Codex connect through MCP and see only what you grant, with an audit trail per tool.
- **Your data stays yours.** An encrypted workspace on your own computer, with a vault password and an optional recovery key.

The [web preview](https://www.startupxos.com/preview) runs a fictional demo company in your browser, with nothing to install.

## Download

| | Requirements | |
|---|---|---|
| **Mac** | Apple Silicon · macOS 15 or later | [Download](https://www.startupxos.com/download) |
| **Windows** | Intel or AMD x64 · Windows 11 | [Download](https://www.startupxos.com/download) |

Early preview: the Mac build is ad-hoc signed and not yet notarized, and the Windows installer is not yet publisher-signed, so your computer may warn before opening it. Read the [install notes](https://www.startupxos.com/install) and check the download against the published [SHA-256 checksums](https://www.startupxos.com/releases/SHA256SUMS.txt).

## Releases

| Version | Date | What changed |
|---|---|---|
| [**0.2.15**](https://github.com/megandmartin/startupxos/releases/tag/v0.2.15) · Mac and Windows · public preview | 12 Nov 2026 | The new startupxOS look: styles x, Clarity and Zen, in light and dark, kept through lock, restart and upgrade. Agent approvals never show more than the records they quote |
| [0.2.14](https://github.com/megandmartin/startupxos/releases/tag/v0.2.14) · Mac · private test build | 10 Nov 2026 | Open demo from the vault screen |
| [0.2.13](https://github.com/megandmartin/startupxos/releases/tag/v0.2.13) · Mac · private test build | 10 Nov 2026 | Founder Desk on Today; an on-device drafting agent for approved tasks |
| [0.2.12](https://github.com/megandmartin/startupxos/releases/tag/v0.2.12) · Windows · private test build | 10 Nov 2026 | Start a new encrypted workspace from the vault screen; recovery-key reminder |
| [0.2.11](https://github.com/megandmartin/startupxos/releases/tag/v0.2.11) · Windows · public preview | 10 Nov 2026 | Resumable vault setup; clearer password and workspace errors; add a recovery key later in Settings |
| [0.2.10](https://github.com/megandmartin/startupxos/releases/tag/v0.2.10) · Windows · private test build | 10 Nov 2026 | Optional recovery-key enrolment after first setup |
| [0.2.9](https://github.com/megandmartin/startupxos/releases/tag/v0.2.9) · Mac · public preview | 4 Nov 2026 | Encrypted workspaces with vault passwords, recovery keys, and an encrypted database and backups |

Public previews are the versions offered for download, and each has its SHA-256 checksums on its release page. Private test builds were tested in-house before the next public preview and were never offered for download. Installers are only on [startupxos.com/download](https://www.startupxos.com/download).

## Built by

[Megan Martinsone](https://github.com/megandmartin), co-founder, CEO and CTO, who writes the code: Electron, React, Node.js, an encrypted SQLite workspace and MCP. startupxOS is built on the [SuperBrain](https://github.com/megandmartin/superbrain-downloads) company-memory core.
