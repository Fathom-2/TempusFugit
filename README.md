![TempusFugit](TempusFugit%20Banner.png)

# TempusFugit

I originally put together this Minecraft 1.21.1 modpack (NeoForge with Fabric Connector) for solo play. I am really enjoying how it turned out, so I decided to share it.

World generation is vast, beautiful, and full of opportunities for exploration. With the included view-distance enhancements, you can enjoy breathtaking landscapes stretching hundreds of chunks into the distance. The screenshot above was taken with a 512 chunk view distance while Minecraft's render distance was set to just 12.

The surface world is stunning, but it is also dangerous in its own unique way. Exploration is rewarding, with structures rare enough that discovering one feels like a genuine achievement. When you do find one, expect more than the standard vanilla experience.

Early game progression is extended through minor ore ages, but without becoming grindy (just enough to slow that five minute race to diamonds). A light selection of farming and cooking mods adds variety without being overwhelming. The Illagers have expanded their evil society, creating new threats across the world. Wildlife is abundant, though not every creature you encounter will be friendly (hint: some can be tamed and ridden or flown). A handful of mini bosses provide additional challenges for adventure seekers.

When you're ready to push into the endgame, definitely defeat the dragon in the expanded End. However, you may have encountered a young Fire Dragon during your journey; the elder dragons seek solitude deep within the world's vast cave systems, and this is where the new endgame begins: when you take to the skies on the back of your own dragon and ride off into the sunset.

Whether solo or with a small group of friends, I hope you enjoy exploring this world as much as I enjoyed creating it. You might call this pack Vanilla++, I just call it Minecraft my way.
Seed used for the screenshot above (minus the AI dragon, of course).

**Seed:** TempusFugit

---

## Download

[Download on CurseForge](https://www.curseforge.com/minecraft/modpacks/tempusfugit/preview)

Download link will update after approval on CurseForge.

---

## Requirements

- Java 21
- NeoForge 1.21.1
- CurseForge App
- Minimum 4GB RAM, 8GB recommended
- High-end PC recommended

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

1. Select Creative mode in world creation screen, safe until pre-generation is complete
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

[Download TempusFugit Configuration & Setup Guide](https://github.com/Fathom-2/TempusFugit/raw/main/Tempusfugit%20configuration%20setup%20guide.pdf)

*This is a beta release for community testing. Please report any issues.*
