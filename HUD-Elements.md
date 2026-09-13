# HUD Elements

All elements can be moved, resized and styled in the [HUD Editor](HUD-Editor.md). The default state is the
one a fresh install starts with.

## Information

| Element | Shows | Default |
|---|---|---|
| Coordinates | X / Y / Z position and facing | On |
| Server | Server address, or Singleplayer | On |
| Compass | Facing direction with yaw angle | On |
| Biome | Name of the biome you're in | Off |
| Light level | Light level at your feet | Off |
| Speed | Horizontal movement speed | Off |
| In-game time | World clock and day number | Off |

## Performance

| Element | Shows | Default |
|---|---|---|
| FPS | Frames per second | On |
| Frame time | Frame time and 1% low | Off |
| Ping | Latency to the server | On |
| TPS | Server ticks per second; in singleplayer also milliseconds per tick | Off |
| Memory | Java heap in use | Off |
| Entity count | Entities loaded on the client | Off |

## Time

| Element | Shows | Default |
|---|---|---|
| Clock | Real-world time | On |
| Session time | Time since the game started | Off |

## Player

| Element | Shows | Default | Options |
|---|---|---|---|
| Potion effects | Active effects and time left | On | While on, vanilla's effect icons in the top right are hidden |
| Armor | Worn armor and durability | On | Show durability · Durability as percent · Include held item · Stack vertically |
| Held item | Durability of the item in your hand | Off | |
| Inventory | Your inventory on the HUD (3 × 9) | Off | Include hotbar · Slot backgrounds |

## PvP

| Element | Shows | Default | Options |
|---|---|---|---|
| Keystrokes | W A S D, mouse buttons and space, lit while pressed | On | Show CPS on mouse keys |
| CPS | Left and right clicks per second | On | |

## Vanilla

| Element | What P-LUMA does | Default |
|---|---|---|
| Scoreboard | Moves and scales the vanilla sidebar at its real size | On |
| Boss bar | Moves and scales the vanilla boss bars | On |

## Performance note

**Limit HUD refresh** on the [Performance](Performance.md) page makes elements recompute their data a set
number of times per second (5 to 240). They still draw every frame from their last value, so nothing
flickers.
