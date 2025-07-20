<div align="center">

![banner](./images/banner.jpg)

</div>

A guide on how to **install mods** on **Cyberpunk 2077** for PC.

Modding Cyberpunk is now easier than ever thanks to community tools and updated file structures! Whether you're adding a new outfit, gameplay overhaul, or visual mod, this guide will walk you through the process step-by-step.

This guide is focused on the **Windows** version of Cyberpunk 2077 via **Steam**, **GOG**, or **Epic Games**.

## Table of Contents
- [Requirements](#requirements)
- [Backup Your Save Files!](#backup-your-save-files)
- [Where To Find Cyberpunk Mods](#where-to-find-cyberpunk-mods)
- [Know Your Game Version and Platform](#know-your-game-version-and-platform)
- [Essential Tools For Modding Cyberpunk](#essential-tools-for-modding-cyberpunk)
    - [Cyber Engine Tweaks (CET)](#cyber-engine-tweaks-cet)
    - [REDmod](#redmod)
- [Installing Mods](#installing-mods)
    - [Manual (Drag & Drop)](#manual-drag--drop)
    - [REDmod (Mod Manager)](#redmod-mod-manager)
- [Testing Mods](#testing-mods)
- [Uninstalling Mods](#uninstalling-mods)
- [Notes](#notes)
    - [Mod Conflict Management](#mod-conflict-management)
- [Conclusion](#conclusion)
- [See Also](#see-also)

## Requirements
- Cyberpunk installed on your PC.
- [7-Zip](https://www.7-zip.org/) or any archive extraction software.
- A basic understanding of copying/moving files on Windows.
- An internet connection.

## Backup Your Save Files!
It is recommended you backup your game's save files before installing mods.

Here is the most common folder for saved games.

```
C:\Users\<username>\Saved Games\CD Projekt Red\Cyberpunk 2077
```

## Where To Find Cyberpunk Mods
Here are some popular websites where you can browse and download mods.

- [Nexus Mods (Cyberpunk)](https://www.nexusmods.com/cyberpunk2077/)
- [Cyberpunk Modding Discord](https://discord.com/invite/redmodding)

**NOTE** - It is recommended you read the mod description to see if it requires other mods or frameworks (like Cyber Engine Tweaks or REDmod).

## Know Your Game Version and Platform
Mods are generally compatible with the latest Cyberpunk version, but some may require specific patches or tools.

| Platform | Moddable | Notes |
|----------|----------| ----- |
| **Steam** | Yes |Fully moddable |
| **GOG** | Yes | Fully moddable |
| **Epic Games** | Yes | File paths may differ slightly |
| **Console (PS/Xbox)** | No | Modding is generally **not supported** |

## Essential Tools For Modding Cyberpunk
Some mods require additional frameworks to function.

### Cyber Engine Tweaks (CET)
- Adds scripting support and debugging tools.
- Download from [here](https://www.nexusmods.com/cyberpunk2077/mods/107).
- Install instructions.
  - Extract contents of file into your `Cyberpunk 2077\bin\x64` directory.
  - Launch the game once and press `~` to bring up the CET console.

### REDmod
- Official modding tool by CDPR.
- Needed for mods using `.archive`, `.redmod`, or script changes.
- Download via Steam/GOG or from [here](https://www.cyberpunk.net/en/modding-support).

## Installing Mods
Cyberpunk supports two main installation paths detailed below.

### Manual (Drag & Drop)
1. Download the mod `.zip` or `.rar` file.
2. Open your game directory:
   - Steam: `C:\Program Files (x86)\Steam\steamapps\common\Cyberpunk 2077`
   - GOG: `C:\GOG Games\Cyberpunk 2077`
3. Extract the mod into the following folder(s) using a tool such as [7-Zip](https://www.7-zip.org/).
   - For **standard mods**: `Cyberpunk 2077\archive\pc\mod\`
   - For **scripts/configs**: `Cyberpunk 2077\bin\x64\plugins\cyber_engine_tweaks\mods\`

**NOTE** - Create any folders that don't exist (e.g. `mod`) manually.

### REDmod (Mod Manager)
If a mod supports REDmod, you can easily install it using the mod manager.

Here are steps to do this.

1. Place the mod's folder inside the folder `Cyberpunk 2077\mods\`.
2. Use the REDmod launcher or start the game via the `REDprelauncher.exe` command.
3. Mods will load automatically if enabled in the launcher.

## Testing Mods
After downloading and installing mods, you can test them by performing the following steps.

1. Launch the game through Steam, GOG Galaxy, or by using the `REDprelauncher.exe` file.
2. If using **Cyber Engine Tweaks**, press `~` key to see if the mods loaded.
3. Mods like visual changes, clothing, or UI tweaks should appear immediately.

**NOTE** - If your game crashes or freezes, remove recently added mod(s) and check compatibility.

## Uninstalling Mods
If you'd like to remove a mod after installing it, perform the following steps.

- Delete the mod's folders and files from the `archive\pc\mod` or `bin\x64\plugins` folders.
- For REDmod mods, delete the folder inside the `Cyberpunk 2077\mods\` folder.

## Notes
### Mod Conflict Management
Conflicts can happen, especially with multiple texture or gameplay mods.

We recommend using [Cyberpunk 2077 Mod Manager (CP77 Tools)](https://www.nexusmods.com/cyberpunk2077/mods/96) to address any conflicts.

Additionally, here are some tips on preventing conflicts.
- Sort mods and check for overlapping `.archive` files.
- Only install one mod per category (e.g., don't install two UI overhauls).

## Conclusion
By now you should have a basic understanding on installing mods in Cyberpunk 2077.

With thousands of mods available, you can turn Night City into anything from a cyber-noir RPG to a neon sandbox with flying cars, new weapons, and full UI overhauls!

## See Also
- [Cyberpunk 2077 Mod Manager (CP77 Tools)](https://www.nexusmods.com/cyberpunk2077/mods/96)
- [REDmod](https://www.cyberpunk.net/en/modding-support)
- [Nexus Mods](https://www.nexusmods.com/)

This guide is a *work-in-progress* and will be improved on over time. If you have any feedback on how to improve the guide, please feel free to reach out!

Happy modding!