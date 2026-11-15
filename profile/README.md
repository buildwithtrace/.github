<p align="center">
  <img src="./trace-logo.png" alt="Trace" width="160" height="160">
</p>

<h3 align="center">Describe the device you want. Trace designs the circuit board and the case, checks it, and helps you order it.</h3>

<p align="center">
  <a href="https://buildwithtrace.com/download"><img src="https://img.shields.io/badge/Download-Trace%20app-blue" alt="Download the Trace app"></a>
  <a href="https://docs.buildwithtrace.com"><img src="https://img.shields.io/badge/Docs-docs.buildwithtrace.com-green" alt="Documentation"></a>
  <a href="https://discord.gg/UNUvQxneCr"><img src="https://img.shields.io/badge/Discord-community-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
  <img src="https://img.shields.io/badge/Platforms-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey" alt="Platforms">
</p>

---

## What is Trace?

**Trace is an AI hardware design tool.** Describe the device you want in plain words, and Trace designs the circuit board (schematic, parts, layout and wiring) and a 3D-printable case for it, checks the design, and helps you order the board. You review and approve each step.

- **New to electronics?** The [Trace app](https://buildwithtrace.com/download) is for everyone, from complete beginners to professional engineers. Start with [How to design hardware with AI](https://buildwithtrace.com/design-hardware-with-ai) or [Design your first hardware](https://docs.buildwithtrace.com/guides/first-hardware/).
- **Already designing in Altium Designer, KiCad or Autodesk Fusion?** The [Trace Plugin](https://buildwithtrace.com/plugin) brings the same assistant into your design tool.
- **Working in a coding assistant?** `trace-cli` comes with the Trace app and includes an MCP server, so assistants such as Claude Code and Codex can use Trace. See [MCP](https://docs.buildwithtrace.com/resources/cli-mcp/).

## What Trace does

| | |
|---|---|
| **Describe it, Trace builds it** | In Flow, describe a board and watch Trace pick real parts, draw the schematic, lay out and route the board and check its own work, with live previews of the schematic, board and 3D view. |
| **Schematics and parts** | AI-drawn schematics; parts from Trace's catalog, or a new symbol, footprint and 3D model built from a datasheet and checked pad by pad. |
| **Layout and checks** | Free basic routing and an advanced placement and routing engine; ERC and DRC, including manufacturers' rule sets. |
| **Simulation** | Ask whether a circuit does what you want; Trace runs the simulation on your computer and answers in plain words. |
| **Enclosures** | Trace Mechanical designs a 3D-printable case around the real board and exports STL, 3MF and STEP. |
| **Manufacturing** | Gerber, drill, BOM and placement files, or send the board to PCBWay or Pikkolo Assembly from inside the Trace app. |

The Trace app runs on macOS (Apple silicon), Windows and Linux and is built on [KiCad](https://www.kicad.org), so your files stay standard. See [what's in each product](https://docs.buildwithtrace.com/resources/availability/).

## Can ChatGPT, Claude or Cursor design a PCB?

Not on their own. General AI assistants are great at explaining circuits and writing firmware, but they have no schematic editor, no parts library with footprints, no placement and routing engine and no design-rule checks. Trace is built for hardware design, and coding assistants can hand board work to it through `trace-cli mcp`. [Read the comparison](https://buildwithtrace.com/compare/ai-assistants).

## Public repositories

| Repository | What it is |
|---|---|
| [trace-public](https://github.com/buildwithtrace/trace-public) | Source code of the Trace app's GPL-licensed KiCad-based core |
| [trace-kicad-symbols-lib](https://github.com/buildwithtrace/trace-kicad-symbols-lib) | Schematic symbol library used by Trace (from KiCad's library) |
| [trace-kicad-footprints-lib](https://github.com/buildwithtrace/trace-kicad-footprints-lib) | PCB footprint library used by Trace (from KiCad's library) |
| [trace-kicad-3dmodels-lib](https://github.com/buildwithtrace/trace-kicad-3dmodels-lib) | 3D component models used by Trace (from KiCad's library) |
| [trace-kicad-templates-lib](https://github.com/buildwithtrace/trace-kicad-templates-lib) | Project and worksheet templates used by Trace (from KiCad's library) |

Browse parts online at [components.buildwithtrace.com](https://components.buildwithtrace.com), [symbols.buildwithtrace.com](https://symbols.buildwithtrace.com) and [footprints.buildwithtrace.com](https://footprints.buildwithtrace.com).

## Links

| | |
|---|---|
| Website | [buildwithtrace.com](https://buildwithtrace.com) |
| Download | [buildwithtrace.com/download](https://buildwithtrace.com/download) |
| Docs | [docs.buildwithtrace.com](https://docs.buildwithtrace.com) |
| Pricing | [buildwithtrace.com/pricing](https://buildwithtrace.com/pricing): free download and editors; the AI assistant uses a plan, credits or a 7-day trial |
| Students | [buildwithtrace.com/education](https://buildwithtrace.com/education) |
| Discord | [discord.gg/UNUvQxneCr](https://discord.gg/UNUvQxneCr) |
| Email | hello@buildwithtrace.com |

---

<p align="center">
  <sub>The Trace app is built on KiCad, an open-source EDA suite licensed under the GPL. Trace's AI modules are proprietary. © 2025–2026 WishEDA Inc.</sub>
</p>
