Latest update: **2022-11-07**  
Compatible with: **The Phoenix Flavour 4.15.5**

# 1. Initial Setup

## Prerequisites
This Installation Guide is written under the assumption that you have an unmodified copy of **The Phoenix Flavour (TPF)** of the version written above. It is also assumed that you are familiar with the tools introduced and provided by TPF. If you wish to use Wabbajack for the entire process, please use [these installation instructions](https://github.com/Amigoliath/Slidikins-Strenuous-Skyrim/blob/main/Wabbajack.md).

### Skyrim Official Files
This list uses the following Creations, all of which are freely available with Special Edition Version 1.6:
- [Survival Mode](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
- [Rare Curios](https://en.uesp.net/wiki/Skyrim:Rare_Curios)
- [Fishing](https://en.uesp.net/wiki/Skyrim:Fishing)

**The Phoenix Flavour** already includes the latter two of these Creations. In order to add Survival Mode:
- Navigate to the Data folder of your Steam installation of Skyrim Special Edition (`..\steamapps\common\Skyrim Special Edition\Data`)
- Copy `ccQDRSSE001-SurvivalMode.bsa` and `ccQDRSSE001-SurvivalMode.esl` from within that folder
- Navigate to your **Creation Club Content** TPF mod folder (`..\The Phoenix Flavour\mods\Creation Club Content`)
- Paste the two files into this folder
- If Mod Organizer 2 is currently open, hit F5 to refresh your modlist

## Mod Organizer 2
### SSS Profile
- Open the **Profile** settings in MO2 (Tools » Profiles or CTRL+P).
- The **The Phoenix Flavour** profile will be selected automatically (assuming you just finished installing it).
- Click **Copy** to set up a new profile based on **The Phoenix Flavour**.
- Select your new profile in the list.
- Click **Close** to exit the settings.
- In the profile list below the top left menu in MO2, select your new profile to switch to it.
> This new profile is separate from your TPF install. It uses its own directory for INIs and save files. This will allow you to switch back to TPF whenever you'd like.

## BethINI
- Close Mod Organizer 2.
- Go to `Your Modding Folder\Tools\BethINI`.
- Double-click **BethINI.exe**.

### BethINI - Basic
If you aren't already there, click the second tab, **Basic**.
- Enable **Always Active**.
> This will keep the game unpaused if you alt-tab away, giving a borderless windowed effect. Leave it disabled if you dislike this behavior.

### BethINI - Gameplay
Continue to the fourth tab, **Gameplay**.
- Enable **NPCs Use Ammo**.
> Archers will no longer have unlimited ammunition in fights. This will also affect followers.

### BethINI - Interface
Continue to the fifth tab, **Interface**.
- Enable **Dialogue Subtitles**.
- Disable **Show Quest Markers**.
> If you want to know where a quest objective is exactly, use Clairvoyance.

## Save Changes
- Return to the second tab, **Basic**, and click `Save and Exit`.
- Restart Mod Organizer 2.

# 2. Compatibility Notes
In order to turn TPF into SSS, you’ll need to **deactivate** the mods I do not use (marked at the top of each section), then place the new mods into a **new separator underneath the TPF one**. For example, for the Gameplay Overhauls section, create a separator called `Gameplay Overhauls - SSS` and place it under `Gameplay Overhauls` (and its mods).

The provided loadorder.txt and Conflict Resolution Patch in the Finalization section assumes that this method is followed for each modified section.

Furthermore, as of The Phoenix Flavour 4.15 there is now a **Difficulty Modifiers** section near the bottom of the modlist. Users have the option of disabling the mods within it for extra difficulty. My recommendation for SSS is to do just that; disable them for the intended experience. 

# 3. Mod Installation

## 3.1 Creation Club Patches
I use all of the mods listed in TPF’s corresponding section.

## 3.2 Essential Mods
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/essential-mods/).

## 3.3 Fixes
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/fixes/) with the exception of:

**Removed RaceMenu 0.4.16 Memory Leak Hotfix** - RaceMenu is no longer included in the modlist in its entirety so this is unnecessary.

**I’ve updated instructions for the following mod:**
### [powerofthree’s Tweaks](https://thephoenixflavour.com/tpf/mod-installation/fixes/#powerofthrees-tweakshttpswwwnexusmodscomskyrimspecialeditionmods51073tabfiles)
#### Additional Instructions
- Double-click **powerofthree’s Tweaks** in your mod order.
- Switch to the INI Files tab and select the **po3_Tweaks.ini**.
- In **Line 72**, change `No Attack Messages =` to `3`.
- In **Line 86**, change `Grabbing is Stealing =` to `true`.
- Hit **CTRL+S** to save your changes and close the window.

**I’ve added the following mods to this section:**
### [Vanilla Scripting Enhancements](https://www.nexusmods.com/skyrimspecialedition/mods/68139?tab=files)
#### Download Instructions
- **Main Files:** Loose Version

### [MFG Fix](https://www.nexusmods.com/skyrimspecialedition/mods/11669?tab=files)
#### Download Instructions
- **Main Files:** MfgFix

### [ENB Light Inventory Fix](https://www.nexusmods.com/skyrimspecialedition/mods/66411?tab=files)
#### Download Instructions
- **Main Files:** ELIF

### [Spiders of Solstheim - Transparency Fix](https://www.nexusmods.com/skyrimspecialedition/mods/60012?tab=files)
#### Download Instructions
- **Main Files:** Spiders of Solstheim - Transparency Fix

### [Moons and Stars](https://www.nexusmods.com/skyrimspecialedition/mods/73336?tab=files)
#### Download Instructions
- **Main Files:** Moons and Stars - Sky Overhaul SKSE

### [Shadow Boost](https://www.nexusmods.com/skyrimspecialedition/mods/73133?tab=files)
#### Download Instructions
- **Main Files:** Shadow Boost

### [Shadow Diffusion](https://www.nexusmods.com/skyrimspecialedition/mods/74632?tab=files)
#### Download Instructions
- **Main Files:** Shadow Diffusion

### [NVIDIA Reflex Support](https://www.nexusmods.com/skyrimspecialedition/mods/74498?tab=files)
#### Download Instructions
- **Main Files:** NVIDIA Reflex Support

### [Barter Limit Fix](https://www.nexusmods.com/skyrimspecialedition/mods/77173?tab=files)
#### Download Instructions
- **Main Files:** Barter Limit Fix

### [Aurora Fix](https://www.nexusmods.com/skyrimspecialedition/mods/77834?tab=files)
#### Download Instructions
- **Main Files:** Aurora Fix-


## 3.4 Tweaks
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/tweaks/).

**I’ve added the following mods to this section:**
### [SSE Gameplay Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/41953?tab=files)
#### Download Instructions
- **Main Files:** GameplayTweaks v5

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

### [Dynamic Collision Adjustment](https://www.nexusmods.com/skyrimspecialedition/mods/76783?tab=files)
#### Download Instructions
- **Main Files:** Dynamic Collision Adjustment

### [Reading is Good](https://www.nexusmods.com/skyrimspecialedition/mods/42026?tab=files)
#### Download Instructions
- **Main Files:** Reading Is Good SE

### [Container and Arrow Weight Restrictions](https://www.nexusmods.com/skyrimspecialedition/mods/13826?tab=files)
#### Download Instructions
- **Main Files:** Container and Arrow Weight Restrictions

#### Additional Instructions
- ESL-ify **Container and Arrow Weight Restrictions.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins))

