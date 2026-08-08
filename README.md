## Releases

[![PC Release](https://img.shields.io/badge/PC-v1.0-blue?logo=windows)](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_PC)
[![Android Release](https://img.shields.io/badge/Android-v1.0-green?logo=android)](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_Android)

# PokemonZMap
![Android](https://img.shields.io/badge/Android-13%2B-green?logo=android)
![AYN Thor](https://img.shields.io/badge/AYN%20Thor-Verified-success)
![PC](https://img.shields.io/badge/PC-Untested-orange?logo=windows)
![License](https://img.shields.io/badge/License-Proprietary-red)

PokemonZMap is a live companion map for **Pokémon Z** that tracks your current location while you play.

It displays the map image associated with your current area, tracks your position on that map, and automatically changes maps when you transition between areas.

---

### Android

The Android version is designed to function as a live map on the AYN Thor's bottom screen while Pokémon Z runs on the top screen.

On first launch, PokemonZMap asks you to select your main **Pokémon Z game folder**.

Once selected, the folder is saved and PokemonZMap will skip setup on future launches.

**Important:** The selected game folder cannot be changed from within the app. To select a different folder, PokemonZMap must be uninstalled and reinstalled.

#### Android Features

- Live player location tracking
- Automatically changes maps when transitioning between areas
- Displays the full current map
- Tracks your position directly on the map
- Automatically loads the selected Pokémon Z installation
- Remembers the selected game folder after initial setup
- Designed for the AYN Thor bottom display
- No internet connection required

---

### PC

**Status:** Untested.

The PC release is the original web-based version of PokemonZMap.

Unlike the Android version, the PC version uses a web-based map viewer.

The tracker reads the Pokémon Z game state and generates the information required for the live map display.

---

## How It Works

PokemonZMap does not contain or distribute Pokémon Z maps.

Instead, it references compatible map image files that already exist inside the user's own Pokémon Z installation.

The tracker determines:

- Current map
- Player X position
- Player Y position

PokemonZMap then displays the corresponding map image and places the player's location marker at the appropriate position.

When the player transitions to another area, PokemonZMap automatically loads the corresponding map.

---

## Android Setup

1. Install the PokemonZMap APK.
2. Launch PokemonZMap.
3. Select your main Pokémon Z game folder when prompted.
4. Confirm the folder selection.
5. Launch Pokémon Z.
6. PokemonZMap will load the current map and track your position.

After initial setup, PokemonZMap remembers the selected folder and opens directly to the map on future launches.

### Folder Selection Warning

Your selected Pokémon Z folder is treated as permanent.

There is no change-folder option inside PokemonZMap.

If you need to use a different Pokémon Z installation later:

1. Uninstall PokemonZMap.
2. Reinstall the APK.
3. Select the new Pokémon Z folder during setup.

---

## Android Tracker

Unlike its web-based PC counterpart, the Android tracker only writes:

`ZMapTracker.txt`

It does not create `ThorMap.html` or Base64-encode map images.

The Android application reads the required information directly and loads the appropriate map image from the selected Pokémon Z installation.

---

## Compatibility

| Platform | Status |
|---|---|
| AYN Thor - Android 13 | Verified |
| Other Android Devices | Not Yet Verified |
| PC | Untested |

PokemonZMap may work on additional Android devices, but the AYN Thor is currently the verified target device.

---

## Privacy / Network Access

PokemonZMap operates locally.

- No account required
- No internet connection required
- No map images are downloaded
- Pokémon Z map assets are read from the user's existing game installation

---

## Pokémon Z Assets

PokemonZMap does **not** include, distribute, or claim ownership of Pokémon Z map images or other Pokémon Z game assets.

PokemonZMap functions as a companion application that references and displays compatible image files already present in the user's own game installation.

These files remain separate from PokemonZMap and are not distributed as part of this repository or its releases.

---

## License

PokemonZMap is proprietary software.

Official compiled releases may be downloaded and used for personal, non-commercial use.

The PokemonZMap source code, scripts, documentation, branding, and other original materials may not be copied, modified, redistributed, reverse engineered, sold, sublicensed, or used to create unofficial versions except where restrictions are prohibited by applicable law.

See [LICENSE](LICENSE) for the complete license terms.

---

## Downloads

### Android

[Download PokemonZMap Android v1.0](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_Android)

### PC

[Download PokemonZMap PC v1.0](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_PC)

---

## Repository

**ChimeraGaming / Pokemon-Z_Live_Map**

PokemonZMap is developed and maintained by **ChimeraGaming**.
