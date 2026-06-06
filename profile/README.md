<p align="center">
  <img src="./trace-logo.png" alt="Trace" width="160" height="160">
</p>

<h3 align="center">The fastest path from idea to manufactured PCB.</h3>

<p align="center">
  <a href="https://discord.gg/UNUvQxneCr"><img src="https://img.shields.io/discord/1234567890?color=5865F2&label=Discord&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://buildwithtrace.com/download"><img src="https://img.shields.io/badge/Download-v1.4.0-blue?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiPjxwYXRoIGQ9Ik0yMSAxNXY0YTIgMiAwIDAgMS0yIDJINWEyIDIgMCAwIDEtMi0ydi00Ii8+PHBvbHlsaW5lIHBvaW50cz0iNyAxMCAxMiAxNSAxNyAxMCIvPjxsaW5lIHgxPSIxMiIgeTE9IjE1IiB4Mj0iMTIiIHkyPSIzIi8+PC9zdmc+" alt="Download"></a>
  <a href="https://docs.buildwithtrace.com"><img src="https://img.shields.io/badge/Docs-docs.buildwithtrace.com-green" alt="Documentation"></a>
  <a href="https://status.buildwithtrace.com"><img src="https://img.shields.io/badge/Status-Operational-brightgreen" alt="Status"></a>
  <img src="https://img.shields.io/badge/Platforms-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey" alt="Platforms">
</p>

---

## About Trace

**Trace** is an AI-native PCB design tool — a desktop application for macOS, Windows, and Linux that covers the full schematic-first workflow: **idea → schematic → PCB → manufacturing files**. Built on [KiCad](https://www.kicad.org) (GPL), enhanced with proprietary AI modules that accelerate every stage of hardware design.

Current version: **1.4.0**

## Key Features

| Category | Capabilities |
|----------|-------------|
| **AI Design** | Natural-language schematic generation, AI-powered suggestions, Plan mode (research → questions → plan → approve → execute) |
| **Routing** | Quick auto-route (freerouting) + Advanced layout (DeepPCB cloud engine), Matched length tuning for high-speed signals |
| **Components** | Nexar/DigiKey distributor search, datasheet parsing (LlamaParse), 30K+ symbols & 24K+ footprints |
| **Verification** | ERC/DRC with AI suggestions, hierarchical schematic support (multi-sheet) |
| **Manufacturing** | Gerber/drill/BOM/pick-and-place export, PCB ordering (PCBWay + Pikkolo partners) |
| **Collaboration** | Version control (local + cloud), team workspaces with per-seat billing |
| **Flexibility** | BYOK — bring your own Anthropic, OpenAI, or Gemini API key |

## Ecosystem

### Core Product

| Repo | Description |
|------|-------------|
| **[Trace Desktop](https://github.com/buildwithtrace/trace)** | AI-powered PCB design tool (C++/wxWidgets + React webview) |
| **[Trace CLI](https://github.com/buildwithtrace/cli)** | Terminal interface + MCP server for AI coding agents — `pip install buildwithtrace` |
| **[Documentation](https://docs.buildwithtrace.com)** | Guides, API reference, tutorials |

### Component Platforms

| Platform | Description |
|----------|-------------|
| **[symbols.buildwithtrace.com](https://symbols.buildwithtrace.com)** | 30,000+ browseable schematic symbols (KiCad + CERN) |
| **[footprints.buildwithtrace.com](https://footprints.buildwithtrace.com)** | 24,000+ PCB footprints catalog |
| **[components.buildwithtrace.com](https://components.buildwithtrace.com)** | Unified symbol + footprint catalog with AI generation |

### Libraries

| Repo | Content |
|------|---------|
| [trace-kicad-symbols-lib](https://github.com/buildwithtrace/trace-kicad-symbols-lib) | Canonical schematic symbol library |
| [trace-kicad-footprints-lib](https://github.com/buildwithtrace/trace-kicad-footprints-lib) | Canonical PCB footprint library |
| [trace-kicad-3dmodels-lib](https://github.com/buildwithtrace/trace-kicad-3dmodels-lib) | 3D component models |

### Build & Packaging (Public)

| Repo | Platform |
|------|----------|
| [trace-mac-builder](https://github.com/buildwithtrace/trace-mac-builder) | macOS `.dmg` packaging & CI |
| [trace-win-builder](https://github.com/buildwithtrace/trace-win-builder) | Windows NSIS installer & CI |
| [trace-linux-builder](https://github.com/buildwithtrace/trace-linux-builder) | Linux AppImage packaging & CI |

## Get Started

```bash
# Install the CLI
pip install buildwithtrace

# Or download the desktop app
# → https://buildwithtrace.com/download
```

## Links

| | |
|---|---|
| 🌐 Website | [buildwithtrace.com](https://buildwithtrace.com) |
| 📖 Docs | [docs.buildwithtrace.com](https://docs.buildwithtrace.com) |
| ⬇️ Download | [buildwithtrace.com/download](https://buildwithtrace.com/download) |
| 💬 Discord | [discord.gg/UNUvQxneCr](https://discord.gg/UNUvQxneCr) |
| 📊 Status | [status.buildwithtrace.com](https://status.buildwithtrace.com) |

## Contributing

We welcome contributions to our open-source libraries and build tooling. See our [Contributing Guide](https://docs.buildwithtrace.com/contributing) for details.

---

<p align="center">
  <sub>Trace is built on KiCad, an open-source EDA suite licensed under GPL.<br>Proprietary AI modules © 2024–2026 Trace.</sub>
</p>
