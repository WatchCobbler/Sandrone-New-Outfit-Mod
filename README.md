# Sandrone – New Outfit (Genshin Impact Skin Mod)

A custom outfit skin mod for **Sandrone** in *Genshin Impact*.
A black cropped zip-up track jacket with white side stripes, a pleated mini skirt, harness straps, a single thigh-high stocking with a thigh strap, and chunky buckled platform boots. The back of the jacket carries a **HIDOLATRAL** print.

![Character sheet](screenshots/preview_sheet.png)

| Front | Back |
|:---:|:---:|
| ![Front](screenshots/preview_front.png) | ![Back](screenshots/preview_back.png) |

---

## Features

- Brand-new outfit for Sandrone (replaces her default skin)
- Custom textures for the jacket, skirt, harness, stocking and boots
- Custom hair accessory (black ribbons and ornament)
- Installs in one click with the included installer (`.exe`)

## Requirements

- Windows 10 / 11 (64-bit)
- Genshin Impact (PC) installed
- A working mod loader setup (e.g. [GIMI / 3DMigoto](https://github.com/SilentNightSound/GI-Model-Importer)) – the installer will tell you if it is missing
- Sandrone unlocked on your account (she must be in your party for the skin to show)

## Installation (via EXE installer)

1. Go to the [**Releases**](../../releases) page and download the latest `Sandrone-New-Outfit-Installer.exe` (or the `.zip` that contains it).
2. **Close Genshin Impact** and your mod loader if they are running.
3. Run `Sandrone-New-Outfit-Installer.exe`.
   - If Windows SmartScreen shows a warning, click **More info → Run anyway**. (Unsigned indie installers trigger this.)
4. In the installer, select your **mod loader `Mods` folder** (for GIMI this is usually `...\GIMI\Mods`).
5. Click **Install** and wait for the *"Installation complete"* message.
6. Start your mod loader, then launch the game. Put Sandrone in your party – the new outfit should appear.

### Uninstall

Run the installer again and choose **Uninstall**, or manually delete the `Sandrone_NewOutfit` folder from your `Mods` directory.

## Troubleshooting

| Problem | Solution |
|---|---|
| Outfit doesn't appear | Make sure the mod loader is running **before** the game, and the mod is inside the loader's `Mods` folder. |
| Installer can't find the folder | Select the folder manually with the **Browse** button. |
| Textures look broken / purple | Re-install; make sure no other Sandrone mod is active at the same time. |
| Antivirus flags the `.exe` | This is a false positive for unsigned installers. You can inspect the source in this repo or install manually (see below). |
| Game crashes after a game update | Mods can break on new game versions. Check [Releases](../../releases) for an updated version. |

## Manual installation (without the installer)

1. Download the `.zip` from Releases.
2. Extract the `Sandrone_NewOutfit` folder into your mod loader's `Mods` folder.
3. Reload the mod loader (default hotkey **F10**) or restart the game.

## Repository structure

```
Sandrone-New-Outfit-Mod/
├── mod/                # Mod files (.ini, .buf, .dds textures, etc.)
├── installer/          # Installer source / notes (the built .exe goes to Releases)
├── screenshots/        # Preview images
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Disclaimer

- This is an **unofficial fan-made mod**. It is **not affiliated with, endorsed by, or connected to HoYoverse / miHoYo**.
- *Genshin Impact* and all related characters, names and assets are trademarks and property of **HoYoverse**.
- Using mods may violate the game's Terms of Service. **Use at your own risk** – the author is not responsible for any account action, bans, or damage.
- This mod is free. Do not sell it or put it behind a paywall.

## Credits

- Mod author: [**WatchCobbler**](https://github.com/WatchCobbler)
- Mod loader: GIMI / 3DMigoto authors
- Original character design: HoYoverse

## License

Original work in this repository (textures, edits, installer, docs) is released under the [MIT License](LICENSE) unless noted otherwise. Game assets remain the property of HoYoverse.
