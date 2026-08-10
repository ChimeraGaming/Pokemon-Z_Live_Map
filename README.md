## Releases

[![PC Release](https://img.shields.io/badge/PC-v1.0-blue?logo=windows)](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_PC)

# PokemonZMap
![Android](https://img.shields.io/badge/Android-13%2B-green?logo=android)
![AYN Thor](https://img.shields.io/badge/AYN%20Thor-Verified-success)
![PC](https://img.shields.io/badge/PC-Untested-orange?logo=windows)
![License](https://img.shields.io/badge/License-Proprietary-red)


# PokemonZMap

PokemonZMap is a live companion map for **Pokémon Z** that tracks your current location while you play.

It displays the map image associated with your current area, tracks your position on that map, and automatically changes maps when you transition between areas.

[![Watch Demo](https://img.shields.io/badge/YouTube-Watch%20Demo-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=OsCFVb43y34)

---

## Android

Moved to https://github.com/ChimeraGaming/FanmakePokemonMaps_Android

---

## PC

**Status:** Untested.

The PC release is the original web-based version of PokemonZMap.

Unlike the Android version, it uses a web-based map viewer. The tracker reads the Pokémon Z game state and generates the information required for the live map display.

---

## How It Works

The tracker records:

- Current map
- Player X position
- Player Y position

The Android tracker writes this information to `ZMapTracker.txt`.

PokemonZMap reads the tracker file, displays the corresponding map, and places the player's location marker at the appropriate position.

As you move or transition between areas, the tracker updates the information and PokemonZMap automatically updates the live map.

Unlike the web-based PC tracker, the Android tracker does not create `ThorMap.html` or Base64-encode map images.

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
- No internet connection required for live tracking
- No player location data is uploaded
- Live tracking information is read locally from `ZMapTracker.txt`

---

## Pokémon Z Assets

PokemonZMap is an unofficial companion application for Pokémon Z.

PokemonZMap does not claim ownership of Pokémon Z map images, artwork, or other Pokémon Z game assets.

Pokémon and related properties belong to their respective owners.

PokemonZMap and ChimeraGaming are not affiliated with or endorsed by the Pokémon Z developers, Nintendo, Game Freak, Creatures Inc., or The Pokémon Company.

---

## License

PokemonZMap is proprietary software.

Official compiled releases may be downloaded and used for personal, non-commercial use.

The PokemonZMap source code, scripts, documentation, branding, and other original materials may not be copied, modified, redistributed, reverse engineered, sold, sublicensed, or used to create unofficial versions except where restrictions are prohibited by applicable law.

See [LICENSE](LICENSE) for the complete license terms.

---

## Downloads

### Android

[Download PokemonZMap Android v1.1](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.1_Android)

### PC

[Download PokemonZMap PC v1.0](https://github.com/ChimeraGaming/Pokemon-Z_Live_Map/releases/tag/v.1.0_PC)
