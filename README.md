# Slidikins' Strenuous Skyrim
Latest update: **08-18-2021**  
Compatible with: **The Phoenix Flavour 4.7.2**

# 1. Introduction
**Slidikins’ Strenuous Skyrim: Special Edition (SSS:SE)** is a fork of **[The Phoenix Flavour (TPF)](https://thephoenixflavour.com/tpf/introduction/)**, a wonderfully curated vanilla-plus modding guide for [The Elder Scrolls V Skyrim: Special Edition](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/). In order to use this document you’ll first need to install TPF, either [manually](https://thephoenixflavour.com/tpf/initial-setup/), or via [Wabbajack Installer](https://thephoenixflavour.com/tpf/wabbajack/). Regardless which you choose, I’m going to assume you’ve read TPF and understand the mods and tools included. Phoenix does a wonderful job explaining the basic modding instructions necessary for installing this fork so I don’t have to.

**What to expect from The Phoenix Flavour:**  
*Copied from the guide*
- A Better Skyrim : The guide includes hundreds of mods across several dozen categories, all carefully selected to fit [Phoenix’s] vision of a lore-friendly, improved but not radically changed Skyrim. The Phoenix Flavour strives to provide a solid upgrade of the vanilla experience with modern visuals and rebalanced gameplay.
- Custom Files and Patches : Both the final patch as well as some patches and plugin replacers installed during the mod setup have been made specifically for the guide by Umgak and [Phoenix]. They ensure compatibility as well as consistency between all included mods.
- Performance : The Phoenix Flavour was created for gameplay rather than screen-archery and will for most people deliver solid framerates on a 1080p monitor resolution. For higher resolutions, better hardware is required. Through INI changes, reasonable texture resolutions, a performance-friendly grass overhaul as well as a skippable ENB section and the choice to use lower settings in DynDOLOD, you can tweak your game until you reach a stable framerate.
- Stability : Skyrim SE itself is already very stable compared to Classic Skyrim. You may still experience the occasional freeze or crash, but they will be very rare (perhaps once every 20 to 30 hours). These happen in Vanilla and they will happen in TPF.

**Key differences between SSS:SE and base TPF:**
- Survival Mode : I use Survival from the Creation Club, meaning you’ll need to eat and sleep among other changes. [More information from UESP.net.](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
- Strict Level Cap : Maximum level is 50 with a total of 55 perk points granted. Use them wisely. On a side note, skills can not be made Legendary.
- Reduced HUD : With all of my interface presets, your HUD will be minimized, limiting on-screen information. You’ll no longer see enemy information or active effects while in combat, for example.
- Tougher Equipment Acquisition : Higher tier items are rarer to find and will likely need to be crafted or commissioned. In addition, gear quality degrades with use if not maintained through tempering. If you’re not trained in the crafting skills, you can commission what you need through Honed Metal, but even then some things may be out of reach.
- Preparedness Rewarded : The lack of natural health regen will dwindle supplies if you’re hurt frequently, forcing you to retreat. Long fights are not your friend. Bringing the right tools for the job, along with accounting for Resistances and Weaknesses, will go a long way towards preventing stalls in your adventures.

# 2. Compatibility Notes
Through plenty of testing and tweaking, these mods work together perfectly if installed in the order given by TPF. If you simply install these mods and run LOOT, **you will not have a good time**. The Conflict Resolution plugin given by TPF handles all the conflicts that occur with the prescribed load order. The mods I’ve added afterwards create no additional conflicts if they are placed at the end of their respective sections, and my included loadorder.txt will make sure plugins are in the correct place as well.  

Learn from [this video](https://youtu.be/LyDpP96LRmA) on how to handle mod conflicts for yourself. Doing so will greatly enhance your modding experience overall and allow you to tinker your game to suit your own needs.

## 2.1 TPF-X Addons

With the release of TPF 4.5, Phoenix is now offering several “add on” modules to the modlist. These are entirely optional modules that can enhance TPF in different ways. I’ve jotted some quick notes on how I feel about each section in case you were wondering, but ultimately they should all be compatible with the mods chosen in SSS:SE. Install any TPF-X mod that you like, just mind the instructions provided by Phoenix.

### [Interface](https://thephoenixflavour.com/tpf-x/installation/interface/)
**Notes:** This section contains a number of mods I explicitly chose to exclude from SSS:SE and therefore doesn’t fit the intended UI of this fork.  
**Compatibility:** Should be compatible but goes against the spirit of this Addon.

### [Gameplay Tweaks](https://thephoenixflavour.com/tpf-x/installation/gameplay-tweaks/)
**Notes:** I like the combat as it is in base TPF so I skipped this one. These mods don’t go against the design of SSS:SE, but they don’t enhance it either.  
**Compatibility:** Should be compatible

### [New Gear](https://thephoenixflavour.com/tpf-x/installation/new-gear/)
**Notes:** In the past I was adamant against adding new gear but Phoenix is pretty selective on what she adds. I trust her judgement so I’ve added it for now.  
**Compatibility:** Compatible, included in loadorder.txt

### [New Companions](https://thephoenixflavour.com/tpf-x/installation/new-companions/)
**Notes:** I don’t like adding companions to my game. Inigo and Lucien won’t ruin the balance of SSS:SE, but they will spoil you when it comes to followers.  
**Compatibility:** Should be compatible

### [Player Homes](https://thephoenixflavour.com/tpf-x/installation/player-homes/)
**Notes:** Similar to the Companions above, Elianora’s homes tend to outshine the vanilla selection. For that reason I don’t add them, but you’re welcome to.  
**Compatibility:** Should be compatible

### [New Music](https://thephoenixflavour.com/tpf-x/installation/new-music/)
**Notes:** If you’re tired of the soundtrack, this is a good way to add more variety to the game. Most, if not all of it, fits in with the existing themes. This used to be in TPF, so I’ve kept it in my order.  
**Compatibility:** Compatible, included in loadorder.txt

### [Miscellaneous](https://thephoenixflavour.com/tpf-x/installation/miscellaneous/)
**Notes:** These mods are entirely up to you. I saw no reason to add any of them to my game but your preference may be different.  
**Compatibility:** Should be compatible

### [AllGud](https://thephoenixflavour.com/tpf-x/installation/allgud/)
**Notes:** If you want favorited items to be visible, this is what you need. Otherwise, Simple Dual Sheath is fine for adding left-handed sheaths to characters. This also used to be in TPF.  
**Compatibility:** Compatible

# 3. Mod List
In order to turn TPF into SSS:SE, you’ll need to disable the mods I do not use, then place the new mod folders into a **new separator underneath the TPF one**. For example, for the Gameplay Overhauls section, create a separator called `Gameplay Overhauls - SSS`, change its color to something that sticks out, and place it under `Gameplay Overhauls`.

## 3.1 Essential Mods
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/essential-mods/).

## 3.2 Fixes
I use all of the mods listed in [TPF’s corresponding section.](https://thephoenixflavour.com/tpf/mod-installation/fixes/)

I’ve updated instructions for the following mod:
### [powerofthree’s Tweaks](https://thephoenixflavour.com/tpf/mod-installation/fixes/#powerofthrees-tweakshttpswwwnexusmodscomskyrimspecialeditionmods51073tabfiles)
#### Additional Instructions
- Double-click **powerofthree’s Tweaks** in your mod order.
- Switch to the INI Files tab and select the **po3_Tweaks.ini**.
- In **Line 74**, change `Grabbing is Stealing =` to `true`.
- In **Line 78**, change `Load Door Activate Prompt =` to `2`.
- In **Line 80**, change `Exit Label =` to `Leave`.
- Hit **CTRL+S** to save your changes and close the window.
## 3.3 Tweaks
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/tweaks/) with the exception of:

(If using _Nordic UI_) **Better Dialogue Controls** - Included with _Nordic UI_.  
(If using _Nordic UI_) **Better MessageBox Controls** - Included with _Nordic UI_.

I’ve added the following mods to this section:
### [SSE Gameplay Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/41953?tab=files)
#### Download Instructions
- **Main Files:** Dynamic Timescale SE

#### Additional Instructions
- Double-click **SSE Gameplay Tweaks** in your mod order.
- Switch to the Text Files tab and select the **GamePlayTweaks.config.txt**.
- In **Line 29**, change `BlockPotionUse.Enabled =` to `true`.
- In **Line 32**, change `BlockPotionUse.BlockPotionInCombat =` to `false`.
- In **Line 38**, change `BlockPotionUse.BlockPoisonInCombat =` to `false`.
- In **Line 114**, change `CumulativeTrainingTimesPerLevel.Enabled =` to `true`.
- In **Line 126**, change `DisableAutoFullHeal.Enabled =` to `true`.
- In **Line 357**, change `TeammateDetection.Enabled =` to `true`.
- Hit **CTRL+S** to save your changes and close the window.

### [Reading is Good](https://www.nexusmods.com/skyrimspecialedition/mods/42026?tab=files)
#### Download Instructions
- **Main Files:** Reading Is Good SE

### [Container and Arrow Weight Restrictions](https://www.nexusmods.com/skyrimspecialedition/mods/13826?tab=files)
#### Download Instructions
- **Main Files:** Container and Arrow Weight Restrictions

#### Additional Instructions
- ESL-ify **Container and Arrow Weight Restrictions.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins))

