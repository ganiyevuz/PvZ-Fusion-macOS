# PvZ Fusion for Mac (macOS, Apple Silicon)

Play **Plants vs. Zombies Fusion** (PvZ Fusion, English translation) on your Mac. This is a native app for Apple Silicon Macs (M1, M2, M3, M4); it is not an emulator or a phone simulator.

[![Latest Release](https://img.shields.io/github/v/release/ganiyevuz/PvZ-Fusion-macOS)](https://github.com/ganiyevuz/PvZ-Fusion-macOS/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ganiyevuz/PvZ-Fusion-macOS/total)](https://github.com/ganiyevuz/PvZ-Fusion-macOS/releases)

This repository hosts the downloads. A new version is published here when the English translation releases one.

---

## Download

Get the latest `.dmg` from the **[Releases page](https://github.com/ganiyevuz/PvZ-Fusion-macOS/releases/latest)**.

## Installation

1. Open the DMG and drag **PvZ Fusion** into your Applications folder.
2. **First launch only:** open the app once (macOS will block it), then go to **System Settings → Privacy & Security** and click **Open Anyway**. Or run:

   ```bash
   xattr -dr com.apple.quarantine "/Applications/PvZ Fusion.app"
   ```

> The app is not signed with an Apple Developer account, so macOS blocks it until you allow it once. After that it opens normally.

## Requirements

- Apple Silicon Mac (M1, M2, M3, M4 or later)
- macOS 12 Monterey or later

Intel Macs are not supported.

## Good to know

- **Hotkeys:** the game's keyboard shortcuts work (listed on its Credits screen). On a Mac keyboard:
  - **F** toggles macOS full screen.
  - **Insert** (open save folder): press **fn + Return** (or keypad Enter), since Mac keyboards have no Insert key.
  - **Page Up** (online almanac): **fn + ↑**.
  - **F1 / F10**: hold **fn**, unless "Use F1, F2, etc. keys as standard function keys" is on in System Settings → Keyboard.
  - **Left Alt** is the **Option** key.
- **Frame rate:** the game runs at 60 fps. On a 120 Hz (ProMotion) display you can switch to 120 fps in **View → Frame Rate**; the choice is remembered.
- **Saves** are kept in `~/Library/Application Support/pvzf/pvzf-macos`, so updating the app keeps your progress. To update, drag the new version over the old one.
- **If macOS asks to reopen windows** after the game was closed unexpectedly, just dismiss it.

## Problems?

Open an [issue](https://github.com/ganiyevuz/PvZ-Fusion-macOS/issues) and include your macOS version and Mac model (for example "macOS 15.2, MacBook Air M2").

## Credits

- **macOS port** — Jakhongir Ganiev ([jakhongir.dev](https://jakhongir.dev), [@ganiyevuz](https://github.com/ganiyevuz)). The game's own Credits screen lists it too.
- **PvZ Fusion** — the original Chinese fan-made game, by its authors. All game content and assets belong to them.
- **English translation** — [silvershadowkat/pvzf-android-translation](https://github.com/silvershadowkat/pvzf-android-translation). Each Mac release repackages that project's Android release.
- **ELF loader** — based on the Nintendo Switch port [ChanseyIsTheBest/pvz_fusion_en_nx](https://github.com/ChanseyIsTheBest/pvz_fusion_en_nx).

## Sharing or modifying

You're welcome to share this app or build on the port. When you do, **credit Jakhongir Ganiev ([jakhongir.dev](https://jakhongir.dev)) and link to this repository**. The port is MIT-licensed, so its copyright notice and license (inside the app at `Contents/Resources/Licenses/LICENSE.txt`) must stay with any copy or modified version. The DMG also includes a `Credits.txt`.

PvZ Fusion's game files and assets are not covered by that license; they belong to their authors.

---

Plants vs. Zombies is a trademark of Electronic Arts. This is an unofficial fan project and is not affiliated with PopCap or EA.
