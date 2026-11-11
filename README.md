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

## Game modes

| Mode | What's different |
|---|---|
| Classic | The full game. Build up, then break their beds. |
| Rush | Start with a stone sword and 64 wool, generators run twice as fast, beds break at 5:00. |
| Lucky Blocks | Yellow ? blocks keep appearing on the middle islands. Break one for loot, or a nasty surprise. |
| Duos | Two players per team. Team up with a friend, or a bot fights beside you. |
| One Life | No beds. Everyone starts geared up, and your first death is your last. |

When you host a room, your friends play the mode you pick. Everyone picks a team color in the lobby, and the host can fill empty spots with bots.

## Kits

Win a match (finish first) to earn **bedcoins**, then pick a kit from the menu. Most kits rent for 50 bedcoins (30 days) or are yours forever for 100. TNT Bomber and Grappler cost 75 to rent and 150 to own.

| Kit | What it does |
|---|---|
| Bounty Hunter | Every kill pays 3 gold. Every final kill pays 2 emeralds. |
| Gingerbread Man | Runs faster and sprints away when low. Can buy Gumdrop Bounce Pads (2 emeralds) that launch anyone 10 blocks up. |
| Electra | Right-click (or R) to lightning-dash 5 blocks, zapping enemies in the way. 2 dashes, each recharges in 10 s. |
| TNT Bomber | A portable cannon that fires TNT. Starts the match with 10 TNT; buy more TNT to reload. Keeps the cannon after dying, but not the TNT. |
| Farmer | Throw eggs that hatch baby chickens. They grow up, follow you and peck nearby enemies (up to 4). Buy more eggs in the shop. |
| Ice Mage | Right-click (or R) for Frost Nova: enemies within 6 blocks take 1 heart and are slowed for 4 s. Recharges in 15 s. Can buy Ice Bombs (3 gold) that slow everyone they hit. |
| Shadow Ninja | Double jump: press jump again in the air. Starts every life with 4 throwing stars; buy more in the shop (4 for 2 gold). |
| Grappler | Right-click (or R) to fire a grappling hook. Hook a block to zip to it, or hook an enemy to yank them to you. Recharges in 5 s. Can buy Bridge Orbs (2 gold) that lay a wool path as they fly. |
| Archer | Starts every life with a bow and 8 arrows. Arrows do +1 damage. |
| Builder | Starts every life with 32 wool and places blocks faster. |
| Medic | Heals twice as fast when out of a fight. |
| Miner | Gets 50% more iron and gold from generators. |
| Pyro | Starts every life with a fireball. |

## Play with friends

Press **Create room** and send your friends the 5-character code. They open the same page, type the code and press **Join**. Up to 4 players, one team each; the host presses **Start game**.

On GitHub Pages the game connects players browser-to-browser with [PeerJS](https://peerjs.com/) and its free public server, so there is nothing to host. The host's browser links everyone together, so if the host closes the game the room ends. Some school or work networks block these connections.
