# Sky Beds

A 3D bed-defense game built with [three.js](https://threejs.org/). Guard your bed, bridge across the void, break every other bed and be the last team standing.

**Play:** open `index.html` in a browser, or turn on GitHub Pages for this repository.

## Controls

| Key | Action |
|---|---|
| WASD | Move |
| Space | Jump |
| Shift | Crouch (stops you falling off edges) |
| Click | Use what you hold: sword hits, blocks place, bow shoots |
| Right click | Place a block |
| E | Shop |
| C | Chest |
| 1-7 | Pick a hotbar slot |
| F | Eat a golden apple |
| L | Shift lock on/off |
| V | First / third person |

On a phone: drag the left side to move, drag the right side to look, and use the on-screen buttons.

## Features

- Four teams on floating islands, with iron, gold, diamond and emerald generators
- Item shop (wool, planks, end stone, swords up to emerald, armor up to emerald, bow and arrows, telepearls, golden apples) and team upgrades
- Bridging with a placement preview, team chests, and bots on Easy, Normal or Hard

## Play with friends

Press **Create room** and send your friends the 5-character code. They open the same page, type the code and press **Join**. Up to 4 players, one team each; the host presses **Start game**.

On GitHub Pages the game connects players browser-to-browser with [PeerJS](https://peerjs.com/) and its free public server, so there is nothing to host. The host's browser links everyone together, so if the host closes the game the room ends. Some school or work networks block these connections.
