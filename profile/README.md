<div align="center">

# 🏴‍☠️🌌🪐 SuperNovae 🪐🌌🏴‍☠️

### `Small crew, massive impact.` Two builders, one studio, charting our own seas: consumer products people love, and the sovereign AI infrastructure underneath that nobody can capture.

<br />

<a href="https://supernovae.studio"><img src="https://raw.githubusercontent.com/supernovae-st/.github/main/assets/supernovae-ship.gif" width="720" alt="The SuperNovae ship" /></a>

</div>

---

<p align="center">
  <a href="https://nika.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://nika.sh/brand/nika-logo-dark.svg">
      <img src="https://nika.sh/brand/nika-logo-light.svg" alt="Nika" width="200">
    </picture>
  </a>
</p>

<h2 align="center">🦋 Nika · Intent as Code</h2>

<p align="center"><strong>The workflow language for AI. One file, 4 verbs, one Rust binary. Local-first, any model, AGPL-3.0.</strong></p>

<p align="center">
  <a href="https://nika.sh"><img src="https://img.shields.io/badge/-nika.sh-FF7A3C?style=flat-square" alt="nika.sh"></a>
  <a href="https://github.com/supernovae-st/nika/releases/latest"><img src="https://img.shields.io/github/v/release/supernovae-st/nika?label=engine&style=flat-square" alt="Engine release"></a>
  <a href="https://www.npmjs.com/package/@supernovae-st/nika"><img src="https://img.shields.io/npm/v/@supernovae-st/nika?label=npm&style=flat-square" alt="npm package"></a>
  <a href="https://docs.nika.sh"><img src="https://img.shields.io/badge/docs-docs.nika.sh-8b8cf8?style=flat-square" alt="Documentation"></a>
  <a href="https://github.com/supernovae-st/nika-spec"><img src="https://img.shields.io/badge/spec-open-8b8cf8?style=flat-square" alt="Open specification"></a>
</p>

<p align="center">
  <a href="https://scorecard.dev/viewer/?uri=github.com/supernovae-st/nika"><img src="https://api.scorecard.dev/projects/github.com/supernovae-st/nika/badge" alt="OpenSSF Scorecard"></a>
  <a href="https://github.com/supernovae-st/nika/actions/workflows/codeql.yml"><img src="https://github.com/supernovae-st/nika/actions/workflows/codeql.yml/badge.svg?branch=main" alt="CodeQL"></a>
  <a href="https://github.com/supernovae-st/nika/releases/latest"><img src="https://slsa.dev/images/gh-badge-level3.svg" alt="SLSA 3 provenance on every release"></a>
  <a href="https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/supernovae-st/nika"><img src="https://archive.softwareheritage.org/badge/origin/https://github.com/supernovae-st/nika/" alt="Archived by Software Heritage"></a>
  <a href="https://github.com/supernovae-st/nika/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-blue.svg" alt="AGPL-3.0-or-later"></a>
</p>

Write one `.nika.yaml`. `nika check` audits it before a token is spent: the order of effects, the permits boundary, the journey of every secret, the cost floor. `nika run` runs it on the models you already have, local first (Ollama · llama.cpp · vLLM), then Mistral, Hugging Face, OpenAI, xAI, Anthropic and the rest of the catalog, and seals a hash-chained trace after. **4 verbs, 17 providers, 28 builtin tools**<!-- counts: nika-spec/canon.yaml is the SSOT · update from there, never by memory -->. Built in public.

### One door per surface

