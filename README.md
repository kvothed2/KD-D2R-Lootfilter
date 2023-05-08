# D2R-Lootfilter
This is my basic D2R lootfilter. After not seeing one from Blizzard i decided to create it to my likings with minimalistic approach to highlighting. Took inspiration in Kryszard loot filter for PD2.

❗❗❗ **NOTE: THIS IS ONLY OFFLINE LOOT FILTER, YOU CANNOT USE IT ONLINE.** ❗❗❗

## Installation
In order to use it follow these steps:
1. Make sure you have 30 Gigs free since you will be extracting the Diablo II Resurrected data to edit.
2. Download CascView
  - Website: http://www.zezula.net/en/casc/main.html
  - Download: http://www.zezula.net/download/cascview_en.zip
3. Open CascView (Use default config)
4. Click Open Storage (Top left corner)
5. Navigate to Diablo II Resurrected Data Folder "Diablo II Resurrected\Data"
6. Select the Data Folder.
7. Inside CascView Navigate to Data\Data
8. Highlight all three folders: global, hd, local
9. Extract to: Diablo II Resurrected\Data (This will take awhile).
10. Diablo II Resurrected\Data should now have the following folders:
-config, data, global, hd, indices, local

## To Add Loot Filter:
1. Navigate to: Diablo II Resurrected\Data\local\lng\strings 
2. Download the files from the latest [Release](https://github.com/kvothed2/D2R-Lootfilter/releases)
3. Unpack and paste 3 json files in the location from point 1(make a copy of the originals just in case)
3. Create a shortcut for the game, add the following parameters in the properties. Launch the game from the shortcut.
-direct -txt 

## Loot Filter Changes

### General items Changed:
+ Gems (Normal, Flawless, Perfect)
+ Crafting/Mid/High Runes (For better visibility)
+ Potions (Shortened)
+ Inferior Items (Black)
+ Few items hidden (Arrows/Bolts etc)
+ Utilities (Shortened)
+ Gold (Shortened)
+ SC & GC Charms (Bigger pick up box. Inverted affixes is a known problem)
+ Jewels (>>> <<< signs)

### Bases Highlighted (Added Bright Red 0 in the end):
+ Pally Shields with high block
+ Ama Bows
+ Ama Javelins
+ Berserker Axes
+ Claws with Skills
+ War / Rune / Archon staves

### Affixes Colors
As an experiment I decided to highlight useful affixes on magic items like Amulets, Rings, Circlets, Charms, Jewels
- Stats (str dex frw fhr fcr fbr etc) - Amber
- Life / Mana - Red / Skyblue
- Dmg & AR - Light gold (Ruby - Red)
- Skills (+1 skillers, +3 Skill trees) - Turqoise
- Resistances - Red / Green / Gold / Sky blue; All res - Purple
- MF GF - Green
- Sockets (Jewelers') - Grey
- Useful Charges (Teleport, Life Tap, Low Res) - Pink

## Screenshots
<img src="https://user-images.githubusercontent.com/80476149/236894862-be3ddf68-f011-43cf-871b-7bed3e784eed.png" width="750">
<img src="https://user-images.githubusercontent.com/80476149/236894867-fd2ba445-2c1a-4c9b-9732-eaa236b9c756.png" width="750">
