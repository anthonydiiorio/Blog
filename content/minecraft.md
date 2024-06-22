---
title: "Minecraft"
date: 2024-06-12T12:00:00-05:00
draft: false
page: true
hidemeta: true
cover:
    image: "mc.jpg"
    alt: "Home Assistant Energy Dashboard"
    relative: true # To use relative path for cover image, used in hugo Page-bundles
---

I prefer to install Fabric, Iris, and Sodium manually as described here:  
[GitHub: Iris Docs - Manual Installation](https://github.com/IrisShaders/Iris/blob/1.19.4/docs/guide.md#manual-installation)

# Fabric

### Mods

These are just client side mods, no need to install them to join the server.

- [Install Fabric](https://fabricmc.net/use/installer/)
- `%APPDATA%\.minecraft\mods`
  - [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) Mod API
  - [Iris](https://modrinth.com/mod/iris/) Shaders
  - [Sodium](https://modrinth.com/mod/sodium) Rendering Engine
  - [JourneyMap](https://teamjm.github.io/journeymap-docs/latest/) Mini Map
  - [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) Power Saving when tabbed out

### Shaders

- `%APPDATA%\.minecraft\shaderpacks`
  - [Complimentary Reimaginied](https://www.curseforge.com/minecraft/shaders/complementary-reimagined)

### Resource Packs
- `%APPDATA%\.minecraft\resourcepacks`
  - [PureBDCraft](https://bdcraft.net/downloads/purebdcraft-minecraft/)

## Server Mods

These are running server side, no need to install on the client.

The server is running Fabric 1.20.6 with the following mods:

- [Fabric API](https://modrinth.com/mod/fabric-api)
  - [Lithium](https://modrinth.com/mod/lithium) Server optimization
  - [Essential Commands](https://modrinth.com/mod/essential-commands)
- [Collective API](https://modrinth.com/mod/collective) for [Serilum](https://modrinth.com/user/Serilum) mods
  - [Passive Endermen](https://modrinth.com/mod/passive-endermen)

# Forge

[Forge Installer](https://maven.minecraftforge.net/net/minecraftforge/forge/1.19.2-43.4.0/forge-1.19.2-43.4.0-installer.jar) 1.19.2

- `%APPDATA%\.minecraft\mods`
  - [Tinkers Construct](https://www.curseforge.com/minecraft/mc-mods/tinkers-construct/files/all?page=1&pageSize=20&version=1.19.2) 1.19.2
    - [Mantle](https://www.curseforge.com/minecraft/mc-mods/mantle/files/all?page=1&pageSize=20&version=1.19.2) 1.19.2 (Dependency)
  - [Just Enough Items](https://www.curseforge.com/minecraft/mc-mods/jei/files/all?page=1&pageSize=20&version=1.19.2&gameVersionTypeId=1) 1.19.2 (11.6.0.1020)
  - [JourneyMap](https://www.curseforge.com/minecraft/mc-mods/journeymap/files/all?page=1&pageSize=20&version=1.19.2&gameVersionTypeId=1) 1.19.2