### [Locks Are Just Locked](https://www.nexusmods.com/skyrimspecialedition/mods/42535?tab=files)
#### Download Instructions
- **Main Files:** Locks Are Just Locked

## 3.5 Interface
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/interface/) with the exception of:

**RaceMenu** - I removed it because (a) I don’t use it, really and (b) it causes harmless bloat that makes saving take longer over time. You can add it back in if you really want to, but you're on your own doing that. 
**Nordic UI - Shout Cooldown** - I prefer the widget that comes with the TrueHUD version of Nordic UI.  
**moreHUD - TPF Preset** - I have my own preset baked into the Config & Runtime Files.  
**A Matter of Time - A Clock HUD Widget** - I’ve decided not to add UI elements needlessly.  
**A Matter of Time - Phoenix Preset** - See above. 
**A Quality World Map** - Switched for A Clear Map of Skyrim and Other Worlds.  
**CoMAP - Common Marker Addon Project** - Incompatible with Nordic UI's map markers, which I like.  

**I’ve updated instructions for the following mods:**
### [NORDIC UI - Interface Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/49881?tab=files)
#### Download Instructions
- **Main Files:** NORDIC UI (Final Design)

#### FOMOD Instructions
- **Main:** HUD (SkyHUD)
- **Main:** Boxes
- **Main:** Race Menu (Vanilla)
- <s>**Main:** Cursor</s>
- <s>**Main:** Dialogue Menu</s>
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

> This is nearly identical to TPF's installation except it includes the Map Markers, UI Sounds and necessary TDM Patch.

### [Nordic UI - Miscellaneous Patches](https://www.nexusmods.com/skyrimspecialedition/mods/54102?tab=files)
#### Download Instructions
- **Main Files:** NORDIC UI - Miscellaneous Patches

#### FOMOD Instructions
- **moreHUD Inventory:** None
- **Stat Screen Colored Icons:** 2.4 style Icons
- **Even Better MessageBox Controls:** Install
- <s>**Extended Hotkey System:** Install</s>
- **MCM:** Wider MCM
- **Remove QuickSave from System Menu:** Install
- <s>**Loading Screen:** Install</s>
- <s>**Tween Menu:** Install</s>

### [TrueHUD](https://www.nexusmods.com/skyrimspecialedition/mods/62775?tab=files)
#### Download Instructions
- **Main Files:** TrueHUD (SE)

#### Additional Instructions
- ESL-ify **TrueHUD.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins))

**I’ve added the following mods to this section:**

### [NORDIC UI Markers](https://www.nexusmods.com/skyrimspecialedition/mods/72209?tab=files)
#### Download Instructions
- **Main Files:** NORDIC UI Markers (QUESTION UNDISCOVER MARK)

### [Nordic-Ish TrueHUD Recent Item Widget](https://www.nexusmods.com/skyrimspecialedition/mods/63212?tab=files)
#### Download Instructions
- **Update Files:** Nordic-Ish TrueHUD Recent Item Widget (Made by SwitchbackModding)

