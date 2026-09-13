# Modules

Modules are features that don't have a place on the HUD. Open **Settings → Modules**; each module has its
own page with an on/off switch, its options and **Reset module**.

| Module | Default |
|---|---|
| [Custom crosshair](#custom-crosshair) | Off |
| [Block overlay](#block-overlay) | Off |
| [Hitboxes](#hitboxes) | Off |
| [Zoom](#zoom) | On |
| [Free look](#free-look) | Off |
| [Full bright](#full-bright) | Off |
| [View model](#view-model) | Off |
| [Disable achievements](#disable-achievements) | Off |
| [Command macros](#command-macros) | On |

If another installed mod already provides zoom, free look or full bright, the matching P-LUMA module turns
itself off completely and its card shows which mod is in use. See [Mod Compatibility](Mod-Compatibility.md).

---

## Custom crosshair

Replaces the vanilla crosshair. The page shows a live preview on a dark and a light background.

| Option | Range | Default |
|---|---|---|
| Shape | Cross, Dot, Circle, X, Cross + dot | Cross |
| Length | 1 – 20 px | 5 px |
| Gap | 0 – 12 px | 2 px |
| Thickness | 0.5 – 6 px | 1 px |
| Colour | any | White |
| Opacity | 0.1 – 1 | 1 |
| Outline | on / off | On |
| Invert | on / off | Off |
| Dynamic | on / off | Off |

- **Outline** keeps the crosshair readable against bright ground.
- **Invert** inverts the colours behind it, like vanilla's crosshair. On 1.21.6 it draws in white.
- **Dynamic** opens the gap while you move.
- Vanilla's attack indicator still works, and the crosshair hides in the same situations vanilla's does
  (third person, spectator, debug crosshair).

## Block overlay

Replaces the outline around the block you're looking at.

| Option | Range | Default |
|---|---|---|
| Line colour | any | White |
| Line opacity | 0.1 – 1 | 0.8 |
| Width | 1x – 8x vanilla | 2x |
| Fill | on / off | Off |
| Fill colour | any | White |
| Fill opacity | 0.05 – 0.8 | 0.15 |

Width only has an effect on Minecraft 1.21.11 and newer.

## Hitboxes

Draws entity boxes independently from vanilla's F3 + B.

| Option | Range | Default |
|---|---|---|
| Targets | All, Players, Living | All |
| Colour | any | White |
| Target colour | any | Red |
| Opacity | 0.1 – 1 | 0.9 |
| Width | 1x – 6x | 1.5x |
| Look direction | on / off | On |
| Eye height | on / off | Off |
| Dropped items | on / off | Off |
| Distance | 8 – 128 blocks | 48 |

**Target colour** is used for the entity under your crosshair. Width only has an effect on 1.21.11 and
newer. Your own box is skipped in first person.

## Zoom

Hold **C** (changeable in Controls).

| Option | Range | Default |
|---|---|---|
| Magnification | 2x – 10x | 4x |
| Smooth | on / off | On |
| Scroll to adjust | on / off | On |
| Lower sensitivity | on / off | On |
| Cinematic camera | on / off | Off |
| Hide hand | on / off | On |

With **Scroll to adjust**, the mouse wheel changes magnification while zooming instead of switching hotbar
slots.

## Free look

Press **Left Alt** to orbit the camera around your character. Where you walk and aim doesn't change.

| Option | Values | Default |
|---|---|---|
| Mode | Hold, Toggle | Hold |
| View | Behind, In front | Behind |
| Invert vertical | on / off | Off |

Some servers don't allow free look. Check the rules before using it.

## Full bright

Toggle with **G**. A short message above the hotbar confirms the change.

| Option | Range | Default |
|---|---|---|
| Strength | 1 – 15 | 10 |

Your brightness setting is borrowed while full bright is on and handed back when it goes off, when you
leave the world, or the next time the game starts after a crash.

## View model

CS2-style first-person hand settings.

| Option | Range | Default |
|---|---|---|
| Horizontal | -1 – 1 | 0 |
| Height | -1 – 1 | 0 |
| Depth | -1 – 1 | 0 |
| Size | 0.1x – 2x | 1x |
| X rotation | -180° – 180° | 0° |
| Y rotation | -180° – 180° | 0° |
| Z rotation | -180° – 180° | 0° |
| Mirror left hand | on / off | On |

## Disable achievements

| Option | Default | Hides |
|---|---|---|
| Toast and sound | On | The advancement card in the top right and its sound |
| Your messages | On | Your own "has made the advancement" chat line |
| Others' messages | On | Other players' advancement chat lines |
| Recipe toasts | Off | "New recipes unlocked" cards |

## Command macros

Bind a key or mouse button to a command or a chat message.

1. Click **Add macro**
2. Click the key box, then press a key, or click the middle, right or a side mouse button
   (left click cancels, Esc unbinds)
3. Type the text. A line starting with `/` is sent as a command; anything else is sent as a chat message

Rules that keep macros from getting you kicked:

- Macros only fire in game, with no screen open
- Each macro sends at most once every half second, even if the key is held
- Up to 50 macros, 256 characters each
