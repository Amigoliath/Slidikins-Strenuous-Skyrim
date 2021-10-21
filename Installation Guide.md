Latest update: **2021-10-18**  
Compatible with: **The Phoenix Flavour 4.8.0.4**

# 1. Initial Setup

## Prerequisites
This Installation Guide is written under the assumption that you have an unmodified copy of **The Phoenix Flavour (TPF)** of the version written above. It is also assumed that you are familiar with the tools introduced and provided by TPF. For Wabbajack users, please use [these installation instructions](https://github.com/Amigoliath/Slidikins-Strenuous-Skyrim/blob/main/Wabbajack.md).

## Mod Organizer 2
### SSS Profile
- Open the **Profile** settings in MO2 (Tools » Profiles or CTRL+P).
- The **The Phoenix Flavour** profile will be selected automatically (assuming you just finished installing it).
- Click **Copy** to set up a new profile based on **The Phoenix Flavour**.
- Enter **Slidikins' Strenuous Skyrim** as the name.
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

## 2.1 TPF-X Addons

With the release of TPF 4.5, Phoenix now offers several “addon” modules. These are entirely optional modules that can enhance TPF in different ways. I’ve jotted some quick notes on how I feel about each section in case you were wondering, but ultimately they should all be compatible with the mods chosen in SSS:SE. Install any TPF-X mod that you like, just mind the instructions provided by Phoenix.

**Note:** Modules that are not included in the `loadorder.txt` will need to be placed manually after finishing the guide. 

### [Interface](https://thephoenixflavour.com/tpf-x/installation/interface/)
**Notes:** This section contains a number of mods I explicitly chose to exclude from SSS:SE and therefore doesn’t fit the intended UI of this fork.  
**Compatibility:** Compatible, but not recommended for this guide.

### [Gameplay Tweaks](https://thephoenixflavour.com/tpf-x/installation/gameplay-tweaks/)
**Notes:** I like the combat as it is in base TPF so I skipped this one. These mods don’t go against the design of SSS:SE, but they don’t enhance it either.  
**Compatibility:** Compatible, will lower the difficulty of the game.

### [New Gear](https://thephoenixflavour.com/tpf-x/installation/new-gear/)
**Notes:** In the past I was adamant against adding new gear but Phoenix is pretty selective on what she adds. I trust her judgement so I’ve added it for now.  
**Compatibility:** Compatible, recommended and included in loadorder.txt.

### [New Companions](https://thephoenixflavour.com/tpf-x/installation/new-companions/)
**Notes:** I don’t like adding companions to my game. Inigo and Lucien won’t ruin the balance of SSS:SE, but they will spoil you when it comes to followers.  
**Compatibility:** Compatible.

### [Player Homes](https://thephoenixflavour.com/tpf-x/installation/player-homes/)
**Notes:** Similar to the Companions above, Elianora’s homes tend to outshine the vanilla selection. For that reason I don’t add them, but you’re welcome to.  
**Compatibility:** Compatible.

### [New Music](https://thephoenixflavour.com/tpf-x/installation/new-music/)
**Notes:** If you’re tired of the soundtrack, this is a good way to add more variety to the game. Most, if not all of it, fits in with the existing themes. This used to be in TPF, so I’ve kept it in my order.  
**Compatibility:** Compatible, recommended and included in loadorder.txt.

### [Miscellaneous](https://thephoenixflavour.com/tpf-x/installation/miscellaneous/)
**Notes:** These mods are entirely up to you. I saw no reason to add any of them to my game but your preference may be different.  
**Compatibility:** Possibly incompatible with Apothecary's additions.

### [AllGud](https://thephoenixflavour.com/tpf-x/installation/allgud/)
**Notes:** If you want favorited items to be visible, this is what you need. Otherwise, Simple Dual Sheath is fine for adding left-handed sheaths to characters. This also used to be in TPF.  
**Compatibility:** Compatible.

# 3. Mod Installation

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
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/tweaks/).

I’ve added the following mods to this section:
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

### [Reading is Good](https://www.nexusmods.com/skyrimspecialedition/mods/42026?tab=files)
#### Download Instructions
- **Main Files:** Reading Is Good SE