### [A Clear Map of Skyrim and Other Worlds](https://www.nexusmods.com/skyrimspecialedition/mods/56367?tab=files)
#### Download Instructions
- **Main Files:** A Clear Map of Skyrim and Other Worlds FOMOD - PART 1
- **Main Files:** ACMOS Road Generator Tool - PART 2

> Part 2 is required for adding roads on the world map after using SSELODGen. You can skip this step by downloading *Slidikins' Strenuous Skyrim - Terrain LOD* from the [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files).

#### FOMOD Instructions
- **DynDOLOD rules:** DynDOLOD 3
- **LOD Setup:** With DynDOLOD LOD32
- <s>**Other Worlds:** None</s>
- <s>**Optional Components:** None</s>
- <s>**Patches:** None</s>

### [SkyUI - Ghost Item Bug Fix](https://www.nexusmods.com/skyrimspecialedition/mods/49106?tab=files)
#### Download Instructions
- **Main Files:** SkyUI - Ghost Item Bug Fix

### [The Frozen North - iHUD Patch](https://www.nexusmods.com/skyrimspecialedition/mods/33068)
#### Download Instructions
- **Optional Files:** The Frozen North - IHUD Patch

### [Forget Spell](https://www.nexusmods.com/skyrimspecialedition/mods/51125?tab=files)
#### Download Instructions
- **Main Files:** Forget Spell

#### FOMOD Instructions
- **Game:** Skyrim Special Edition
- **Interface:** SkyUI

### [Simple Activate SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/56767?tab=files)
#### Download Instructions
- **Main Files:** Simple Activate SKSE

#### Additional Instructions
- Double-click **Simple Activate SKSE** in your mod order.
- Switch to the INI Files tab and select the **po3_SimpleActivateSKSE.ini**.
- In **Line 43**, change `Show Indicator Using Name =` to `false`.
- In **Line 52**, change `Show Indicator Using Name =` to `false`.
- In **Line 65**, change `Custom Locked Tag =` to ``.
- In **Line 68**, change `Show Indicator Using Name =` to `false`.
- In **Line 87**, change `Custom Indicator Color =` to `#4d4d4d`.
- Hit **CTRL+S** to save your changes and close the window.

## 3.6 Graphics Baseline
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/graphics-baseline/).

## 3.7 Seasons of Skyrim
I've added this section to TPF until it's officially adopted.

### [Seasonal Weathers Framework](https://www.nexusmods.com/skyrimspecialedition/mods/63562?tab=files)
#### Download Instructions
- **Main Files:** Seasonal Weathers Framework - 1.01

### [Seasonal Weathers Framework - Cathedral Weathers and Seasons](https://www.nexusmods.com/skyrimspecialedition/mods/63562?tab=files)
#### Download Instructions
- **Optional Files:** Seasonal Weathers Framework - Cathedral Weathers and Seasons

### [Seasons of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/62861?tab=files)
#### Download Instructions
- **Main Files:** Seasons of Skyrim SE

### [Seasons of Skyrim - Remove Unwanted Grass](https://www.nexusmods.com/skyrimspecialedition/mods/63476?tab=files)
#### Download Instructions
- **Main Files:** Seasons of Skyrim - Remove Unwanted Grass

### [Turn of the Seasons](https://www.nexusmods.com/skyrimspecialedition/mods/63623?tab=files)
#### Download Instructions
- **Main Files:** Turn of the Seasons

#### FOMOD Instructions
- **Optionals:** Icy Waterways
- **Optionals:** Invisible Mountain Slope Fix
- <s>**Patches:** Happy Little Trees</s>
- **Patches:** Fixed Mesh Lighting

### [Seasonal Aspen Trees](https://www.nexusmods.com/skyrimspecialedition/mods/63641?tab=files)
#### Download Instructions
- **Main Files:** Seasonal Aspen Trees

#### FOMOD Instructions
- **Textures:** 4K Textures
- **Bark:** Vanilla Bark Textures

### [Shrubs of Snow](https://www.nexusmods.com/skyrimspecialedition/mods/63463?tab=files)
#### Download Instructions
- **Main Files:** Shrubs of Snow

### [Seasonsal Aspen Trees - Shrubs of Snow Patch](https://www.nexusmods.com/skyrimspecialedition/mods/63641?tab=files)
#### Download Instructions
- **Optional Files:** Shrubs of Snow patch

### [Seasonal Aspen Trees - Turn of the Seasons Patch](https://www.nexusmods.com/skyrimspecialedition/mods/63641?tab=files)
#### Download Instructions
- **Optional Files:** Turn of the Seasons patch

## 3.8 Weather
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/weather/).

**I’ve added the following mods to this section:**

### [Splashes of Storms](https://www.nexusmods.com/skyrimspecialedition/mods/72115?tab=files)
#### Download Instructions
- **Main Files:** Splashes of Storms

## 3.9 Lighting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/lighting/).

## 3.10 Visual FX
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/visual-fx/).

**I've changed the instructions for the following mod:**

### [Enhanced Blood Textures](https://www.nexusmods.com/skyrimspecialedition/mods/2357/?tab=files)
#### Download Instructions
- **Main Files:** Enhanced Blood Textures

#### FOMOD Instructions
- **SPID Compatibility and Script Distance:** SPID Compatible
- <s>**Compatibility Patch:** Immersive Creatures</s>
- **Blood Size:** Default Splatter Size
- **Wounds (Optional):** Reduced Wound Size (Optional)
- **Drips (Optional):** Default
- **Screen Blood:** Default
- **Resolution and Color:** Reduced Res / Default Color
- **Alt. Blood Textures (Optional):** Reduced Res / Default Color

