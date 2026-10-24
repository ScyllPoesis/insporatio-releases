# Insporatio for Windows

Insporatio is a local desktop app for artist inspiration. Choose an image folder,
view a random image, reroll for another, copy an image, or reveal its file in
Explorer. Your images stay on your computer.

This repository hosts Windows downloads and release notes.

## Downloads

[Browse releases](https://github.com/ScyllPoesis/insporatio-releases/releases).
Windows 10/11 x64 is the supported target. You do not need Node.js or a separate
server.

The first download is an **experimental, unsigned preview** for testing delivery.
No stable release is available yet. Signing and clean Windows 10/11 installation
checks are still pending. Windows may warn about or block this unsigned download;
if you are unsure, wait for a signed release.

For a preview, open its prerelease page and read the limitations before downloading
`Insporatio-<version>-Setup-x64.exe`. A `.sha256` file accompanies the installer
to check that your download matches the published file.

## Installation

Run Setup to install for your Windows account, then open Insporatio from the Start
menu. Choose an image folder on first launch; use the folder button to change it.
For manual upgrades, close Insporatio and run the new installer. Settings and image
collections are designed to be retained, including when uninstalling the app.

The preview has automatic update networking disabled. Future signed releases will
offer update checks, downloads, and an explicit restart to install.
