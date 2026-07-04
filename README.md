![TempusFugit](TempusFugit%20Banner.png)

# TempusFugit

I originally put together this Minecraft 1.21.1 modpack (NeoForge with Fabric Connector) for solo play. I really enjoyed how it turned out, so I decided to share it.

World generation is vast, beautiful, and full of opportunities for exploration. With the included view-distance enhancements, you can enjoy breathtaking landscapes stretching hundreds of chunks into the distance. The screenshot above was taken with a 512 chunk view distance while Minecraft's render distance was set to just 12.

The surface world is stunning, but it is also dangerous in its own unique way. Exploration is rewarding, with structures rare enough that discovering one feels like a genuine achievement. When you do find one, expect more than the standard vanilla experience.

Early game progression has been reworked to extend the early game through minor ore ages, but without becoming grindy (just enough to slow that five minute race to diamonds). A light selection of farming and cooking mods adds variety without being overwhelming. The Illagers have expanded their evil society, creating new threats across the land. Wildlife is abundant, though not every creature you encounter will be friendly (hint: some can be tamed and ridden or flown). A handful of mini bosses provide additional challenges for adventure seekers.

Enter the Nether in search of the riches found only there, where perilous terrain and new dangers stand between you and the treasures you seek. Then enter the reimagined End, discovering expansive floating landscapes, perilous journeys across the void, and an enhanced encounter with the Ender Dragon.

Chances are you will come across a young Fire Dragon or two on the surface during your journey; this is only the beginning. Venture deep within the world's endless cave systems to face the elder dragons seeking solitude upon their piles of treasure. This presents a new challenge: defeat them, and you might claim a reward that allows you to take to the skies on the back of your own dragon.

Whether solo or with a small group of friends, I hope you enjoy exploring this world as much as I enjoyed creating it. You might call this pack Vanilla++, I just call it Minecraft my way.

Seed used for the screenshot above (minus the AI dragon, of course).

**Seed:** TempusFugit

---

## Installation Instructions

[Install on CurseForge](https://www.curseforge.com/minecraft/modpacks/tempusfugit)

Installing directly through the CurseForge App is the recommended method. All included mods, configs, scripts, datapacks, resource packs, shader packs, and recommended settings are installed automatically with no manual setup required.

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
- Mid to High-end PC recommended

---

## First Time Setup — Important

> **Note:** TempusFugit ships with Distant Horizons preconfigured with a **256 chunk LOD Render Distance**. You only need to adjust this LOD distance if you choose a different Chunky pre-generation radius, but the two settings **must match**. In my opinion, **256 chunks is the minimum pre-generation radius worth using.** Although Distant Horizons will eventually generate the world on its own, using Chunky to pre-generate your world **dramatically speeds up the process**. **Taking the time to pre-generate your world is highly recommended.** Skipping this step will dramatically reduce the visual impact of Distant Horizons, and **you won't experience the modpack as the screenshots present it.**

> **Distant Horizons Settings:** Press **Esc** → **Options**, then click the **Distant Horizons** button (the small square button immediately to the left of the FOV slider).
>
> **Optional:** Under **Advanced Settings**, change **Show Generation Progress** from **Disabled** to **Overlay** to display Distant Horizons' real-time generation progress, similar to Chunky's progress display.

 1. Create your world in **Creative** mode to safely complete world pre-generation before beginning your Survival adventure.
 2. Go to **More > Game Rules > World Updates** and set **Update Fire to OFF** (recommended)
 3. Disable any shader pack before starting Chunky pre-generation (recommended)
 4. Freeze time: `/gamerule doDaylightCycle false`
 5. Freeze weather: `/gamerule doWeatherCycle false`
 6. In-Game, set **Distant Horizons → LOD Chunk Render Distance Radius** to match the Chunky radius you intend to use.
 7. Run Chunky: `/chunky radius 256c` (**minimum recommended**) or `/chunky radius 512c` (**recommended for high-end systems**) then `/chunky start`
    > **Note:** World pre-generation can take a considerable amount of time depending on your selected radius and hardware. Allow it to complete before continuing.
 8. Distant Horizons may continue generating LOD data for a short time after Chunky completes world pre-generation.
 9. When complete, re-enable: `/gamerule doDaylightCycle true` and `/gamerule doWeatherCycle true`
10. Slowly do a full 360 rotation to fully populate LOD view.
11. Switch to Survival: `/gamemode survival`
12. Re-enable your shaders (if desired) and set Minecraft's render distance to your preferred value. **12 chunks is recommended when using Distant Horizons.**

> **Note:** Distant Horizons will continue generating terrain beyond the pre-generated area as you explore. If you later wish to expand your pre-generated world, use `/chunky center` to set Chunky's center to your current position, then repeat **Steps 3–12**.

---

## Shader Support

These shader packs (including custom configuration files) are included with the modpack when installed through the CurseForge App.

**Recommended Shaders:**
- 🎨 [Complementary Unbound r5.8.1](https://www.curseforge.com/minecraft/shaders/complementary-unbound)
  - **Optional:** *Euphoria Patches* is also included and will appear as a separate shader option in-game.
- ⚡ [Photon 1.3b](https://www.curseforge.com/minecraft/shaders/photon-shader)

- Custom pre-configured settings are included for all three shader options and will apply automatically when enabled in-game.

**Note:** TempusFugit is intended to be installed through the CurseForge App. Installation using third-party launchers is unsupported and may require additional manual configuration.

---

## Additional Documentation

[TempusFugit Configuration & Setup Guide (PDF)](https://github.com/Fathom-2/TempusFugit/raw/main/Tempusfugit%20configuration%20setup%20guide.pdf)

Questions, bug reports, progression issues, balance suggestions, and feedback are always welcome.

Please report them [here](https://github.com/Fathom-2/TempusFugit/issues).
