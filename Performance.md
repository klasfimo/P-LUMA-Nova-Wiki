# Performance

## Bundled mods

Every P-LUMA jar includes these, built for its Minecraft version:

| Mod | What it improves |
|---|---|
| Lithium | Game logic and tick performance |
| FerriteCore | Memory use |
| ImmediatelyFast | HUD, text and entity drawing |

They're unmodified and load as separate mods. A newer copy in your `mods` folder replaces the bundled one.

## What P-LUMA never does

- **Players are never hidden**, by any setting, at any distance, including the automatic FPS manager
- **Terrain rendering is untouched.** That's Sodium's job, and P-LUMA works alongside it

## Settings

Open **Settings → Performance**.

### Render

| Setting | Range | Default | What it does |
|---|---|---|---|
| Entity culling | on / off | Off | Stops drawing entities past the distance (players excluded) |
| Entity cull distance | 8 – 256 blocks | 64 | |
| Block entity culling | on / off | Off | Stops drawing chests, signs, banners, heads and other block entities past the distance |
| Block entity distance | 16 – 256 blocks | 64 | |
| Sign text culling | on / off | Off | Keeps distant signs but skips their text |
| Sign text distance | 4 – 64 blocks | 16 | |
| Item & XP orb culling | on / off | Off | Stops drawing dropped items and orbs past the distance |
| Item cull distance | 8 – 128 blocks | 32 | |
| Name tag culling | on / off | Off | Hides name tags past the distance |
| Name tag distance | 4 – 128 blocks | 32 | |
| Only tags you are looking at | on / off | Off | Hides name tags outside the direction you're facing |
| Particles per tick | 0 – unlimited | Unlimited | Caps how many particles spawn each tick |
| Disable weather | on / off | Off | No rain or snow |
| Disable sky | on / off | Off | No sky, sun, moon or stars |

Block entities are drawn one by one outside the chunk mesh, which is why limiting them helps even with
Sodium installed.

### HUD

| Setting | Range | Default |
|---|---|---|
| Limit HUD refresh | on / off | Off |
| HUD refresh rate | 5 – 240 per second | 60 |

### Vanilla video settings

Max FPS, render distance, simulation distance, entity distance, VSync, entity shadows and clouds, without
leaving the page.

## Presets

| | Vanilla | PvP | Maximum FPS |
|---|---|---|---|
| Entity culling | off | 96 blocks | 48 blocks |
| Block entity culling | off | 64 blocks | 32 blocks |
| Sign text culling | off | 16 blocks | 8 blocks |
| Item culling | off | 48 blocks | 24 blocks |
| Name tag culling | off | off | 24 blocks, only tags you look at |
| Particles per tick | unchanged | 250 | 0 |
| Weather | on | off | off |
| Sky | on | on | off |
| HUD refresh limit | off | 60 / s | 30 / s |
| Full bright | off | on | on |
| Automatic FPS manager | off | on | on, aggressive |

A preset is just a starting point. Change any setting afterwards.

## Automatic FPS manager

| Setting | Range | Default |
|---|---|---|
| Automatic FPS manager | on / off | Off |
| Target FPS | 30 – 480, or monitor refresh rate | Monitor |
| Aggressive mode | on / off | Off |

When the frame rate stays below the target, the manager tightens P-LUMA's own settings step by step. It
relaxes them again once there's headroom. The status line shows current FPS, average, target and step.

**Aggressive mode** also lets it lower vanilla options: render distance, clouds and entity distance. It
only borrows them. Your own values are saved first and restored when it no longer needs them, when you
leave the world, or on the next start after a crash.

## Reduce motion

Found on the General page. Makes every menu transition instant.