#### Additional Instructions
- ESL-ify **dD-Reduced Wound Size.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins)).

**I’ve added the following mods to this section:**

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

### [Wash That Blood Off 2](https://www.nexusmods.com/skyrimspecialedition/mods/62358?tab=files)
#### Download Instructions
- **Main Files:** Wash That Blood Off SE

### [Splashes of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files)
#### Download Instructions
- **Main Files:** Splashes Of Skyrim - 1.3

## 3.11 Landscape
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/landscape/) with the exception of:

**Assorted Mesh Fixes - SMIM - Really Blended Roads Patch** - Unnecessary with the updated *Skyland - Solitude*

**I’ve added the following mod to this section:**

### [IcyCollisions](https://www.nexusmods.com/skyrimspecialedition/mods/70656?tab=files)
#### Download Instructions
- **Main Files:** IcyCollisionsSkyrimRemastered

### [Snowy Surfaces Sound Collision and Aesthetics](https://www.nexusmods.com/skyrimspecialedition/mods/76257?tab=files)
#### Download Instructions
- **Main Files:** Snowy Surfaces Sound Collision and Aesthetics (Majestic Mountains version)

### [FYX - Water Splash](https://www.nexusmods.com/skyrimspecialedition/mods/77971?tab=files)
#### Download Instructions
- **Main Files:** FYX - Water Splash - RWT2

## 3.12 Trees & Plants
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/trees-plants/).

## 3.13 Architecture
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/architecture/).

**I’ve added the following mod to this section:**

### [Unique Markarth Doors](https://www.nexusmods.com/skyrimspecialedition/mods/62969?tab=files)
#### Download Instructions
- **Main Files:** Unique Markarth Doors

### [Whiterun Objects SMIMed](https://www.nexusmods.com/skyrimspecialedition/mods/69125?tab=files)
#### Download Instructions
- **Main Files:** Whiterun Objects SMIMed

### [3D Trellis Improved - Gildergreen Plaza](https://www.nexusmods.com/skyrimspecialedition/mods/75882?tab=files)
#### Download Instructions
- **Main Files:** 3D Trellis Improved - Gildergreen Plaza

## 3.14 Misc Structures
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/misc-structures/).

## 3.15 Interiors
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/interiors/).

**I’ve added the following mods to this section:**

### [Skyrim Objects SMIMed - Noble Furniture](https://www.nexusmods.com/skyrimspecialedition/mods/77499?tab=files)
#### Download Instructions
- **Main Files:** Skyrim Objects SMIMed - Noble Furniture

## 3.16 Dungeons
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/dungeons/).

## 3.17 Clutter
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/clutter/).

## 3.18 Valuable Items
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/valuable-items/).

## 3.19 Food & Ingredients
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/food-ingredients/).

## 3.20 Apparel & Weapons
I use all of the mods from the corresponding section of the upcoming TPF 5.0 release.

**I’ve added the following mod to this section:**
### [Elemental Staffs](https://www.nexusmods.com/skyrimspecialedition/mods/5319?tab=files)
#### Download Instructions
- **Main Files:** Elemental Staffs SE
- **Optional Files:** Elemental Staffs SE Basic » `merge with the first file`
- **Optional Files:** Mysticism 2 Patch

#### Additional Instructions
- ESL-ify **Elemental_Staffs_Patch_Mysticism.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins)).

## 3.21 Creatures
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/creatures/).

## 3.22 Appearance
I use all of the mods from the corresponding section of the upcoming TPF 5.0 release.

## 3.23 Gameplay Overhauls
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/gameplay-overhauls/) with the exception of:

**Adamant - Shrines and Amulets** - Superceded by _Pilgrim - A Religion Overhaul_  
**Skyrim Uncapper - Adamant Arena** - Replaced by my own Uncapper preset later, naturally.

**I’ve added the following mods to this section:**

### [Pilgrim - A Religion Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/54099?tab=files)
#### Download Instructions
- **Main Files:** Pilgrim - A Religion Overhaul

### [Survival Mode Improved](https://www.nexusmods.com/skyrimspecialedition/mods/56374?tab=files)
#### Download Instructions
- **Main Files:** Survival Mode Improved

## 3.24 Loot & Crafting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/loot-crafting/).

**I’ve added the following mods to this section:**

