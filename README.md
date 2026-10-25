# PvZ Fusion for Mac

Plants vs. Zombies Fusion (English translation) as a native app for Apple Silicon Macs.

[![Latest Release](https://img.shields.io/github/v/release/ganiyevuz/pvzf-macos-releases)](https://github.com/ganiyevuz/pvzf-macos-releases/releases/latest)

This repository only hosts the downloads. A new version is published here when the English translation releases one.

---

## Download

Get the latest `.dmg` from the **[Releases page](https://github.com/ganiyevuz/pvzf-macos-releases/releases/latest)**.

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

- **Frame rate:** the game runs at 60 fps. On a 120 Hz (ProMotion) display you can switch to 120 fps in **View → Frame Rate**; the choice is remembered.
- **Saves** are kept in `~/Library/Application Support/pvzf/pvzf-macos`, so updating the app keeps your progress. To update, drag the new version over the old one.
- **If macOS asks to reopen windows** after the game was closed unexpectedly, just dismiss it.

## Credits

- **PvZ Fusion** — the original Chinese fan-made game, by its authors. All game content and assets belong to them.
- **English translation** — [silvershadowkat/pvzf-android-translation](https://github.com/silvershadowkat/pvzf-android-translation). Each Mac release repackages that project's Android release.
- **ELF loader** — based on the Nintendo Switch port [ChanseyIsTheBest/pvz_fusion_en_nx](https://github.com/ChanseyIsTheBest/pvz_fusion_en_nx).

Plants vs. Zombies is a trademark of Electronic Arts. This is an unofficial fan project and is not affiliated with PopCap or EA.
