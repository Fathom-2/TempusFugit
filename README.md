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

## Installation Instructions

[Install on CurseForge](https://www.curseforge.com/minecraft/modpacks/tempusfugit)

Installing directly through the CurseForge App is the recommended method. All mods, configs, scripts, datapacks, and included shader packs install automatically with no manual steps required. See below for First Time Setup and Shader Support.

---

## Credits

[Credit Where Credit is Due](https://github.com/Fathom-2/TempusFugit/blob/main/CREDITS.md)

TempusFugit would not exist without the incredible work of the Minecraft modding community. Please take a moment to check out the mod authors who made this pack possible.

---

## Requirements

- Java 21
- NeoForge 1.21.1
- CurseForge App
- Minimum 4GB RAM, 8GB recommended
- High-end PC recommended

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

## Shader Support

Shader packs are not distributed with the modpack and must be downloaded separately.

**Recommended Shaders:**
- 🎨 [Complementary Unbound r5.8.1](https://www.curseforge.com/minecraft/shaders/complementary-unbound)
*Custom pre-configured settings included in shaderpack folder will apply if using CU*
- ⚡ [Photon 1.3b](https://www.curseforge.com/minecraft/shaders/photon-shader)
*Higher FPS alternative, Voxy compatible*

**Installation:**
1. CurseForge: In My Modpacks, click on **TempusFugit**, then click the **⋯** next to the orange **Play** button and select **Open Folder**
2. Open the **shaderpacks** folder and just drop your downloaded shader zip inside; the custom settings file `ComplementaryUnbound_r5.8.1.zip.txt` will already be in this folder
3. Launch the pack, then in-game go to **ESC > Options > Video Settings > IRIS**
4. Select your shader, click **Apply** and wait for it to load

---

## Known Issues

- **Physics Mod Pro** ocean physics must remain **OFF** due to a known incompatibility with Voxy LOD water rendering. All other Physics Mod features work correctly, however liquid & snow physics are turned off (personal preference). Pre-configured settings handle this automatically.

---

## Documentation

[Download TempusFugit Configuration & Setup Guide](https://github.com/Fathom-2/TempusFugit/raw/main/Tempusfugit%20configuration%20setup%20guide.pdf)

*This is a beta release for community testing. Please report any issues.*
