# Download

**Latest version: Nova 1.4.5** · [Release page](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/tag/v1.4.5) ·
[All releases](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases) · [Changelog](Changelog.md)

Pick the file for your exact Minecraft version. Each jar only runs on the version it was built for.

| Minecraft | Java | Download | Size |
|---|---|---|---|
| 26.2 | 25 | [pluma-nova.1.4.5-26.2.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-26.2.jar) | 1.2 MB |
| 26.1, 26.1.1, 26.1.2 | 25 | [pluma-nova.1.4.5-26.1.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-26.1.jar) | 1.4 MB |
| 1.21.11 | 21 | [pluma-nova.1.4.5-1.21.11.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-1.21.11.jar) | 1.4 MB |
| 1.21.10 | 21 | [pluma-nova.1.4.5-1.21.10.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-1.21.10.jar) | 1.4 MB |
| 1.21.8 | 21 | [pluma-nova.1.4.5-1.21.8.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-1.21.8.jar) | 1.4 MB |
| 1.21.7 | 21 | [pluma-nova.1.4.5-1.21.7.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-1.21.7.jar) | 1.2 MB |
| 1.21.6 | 21 | [pluma-nova.1.4.5-1.21.6.jar](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases/download/v1.4.5/pluma-nova.1.4.5-1.21.6.jar) | 1.2 MB |

Not sure which Minecraft version you have? The launcher shows it next to the profile, and the bottom-left
corner of the vanilla title screen shows it too.

You also need [Fabric Loader](https://fabricmc.net/use/) 0.19.3+ and [Fabric API](https://modrinth.com/mod/fabric-api)
for the same Minecraft version. Step-by-step instructions are on the [Installation](Installation.md) page.

## What's inside every jar

- P-LUMA itself
- **Lithium**, **FerriteCore** and **ImmediatelyFast**, built for that Minecraft version (see
  [Performance](Performance.md#bundled-mods)). Their licences are included in the jar.

## Checking the file

Every release also has a `SHA256SUMS.txt`. To check a download on Windows, run this in PowerShell in the
folder with the jar and compare the result with the line for that file:

```powershell
Get-FileHash .\pluma-nova.1.4.5-26.2.jar -Algorithm SHA256
```

On Linux or macOS: `sha256sum -c SHA256SUMS.txt --ignore-missing`.

SHA-256 for 1.4.5:

| File | SHA-256 |
|---|---|
| `pluma-nova.1.4.5-26.2.jar` | `bef0fe343a81623d2252b6eea5262ecc0be644d8b5f86899e44fa2fccc861c66` |
| `pluma-nova.1.4.5-26.1.jar` | `10c4fced90af8596985fe397ff1e7468f4c7e57803d40e04677122a600b633ae` |
| `pluma-nova.1.4.5-1.21.11.jar` | `de427d83ca0fddc50dcc1cd8851a4747bcb4dadb2eb3f13338f304a4e77d0d6a` |
| `pluma-nova.1.4.5-1.21.10.jar` | `28e00e860676a76c539d6a79c983c1c6cf57b7f7e75f8c8809fe05193bbf0431` |
| `pluma-nova.1.4.5-1.21.8.jar` | `a00bd408994ef3cb3483988647128338a3249004da851093337858244f401a1a` |
| `pluma-nova.1.4.5-1.21.7.jar` | `56ec5981fc35bfbeb3fa8941e73e3166571bd2ca1fdc7622fb20155130769ad1` |
| `pluma-nova.1.4.5-1.21.6.jar` | `bdbb418ce643324c3d6b029eb5833ba899434f704e6a7be7d891094e045cba62` |

Only download P-LUMA from this repository's releases. Re-uploads elsewhere may be outdated or modified.

## Older versions

Every earlier version stays available on the [releases page](https://github.com/klasfimo/P-LUMA-Nova-Wiki/releases).