[Armor and Clothing Extension - Spell Perk Item Distributor Patch](https://www.nexusmods.com/skyrimspecialedition/mods/19002?tab=files)
#### Download Instructions
- **Optional Files:** Armor and Clothing Extension - Spell Perk Item Distributor (SPID) Patch

### [Apothecary - Food and Drink Addon - Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Apothecary - Food and Drink Addon - Survival Mode Patch

### [Honed Metal](https://www.nexusmods.com/skyrimspecialedition/mods/61015?tab=files)
#### Download Instructions
- **Main Files:** Honed Metal SSE

### [Honed Metal Revoiced](https://www.nexusmods.com/skyrimspecialedition/mods/34393?tab=files)
#### Download Instructions
- **Main Files:** Honed Metal Revoiced (For Honed Metal SSE 1.2)

### [Simple Degradation](https://www.nexusmods.com/skyrimspecialedition/mods/74790?tab=files)
#### Download Instructions
- **Main Files:** Simple Degradation
- **Optional Files:** NPC Tempering

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

### [C.O.I.N. - Adamant and Hand to Hand Patches](https://www.nexusmods.com/skyrimspecialedition/mods/76605?tab=files)
#### Download Instructions
- **Main Files:** C.O.I.N. Hand to Hand Patch

### [C.O.I.N. - Merchant Exchange](https://www.nexusmods.com/skyrimspecialedition/mods/70644?tab=files)
#### Download Instructions
- **Main Files:** C.O.I.N. - Merchant Exchange

### [Open World Loot - C.O.I.N. Patch](https://www.nexusmods.com/skyrimspecialedition/mods/60889?tab=files)
#### Download Instructions
- **Main Files:** OWL - COIN

## 3.25 Non-Player Characters
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/non-player-characters/) with the exception of:

**Immersive Patrols Simplified** - No longer necessary with _Immersive Patrols_ v3.0 

**I’ve updated instructions for the following mod:**
### [Immersive Patrols](https://thephoenixflavour.com/tpf/mod-installation/non-player-characters/#immersive-patrolshttpswwwnexusmodscomskyrimspecialeditionmods718tabfiles)
#### Download Instructions
- **Main Files:** Immersive Patrols (Lite)

**I’ve added the following mods to this section:**

### [NPCs Wear Amulets of Mara](https://www.nexusmods.com/skyrimspecialedition/mods/66125?tab=files)
#### Download Instructions
- **Main Files:** NPCs Wear Amulets of Mara 2.0

### [NPCs React to Necromancy](https://www.nexusmods.com/skyrimspecialedition/mods/70428?tab=files)
#### Download Instructions
- **Main Files:** NPCs React to Necromancy

### [Civil War Lines Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/77566?tab=files)
#### Download Instructions
- **Main Files:** Civil War Lines Expansion

### [Afterlife - Resurrected](https://www.nexusmods.com/skyrimspecialedition/mods/55051?tab=files)
#### Download Instructions
- **Main Files:** Reverb Interior Sounds Expansion (1.3.0)

### [Ashlander Nomads Names](https://www.nexusmods.com/skyrimspecialedition/mods/73315?tab=files)
#### Download Instructions
- **Main Files:** Afterlife

### [Daedric Names](https://www.nexusmods.com/skyrimspecialedition/mods/74055?tab=files)
#### Download Instructions
- **Main Files:** Daedric Names

### [Dovah Names](https://www.nexusmods.com/skyrimspecialedition/mods/74053?tab=files)
#### Download Instructions
- **Main Files:** Dovah Names

### [Reachmen Tribes Names](https://www.nexusmods.com/skyrimspecialedition/mods/73312?tab=files)
#### Download Instructions
- **Main Files:** Reachmen Tribes Names
- **Optional Files:** Forsworn Matriachs » `merge with the first file`

### [Tamrielic Names](https://www.nexusmods.com/skyrimspecialedition/mods/73153?tab=files)
#### Download Instructions
- **Main Files:** Tamrielic Names

## 3.26 Improved Vanilla Quests
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/improved-vanilla-quests/).

**I’ve added the following mods to this section:**

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

## 3.27 Combat & Encounters
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/combat-encounters/) with the exception of:

**Blade and Blunt - Vanilla Difficulty Modifiers** - C’mon now, did you really think we were turning this down?
**Briraka's Draugr Overhaul** - Updated to Haugbui - A Draugr Overhaul
**Briraka's Draugr Overhaul - WACCF Patch** - See above
**Briraka's Draugr Overhaul - High Quality Shield Textures** - See above
**Open World Loot - Ancient Nord Stalhrim and Briraka's Draugr Overhaul Patch** - See above

**I’ve added the following mods to this section:**

### [Haugbui - A Draugr Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/26188?tab=files)
#### Download Instructions
- **Main Files:** Haugbui - A Draugr Overhaul
- **Optional Files:** Haugbui - SimonRim Patch
- **Optional Files:** Haugbui - CC Fishing Patch
- **Optional Files:** Haugbui - WACCF Patch
- **Miscellaneuous Files:** Better Shaped Weapons Patch

### [Resistances and Weaknesses](https://www.nexusmods.com/skyrimspecialedition/mods/45253?tab=files)
#### Download Instructions
- **Main Files:** Resistances and Weaknesses - Main File

### [Enchantments and Potions Work for NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/37607?tab=files)
#### Download Instructions
- **Main Files:** Enchantments and Potions Work for NPCs - EPW4NPCs (MO2 Friendly Edition)

### [NPCs Learn Skills and Spells](https://www.nexusmods.com/skyrimspecialedition/mods/77342?tab=files)
#### Download Instructions
- **Main Files:** NPCs Learn Skills and Spells

### [STAYDOWN](https://www.nexusmods.com/skyrimspecialedition/mods/41228?tab=files)
#### Download Instructions
- **Main Files:** STAYDOWN - LIGHT

### [Dynamic Weather and Time Based Detection](https://www.nexusmods.com/skyrimspecialedition/mods/62546?tab=files)
#### Download Instructions
- **Main Files:** Dynamic Weather and Time Based Detection