### [Container and Arrow Weight Restrictions](https://www.nexusmods.com/skyrimspecialedition/mods/13826?tab=files)
#### Download Instructions
- **Main Files:** Container and Arrow Weight Restrictions

### [Locks Are Just Locked](https://www.nexusmods.com/skyrimspecialedition/mods/42535?tab=files)
#### Download Instructions
- **Main Files:** Locks Are Just Locked

#### Additional Instructions
- ESL-ify **Container and Arrow Weight Restrictions.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins))

## 3.4 Interface
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/interface/) with the exception of:

**RaceMenu** - You can leave this in if you want, but I removed it because (a) I don’t use it, really and (b) it causes harmless bloat that makes saving take longer over time.  
**SkyHUD - TPF Preset** - I have my own preset, of course.  
**moreHUD - TPF Preset** - See above.  
**A Matter of Time - A Clock HUD Widget** - I’ve decided not to add UI elements needlessly.  
**A Matter of Time - Phoenix Preset** - See above.  
**KenMOD - Time On Loading Screen** - Again, an extra UI element that may be useful but ultimately unnecessary for me.

I’ve added the following mods to this section:
### [SkyUI - Ghost Item Bug Fix](https://www.nexusmods.com/skyrimspecialedition/mods/49106?tab=files)
#### Download Instructions
- **Main Files:** SkyUI - Ghost Item Bug Fix

### [NORDIC UI - Interface Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/49881?tab=files)
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

#### Additional Instructions
- Deactivate the following mods:
  - Better Dialogue Controls (from **Controls & Camera**) 
  - Better MessageBox Controls (from **Controls & Camera**)
  - Remove QuickSave Button from SkyUI System Menu (from **Interface**)
  - Wider MCM Menu for SkyUI (from **Interface**)
  - Favorite Things - Extended Favorites Menu for SkyUI (from **Interface**)
  - SkyHUD - Alternate White Dot Crosshair (from **Interface**)

### [Nordic UI - Miscellaneous Patches](https://www.nexusmods.com/skyrimspecialedition/mods/54102?tab=files)
#### Download Instructions
- **Main Files:** NORDIC UI - Miscellaneous Patches

#### FOMOD Instructions
- **moreHUD Inventory:** None
- **Stat Screen Colored Icons:** None
- **Even Better MessageBox Controls:** Install
- <s>**Extended Hotkey System:** Install</s>
- **MCM:** Wider MCM
- **Remove QuickSave from System Menu:** Install
- <s>**Loading Screen:** Install</s>
- <s>**Tween Menu:** Install</s>

### [SkyHUD - Slidikins’ Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) or [SkyHUD - Slidikins’ Nordic UI Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** SkyHUD - Slidikins' Preset (if you chose not to use _Nordic UI_)
- **Miscellaneous Files:** SkyHUD - Slidikins' Nordic UI Preset (if you chose _Nordic UI_ above)

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

### [Simple Activate SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/56767?tab=files)
#### Download Instructions
- **Old Files:** Simple Activate SKSE (v1.0)
- **Main Files:** Simple Activate SKSE » `merge with the old file`


#### Additional Instructions
- Double-click **Simple Activate SKSE** in your mod order.
- Switch to the INI Files tab and select the **po3_SimpleActivateSKSE.ini**.
- In **Line 28**, change `Show Indicator Using Name =` to `false`.
- In **Line 46**, change `Hide Locked Tag =` to `true`.
- Hit **CTRL+S** to save your changes and close the window.

## 3.5 Graphics Baseline
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/graphics-baseline/).

## 3.6 Weather
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/weather/).

## 3.7 Lighting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/lighting/).

## 3.8 Visual FX
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/visual-fx/).

I've changed the instructions for the following mod:

### [Enhanced Blood Textures](https://www.nexusmods.com/skyrimspecialedition/mods/2357/?tab=files)
#### Download Instructions
- **Miscellaneous Files:** 4.0 beta 3

#### FOMOD Instructions
- **SPID Compatibility and Script Distance:** SPID Compatible
- <s>**Compatibility Patch:** Immersive Creatures</s>
- **Blood Size:** Default Splatter Size
- **Wounds (Optional):** Reduced Wound Size (Optional)
- **Screen Blood:** EBT - Default
- **Resolution and Color:** Reduced Res / Default Color
- **Alt. Blood Textures (Optional):** Reduced Res / Default Color