## 3.4 Interface
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/interface/) with the exception of:

(If using _Nordic UI_) **Remove QuickSave Button from SkyUI System Menu** - Not compatible with _Nordic UI’s_ swf files.  
(If using _Nordic UI_) **Wider MCM Menu for SkyUI** - Not compatible with _Nordic UI’s_ swf files.  
(If using _Nordic UI_) **Favorite Things - Extended Favorites Menu for SkyUI** - Not compatible with _Nordic UI’s_ swf files.  
**RaceMenu** - You can leave this in if you want, but I removed it because (a) I don’t use it, really and (b) it causes harmless bloat that makes saving take longer over time.  
**SkyHUD - TPF Preset** - I have my own preset, of course.  
**moreHUD - TPF Preset** - See above.  
(If using _Nordic UI_) **SkyHUD - Alternate White Dot Crosshair** - Not compatible with _Nordic UI’s_ HUD swf file.  
**A Matter of Time - A Clock HUD Widget** - I’ve decided not to add UI elements needlessly.  
**A Matter of Time - Phoenix Preset** - See above.  
**KenMOD - Time On Loading Screen** - Again, an extra UI element that may be useful but ultimately unnecessary for me.

I’ve added the following mods to this section:
### [True Directional Movement - Modernized Third Person Gameplay](https://www.nexusmods.com/skyrimspecialedition/mods/51614?tab=files)
#### Download Instructions
- **Main Files:** True Directional Movement

