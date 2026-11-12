# Spartan Shields [Unofficial]

Unofficial Architectury port of **[Spartan Shields](https://github.com/ObliviousSpartan/SpartanShields)** by **ObliviousSpartan**: 60+ shields in vanilla and modded materials, shield bashing, shield enchantments and tower shields you can decorate with banners.

## Download

- [CurseForge](https://www.curseforge.com/minecraft/mc-mods/spartan-shields-fabric)
- [Modrinth](https://modrinth.com/mod/spartanshieldsunofficial)

## Supported versions

| Loader | Minecraft versions |
|---|---|
| Fabric | 1.20 – 1.21.11 |
| NeoForge | 1.20.2, 1.20.4 – 1.21.11 |
| Forge | 1.20 – 1.20.4 |

Requires **Architectury API**, and **Fabric API** on Fabric.

## Repository layout

One branch per Minecraft version (`1.20` … `1.21.11`). Each branch is an Architectury project:

```
common/    shared code
fabric/    Fabric build
forge/     Forge build (branches 1.20 – 1.20.4)
neoforge/  NeoForge build (branches 1.20.2, 1.20.4 and newer)
```

```bash
./gradlew build
```

## Reporting bugs

This is an **unofficial** port. Please do not report its bugs to ObliviousSpartan; use this repository's [Issues](https://github.com/sanufsoiii/spartanShilds-unofficial/issues).

## License and credits

- Spartan Shields was created by **ObliviousSpartan**. All original concepts and designs belong to them.
- This port is not affiliated with or endorsed by the original author.
- Licensed under the **Apache License 2.0**, like the original (see `LICENSE`). Sources have been modified from the original to support more loaders and Minecraft versions.
