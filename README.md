# keyer releases

Official macOS downloads and automatic updates for **Keyer**, the menu bar companion for the **Huion KeyDial Mini K20**.

[![Download Keyer for macOS](https://img.shields.io/badge/Download_for_macOS-007AFF?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AbdulazizBusbate/keyer-releases/releases/latest/download/Keyer-notarized.dmg)

**macOS 13 or later · Apple Silicon and Intel · Developer ID signed and Apple-notarized**

1. Open the downloaded DMG and drag **Keyer** onto **Applications**, following the arrow. Replace an older copy in its existing Applications folder. If the app is still installed under its old name, **KeyDial**, quit it and move it to the Trash.
2. Open the installed app and click its menu bar icon. Choose the Hammerspoon status, then **Connect Hammerspoon**. Follow any **Reload Config** or Accessibility instructions.
3. Press **Control + period (Ctrl + .)** to toggle the K20 layout. A keyboard key or mouse click dismisses it.

## Automatic updates

Install version 0.9.0 or later manually once. Earlier versions, released as KeyDial, do not update to Keyer on their own. Keyer then checks for updates every hour, downloads verified releases, and installs them when ready. **Check for Updates…** and **Automatically Update Keyer** are available in the menu. Installation or restart prompts may appear when needed.

Both the update feed and download require signatures. Future updater relaunches refresh an existing Hammerspoon connection. Shortcut settings and personal Hammerspoon configuration stay in place.

[Release history and checksums](https://github.com/AbdulazizBusbate/keyer-releases/releases) · [Signed update feed](https://github.com/AbdulazizBusbate/keyer-releases/releases/download/keyer-updates/appcast.xml)

This repository contains compiled downloads and update metadata. The application source is maintained privately.
