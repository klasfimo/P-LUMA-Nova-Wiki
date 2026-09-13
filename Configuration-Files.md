# Configuration Files

Everything you change in the settings hub is saved automatically, a moment after the change, in your
game's `config` folder.

| File | Contents |
|---|---|
| `config/pluma-hud.json` | HUD layout (anchor and offset for each element), element styles and options |
| `config/pluma-perf.json` | Performance, chat and interface settings, automatic FPS manager |
| `config/pluma-modules.json` | Modules, their options and your command macros |

## Safe by design

The files are read carefully, so a hand edit or a damaged file can't break the game:

- Unknown elements, modules or options are ignored
- Every value is pushed back into its valid range
- If a file can't be read at all, P-LUMA starts with defaults instead of crashing
- When a file comes from an older P-LUMA version, the old copy is kept next to it as a `.bak`

## Borrowed vanilla settings

Full bright and the automatic FPS manager temporarily change vanilla options (brightness, and in
aggressive mode render distance, clouds and entity distance). Your original values are written to
`pluma-perf.json` before anything changes. They're restored when the feature turns off, when you leave the
world or close the game, and on the next start if the game crashed in between.

## Resetting

| To reset | Do this |
|---|---|
| One HUD element | Its settings page → Reset element |
| The whole HUD | HUD page → Reset every element |
| One module | Its page → Reset module |
| Everything | Close the game and delete the three `pluma-*.json` files |

## Sharing a layout

Copy `pluma-hud.json` to another installation's `config` folder. Positions are anchored to screen edges,
so the layout carries over between resolutions and GUI scales.
