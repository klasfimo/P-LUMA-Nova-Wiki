# Changelog

Downloads for every version are on the [releases page](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases).
The latest one is always on [Download](Download.md).

## Nova 1.4.5

[Release](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/tag/v1.4.5) · Minecraft 26.2 · 26.1–26.1.2 ·
1.21.11 · 1.21.10 · 1.21.8 · 1.21.7 · 1.21.6

**Interface**
- Flatter, cleaner look: tight corners on buttons, cards, inputs and switches instead of rounded pills;
  flat slider tracks and scrollbar
- HUD cards in the settings hub have a neutral border; an element's colour now shows only in its preview
- HUD element corners are now **sharp**, **soft** or **round** (soft by default). Existing layouts switch to
  soft once; pick another step in the element's settings

**Fixes**
- "Only tags you are looking at" now follows the camera, so name tags on screen no longer disappear in free
  look or the front third-person view. Its angle adapts to your FOV and window shape, so tags don't pop at
  the edge of wide screens
- A command macro no longer fires when the key or mouse button that closes a menu is also bound to it
- Settings are saved safely: a crash during a save can't leave a half-written file, and a broken file is kept
  as `.corrupt` instead of being replaced by defaults
- `NaN` or `Infinity` in a hand-edited `pluma-perf.json` falls back to the default value
- Unlimited chat history keeps up to 50,000 lines, so very long sessions can't use more and more memory
- Each jar suggests the Mod Menu version it was built for, and Mod Menu shows links to this wiki and its
  issues

## Nova 1.4.4

First public release.

**Versions**
- Builds for Minecraft 26.2, 26.1 (26.1–26.1.2), 1.21.11, 1.21.10, 1.21.8, 1.21.7 and 1.21.6

**HUD**
- Drag-and-drop HUD editor with 23 elements, edge snapping and anchored positions that hold at every
  resolution and GUI scale
- New elements: TPS, inventory
- The scoreboard and boss bar can be moved and scaled at their real size
- The potion effects element hides the vanilla effect icons while it is on

**Modules**
- Custom crosshair with live preview
- Block overlay, hitboxes, zoom, free look, full bright, view model
- Disable achievements
- Command macros, including mouse buttons
- Modules step aside automatically when another mod already provides the same feature

**Chat**
- Chat search from the chat input line
- Longer or unlimited chat history, kept when switching servers

**Performance**
- Lithium, FerriteCore and ImmediatelyFast bundled
- Distance limits for entities, block entities, sign text, dropped items and name tags
- Presets and an automatic FPS manager
- Mod compatibility page

**Menus**
- New title screen, pause menu and settings hub, smooth at any GUI scale