#### Additional Instructions
- ESL-ify **dD-Reduced Wound Size.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins)).

I’ve added the following mods to this section:

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
- **Main Files:** Splashes Of Skyrim - 1.3

### [ENB Lights for Effect Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/56362?tab=files)
#### Download Instructions
- **Main Files:** ENB Lights For Effect Shaders

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
- Deactivate **Expressive Facegen Morphs.esl** in the load order. If you did not remove RaceMenu, you can leave it active.

## 3.21 Gameplay Overhauls
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/gameplay-overhauls/) with the exception of:

**Adamant - Shrines and Amulets** - Superceded by _Pilgrim - A Religion Overhaul_  
**Skyrim Uncapper - Adamant Arena** - Replaced by my own Uncapper preset, naturally.

I’ve added the following mods to this section:

### [Pilgrim - A Religion Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/54099?tab=files)
#### Download Instructions
- **Main Files:** Pilgrim - A Religion Overhaul

### [Skyrim Uncapper - Slidikins’ Strenuous Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Skyrim Uncapper - Slidikins' Strenuous Skyrim

### [Survival (CC)](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
This is mandatory for this modlist as I prefer it over other Survival mods. _[SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/39414)_ is a close second, but I offer no support towards making that work here.
#### Download Instructions
- Launch **The Elder Scrolls V: Skyrim Special Edition** from Steam.
- Select **Play**.
- At the title screen, select **Creation Club**. Log in if needed.
- (Purchase **Survival Mode** under Gameplay if needed.)
> To save on time, it's recommend to download **Rare Curios** now as well. Rare Curios is completely optional, however.
- Select **Survival Mode** under the Purchased tab.
- Click **Download**.
- Exit the Creation Club, reload, then exit the game.
- Go to your Skyrim SE **root** folder, then double click **Data**.
- Create a new folder called **[NoDelete] Survival (CC)**.
- Move the following files into the new folder:
  - `ccqdrsse001-survivalmode.bsa`
  - `ccqdrsse001-survivalmode.esl`