### [Wait Your Turn - Enemy Circling Behaviour](https://www.nexusmods.com/skyrimspecialedition/mods/65091?tab=files)
#### Download Instructions
- **Main Files:** Wait Your Turn - Enemy Circling Behaviour

### [Quintessential Quivers](https://www.nexusmods.com/skyrimspecialedition/mods/77860?tab=files)
#### Download Instructions
- **Main Files:** Quintessential Quivers

## 3.28 Miscellaneous
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/miscellaneous/) with the exception of:

**Misc Tweaks - More Expensive Inns** - Covered by _Coherent Inns Prices_  
**Misc Tweaks - Shrines Don’t Cure Diseases** - Superceded by _Pilgrim - A Religion Overhaul_  
**Viewable Faction Ranks** - You shouldn’t have to go into the MCM for any information after the initial setup.  
**Wearable Lanterns** - The game has plenty of lighting options that a two-hander or dual wielder can utilize instead of a torch.
**Wearable Lanterns - Patch** - For Wearable Lanterns, which has been removed.
**ENB Particle Light for Wearable Lanterns** - For Wearable Lanterns, which has been removed.

**I’ve added the following mod to this section:**

### [Coherent Inns Prices](https://www.nexusmods.com/skyrimspecialedition/mods/55207?tab=files)
#### Download Instructions
- **Main Files:** Coherent Inns Prices

#### Additional Instructions
- Double-click **Coherent Inns Prices** in your mod order.
- Switch to the **Filetree** tab and rename the plugin:
  - CoherentInnsPrices.esl » CoherentInnsPrices.esp

### [Dynamic Mercenary Fees](https://www.nexusmods.com/skyrimspecialedition/mods/45677?tab=files)
#### Download Instructions
- **Main Files:** Dynamic Mercenary Fees

### [Dynamic Timescale](https://www.nexusmods.com/skyrimspecialedition/mods/18922?tab=files)
#### Download Instructions
- **Main Files:** Dynamic Timescale SE

### [Sensible Bribes](https://www.nexusmods.com/skyrimspecialedition/mods/55450?tab=files)
#### Download Instructions
- **Main Files:** Sensible Bribes

### [Random Barrel Roll](https://www.nexusmods.com/skyrimspecialedition/mods/78195?tab=files)
#### Download Instructions
- **Main Files:** Random Barrel Roll

## 3.29 Assorted Plugins
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/assorted-plugins/) with the exception of:

**Sales Overflow Solved** - Covered by _Barter Limit Fix_  

**I’ve added the following mods to this section:**

### [Crafting Skill Leveling Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/21727?tab=files)
#### Download Instructions
- **Main Files:** CraftingSkill v3

#### Additional Instructions
- Double-click **Crafting Skill Leveling Overhaul** in your mod order.
- Switch to the Text Files tab and select the **CraftingSkill.config.txt**.
- In **Line 316**, change `AlchemyXPMult =` to `1`.
- Hit **CTRL+S** to save your changes and close the window.

### [Don't Stay in the Water](https://www.nexusmods.com/skyrimspecialedition/mods/52164?tab=files)
#### Download Instructions
- **Main Files:** Don't Stay in The Water

### [Immersive Equipment Displays](https://www.nexusmods.com/skyrimspecialedition/mods/62001?tab=files)
#### Download Instructions
- **Main Files:** Immersive Equipment Displays

## 3.30 Sound FX
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/sound-fx/).

**I’ve added the following mods to this section:**

### [Regional Sounds Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/77829?tab=files)
#### Download Instructions
- **Main Files:** Regional Sounds Expansion (1.6.0)
- **Optional Files:** Replacer Plugin for Audio Overhaul for Skyrim Users » `merge with the first file`

### [Reverb Interior Sounds Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/77947?tab=files)
#### Download Instructions
- **Main Files:** Reverb Interior Sounds Expansion (1.3.0)

## 3.31 Controls & Camera
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/controls-camera/).

**I’ve updated instructions for the following mod:**
### [Alternate Conversation Camera Plus](https://www.nexusmods.com/skyrimspecialedition/mods/40722?tab=files)
#### Additional Instructions
- Double-click **Alternate Conversation Camera Plus** in your mod order.
- Switch to the INI Files tab and select the **AlternateConversationCamera.ini**.
- In **Line 26**, change `bSwitchTarget=` to `0`.
- In **Line 73**, change `bEnableHUDMessagePositioning` to `1`.
- Hit **CTRL+S** to save your changes and close the window.

**I’ve added the following mods to this section:**
### [True Directional Movement - Modernized Third Person Gameplay](https://www.nexusmods.com/skyrimspecialedition/mods/51614?tab=files)
#### Download Instructions
- **Main Files:** True Directional Movement

### [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252?tab=files)
#### Download Instructions
- **Main Files:** SmoothCam

#### FOMOD Instructions
- **Version:** SmoothCam AVX
- **Select Plugin Type:** ESL

#### Additional Instructions
- Double-click **SmoothCam** in your mod order.
- Switch to the **Filetree** tab and rename the plugin:
  - SmoothCam.esl » SmoothCam.esp

### [Better Third Person Selection](https://www.nexusmods.com/skyrimspecialedition/mods/64339?tab=files)
#### Download Instructions
- **Main Files:** Better Third Person Selection (SE)

## 3.32 Skeleton & Animations
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/) with the exception of:

