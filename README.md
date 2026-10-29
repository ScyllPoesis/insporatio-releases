# Insporatio for Windows

Insporatio is a local desktop app for artist inspiration. Choose an image folder,
view a random image, reroll for another, copy an image, or reveal its file in
Explorer. Your images stay on your computer.

This repository hosts Windows downloads and release notes.

## Downloads

[Download Insporatio 0.11.0](https://github.com/ScyllPoesis/insporatio-releases/releases/tag/v0.11.0)
or [browse releases](https://github.com/ScyllPoesis/insporatio-releases/releases).
Windows 10/11 x64 is the supported target. You do not need Node.js or a separate
server.

Version 0.11.0 is **unsigned** and supports updates inside the app without a paid
signing certificate. Windows may warn about or block an unsigned download.
Automated application and packaging checks passed, but clean Windows 10/11
install, upgrade, and uninstall testing is still pending. Read the release notes
before installing.

Open the release page and download
`Insporatio-<version>-Setup-x64.exe`. A `.sha256` file accompanies the installer
to check that your download matches the published file.

## Installation

Run Setup to install for your Windows account, then open Insporatio from the Start
menu. Choose an image folder on first launch; use the folder button to change it.
For manual upgrades, close Insporatio and run the new installer. Settings and image
collections are designed to be retained, including when uninstalling the app.

Version 0.11.0 checks the public GitHub release feed when opened. About and updates
offers Download update and Restart and install when a newer version is available.
Downloads and restarts require your action; normal quit never installs an update.
Unsigned updates use HTTPS and download checksums, without publisher signature
verification. Their trust depends on control of this GitHub repository.

The older 0.10.0 preview has updates disabled. Close it and run the 0.11.0 installer
once to move onto the update-enabled version. Later higher versions can then be
offered inside the app.