- Move the **[NoDelete] Survival (CC)** folder into `Mod Organizer 2\mods\`
- Back in MO2, press **F5** to refresh and it will show up at the bottom of the left pane.

### [Conner's Survival Mode](https://www.nexusmods.com/skyrimspecialedition/mods/19152?tab=files)
#### Download Instructions
- **Main Files:** Conner’s Survival Mode

### [The Phoenix Flavour - Conner's Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/45830?tab=files)
#### Download Instructions
- **Main Files:** The Phoenix Flavour - Conner's Survival Mode Patch

### [Slidikins' Strenuous Skyrim - Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Optional Files:** Slidikins' Strenuous Skyrim - Survival Mode Patch

## 3.22 Loot & Crafting
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/loot-crafting/) with the exception of:

**Improvement Names Customized** - This functionality will get covered by _Item Durability_.
**Enchanting Adjustments Updated** - This is replaced by Thaumaturgy - An Enchanting Overhaul.

I’ve added the following mods to this section:

### [Thaumaturgy - An Enchanting Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/57138?tab=files)
#### Download Instructions
- **Main Files:** Thaumaturgy - An Enchanting Overhaul
- **Miscellaneous Files:** Thaumaturgy - WACCF Patch

### [Thaumaturgy - Armor and Clothing Extension Patch](https://www.nexusmods.com/skyrimspecialedition/mods/57199?tab=files)
#### Download Instructions
- **Main Files:** Thaumaturgy - Armor and Clothing Extension Patch

### [Apothecary - Food and Drink Addon - Survival Mode Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Apothecary - Food and Drink Addon - Survival Mode Patch

### [Apothecary - Food Duration Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)
#### Download Instructions
- **Optional Files:** Apothecary - Food Duration Tweaks

#### Additional Instructions
- ESL-ify **Apothecary - Food Duration Tweaks.esp** with SSEEdit ([instructions](https://thephoenixflavour.com/tpf/guide-resources/basic-instructions/#esl-ifying-plugins))

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
- **Update Files:** Honed Metal 1.21 Hotfix » `merge with the first file`

### [Honed Metal Revoiced](https://www.nexusmods.com/skyrimspecialedition/mods/34393?tab=files)
#### Download Instructions
- **Main Files:** Honed Metal Revoiced (For Honed Metal SSE 1.2)

### [Rare Curios (CC)](https://en.uesp.net/wiki/Skyrim:Rare_Curios)
This adds new alchemy ingredients (and a couple of effects), as well as some other miscellaneous items. **Completely optional**, so skip it (and the two patches below) if you don’t have it.
#### Download Instructions
- Launch **The Elder Scrolls V: Skyrim Special Edition** from Steam.
- Select **Play**.
- At the title screen, select **Creation Club**. Log in if needed.
- (Purchase **Rare Curios** under Gameplay if needed.)
- Select **Rare Curios** under the Purchased tab.
- Click **Download**.
- Exit the Creation Club, reload, then exit the game.
- Go to your Skyrim SE **root** folder, then double click **Data**.
- Create a new folder called **[NoDelete] Rare Curios (CC)**.
- Move the following files into the new folder:
  - `ccbgssse037-curios.bsa`
  - `ccbgssse037-curios.esl`
- Move the **[NoDelete] Rare Curios (CC)** folder into `Mod Organizer 2\mods\`
- Back in MO2, press **F5** to refresh and it will show up at the bottom of the left pane.

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

### [STAYDOWN](https://www.nexusmods.com/skyrimspecialedition/mods/41228?tab=files)
#### Download Instructions
- **Main Files:** STAYDOWN - LIGHT

## 3.26 Miscellaneous
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/miscellaneous/) with the exception of:

**Misc Tweaks - More Expensive Inns** - Covered by _Coherent Inns Prices_
**Misc Tweaks - Shrines Don’t Cure Diseases** - Superceded by _Pilgrim - A Religion Overhaul_  
**Viewable Faction Ranks** - You shouldn’t have to go into the MCM for any information after the initial setup.

I’ve added the following mod to this section:

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

## 3.29 Controls & Camera
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/controls-camera/).

I’ve added the following mods to this section:
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

### [Slidikins’ SmoothCam Preset](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files)
#### Download Instructions
- **Miscellaneous Files:** Slidikins’ SmoothCam Preset

### [iHUD - SmoothCam Automated Compatibility Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51918)
#### Download Instructions
- **Main Files:** iHUD - SmoothCam Automated Compatibility Patch

## 3.30 Skeleton & Animations
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/) with the exception of:

**XP32 Maximum Skeleton Special Extended - Fixed Scripts** - The scripts aren’t being used in _XPMSSE_ so this is unnecessary.

I’ve updated instructions for the following mod:

### [XP32 Maximum Skeleton Special Extended (XPMSSE)](https://thephoenixflavour.com/tpf/mod-installation/skeleton-animations/#xp32-maximum-skeleton-special-extended-xpmssehttpswwwnexusmodscomskyrimspecialeditionmods1988tabfiles)
#### Additional Instructions
- Reinstall the mod under the name **XP32 Maximum Skeleton Special Extended - Skeletons Only**
- Place **XP32 Maximum Skeleton Special Extended - Skeletons Only** right below the original in the **SKELETONS & ANIMATIONS** section.
- Delete the following file(s) and / or folder(s) from the new mod:
  - `interface\`
  - `scripts\`
  - `XPMSE.esp`
- Deactivate the old **XP32 Maximum Skeleton Special Extended** mod.
> This is mainly a change to allow for the removal of RaceMenu but it’s a chance I’d make regardless as I don’t utilize XPMSSE to its full extent. If you want to change weapon positions and all that, you can leave this untouched. In a later update I’ll add the plugin to loadorder.txt for those who use it.

I’ve added the following mods to this section:

### [Movement Behavior Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/38950?tab=files)
#### Download Instructions
- **Main Files:** Movement Behavior Overhaul SE - AIO

#### FOMOD Instructions
- **Behavior Trigger:** Non-Combat Only
- **Perk Options:** No Perk
- <s>**Patch Options:** 360 Walk and Run Plus</s>
- <s>**Patch Options:** Combat Gameplay Overhaul</s>

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
  - `Draw2.achlist`
  - `Draw2.bsa`
  - `Draw2.esp`

### [EVG Animation Variance](https://www.nexusmods.com/skyrimspecialedition/mods/38534?tab=files)
#### Download Instructions
- **Main Files:** EVG Animation Variance

#### FOMOD Instructions
- Page 1: Install Type
  - **Options:** Modular
- Page 2: Modular
  - **Torch:** Full
  - **Repurposed Idles:** Full
  - <s>**Personality:** Elder</s>
  - <s>**Personality:** Elder - Sitting</s>
  - **Personality:** Children
  - **Personality:** Young Female
  - **Personality:** Imperial Guards
  - **Personality:** Egoistic
  - **Miscellaneous:** Wounded
  - **Miscellaneous:** Smooth Floating
  - <s>**Miscellaneous:** Laying Down</s>

### [EVG Conditional Idles](https://www.nexusmods.com/skyrimspecialedition/mods/34006?tab=files)
#### Download Instructions
- **Main Files:** EVG Conditional Idles

### [First Person Combat Animations Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/45177?tab=files)
#### Download Instructions
- **Main Files:** FPCAO2 - SIZE MATTERS SE ALL-IN-ONE 2.01

### [Ice Skating Fixed For Real](https://www.nexusmods.com/skyrimspecialedition/mods/55417?tab=files)
#### Download Instructions
- **Main Files:** EVE - Ice skating fixed for real - No more attack skating movement

## 3.31 Utilities
I use all of the mods listed in [TPF’s corresponding section](https://thephoenixflavour.com/tpf/mod-installation/utilities/).

I’ve added the following mods to this section:

### [Keyword Item Distrubtor](https://www.nexusmods.com/skyrimspecialedition/mods/55728?tab=files)
#### Download Instructions
- **Main Files:** Keyword Item Distributor

# 4. Finalization

## 4.1 Conflict Resolution Patch
- Create a **FINAL PATCHES - SSS** separator in Mod Organizer 2
- Download the [Conflict Resolution Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) from the guide's Nexus page.
- Install it as usual, place it last below a **FINAL PATCHES - SSS** separator (which you should create), and activate it.
> This second patch is necessary for resolving the few conflicts between SSS and TPF. It also includes edits to Magic Effects similar to _[No Edge Glow](https://www.nexusmods.com/skyrimspecialedition/mods/3205)_. This is done instead of simply including _No Edge Glow_ so that I can better maintain it as I encounter edge shaders that may have been modded in. Finally, it makes a few GameSettings changes to make falling more hazardous.

## 4.2 Load Order TXT
- Close Mod Organizer 2.
- Download the [Universal Lord Order TXT](https://www.nexusmods.com/skyrimspecialedition/mods/53939?tab=files) from the guide's Nexus page.
- Open the archive and extract the **loadorder.txt** to `Mod Organizer 2\profiles\Slidikins' Strenuous Skyrim`.
- Restart Mod Organizer 2 and the changes will be applied.