**XP32 Maximum Skeleton Special Extended - Fixed Scripts** - The scripts aren’t being used in _XPMSSE_ so this is unnecessary.

**I’ve updated instructions for the following mods:**

### [XP32 Maximum Skeleton Special Extended (XPMSSE)](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/#xp32-maximum-skeleton-special-extended-xpmssehttpswwwnexusmodscomskyrimspecialeditionmods1988tabfiles)
#### FOMOD Instructions
- **Animation Rig Map:** No Physics
- **Character Creation:** None
- **Weapon Style Randomizer for NPCs:** None
- **Animation Variants:** *leave everything on None*
- **First Person Animation - Axes:** <s>Axes on Back</s>
- **First Person Animation - Swords:** None
- **Mounted Combat Animation - Axes:** <s>Axes on Back</s>
- **Mounted Combat Animation - Bow:** <s>Belt-Fastened Quiver</s>
- **Mounted Combat Animation - Sword:** None
- **The Joy of Perspective:** None
- **Schlongs of Skyrim:** None » `defaults to SOS, set to None`
- **Deadly Mutilation:** None
- **Enderal:** None
> This is mainly a change to allow for the removal of RaceMenu but it’s a chance I’d make regardless as I don’t utilize XPMSSE to its full extent. If you want to change weapon positions and all that, you can leave this untouched.

### [Simple Dual Sheath](https://www.nexusmods.com/skyrimspecialedition/mods/50049?tab=filess)
#### Additional Instructions
- Double-click **Simple Dual Sheath** in your mod order.
- Switch to the INI Files tab and select the **SimpleDualSheath.ini**.
- In **Line 75**, change `EquipLeft=` to `true`.
- Hit **CTRL+S** to save your changes and close the window.

**I’ve added the following mods to this section:**

### [Draw 2 - Dual Weapon Equip-Unequip Animations](https://www.nexusmods.com/skyrimspecialedition/mods/45579?tab=files)
#### Download Instructions
- **Main Files:** Draw 2

### [EVG Animation Variance](https://www.nexusmods.com/skyrimspecialedition/mods/38534?tab=files)
#### Download Instructions
- **Main Files:** EVG Animation Variance

#### FOMOD Instructions
- Page 1: Install Type
  - **Options:** Recommended

### [EVG Conditional Idles](https://www.nexusmods.com/skyrimspecialedition/mods/34006?tab=files)
#### Download Instructions
- **Main Files:** EVG Conditional Idles

### [Gesture Animation Remix](https://www.nexusmods.com/skyrimspecialedition/mods/64420?tab=files)
#### Download Instructions
- **Main Files:** Gesture Animation Remix (DAR) - main archive

### [NPC Animation Remix](https://www.nexusmods.com/skyrimspecialedition/mods/63471?tab=files)
#### Download Instructions
- **Main Files:** NPC Animation Remix - Main archive (no looped idles) - DAR

### [Conditional Expressions - Subtle Face Animations](https://www.nexusmods.com/skyrimspecialedition/mods/45148?tab=files)
#### Download Instructions
- **Main Files:** Conditional Expressions

### [Tools Not Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/70117?tab=files)
#### Download Instructions
- **Main Files:** Tools not weapons DAR animations

### [Ice Skating Fixed For Real](https://www.nexusmods.com/skyrimspecialedition/mods/55417?tab=files)
#### Download Instructions
- **Main Files:** EVE - Ice skating fixed for real - No more attack skating movement

### [Immersive Equipping Animations](https://www.nexusmods.com/skyrimspecialedition/mods/77187?tab=files)
#### Download Instructions
- **Main Files:** Immersive Equipping Animations

### [Read the Room](https://www.nexusmods.com/skyrimspecialedition/mods/77605?tab=files)
#### Download Instructions
- **Main Files:** Read the Room
- **Optional Files:** Immersive Equipping Animations Patch » `merge with the first file`

## 3.33 Utilities
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/utilities/).

**I’ve added the following mods to this section:**

### [Keyword Item Distrubtor](https://www.nexusmods.com/skyrimspecialedition/mods/55728?tab=files)
#### Download Instructions
- **Main Files:** Keyword Item Distributor

### [Base Object Swapper](https://www.nexusmods.com/skyrimspecialedition/mods/60805?tab=files)
#### Download Instructions
- **Main Files:** Base Object Swapper SE

### [NPCs Names Distributor](https://www.nexusmods.com/skyrimspecialedition/mods/73081?tab=files)
#### Download Instructions
- **Main Files:** NPCs Names Distributor

# 4. Finalization

