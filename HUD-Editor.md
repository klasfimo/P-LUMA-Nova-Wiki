# HUD Editor

Press **Right Shift** in game, or use **Move HUD** in the settings hub.

## Moving and resizing

- **Drag** an element to move it. It snaps to the screen edges and to the horizontal and vertical centre
  lines.
- **Drag the handle** in the bottom-right corner of the selected element to resize it between 0.5x and 3x.
- **Arrow keys** nudge the selected element by 1 px, **Shift + arrow keys** by 10 px.
- **Right click** turns an element on or off without leaving the editor.
- **Esc** saves and closes.

## Anchoring

Every position is stored relative to the nearest edge or the centre of the screen. This is why a layout
looks the same at any resolution or GUI scale.

It also decides how an element grows when you resize it. An element pushed against the right edge grows
to the left, one at the bottom grows upwards, one in the centre grows evenly. The scoreboard, for example,
stays flush with the right side of the screen at every size.

## Disabled elements

Elements that are turned off, or that have nothing to show right now (for example potion effects when
you have none), appear in the editor as a named card so you can still find and place them. **Show
disabled** hides those cards if the screen gets busy.

## Element settings

The gear on a selected element, or its card on the HUD page of the settings hub, opens its settings page
with a live preview.

| Setting | What it does |
|---|---|
| Enabled | Shows or hides the element |
| Scale | Size, 0.5x to 3x |
| Opacity | How see-through the element is |
| Colour | Accent colour of the element's values; "follow accent" uses P-LUMA's purple |
| Background | Panel behind the element |
| Corner | Panel corners: sharp, soft (default) or round |
| Panel shadow | Soft shadow under the panel |
| Text effect | None, shadow or outline, to separate text from the world |
| Element options | Extra switches for some elements, see [HUD Elements](HUD-Elements.md) |
| Reset element | Back to its default position and style |

**Reset every element** on the HUD page restores the whole default layout.

## Vanilla elements

The **scoreboard** and **boss bar** entries control the real vanilla elements. P-LUMA only moves and
scales them; what they display is up to the game and the server. Turning them off hides them.
