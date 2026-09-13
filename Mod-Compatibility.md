# Mod Compatibility

P-LUMA is built to sit next to other mods rather than fight them:

- It never touches terrain rendering
- It only adds hooks. It never replaces a vanilla method outright, so other mods patching the same code
  keep working
- When another mod already does the same job as a P-LUMA feature, P-LUMA's version turns itself off

The **Mod compatibility** section at the bottom of the Performance page lists what's installed, what's
bundled and what's recommended, with versions and links.

## Automatic hand-off

| P-LUMA feature | Turns off when one of these is installed |
|---|---|
| Zoom | Zoomify, Ok Zoomer, Logical Zoom, WI Zoom |
| Free look | Freelook, Perspective / Perspective Mod |
| Full bright | Fullbright, Fullbrightness, Gamma Utils, Brightness Slider |
| Chat history | MoreChatHistory, Chat Patches, No Chat Reset, Don't Clear Chat History |

When this happens:

- P-LUMA doesn't register a key for the feature, so there are no key conflicts
- Its hooks into the game for that feature aren't applied
- The module card shows which mod is in use
- Your P-LUMA settings for it stay in the config file, ready if you remove the other mod

## Performance mods

| Mod | Status |
|---|---|
| Lithium | Bundled |
| FerriteCore | Bundled |
| ImmediatelyFast | Bundled |
| Sodium | Recommended, works together |
| Iris | Recommended for shaders, works together |
| Entity Culling | Recommended, works together |
| More Culling | Recommended, works together |
| Dynamic FPS | Recommended, works together |

Sodium and Iris can't be bundled because of their licences, and Dynamic FPS contains a native library
that doesn't load when nested, so these need a separate install.

## HUD mods

Other HUD or minimap mods work, but may draw in the same corners. Move P-LUMA's elements in the
[HUD Editor](HUD-Editor.md), or turn the overlapping ones off.

## Reporting a conflict

If P-LUMA crashes or misbehaves with another mod, open an issue with:

- Minecraft version and P-LUMA jar name
- The list of mods (or the modpack)
- `logs/latest.log`, and the crash report from `crash-reports/` if there is one
