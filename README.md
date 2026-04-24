# Fallout 4 Definitive Edition
### A Comprehensive Modlist by [CrowdRocker](https://github.com/CrowdRocker)

> *A heavily modded Fallout 4 experience focused on stunning visuals, quality of life improvements, and deep settlement building with Sim Settlements 2. Built and tested on Linux/Proton — also compatible with Windows.*

---

## 📸 Screenshots

> *(Add your screenshots here — drag and drop images into the GitHub editor)*

---

## ✨ Highlights

- 🌄 **Visual Overhaul** — NMC Texture Bundle, weather mods, and lighting overhauls transform the Commonwealth into a stunning post-apocalyptic world
- 🏙️ **Sim Settlements 2** — Full SS2 setup with Chapters 1, 2 & 3. Let your settlers build and manage their own thriving cities
- 🎮 **Controller Ready** — Fully configured for Xbox controller on both Linux and Windows
- 🐧 **Linux/Proton Tested** — Built and played on Linux using Steam/Proton with MO2
- 🖥️ **FallUI Suite** — Complete UI overhaul with FallUI Inventory, HUD, Map, and more
- ⚙️ **574 Mods** — Carefully curated and stable on Fallout 4 AE (v1.11.191)

---

## 📋 Requirements

- **Fallout 4 Anniversary Edition** (v1.11.191)
- **Mod Organizer 2**
- **F4SE 0.7.7** — [Download](https://f4se.silverlock.org/)
- **Address Library for F4SE (AE version)** — [Download](https://www.nexusmods.com/fallout4/mods/47327)

---

## ⚠️ Off-Site Downloads

These mods are **not on Nexus** and must be downloaded separately before installing the modlist.

### 🔧 Required

| Mod | Source | Notes |
|-----|--------|-------|
| MCM Settings Manager v1.3-beta2 | [Collective Modding Discord](https://discord.com/channels/830436661736243230/831622946292105236) | Fixes save crash on AE — Nexus version (v1.2) is broken on AE |

### 💇 Hair Mods

| Mod | Source |
|-----|--------|
| MiscHairstyle / MoreHairstyles | [Tumblr](https://fo4-mischairstyle.tumblr.com/post/139169515871/mischairstyle16-download-47-new-hairs-for-male) |
| Supersalon Hairpack 4.7 | [Mega](https://mega.nz/file/r3pkDTwD#R_KhUxNOvncFFJyO8wXkZCCbl4_mvGdVHtrAV1Htuvw) |
| ZGC Hairpack | [LoversLab](https://www.loverslab.com/topic/113712-zgc-hairpack/) |
| IceStorm Hairs | [IceStorm Mods](https://storage.icestormng-mods.de/s/Jp9nfE8g4iQmyy8) |
| IceStorm Seeker Mines | [IceStorm Mods](https://storage.icestormng-mods.de/s/Jp9nfE8g4iQmyy8) |
| IceStorm Combat Drones 1.1 | [IceStorm Mods](https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY) |
| IceStorm GRL45 Grenade Launcher | [IceStorm Mods](https://storage.icestormng-mods.de/s/SdR9jL6PAfkCodB) |
| BDO Hairs, THBrows, THPoses & more | [TrophiHunter](https://www.trophihunter.com/fallout4-mods/black-desert-online-hairs) |

### 👙 Optional — Fusion Girl Body

These are optional. If you choose not to use Fusion Girl, the modlist will still work fine.

| Mod | Source |
|-----|--------|
| Fusion Girl | [LoversLab](https://www.loverslab.com/files/file/18238-zex-fusion-girl/) |
| ZeX - ZaZ Extended Skeleton 6.0 | [LoversLab](https://www.loverslab.com/files/file/24592-zex-zaz-extended-skeleton/) |
| ZeX Discord | [Discord](https://discord.gg/hjfCQYcN4c) |

---

## 🏙️ Sim Settlements 2 Setup

SS2 requires its own setup. Follow Kinggath's official tutorials and install the collections **before** applying this modlist.

| Collection | Link |
|-----------|------|
| SS2 Starter Collection | [Nexus](https://www.nexusmods.com/games/fallout4/collections/u4durh) |
| SS2 Starter+ Collection | [Nexus](https://www.nexusmods.com/games/fallout4/collections/u7nfmy) |
| SS2 Starter+ F4SE Collection | [Nexus](https://www.nexusmods.com/games/fallout4/collections/hfs1fq) |
| SS2 New Players Guide | [Wiki](https://wiki.simsettlements2.com/) |

> 💡 Watch Kinggath's YouTube tutorials — they are incredibly helpful for getting started with SS2.

---

## 🐧 Linux/Proton Setup

This modlist was built and tested on Linux. A few extra steps are needed:

**1. UAS Fix for external USB drives** (if applicable)
Add to Steam Launch Options:
```
usb-storage.quirks=XXXX:YYYY:u %command%
```

**2. Controller vs Mouse conflict fix**
Use **one** of the following — not both:
- ✅ Steam Input ON + no RAW INPUT mod
- ✅ RAW INPUT mod + Steam Input OFF

**3. Pip-Boy map cursor fix**
Make sure your `fallout4prefs.ini` has:
```ini
[Display]
uPipboyTargetHeight=700
uPipboyTargetWidth=876
```

---

## ⚙️ INI Settings

Add these to your `fallout4custom.ini` for SS2 stability:

```ini
[General]
iNumHWThreads=8
uExterior Cell Buffer=36

[Papyrus]
fUpdateBudgetMS=1.2
fExtraTaskletBudgetMS=1.2
fPostLoadUpdateTimeMS=2000
```

---

## 📦 Load Order Library

Full modlist available on [Load Order Library](https://loadorderlibrary.com/lists/fallout-4-definitive-edition)

---

## 🙏 Credits

- **Kinggath** — Sim Settlements 2 and incredible tutorials
- **All mod authors** on Nexus, LoversLab, and off-site
- **Collective Modding Discord** — for MCM Settings Manager beta and community support

---

*Modlist version 1.0.0 — Built on Fallout 4 AE v1.11.191*