### [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252?tab=files)
#### Download Instructions
- **Main Files:** SmoothCam

### [Slidikins’ SmoothCam Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Slidikins’ SmoothCam Preset

### [iHUD - SmoothCam Automated Compatibility Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51918)
#### Download Instructions
- **Main Files:** iHUD - SmoothCam Automated Compatibility Patch

### [Nordic UI](https://www.nexusmods.com/skyrimspecialedition/mods/49881?tab=files)
Completely optional, skip if you’re playing ultra wide.
#### Download Instructions
- **Main Files:** NORDIC UI (Final Design)

#### FOMOD Instructions
- **Main:** HUD (SkyHUD)
- **Main:** Boxes
- **Main:** Race Menu (Vanilla)
- <s>**Main:** Cursor</s>
- **Main:** Dialogue Menu
- **Main:** Favorite Menu
- **Main:** Icons
- **Main:** Pause Menu (Journal)
- **Main:** Map Markers
- **Main:** Skill Menu
- **Main:** Skill Menu 3D Visuals
- <s>**Main:** Start Menu</s>
- <s>**Main:** Start Menu 3D Background</s>
- **Main:** Game Menus
- **Main:** UI Sounds
- <s>**Main:** QuickLoot Patch</s>
- **Main:** TDM Patch
- <s>**Main:** SkyHUD Preset</s>
- **Loading Screen:** No Empty Background

### [SkyHUD - Slidikins’ Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) or [SkyHUD - Slidikins’ Nordic UI Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** SkyHUD - Slidikins' Preset (if you chose not to use _Nordic UI_)
- **Miscellaneous Files:** SkyHUD - Slidikins' Nordic UI Preset (if you use _Nordic UI_ above)

### [moreHUD - Slidikins’ Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** moreHUD - Slidikins' Preset

### [The Frozen North - iHUD Patch](https://www.nexusmods.com/skyrimspecialedition/mods/33068)
#### Download Instructions
- **Optional Files:** The Frozen North - IHUD Patch

### [Forget Spell](https://www.nexusmods.com/skyrimspecialedition/mods/51125?tab=files)
#### Download Instructions
- **Main Files:** Forget Spell

#### FOMOD Instructions
- **Game:** Skyrim Special Edition
- **Interface:** SkyUI

