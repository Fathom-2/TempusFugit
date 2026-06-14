![TempusFugit](TempusFugit%20Banner.png)

# TempusFugit

A curated solo survival modpack for NeoForge 1.21.1. The world tells a story through geography, not quest text. The surface is beautiful but dangerous, caves escalate in dread the deeper you venture, and structures are rare enough that finding one feels like a genuine discovery.

**Seed:** TempusFugit

---

## Download

[Download TempusFugit v1.0.0 Beta](https://github.com/Fathom-2/TempusFugit/releases/tag/v1.0.0)

Download **TempusFugit-1.0.0.zip** only — ignore the Source code files, they are not needed.

---

## Requirements

- Java 21
- NeoForge 1.21.1
- CurseForge App
- Minimum 4GB RAM, 8GB recommended
- High-end PC recommended

**Recommended Java Arguments:**
`-XX:+UseZGC -XX:+ZGenerational -XX:+AlwaysPreTouch -XX:+UseStringDeduplication -XX:ZUncommitDelay=60`

---

## Installation

There are two ways to install TempusFugit depending on your situation:

---

### Option 1: GitHub Import (Private/Personal Use)
*All mods including Voxy, Voxy Auto LOD and Physics Mod Pro are bundled — no manual installs required.*

1. Download and install the CurseForge app
2. Download **TempusFugit-1.0.0.zip** using the Download link above
3. Open CurseForge, go to **My Modpacks** and click **Import**
4. Select the downloaded zip and wait for installation to complete
5. Launch and enjoy

---

### Option 2: Public CurseForge Release *(coming soon)*
*When the pack is published publicly on CurseForge, some mods must be installed manually due to licensing restrictions.*

1. Install from CurseForge directly
2. Download **Voxy** for NeoForge 1.21.1 from: https://github.com/j-shelfwood/voxy-neoforge — place jar in mods folder
3. Download **Voxy Auto LOD** from: https://modrinth.com/mod/voxy-auto-lod — place jar in mods folder
4. Download **Physics Mod Pro** from: https://www.patreon.com/haubna — place jar in mods folder

---

## Optional but Highly Recommended

- **Physics Mod Pro** — included in Option 1, manual install required for Option 2. Adds realistic physics to blocks, mobs and items. Pre-configured settings in the config folder apply automatically.
- **Voxy** — included in Option 1, manual install required for Option 2. Provides stunning long distance LOD rendering far beyond your normal render distance.
- **Complementary Unbound 5.8.1** shader is already included in the pack's shaderpacks folder. Pre-configured settings included in config folder.

---

## First Time Setup — Important

1. Start your world in Creative mode until pre-generation is complete
2. Go to **More > Game Rules > World Updates** and set **Update Fire to OFF**
3. Freeze time: `/gamerule doDaylightCycle false`
4. Freeze weather: `/gamerule doWeatherCycle false`
5. Run Chunky: `/chunky radius 256c` (recommended) or `/chunky radius 512c` (highly recommended) then `/chunky start`
   > **Note:** Pre-generation is time intensive — allow plenty of time to complete
6. When complete re-enable: `/gamerule doDaylightCycle true` and `/gamerule doWeatherCycle true`
7. Run: `/voxy import current`
8. Do a full 360 rotation to populate LOD view
9. Switch to Survival: `/gamemode survival`

---

## Known Issues

- **Physics Mod Pro** ocean/water/liquid/snow physics must remain **OFF** — known incompatibility with Voxy LOD water rendering. All other Physics Mod features work correctly. Pre-configured settings handle this automatically.

---

## Documentation

[TempusFugit Configuration & Setup Guide](https://github.com/Fathom-2/TempusFugit/blob/main/TempusFugit_Configuration_Setup_Guide.pdf)

*This is a beta release for community testing. Please report any issues.*
