<picture>
  <source media="(prefers-color-scheme: dark)" srcset="Resources/Icons/Snoopy Exports/Snoopy-macOS-Default-1024@1x.png">
  <source media="(prefers-color-scheme: light)" srcset="Resources/Icons/Snoopy Exports/Snoopy-macOS-Dark-1024@1x.png">
  <img alt="Snoopy Icon" src="Resources/Icons/Snoopy Exports/Snoopy-macOS-Default-1024@1x.png" width="100">
</picture>

# Snoopy

![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Compute](https://img.shields.io/badge/Compute-Raspberry%20Pi%20CM4-c51a4a?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

**A 3-port Ethernet switch with a built-in monitoring layer, powered by a Raspberry Pi CM4. Sits between your ISP's router and your devices, giving you real visibility and control over your home network — something most stock router software simply doesn't offer**

EasyEDA: [Snoopy](https://easyeda.com/editor#project_id=7b067378073640e4a270a95197bfada5)

---

**Navigate:** [Schematics](./Schematics/README.md) · [PCB](./PCB/README.md) · [Enclosure](./Enclosure/README.md) · [BOM](./BOM.md) · [Resources](./Resources/README.md)

---

## Overview

Snoopy is a custom PCB that combines a 3-port Gigabit Ethernet switch (Realtek RTL8367S) with a Raspberry Pi CM4 as the system brain. The idea is simple: your ISP's router is a locked-down box, and there's only so much you can do with its stock software. Snoopy plugs into that setup and hands control back to you — packet inspection, traffic monitoring, custom routing rules, whatever you want to run on the CM4

The board handles its own power management, runs the CM4 over a high-density board-to-board connector, and exposes two RJ45 MagJack ports for the switch-side connections. Designed in EasyEDA

For component details, see the [BOM](./BOM.md). For schematics, head to [Schematics](./Schematics/README.md)

![PCB](./PCB/Screenshot%202026-07-09%20at%207.16.14%E2%80%AFPM.png)

---

## Progress

| Module | Status | Schematic |
|---|---|---|
| PWR Management | ![Complete](https://img.shields.io/badge/Schematic-Complete-brightgreen?style=flat-square) | [View](./Schematics/PWR%20Management/README.md) |
| Ethernet Connections | ![Complete](https://img.shields.io/badge/Schematic-Complete-brightgreen?style=flat-square) | [View](./Schematics/Ethernet%20Connections/README.md) |
| CM4 Connections | ![Complete](https://img.shields.io/badge/Schematic-Complete-brightgreen?style=flat-square) | [View](./Schematics/CM4%20Connections/README.md) |
| PCB Layout & Routing | ![Complete](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square) | [View](./PCB/README.md) |
| Enclosure | ![Complete](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square) | [View](./Enclosure/README.md) |

---

## License

MIT — see [LICENSE](./LICENSE)

---

<img src="https://assets.hackclub.com/flag-standalone.svg" alt="Hack Club" width="48"> &nbsp; A [Hack Club](https://hackclub.com) project, built for [Macondo](https://github.com/hackclub/macondo).
