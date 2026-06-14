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

- NeoForge 1.21.1
- CurseForge App
- Minimum 8192MB RAM recommended
- High-end PC recommended

---

## Installation

1. Download and install the CurseForge app
2. Download **TempusFugit-1.0.0.zip** using the Download link above and import into CurseForge
3. Download **Voxy** for NeoForge 1.21.1 from: https://github.com/j-shelfwood/voxy-neoforge — place jar in mods folder
4. Download **Voxy Auto LOD** from: https://modrinth.com/mod/voxy-auto-lod — place jar in mods folder

---

## Optional but Highly Recommended

- **Physics Mod Pro** — Download NeoForge 1.21.1 version from: https://www.patreon.com/haubna — place jar in mods folder. Pre-configured settings are included in the config folder and will apply automatically.
- **Complementary Unbound 5.8.1** shader is already included in the pack's shaderpacks folder. Pre-configured settings included in config folder.

---

## First Time Setup — Important

1. Start your world in Creative mode until pre-generation is complete
2. Freeze time: `/gamerule doDaylightCycle false`
3. Freeze weather: `/gamerule doWeatherCycle false`
4. Run Chunky: `/chunky radius 256c` (recommended) or `/chunky radius 512c` (highly recommended) then `/chunky start`
   > **Note:** Pre-generation is time intensive — allow plenty of time to complete
5. When complete re-enable: `/gamerule doDaylightCycle true` and `/gamerule doWeatherCycle true`
6. Run: `/voxy import current`
7. Do a full 360 rotation to populate LOD view
8. Switch to Survival: `/gamemode survival`

---

## Known Issues

- **Physics Mod Pro** ocean/water/liquid/snow physics must remain **OFF** — known incompatibility with Voxy LOD water rendering. All other Physics Mod features work correctly. Pre-configured settings handle this automatically.

---

## Documentation

[TempusFugit Configuration & Setup Guide](TempusFugit_Configuration_Setup_Guide.pdf)

*This is a beta release for community testing. Please report any issues.*
