# cs2_gc
> [!CAUTION]
> This project is incomplete, Semi-Broken and VAC Bannable.
> Proceed with caution. Made for the Limited Test version of Counter-Strike 2.

## What is this?
In Valve games, the Game Coordinator (GC) is a backend service most notably responsible for matchmaking and inventory management (like loadouts and skins). This project redirects the GC traffic to a custom, in-process implementation.

## Why would you want this?
Uhh to see skins in game you know and feel rich like bling bling modafucka

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/38f168d5-eb1c-4157-b9aa-5f8ac356ff71" />

## This does include opening cases and Sticker Capsules thanks to Parker for his amazing mod <3
![20260325112454_1](https://github.com/user-attachments/assets/4038ff03-48fc-4e61-9895-41e778d5e4cf)

## Current features
- Editable inventory (inventory.txt)
- Item equipping
- Opening cases (including sticker capsules, patch packs, graffiti boxes and music kit boxes)
- Graffiti support
- Weapon StatTrak support
- Stickers and patches
- Name tags
- Music kits
- In-game store
- Works without full Steam API emulation
- Full Windows, Linux and macOS support
- Functional lobbies
- Dedicated server support
- Functional server browser (only shows csgo_gc servers by default)
- Networking using Steam's P2P interface

## Planned features
- Rest of the core features (trade ups, souvenirs, storage units, StatTrak swaps...)

I'm still looking for the **full** CS:GO (or cs2) Item Schema.

## Not planned
- Matchmaking (can't be implemented without a centralized server)

## Installation (WINDOWS)
- Download the depots below:
-
-
- Download the latest release for your platform from the [releases page](https://github.com/dricotec/cs2_gc/releases/latest)
- Navigate to the game's installation directory
- Extract the contents of the downloaded archive to your game directory @ game\bin\win64.
- Launch the game.

## Inventory editing
https://github.com/dricotec/csgo_gc_inventory-editor but if you want to do it manually [check my gist here :)](https://gist.github.com/dricotec/1ae3deb06c42012970c00df914348e76)

## Building
Requirements:
- Git
- CMake 3.20 or newer
- C++ compiler with C++17 support (VS 2017 or later, Clang 5 or later, GCC 7 or later)

INSTRUCTIONS SOON.

## License
This project is licensed under the 2-Clause BSD License. See [LICENSE.md](LICENSE.md) for details.

## Credits
* **Mikko Kokko** - Original Author
* **Theeto** - Code reused from the predecessor project, unusual loot lists
* **Drico** - Launcher for Counter-Strike 2 and Modifications to csgo_gc
* **Parker** - Modifications to the Counter-Strike 2 Panorama for opening cases, sticker capsules & more.

## Third party dependencies
- [Crypto++](https://github.com/weidai11/cryptopp) ([Boost Software License](https://github.com/weidai11/cryptopp/blob/master/License.txt))
- [funchook](https://github.com/kubo/funchook) ([GPL v2 with Classpath Exception](https://github.com/kubo/funchook/blob/master/LICENSE))
- [diStorm3](https://github.com/gdabah/distorm) ([3-Clause BSD License](https://github.com/gdabah/distorm/blob/master/COPYING))
- [protobuf](https://github.com/protocolbuffers/protobuf) ([3-Clause BSD License](https://github.com/protocolbuffers/protobuf/blob/main/LICENSE))