After applying the loadorder.txt and restarting MO2, there should be no plugins below the The Phoenix Flavour - Facegen.esp in the load order (right pane).

If there are other plugins below the Facegen plugin, you either made a mistake during the mod installation, or a mod was updated and the loadorder.txt is not accounting for it yet. Go back to the mod(s) in question (they will be highlighted in the mod order when you click on the plugin in the load order) and re-install them according to the instructions in the guide.

If you are unable to resolve all issues, please join us on Discord and post your Modwat.ch link or a picture of the bottom of your load order in the `#tpf-addons-support` channel.

## 4.3 Nemesis

### New Separator
- Create a **PATCHER OUTPUT - SSS** separator in Mod Organizer 2.
- It should be at the bottom of your mod order, below PATCHER OUTPUT.

### Nemesis Output Folder
- In Mod Organizer 2, click the tools icon above your mod order and select **Create empty mod**.
- Rename the new mod folder to **Slidikins' Strenuous Skyrim - Nemesis Output**.
- Drag the new empty mod (displayed in grey italics) below the **PATCHER OUTPUT - SSS** separator and activate it.

### Edit Nemesis Settings
- Open the Executables window in Mod Organizer 2 (Tools > Executables or CTRL + E).
- Click **Nemesis** in the left panel.
- Check the **Create files in mod instead of overwrite** checkbox and select **Slidikins' Strenuous Skyrim - Nemesis Output** from the drop down menu.
- Click OK to close the Tools window.

