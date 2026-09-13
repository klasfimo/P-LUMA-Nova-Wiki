# Installation

## Requirements

| | |
|---|---|
| Mod loader | [Fabric Loader](https://fabricmc.net/use/) 0.19.3 or newer |
| Dependency | [Fabric API](https://modrinth.com/mod/fabric-api) for your Minecraft version |
| Java | 25 for Minecraft 26.x, 21 for Minecraft 1.21.x |
| Side | Client only |

The official Minecraft launcher, Prism, Modrinth App and CurseForge all ship the right Java version
automatically.

## Steps

1. Install Fabric Loader for your Minecraft version
2. Put Fabric API in your `mods` folder
3. Put the P-LUMA jar that matches your Minecraft version in the same folder
4. Start the game. The P-LUMA title screen should appear.

## Which file?

Every Minecraft version has its own jar. Using the wrong one will stop the game from launching, and
Fabric Loader will tell you which version it expects.

| Minecraft | File |
|---|---|
| 26.2 | `pluma-nova.1.4.4-26.2.jar` |
| 26.1, 26.1.1, 26.1.2 | `pluma-nova.1.4.4-26.1.jar` |
| 1.21.11 | `pluma-nova.1.4.4-1.21.11.jar` |
| 1.21.10 | `pluma-nova.1.4.4-1.21.10.jar` |
| 1.21.8 | `pluma-nova.1.4.4-1.21.8.jar` |
| 1.21.7 | `pluma-nova.1.4.4-1.21.7.jar` |
| 1.21.6 | `pluma-nova.1.4.4-1.21.6.jar` |

1.21.9 and 1.21.5 or older are not supported. See the [FAQ](FAQ.md) for why.

## Bundled mods

Each jar already contains **Lithium**, **FerriteCore** and **ImmediatelyFast**, built for that
Minecraft version. You don't need to install them. If you add a newer copy of any of them to your
`mods` folder, Fabric Loader picks the newer one.

## Recommended alongside

| Mod | Why |
|---|---|
| [Sodium](https://modrinth.com/mod/sodium) | Much faster terrain rendering; the biggest FPS gain you can get |
| [Iris](https://modrinth.com/mod/iris) | Shaders (needs Sodium) |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Skips entities you can't see |
| [More Culling](https://modrinth.com/mod/moreculling) | Culls more block faces |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Lowers FPS while the game is in the background |

See [Mod Compatibility](Mod-Compatibility.md) for details.

## Updating

Replace the old P-LUMA jar with the new one. Your settings in the `config` folder are kept.