## 4.1 Conflict Resolution Patch
- Create a **FINAL PATCHES - SSS** separator in Mod Organizer 2
- Download the [Conflict Resolution Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) from the guide's Nexus page.
- Install it as usual, place it last below a **FINAL PATCHES - SSS** separator (which you should create), and activate it.
> This second patch is necessary for resolving the few conflicts between SSS and TPF. It also includes edits to Magic Effects similar to _[No Edge Glow](https://www.nexusmods.com/skyrimspecialedition/mods/3205)_. This is done instead of simply including _No Edge Glow_ so that I can better maintain it as I encounter edge shaders that may have been modded in. Finally, it makes a few GameSettings changes to make falling more hazardous.

## 4.2 Configuration & Runtime Files
- Download the [Configuration & Runtime Files](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) from the guide's Nexus page.
- Install it as usual and place it below the **------------------------------** separator (which you should create if it doesn't exist), and activate it.
> This allows you to skip the **MCM Configuration** section completely. There's a chance that additional files will appear in your Overwrite folder after your first launch. Feel free to drag those into this mod. (Beyond that will be crash logs, but those hopefully shouldn't happen.)

## 4.3 Load Order TXT
- Close Mod Organizer 2.
- Download the [Universal Lord Order TXT](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) from the guide's Nexus page.
- Open the archive and extract the **loadorder.txt** to `Mod Organizer 2\profiles\Slidikins' Strenuous Skyrim`.
- Restart Mod Organizer 2 and the changes will be applied.

After applying the loadorder.txt and restarting MO2, there should be no plugins below the The Phoenix Flavour - Facegen.esp in the load order (right pane).

If there are other plugins below the Facegen plugin, you either made a mistake during the mod installation, or a mod was updated and the loadorder.txt is not accounting for it yet. Go back to the mod(s) in question (they will be highlighted in the mod order when you click on the plugin in the load order) and re-install them according to the instructions in the guide.

If you are unable to resolve all issues, please join us on Discord and post your Modwat.ch link or a picture of the bottom of your load order in the `#tpf-addons-support` channel.

## 4.3 Nemesis

### Nemesis Output Folder
- In Mod Organizer 2, click the tools icon above your mod order and select **Create empty mod**.
- Rename the new mod folder to **Slidikins' Strenuous Skyrim - Nemesis Output**.
- Drag the new empty mod (displayed in grey italics) below the **PATCHER OUTPUT** separator and activate it.

### Edit Nemesis Settings
- Open the Executables window in Mod Organizer 2 (Tools > Executables or CTRL + E).
- Click **Nemesis** in the left panel.
- Check the **Create files in mod instead of overwrite** checkbox and select **Slidikins' Strenuous Skyrim - Nemesis Output** from the drop down menu.
- Click OK to close the Tools window.

### Generate Nemesis

- Run **Nemesis** through Mod Organizer 2.
- There will be two warnings about missing (not yet generated) cache, click **OK** to both.
- Click the **Update Engine** button and wait for the process to be completed.
- When it’s done, check the **Unarmed Scaling Unlocked** box.
- Also check the **Precision** box.
- Also check the **Ice Skating Fixed for Real** box.
- Also check the **Jump Behavior Overhaul** box.
- Also check the **True Directional Movement - 360 Horse Archery** box.
- Also check the **True Directional Movement - Procedural Leaning** box.
- Finally, check the **True Directional Movement - Headtracking** box.
- Click the big Launch Nemesis Behavior Engine button.
- Nemesis will eventually return `Behavior generation complete` and you can close the tool.
- Back in Mod Organizer 2, press F5 to refresh and you can see that files were added to the **Slidikins' Strenuous Skyrim - Nemesis Output** mod folder.
- Deactivate the old **Nemesis Output** mod in the left pane.

# 5. Configuration

## 5.1 Controls

All controls changed from the Default:

**Journal:** `F4`  
**Quick Inventory:** `F2`  
**Quick Magic:** `F3`  
**Quick Stats:** `F1`

## 5.2 Mod Configuration

> **NOTE:** If you downloaded the _Configuration & Runtime Files_ from step 4.2 (or used Wabbajack), this step is unnecessary. All of the configurations have been made by default. However, this section has been left in for those who want to know some of the changes. If a mod has been pre-configured by TPF, it is not listed here.

### Dynamic Timescale
- **AutoSave** Section
  - Reoccurring Time: `0 MIN`
  - After picking a lock time: `0 SEC`
  - After combat time: `0 SEC`

### Honed Metal
- **General** Section
  - Crafting Cost Modifier: `0.80`
  - Tempering Cost Modifier: `0.05`
  - Enchanting Cost Modifier: `0.28`

### moreHUD
- **Presets** Panel
  - **Save setting with FISS** Section
    - Load User Settings?: `Select`

### Sky UI
- **General** Panel
  - **Item List** Section
    - Font Size: `Small`
  - **Active Effects** HUD Section
    - Enabled: `Disabled`
- **Controls** Panel
  - **Favorite Groups** Section
    - Group 1: `9`
    - Group 2: `0`
    - Group 3: `-`
    - Group 4: `=`

### Timing is Everything
- **Extra Options** Panel
  - **Presets** Section
    - Load Preset: `Select`
- **Other Quests** Panel
  - **Misc Quests** Section
    - Ebony Warrior: `50`

### True Directional Movement
- **General** Panel
  - **General Settings** Section
    - Directional Movement (Drawn): `Disabled`
- **Target Lock** Panel
  - **Projectile Settings** Section
    - Arrow Aim Mode: `Free Aim`
    - Missile Aim Mode: `Free Aim`
  - **Controls** Section
    - Toggle Target Lock Key: `M3`
    - Switch Targets with Mouse Movement: `Disabled`
- **HUD** Panel
  - **Target Lock Reticle Settings** Section
    - Reticle Style: `Dot`
    - Reticle Scale: `0.5`

### Wergild Depreciation
- **Set the Default Values** Panel
  - **Set the Default Values** Section
    - Exile Required: `Enabled`