## 3.5 Graphics Baseline
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/graphics-baseline/).

## 3.6 Weather
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/weather/).

## 3.7 Lighting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/lighting/).

## 3.8 Visual FX
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/visual-fx/).

I’ve added the following mods to this section:

### [Enhanced Blood Textures - Transparency Fix for ENB](https://www.nexusmods.com/skyrimspecialedition/mods/2357/?tab=files)
#### Download Instructions
- **Miscellaneous Files:** enb square test alpha test test file v31

#### Additional Instructions
- Delete the following file(s) and / or folder(s):
  - `dD-Larger Splatter Size.esp`
  - `dD-Reduced Splatter Size.esp`

### [Just Blood - Dirt and Blood Lite](https://www.nexusmods.com/skyrimspecialedition/mods/46501?tab=files)
#### Download Instructions
- **Main Files:** Just Blood

### [Dirt and Blood HD Retexture](https://www.nexusmods.com/skyrimspecialedition/mods/44162?tab=files)
#### Download Instructions
- **Main Files:** Dirt and Blood HD Retexture

#### FOMOD Instructions
- **Resolution:** 2k
- **Blood Brightness:** Default
- **Plugin:** No

### [Splashes of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files)
#### Download Instructions
- **Main Files:** Splashes Of Skyrim - 1.2

## 3.9 Landscape
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/landscape/).

## 3.10 Trees & Plants
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/trees-plants/).

## 3.11 Architecture
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/architecture/).

## 3.12 Misc Structures
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/misc-structures/).

## 3.13 Interiors
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/interiors/).

## 3.14 Dungeons
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/dungeons/).

## 3.15 Clutter
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/clutter/).

## 3.16 Valuable Items
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/valuable-items/).

## 3.17 Food & Ingredients
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/food-ingredients/).

## 3.18 Apparel & Weapons
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/apparel-weapons/).

I’ve added the following mod to this section:
### [Elemental Staffs](https://www.nexusmods.com/skyrimspecialedition/mods/5319?tab=files)
#### Download Instructions
- **Main Files:** Elemental Staffs SE

## 3.19 Creatures
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/creatures/).

## 3.20 Appearance
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/appearance/).

I’ve updated instructions for the following mod:

### [Expressive Facegen Morphs](https://thephoenixflavour.com/tpf/mod-installation/appearance/#expressive-facegen-morphshttpswwwnexusmodscomskyrimspecialeditionmods35785tabfiles)
#### Additional Instructions
- Delete **Expressive Facegen Morphs.esl.** If you did not remove RaceMenu, you can skip deleting this.

## 3.21 Gameplay Overhauls
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/gameplay-overhauls/) with the exception of:

**Skyrim Uncapper - Adamant Arena** - Replaced by my own Uncapper preset, naturally.

I’ve added the following mods to this section:

### [Skyrim Uncapper - Slidikins’ Strenuous Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Skyrim Uncapper - Slidikins' Strenuous Skyrim

### [Survival (CC)](https://en.uesp.net/wiki/Skyrim:Survival_Mode)

### [Apothecary - Food Duration Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)
#### Download Instructions
- **Optional Files:** Apothecary - Food Duration Tweaks

#### Additional Instructions
- ESL-ify **Apothecary - Food Duration Tweaks.esp** with SSEEdit (instructions)

### [Apothecary Food - Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53236?tab=files)
#### Download Instructions
- **Main Files:** Apothecary Food - Survival Mode Patch

### [Conner's Survival Mode](https://www.nexusmods.com/skyrimspecialedition/mods/19152?tab=files)
#### Download Instructions
- **Main Files:** Conner’s Survival Mode

### [The Phoenix Flavour - Conner's Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/45830?tab=files)
#### Download Instructions
- **Main Files:** The Phoenix Flavour - Conner's Survival Mode Patch

## 3.22 Loot & Crafting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/loot-crafting/) with the exception of:

**Improvement Names Customized** - This functionality will get covered by _Item Durability_.

I’ve added the following mods to this section:

## [Item Durability](https://www.nexusmods.com/skyrimspecialedition/mods/42544?tab=files)
#### Download Instructions
- **Main Files:** Item Durability v3

