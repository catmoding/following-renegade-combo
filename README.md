# following renegade platinum combo patches
easy to use patches with lots of availalbe options for however you prefer to play following + renegade platinum!

i really love renegade platinum and following pokemon, but recently i struggled to find the right way to patch my platinum rom to include both, and kept getting patched roms that would crash on the first battle or refused to load at all. information on this combo is all over the internet but nothing worked, and some posts that are referenced online don't exist anymore. so i decided to dig into this myself and make a single patch, because it seems like stacking the patches on top of each other one by one was part of the issue. another issue is that there are *generally* 3 different platinum roms that someone could have, and sometimes it can be hard to figure out which one you need or which patch goes where, so included in this release is a set of patches for each of those 3 rom versions:

- xenophobia 3541 usa
- platinum usa rev 0 (per no-intro)
- platinum usa rev 1 (per no-intro)

these are only made for usa copies of the game because that's what the original renegade platinum is based on

# how to play
1. always check your roms's crc32 or sha-1 by using a site like [rom patcher js](https://www.marcrobledo.com/rompatcher.js/)

| your ROM | CRC32 | SHA-1 | folder |
|---|---|---|---|
| Pokemon - Platinum Version (USA), XenoPhobia release #3541 | `1D8A5220` | `c5072bf51a5ecc51ade99d3506c023f5bac3eeb3` | Platinum (USA) XenoPhobia 3541 base |
| Pokemon - Platinum Version (USA) | `9253921D` | `ce81046eda7d232513069519cb2085349896dec7` | Platinum (USA) (Rev 0) No-Intro base |
| Pokemon - Platinum Version (USA) (Rev 1) | `69D628E8` | `0862ec35b24de5c7e2dcb88c9eea0873110d755c` | Platinum (USA) (Rev 1) No-Intro base |

*please note that it doesn't matter which base you start with, as long as you use the correct patches for that base, the output is the same*

2. download the zip file that matches your rom base
3. within that zip, pick which **mode** you want
- complete renegade (some changes to pokemon types/stats/etc made by drayano)
- classic renegade

*please see drayano's documentaion to see the main differences between these, it's linked below*

4. within the **mode** folder, pick the shiny rate you prefer and if you want speed-up

*speed patches add instant text, no hp/xp animations, and uncapped fps*

5. apply using the patcher of your choice, i like using [rom patcher js](https://www.marcrobledo.com/rompatcher.js/), but you can use [delta patcher](https://github.com/marco-calautti/deltapatcher) too
6. enjoy! you only need to apply one patch

*one last thing, save files created by one of these patched roms should load up fine in a different patch, for example if you started with speed off but wanted to continue the save with speed on. i tested this between a couple patched roms but not every single patch in the release, so please make sure you backup your save file before trying to switch roms.*

if there are any issues please let me know, i hope playing this combo brings you as much joy as it does for me. ♥
# credits
original creators keep all rights, if any of the original creators wants this repo removed please let me know and i'll take it down

- **renegade platinum** by drayano — [original post](https://projectpokemon.org/home/forums/topic/52294-pok%c3%a9mon-renegade-platinum/) ·
  [documentation](https://pastebin.com/u/renegadeplatinum). speed up option comes from drayano's additional patches.
- **following platinum** by [mikelan98](https://projectpokemon.org/home/profile/56209-mikelan98/) and adastra
- **following + renegade integration** (base, classic mode and shiny rate patches) by chensquared — [original release](https://www.reddit.com/r/pokemonromhacks/comments/s4fbhi/complete_renegade_platinum_and_following_platinum/)
  ([archived copy](https://web.archive.org/web/20220725082513/https://www.reddit.com/r/pokemonromhacks/comments/s4fbhi/complete_renegade_platinum_and_following_platinum/))
- **qol patches for renegade + following** — [r/pokemonromhacks post](https://www.reddit.com/r/pokemonromhacks/comments/sabf2j/qol_patches_for_renegade_platinum_and_following/)