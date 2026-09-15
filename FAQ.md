# FAQ

### Is there a version for 1.21.9?

No. Fabric API for 1.21.9 didn't include the world rendering events the block overlay and hitboxes need,
and 1.21.10 replaced 1.21.9 a few days after release. Use 1.21.10.

### What about 1.21.5 and older?

Not supported. P-LUMA's menus and HUD are built on the GUI rendering system Minecraft introduced in 1.21.6.

### Is there a Forge or NeoForge version?

No, P-LUMA is Fabric only.

### The game doesn't start after adding P-LUMA

- Make sure the jar matches your exact Minecraft version, see [Installation](Installation.md#which-file)
- Make sure Fabric API is installed and matches your Minecraft version
- On 26.x, make sure the game runs on Java 25

Fabric Loader's error screen usually names the missing or mismatched mod.

### The line width setting doesn't change anything

On Minecraft 1.21.10 and older, world lines are always drawn at a fixed width, so the width options of the
block overlay and hitboxes only work on 1.21.11 and newer.

### The inverted crosshair is white

On 1.21.6 Minecraft has no inverting draw mode for plain shapes, so the inverted crosshair draws in white.
It works as expected on 1.21.7 and newer.

### My zoom / free look / full bright module says "Using …"

Another installed mod provides that feature, so P-LUMA's module turned itself off to avoid conflicts.
Remove the other mod if you'd rather use P-LUMA's. See [Mod Compatibility](Mod-Compatibility.md).

### Can I get banned for using it?

P-LUMA is a client-side mod and doesn't give an unfair advantage on its own, but every server sets its own
rules. Some servers forbid free look, hitboxes or full bright. Check the rules of the server you play on.

### Does P-LUMA replace Sodium?

No. P-LUMA doesn't touch terrain rendering, which is where Sodium makes the biggest difference. Install
both.

### I don't want P-LUMA's title screen or pause menu

Turn off **P-LUMA main menu** and **P-LUMA pause menu** on the General page. The settings hub stays
reachable from a small icon in the corner of the vanilla screens and from Mod Menu.

### Menus feel too animated

Turn on **Reduce motion** on the General page.

### Does P-LUMA send any data anywhere?

No. P-LUMA makes no network connections of its own. Links on the compatibility page only open in your
browser when you click them, after a confirmation screen.

### Where do I download it?

From the [Download](Download.md) page or this repository's
[releases](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases). Other sites may host outdated or modified
copies.

### Where do I report a bug?

[Open an issue](https://github.com/klasfimo/P-LUMA-Nova-Wiki/issues/new/choose) in this repository with your
Minecraft version, the P-LUMA jar name, your mod list and `logs/latest.log`.