#### Additional Instructions
- Double-click **Item Durability** in your mod order.
- Switch to the Text Files tab and select the **ItemDurability.config.txt**.
- In **Line 32**, change `WeaponHealthNames =` to `"0;0.01;-10;0.01;0.11;-9;0.11;0.21;-8;0.21;0.31;-7;0.31;0.41;-6;0.41;0.51;-5;0.51;0.61;-4;0.61;0.71;-3;0.71;0.81;-2;0.81;0.91;-1;1.01;1.11;+1;1.11;1.21;+2;1.21;1.31;+3;1.31;1.41;+4;1.41;1.51;+5;1.51;1.61;+6;1.61;1.71;+7;1.71;1.81;+8;1.81;1.91;+9;1.91;2.01;+10"`
- In **Line 42**, change `ArmorHealthNames =` to `"0;0.01;-10;0.01;0.11;-9;0.11;0.21;-8;0.21;0.31;-7;0.31;0.41;-6;0.41;0.51;-5;0.51;0.61;-4;0.61;0.71;-3;0.71;0.81;-2;0.81;0.91;-1;1.01;1.11;+1;1.11;1.21;+2;1.21;1.31;+3;1.31;1.41;+4;1.41;1.51;+5;1.51;1.61;+6;1.61;1.71;+7;1.71;1.81;+8;1.81;1.91;+9;1.91;2.01;+10"`
- In **Line 250**, change `ApplyToNPC =` to `True`
> The jumble of numbers on Lines 32 and 42 will change the regular tempering (and degradation) names to a -10 to +10 system, making it easier to tell exactly what level of quality a piece of equipment is at. This is what Improvement Names Customized accomplishes, but since that mod doesn’t account for degradation I chose to apply the feature here instead. These numbers aren’t 100% accurate on a cusp but it’ll be close enough for our purposes.

### [Honed Metal Updated](https://www.nexusmods.com/skyrimspecialedition/mods/51254?tab=files)
#### Download Instructions
- **Main Files:** Honed Metal SSE Updated
- **Update Files:** Honed Metal 1.21 Hotfix >> `merge with the first file`

### [Honed Metal Revoiced](https://www.nexusmods.com/skyrimspecialedition/mods/34393?tab=files)
#### Download Instructions
- **Main Files:** Honed Metal Revoiced (For Honed Metal SSE 1.2)

### [Rare Curios (CC)](https://en.uesp.net/wiki/Skyrim:Rare_Curios)
This adds new alchemy ingredients (and a couple of effects), as well as some other miscellaneous items. Completely optional, so skip it (and the patches) if you don’t have it.

### [The Phoenix Flavour - Rare Curios Patch](https://www.nexusmods.com/skyrimspecialedition/mods/45830?tab=files)
#### Download Instructions
- **Main Files:** The Phoenix Flavour - Rare Curios Patch

### [Apothecary - Rare Curios Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Apothecary - Rare Curios Patch

### [C.O.I.N. - Coins of Interesting Natures](https://www.nexusmods.com/skyrimspecialedition/mods/51439?tab=files)
#### Download Instructions
- **Main Files:** C.O.I.N.

#### FOMOD Instructions
- **Asset Selection:** Author’s Choice  
- **Auto-Conversion:** Enabled  
- <s>**Revisited Dungeons:** Dungeons - Revisited</s>
- <s>**Revisited Dungeons:** Bleak Falls Barrow - Revisited</s>
- <s>**Revisited Dungeons:** Ustengrav - Revisited</s>
- <s>**Other Patches:** Ancient Nord Armo(u)ry EXTREME</s>
- <s>**Other Patches:** Cutting Room Floor</s>
- <s>**Other Patches:** Dynamic Dungeon Loot (DDL) - Random Loot System</s>
- <s>**Other Patches:** Expanded Townsand Cities - Riverwood</s>
- <s>**Other Patches:** Legacy of the Dragonborn</s>
- <s>**Other Patches:** Lock Related Loot</s>
- <s>**Other Patches:** Radiance - Locations</s>
- <s>**Other Patches:** The Tools of Kagrenac</s>
- **Other Patches:** Weapons Armor Clothing and Clutter Fixes
- <s>**Other Patches:** Wintersun</s>
- <s>**Morrowloot:** None</s>
- <s>**Other Patches:** Complete Alchemy and Cooking Overhaul</s>
- **Other Patches:** Unofficial Skyrim Special Edition Patch

### [Open World Loot - C.O.I.N. Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51489?tab=files)
#### Download Instructions
- **Main Files:** OWL - COIN Patch

