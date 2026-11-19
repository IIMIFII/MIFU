# 🐾 MIFU

**Your pocket-sized programmable companion.**

*Code. Play. Care.*

MIFU is a programmable handheld gaming console and multifunctional tool with a built-in virtual pet.

Designed for creativity, experimentation, and entertainment, MIFU combines gaming, scripting, and a digital companion in one portable device.

## ✨ Features

- 🐾 **Virtual Pet** — Take care of your digital companion.
- 🎮 **Gaming Console** — Play games on your handheld device.
- 💻 **Custom Scripts** — Upload and run your own scripts.
- 🕹️ **Custom Games** — Create and load your own games.
- 🛠️ **Multitool** — Explore different tools and utilities.
- 🧩 **Programmable Platform** — Extend the device with your own creations.

## 🚀 About the Project

MIFU is more than just a gaming console.

It's a customizable pocket-sized device that combines a virtual pet, games, and programmable utilities.

The goal is to create a fun and flexible platform where users can develop their own experiences while interacting with their digital companion.

## 🎮 Games & Scripts

MIFU is designed to support user-created content.

Users can develop and upload their own games and scripts to expand the device's functionality.

More information about development and compatibility will be available as the project evolves.

## 🔧 Development

MIFU is an independently developed project created by **MIF**.

The project is under development. Features, specifications, and documentation may change.

## ⬇️ Firmware Updates

The device checks this repository on its own once it is on Wi-Fi: **Settings → ESP32 MODULE → ONLINE UPDATE**.

| File | What it is |
|---|---|
| `update.txt` | Update list read by the device: `KIND VERSION SIZE CRC32 FILE` |
| `FW_NEW.BIN` | Console firmware update |
| `MIF_FULL.BIN` | Console bootloader + firmware, first flash over USB DFU at `0x08000000` |
| `mif_esp.bin` | ESP32 module update |
| `mif_esp_full.bin` | ESP32 module full image, first flash over USB at `0x0` |

Online update needs console firmware 0.1.2+ and ESP32 module 1.1+. Older devices: update once from the SD card or the module's web page.

## 🔒 License & Copyright

**Copyright © 2026 MIF. All Rights Reserved.**

MIFU is proprietary software.

No permission is granted to use, copy, modify, distribute, sublicense, or commercially exploit the source code, in whole or in part, without prior written authorization from the copyright holder.

Unauthorized use, reproduction, modification, or redistribution of this project's source code is prohibited.

Public availability of the source code does not constitute permission to use it.

**User-created games and scripts:** This restriction applies to MIFU's proprietary source code and does not automatically impose ownership restrictions on independently created user content.

For licensing inquiries or permission requests, please contact the project author.

---

**Made by MIF 🐾**