| Surface | The door |
|---|---|
| Terminal · macOS and Linux | `curl -LsSf https://nika.sh/install.sh \| sh` |
| Homebrew | `brew install supernovae-st/tap/nika` |
| Node.js | `npm install @supernovae-st/nika` |
| VS Code · Cursor · Windsurf · VSCodium | [`supernovae.nika-lang`](https://marketplace.visualstudio.com/items?itemName=supernovae.nika-lang) on the Marketplace, [on Open VSX](https://open-vsx.org/extension/supernovae/nika-lang) for the forks |
| GitHub CLI | `gh extension install supernovae-st/gh-nika` · then `gh nika check flow.nika.yaml` |
| GitHub Actions | `uses: supernovae-st/nika-action@v1` |
| Your coding agent | `npx plugins add supernovae-st/nika-plugins` |
| Shared workflows | `invoke: { workflow: "registry:<owner>/<name>@<version>" }` |

<!-- city:map -->
### The city · thirteen buildings

```text
📜 nika-spec ──── the law of the language · nine keys, four verbs, the conformance suite
    │
    ▼
⚙️ nika ───────── the engine · one binary that audits, runs, traces and schedules every workflow
    │
    ├── 🖥️ nika.sh · the site and the timeline        📖 nika-docs · the manual
    ├── 📦 homebrew-tap · npm · the docks
    ├── 🔌 nika-client · 🎨 nika-vscode · 🤖 nika-plugins · ⚡ gh-nika · the doors
    ├── 🏭 nika-action · 🧪 nika-actions-starter · the CI district
    └── 🏪 nika-registry · the market                 🏛 nika-estate · the land registry
```

| Building | What it is for |
|---|---|
| [`nika`](https://github.com/supernovae-st/nika) | The engine: one Rust binary that audits, runs and traces every workflow · AGPL-3.0-or-later |
| [`nika-spec`](https://github.com/supernovae-st/nika-spec) | The law of the language: nine keys, four verbs, a conformance suite anyone can run · Apache-2.0 |
| [`nika-docs`](https://github.com/supernovae-st/nika-docs) | The manual: guides, reference, recipes · [docs.nika.sh](https://docs.nika.sh) |
| [`nika.sh`](https://nika.sh) | The site, and [the timeline](https://nika.sh/timeline): every claim re-proven in CI · gates, never dates |
| [`nika-client`](https://github.com/supernovae-st/nika-client) | The TypeScript SDK, published as `@supernovae-st/nika`: typed check, streamed runs, receipts |
| [`nika-vscode`](https://github.com/supernovae-st/nika-vscode) | The editor: diagnostics as you type, the DAG canvas, live runs and replay, local models |
| [`nika-plugins`](https://github.com/supernovae-st/nika-plugins) | One Add teaches your coding agent the language: skills, commands, hooks, the read-only MCP oracle |
| [`gh-nika`](https://github.com/supernovae-st/gh-nika) | The GitHub CLI extension: `gh nika check`, `gh nika run`, the engine fetched checksum-verified |
| [`homebrew-tap`](https://github.com/supernovae-st/homebrew-tap) | The Homebrew door: `brew install supernovae-st/tap/nika`, completions included |
| [`nika-action`](https://github.com/supernovae-st/nika-action) | The GitHub Action: the check verdict, the cost floor and the DAG on every pull request |
| [`nika-actions-starter`](https://github.com/supernovae-st/nika-actions-starter) | The template repository: receipts on every pull request from the first green run |
| [`nika-registry`](https://github.com/supernovae-st/nika-registry) | Share workflows, packs, skills and agents: every entry re-proven by CI, hash and oracle |
| [`nika-estate`](https://github.com/supernovae-st/nika-estate) | The land registry: every file's provenance declared, sealed, anchored · the hundred-year machinery |

The living map: [nika.sh/map](https://nika.sh/map).
<!-- /city:map -->

**The watchdogs** · the city proves itself on a schedule, in public:

[![timeline](https://github.com/supernovae-st/nika-spec/actions/workflows/timeline.yml/badge.svg)](https://github.com/supernovae-st/nika-spec/actions/workflows/timeline.yml)
[![e2e smoke](https://github.com/supernovae-st/nika/actions/workflows/e2e-smoke.yml/badge.svg)](https://github.com/supernovae-st/nika/actions/workflows/e2e-smoke.yml)
[![ecosystem coherence](https://github.com/supernovae-st/nika/actions/workflows/ecosystem-coherence.yml/badge.svg)](https://github.com/supernovae-st/nika/actions/workflows/ecosystem-coherence.yml)
[![scorecard](https://github.com/supernovae-st/nika/actions/workflows/scorecard.yml/badge.svg)](https://github.com/supernovae-st/nika/actions/workflows/scorecard.yml)
[![board](https://github.com/supernovae-st/nika-spec/actions/workflows/board.yml/badge.svg)](https://github.com/supernovae-st/nika-spec/actions/workflows/board.yml)

Red anywhere means a claim stopped proving, the shipped binary stopped working for a new user, a projection drifted between two buildings, or the board fell behind. Green is earned daily, never assumed.

---

## The other products

| | |
|---|---|
| 🔲 **[QR Code AI](https://qrcode-ai.com)** [![Live](https://img.shields.io/badge/-Live-10b981?style=flat-square)](https://qrcode-ai.com) [![X](https://img.shields.io/badge/-@QRCODEAI-000?style=flat-square&logo=x)](https://x.com/QRCODEAI) | Artistic QR codes people actually scan. SaaS in production, free tier and API, Nicolas at the helm. The Rust scanner is open source: [`qrcode-ai-scanner`](https://github.com/supernovae-st/qrcode-ai-scanner). |
| 🌈 **rain.bo** | Brewing: your link-in-bio, bento-grade, with the context on top. |

---

## How we think

- **Small crew, massive impact** · Nicolas and Thibaut, no headcount to scale: technology is the leverage.
- **Chart your own seas** · local-first and open by default: your data, your models, no vendor owns your course.
- **The flag is a butterfly** 🦋 · liberation through open source: AGPL engine, open spec, everything portable.

Quality creates adoption, not marketing. We stay small because constraints make better products. We open source our infrastructure because freedom matters more than control. If shipping better products means building the workflow engine underneath, we build it. That's [Nika](https://nika.sh).

---

<div align="center">

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ThibautMelen">
        <img src="https://github.com/ThibautMelen.png" width="100" style="border-radius:50%" alt="Thibaut"/>
      </a>
      <br />
      <b>Thibaut</b>
      <br />
      <sub>Co-founder, Engineering</sub>
      <br />
      <a href="https://github.com/ThibautMelen"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github" alt="GitHub"/></a>
      <a href="https://x.com/ThibautMelen"><img src="https://img.shields.io/badge/X-000?style=flat-square&logo=x" alt="X"/></a>
    </td>
    <td align="center">
      <a href="https://github.com/NicolasCELLA">
        <img src="https://github.com/NicolasCELLA.png" width="100" style="border-radius:50%" alt="Nicolas"/>
      </a>
      <br />
      <b>Nicolas</b>
      <br />
      <sub>Co-founder, Product</sub>
      <br />
      <a href="https://github.com/NicolasCELLA"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github" alt="GitHub"/></a>
      <a href="https://x.com/ncella_"><img src="https://img.shields.io/badge/X-000?style=flat-square&logo=x" alt="X"/></a>
    </td>
  </tr>
</table>

<br />

Paris · [supernovae.studio](https://supernovae.studio) · [nika.sh](https://nika.sh) · [docs.nika.sh](https://docs.nika.sh) · [qrcode-ai.com](https://qrcode-ai.com)

<sub>[Security policy](https://github.com/supernovae-st/.github/blob/main/SECURITY.md) · [Code of conduct](https://github.com/supernovae-st/.github/blob/main/CODE_OF_CONDUCT.md) · [Contributing to the engine](https://github.com/supernovae-st/nika/blob/main/CONTRIBUTING.md)</sub>

</div>