## 3.23 Non-Player Characters
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/non-player-characters/).

## 3.24 Improved Vanilla Quests
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/improved-vanilla-quests/).

I’ve added the following mods to this section:

### [Wergild Depreciation - Crime Bounty Reduction Over Time](https://www.nexusmods.com/skyrimspecialedition/mods/11452?tab=files)
#### Download Instructions
- **Main Files:** Wergild Depreciation

### [Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576?tab=files)
#### Download Instructions
- **Main Files:** Missives 2.03 SSE

### [Missives - Carriage and Ferry Travel Overhaul Patch](https://www.nexusmods.com/skyrimspecialedition/mods/44498?tab=files)
#### Download Instructions
- **Main Files:** Missives - Carriage and Ferry Travel Overhaul Patch

### [Missives - Notes Retexture](https://www.nexusmods.com/skyrimspecialedition/mods/46201?tab=files)
#### Download Instructions
- **Main Files:** Missives Notes Retexture

## 3.25 Combat & Encounters
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/combat-encounters/) with the exception of:

**Blade and Blunt - Vanilla Difficulty Modifiers** - C’mon now, did you really think we were turning this down?

I’ve added the following mods to this section:

### [Resistances and Weaknesses](https://www.nexusmods.com/skyrimspecialedition/mods/45253?tab=files)
#### Download Instructions
- **Main Files:** Resistances and Weaknesses - Main File

### [Enchantments and Potions Work for NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/37607?tab=files)
#### Download Instructions
- **Main Files:** Enchantments and Potions Work for NPCs - EPW4NPCs (MO2 Friendly Edition)

## 3.26 Miscellaneous
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/miscellaneous/) with the exception of:

**Viewable Faction Ranks** - You shouldn’t have to go into the MCM for any information after the initial setup.

I’ve added the following mod to this section:

### [Dynamic Timescale](https://www.nexusmods.com/skyrimspecialedition/mods/18922?tab=files)
#### Download Instructions
Main Files: Dynamic Timescale SE

## 3.27 Assorted Plugins
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/assorted-plugins/) with the exception of:

**Disable Follower Collision** - Getting stuck behind a follower in a hallway or door can be frustrating, but I don’t like the ability to phase through them at one’s convenience.

I’ve added the following mods to this section:

### [Crafting Skill Leveling Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/21727?tab=files)
#### Download Instructions
- **Main Files:** CraftingSkill v3

### [Don't Stay in the Water](https://www.nexusmods.com/skyrimspecialedition/mods/52164?tab=files)
#### Download Instructions
- **Main Files:** Don't Stay in The Water

## 3.28 Sound FX
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/sound-fx/).

## 3.29 Skeleton & Animations
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/) with the exception of:

**XP32 Maximum Skeleton Special Extended - Fixed Scripts** - The scripts aren’t being used in _XPMSSE_ so this is unnecessary.

I’ve updated instructions for the following mod:

### [XP32 Maximum Skeleton Special Extended (XPMSSE)](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/#xp32-maximum-skeleton-special-extended-xpmssehttpswwwnexusmodscomskyrimspecialeditionmods1988tabfiles)
#### Additional Instructions
- Delete the following file(s) and / or folder(s):
  - `interface\`
  - `scripts\`
  - `XPMSE.esp`
> This is mainly a change to allow for the removal of RaceMenu but it’s a chance I’d make regardless as I don’t utilize XPMSSE to its full extent. If you want to change weapon positions and all that, you can leave this untouched. In a later update I’ll add the plugin to loadorder.txt for those who use it.

I’ve added the following mods to this section:

### [Movement Behavior Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/38950?tab=files)
#### Download Instructions
- **Main Files:** Movement Behavior Overhaul SE - AIO

#### FOMOD Instructions
- **Behavior Trigger:** Non-Combat Only
- **Perk Options:** No Perk
- **Patch Options:** 360 Walk and Run Plus
- **Patch Options:** Combat Gameplay Overhaul

#### Additional Instructions
- Delete the following file(s) and / or folder(s):
  - `meshes\actors\character\animations`
  - `scripts\`
  - `MBO.esp`

### [Draw 2 - Dual Weapon Equip-Unequip Animations](https://www.nexusmods.com/skyrimspecialedition/mods/45579?tab=files)
#### Download Instructions
- **Main Files:** Draw 2

#### Additional Instructions
- Delete the following file(s) and / or folder(s):
  - Draw2.achlist
  - Draw2.bsa
  - Draw2.esp

### [EVG Conditional Idles](https://www.nexusmods.com/skyrimspecialedition/mods/34006?tab=files)
#### Download Instructions
- **Main Files:** EVG Conditional Idles

### [First Person Combat Animations Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/45177?tab=files)
#### Download Instructions
**Main Files:** FPCAO2 - SIZE MATTERS SE ALL-IN-ONE 2.01

## 3.30 Utilities
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/utilities/).

# 4. Finishing Up

## 4.1 Conflict Resolution Patch
### Download the [Conflict Resolution Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) here.
This second patch is necessary for resolving the very very few conflicts between SSS:SE and TPF. It also includes edits to Magic Effects similar to [No Edge Glow](https://www.nexusmods.com/skyrimspecialedition/mods/3205). This is done instead of simply including No Edge Glow so that I can better maintain it as I encounter edge shaders that may have been modded in. Finally, it makes the following GameSettings changes:

- **setgs fJumpFallHeightMin 250** (default 600)
- **setgs fJumpFallHeightMinNPC 250** (default 450)
- **setgs fMagicSkillCostScale 1** (default 0.5)
- **setgs fMagicCasterSkillCostMult 1** (default 0.5)

## 4.2 Load Order TXT
### Download [my updated loadorder.txt](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) here
For instructions on what to do with this, see [TPF’s section](https://thephoenixflavour.com/tpf/finalisation/wrapping-up/#load-order-txt) on it.

## 4.3 Controls Configuration

All controls changed from the Default:

**Auto Move:** Right Alt  
**Journal:** F4  
**Quick Inventory:** F2  
**Quick Magic:** F3  
**Quick Stats:** F1

## 4.3 MCM Configuration

### Cathedral Weathers
- Settings Panel
  - General Section
    - Configuration Spell: Disabled
  - Weather Section
    - Seasonal Perspective: Enabled

## Conner’s Survival Mode
- General Panel
  - Quality of Life Section
    - Shrine Gold Cost: 500
    - Enable Health Regen: Disabled

## Dynamic Timescale
- AutoSave Section
  - Reoccurring Time: 0 MIN
  - After picking a lock time: 0 SEC
  - After combat time: 0 SEC

## Favorite Howls Menu
- Revert Form: Enabled
- Night Eye: Enabled

## Honed Metal
- General Section
  - Crafting Cost Modifier: 0.60
  - Tempering Cost Modifier: 0.04
  - Enchanting Cost Modifier: 0.28

## Immersive HUD
- Activation Panel
  - Compass Activation Section
    - iHUD hotkey: Backspace
    - Key press toggles: Enabled
  - SkyUI Active Effects Section
    - Link ALL SkyUI Widgets: Enabled
- Options Panel
  - Stealth indicator enabled: Disabled
  - Enemy health indicator enabled: Disabled
  - Hide shout meter with compass: Enabled
  - Force crosshair to hide: Enabled
  - Enable fast fade of magicka: Enabled
  - Enable fast fade of stamina: Enabled
- Transparencies Panel
  - Compass: 60%
  - Magicka: 60%
  - Health: 60%
  - Stamina: 60%

## moreHUD
- Presets Panel
  - Save setting with FISS Section
    - Load User Settings?: Select

## Simple Smithing
- Settings Panel
  - Craftable Toggles Section
    - Allow Artefact Replication: Disabled
    - Allow Upgrade Unique Gear Levels: Disabled

## Sky UI
- General Panel
  - Item List Section
    - Font Size: Small
  - Active Effects HUD Section
    - Enabled: Disabled
- Controls Panel
  - Favorite Groups Section
    - Group 1: 9
    - Group 2: 0
    - Group 3: -
    - Group 4: =

## SmoothCam
- Presets Panel
  - Load Preset Section
    - Slot 3: Slidikins’ Strenuous Skyrim: Select

## Timing is Everything
- Extra Options Panel
  - Presets Section
    - Load Preset: Select
- Other Quests Panel
  - Misc Quests Section
    - Ebony Warrior: 50

## Trade & Barter
- Barter Rates Panel
  - Settings Section
    - Modify Barter Settings: Enabled

## True Directional Movement
- Target Lock Panel
  - Projectile Settings Section
    - Arrow Aim Mode: Free Aim
    - Missile Aim Mode: Free Aim
  - Controls Section
    - Toggle Target Lock Key: M3
    - Switch Targets with Mouse Movement: Disabled
- Target Lock Widget Panel
  - Visibility Settings Section
    - Show Target Bar: Disabled
    - Show Soft Target Bar: Disabled
  - Widget Settings Panel
    - Reticle Style: Simple Dot
  - Scale and Opacity Settings Section
    - Reticle Scale: 0.5
- Boss Bar Widget Panel
  - Visibility Settings Section
    - Show Boss Bar: Disabled

## Wergild Depreciation
- Set the Default Values Panel
  - Set the Default Values Section
    - Exile Required: Enabled

# 5. Gameplay Tips
As you can probably infer from the name of this addon, your adventure in Skyrim will have its difficult moments. Here are some tips that I’ve found useful for making the journey in one piece.

## 5.1 General Advice

### Bring a Follower
I know, some people prefer to be a lone wolf. However, having someone around to watch your back is invaluable. Your enemies will certainly have buddies in spades; even out the odds by bringing a friend of your own even if it’s just temporarily. When choosing a follower look for skills that complement your own. If you generally do well on the back lines, get a companion that can stand their ground up front. If you do best up close and personal, look for an archer or a mage to bring the heat from the rear. If the two of you fit the same ‘role’ you’ll often get in each other’s ways.

### Utilize Crafting
With Honed Metal, the only thing that keeps you from the benefits of Smithing and Enchanting is your coin pouch. Unless you’re saving up for something in particular, put your septims to use by getting a solid piece of equipment or tempering what you already have. Keep in mind that you’d need to pay extra for any materials that aren’t provided, so keep stock of crafting materials even if you aren’t a crafter yourself.

Alchemy is a beast unto itself. While investment will certainly boost the power and duration of your potions and poisons, the effects are nothing to scoff at even without perks. Alchemical ingredients are literally lying on the floor throughout your adventure as well! Grab a handful as you go, find the effects that complement your playstyle, and keep a few vials on hand for the tough spots. You never know when a 20% boost to your main skill will come in handy, after all!

## 5.2 Early Game (Level 1 - 10)

### Take it Easy and Start Small
You’ve just escaped Helgen by the skin of your teeth. You don’t have much to your name, and you don’t have nifty perks that deliver the pain to your enemies. Take a moment to collect yourself in town. Craft a bit and make a little money to get yourself started. The Skyrim Uncapper is configured to give less exp for your crafting skills, so there’s no need to worry about overleveling yourself out of the gate. There will be plenty of time to delve into dungeons later. Make sure you’re properly equipped now.

### Stay in Range of Whiterun
The urge to explore is strong but try to fight it off in the early game. There is plenty to do in Whiterun hold once you’ve reached Riverwood, and that content should get you to Level 10 without too many hitches. A Missives board can be found in Whiterun if you need additional tasks. Bleak Falls Barrow can be handled easily at Level 5, though you may want to wait until you’re closer to Level 10 before tackling Dragon Rising. Also, buy Breezehome. All of the other homes are more expensive and you’ll need someplace reliable to store your valuables until you come into money.

## 5.3 Mid Game (Level 10 - 30)

### Buy a Horse (or Two!)
Forget what I just said about staying local. It’s time to explore and get into the thick of it! Time passes fast on the overworld, however, so unless you want to spend all of daylight traveling from Point A to Point B, invest in a horse to shorten your travel times. And if you’re really going far I recommend making use of the carriages from time to time. Since your carry weight (and that of your follower) is halved, horses are also the best way to move a lot of supplies from one place to another.

### Join a Faction
Go find yourself a faction (e.g. The Companions) that suits your character and sign up. Their quests will support the skills you’re looking to improve. As you progress through the tier, consider signing up for the Stormcloaks or the Imperial Legion if you have a stake in the civil war. Their quests are less focused, but they’ll provide plenty of targets to practice on to level up further.

## 5.4 Late Game (Level 30 - 50)

### Utilize Crafting, Part Deux
Seriously, I can’t stress this enough. In the late game you may be dealing with areas that are scaled high above your Level 50 limit, some at that point long before you reach the cap. You’ll need every advantage you can get to bridge the gap, and most of those advantages are obtained through crafting. If you ignored that advice early on, now’s a good time to reconsider it. It might be time to make different equipment sets for different types of enemies, even.