### Generate Nemesis

- Run **Nemesis** through Mod Organizer 2.
- There will be two warnings about missing (not yet generated) cache, click **OK** to both.
- Click the **Update Engine** button and wait for the process to be completed.
- When it’s done, check the **Ice Skating Fixed for Real** box.
- Also check the **Jump Behavior Overhaul** box.
- Also check the **Movement Behavior Overhaul** box.
- Finally, check the **True Directional Movement** box.
- Click the big Launch Nemesis Behavior Engine button.
- Nemesis will eventually return `Behavior generation complete` and you can close the tool.
- Back in Mod Organizer 2, press F5 to refresh and you can see that files were added to the **Slidikins' Strenuous Skyrim - Nemesis Output** mod folder.
- Deactivate the old **Nemesis Output** mod in the left pane.

# 5. Configuration

## 5.1 Controls

All controls changed from the Default:

**Auto Move:** `Right Alt`  
**Journal:** `F4`  
**Quick Inventory:** `F2`  
**Quick Magic:** `F3`  
**Quick Stats:** `F1`

## 5.2 Mod Configuration

### Cathedral Weathers
- **Settings** Panel
  - **General** Section
    - Configuration Spell: `Disabled`
  - **Weather** Section
    - Seasonal Perspective: `Enabled`

### Conner’s Survival Mode
- **General** Panel
  - **Quality of Life** Section
    - Shrine Gold Cost: `Freeeee`
    - Enable Health Regen: `Disabled`

### Dynamic Timescale
- **AutoSave** Section
  - Reoccurring Time: `0 MIN`
  - After picking a lock time: `0 SEC`
  - After combat time: `0 SEC`

### Honed Metal
- **General** Section
  - Crafting Cost Modifier: `0.60`
  - Tempering Cost Modifier: `0.04`
  - Enchanting Cost Modifier: `0.28`

### Immersive HUD
- **Activation** Panel
  - **Compass Activation** Section
    - iHUD hotkey: `Backspace`
- **Options** Panel
  - Stealth indicator enabled: `Disabled`
  - Enemy health indicator enabled: `Disabled`
  - Hide shout meter with compass: `Enabled`
  - Force crosshair to hide: `Enabled`
  - Enable fast fade of health: `Disabled`
- **Transparencies** Panel
  - Compass: `60%`
  - Magicka: `60%`
  - Health: `60%`
  - Stamina: `60%`

### moreHUD
- **Presets** Panel
  - **Save setting with FISS** Section
    - Load User Settings?: `Select`

### Simple Smithing
- **Settings** Panel
  - **Craftable Toggles** Section
    - Allow Artefact Replication: `Disabled`
    - Allow Upgrade Unique Gear Levels: `Disabled`

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

### SmoothCam
- **Presets** Panel
  - **Load Preset** Section
    - Slot 3: Slidikins’ Strenuous Skyrim: `Select`

### Timing is Everything
- **Extra Options** Panel
  - **Presets** Section
    - Load Preset: `Select`
- **Other Quests** Panel
  - **Misc Quests** Section
    - Ebony Warrior: `50` » This is unneccesary for Wabbajack users as it's baked into the preset`\

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
- **Target Lock Widget** Panel
  - **Visibility Settings** Section
    - Show Target Bar: `Disabled`
    - Show Soft Target Bar: `Disabled`
  - **Widget Settings** Panel
    - Reticle Style: `Simple Dot`
  - **Scale and Opacity Settings** Section
    - Reticle Scale: `0.5`
- **Boss Bar Widget** Panel
  - **Visibility Settings** Section
    - Show Boss Bar: `Disabled`

### Wergild Depreciation
- **Set the Default Values** Panel
  - **Set the Default Values** Section
    - Exile Required: `Enabled`
