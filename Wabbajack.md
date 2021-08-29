# Wabbajack Installation

## What is Wabbajack?

**Wabbajack** is an auto-installer for mod lists. If you have questions about what that means, its legality, its stability, or other frequently asked topics, pleae refer to Phoenix's article, [About Wabbajack](https://thephoenixflavour.com/wj/about-wabbajack/). If you're still here, I'll assume you want to play as soon as possible, so let's get started!

## Game Setup

Phoenix also wrote a comprehensive article on [setting up your Skyrim SE correctly](https://thephoenixflavour.com/wj/wj-sse/game-setup/) for a Wabbajack list. Follow that guide through until you reach **Creation Club**, then follow the instructions below instead:

### Creation Club
The Creation Club is an in-game cash shop in Skyrim SE where users can buy add-ons. These add-ons, unlike the several hundreds you're about to download, are considered official Bethesda content. They are made by third party mod developers that Bethesda recognized and contracted. That being said, any Creations purchased by the user are downloaded to their **data** folder, which causes issues for Mod Organizer 2. Those files will need to be moved before we continue.

#### Creations Used

The list utilizes the following Creations:
- [Survival Mode](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
- [Rare Curios](https://en.uesp.net/wiki/Skyrim:Rare_Curios) `Optional`

> **Note:** If **Survival Mode** is not present, you'll be unable to launch the Slidikins' Strenuous Skyrim profile in Mod Organizer 2. You'll still be able to play and enjoy The Phoenix Flavour profile that is included. If you don't intend on playing Slidikins' Strenuous Skyrim, you can skip the remainder of this section.

#### Purchasing Creations
- Launch **The Elder Scrolls V: Skyrim Special Edition** via Steam and hit Play.
- At the main menu, scroll down and select **Creation Club**. Make an account and/or log in as needed.
- Navigate to the fourth tab, **Gameplay**.
- Scroll right through the Creations to **Survival Mode**.
  - If it says `OWNED` underneath, perfect!
  - If not, you can purchase it for 500 credits.
- Scroll back to the left to **Rare Curios**
  - If it says `OWNED` underneath, perfect!
  - If not, you can purchase it for 100 credits if you want the additional content.
- Navigate to the seventh tab, **Purchased**.
  - Scroll right and click **Survival Mode**.
    - Click **Download**. It will change to say `Installed` once complete.
  - Scroll back left to **Rare Curios** _(if owned)_.
    - Click **Download**. It will change to say `Installed` once complete.
- Exit the Creation Club. Hit **Yes** when it asks to reload.
- Exit the game to desktop.

#### Backing Up Creations
- Navigate to your **data** folder.
- Create a new folder and name it **Creation Club**.
- Move the following files into **Creation Club**:
  - ccbgssse037-curios.bsa _(if owned)_
  - ccbgssse037-curios.esl _(if owned)_
  - ccqdrsse001-survivalmode.bsa
  - ccqdrsse001-survivalmode.esl
- Move the **Creation Club** folder outside of your **data** and **root** folders completely. It will be used later on.
> If you own any other Creations they might also exist in the **data** folder at this time. These files are all prefixed with `cc` for "Creation Club." Move them into the **Creation Club** folder as well so they are not in your **data** folder.

## List Installation
As of right now, Slidikins' Strenuous Skyrim is not listed in the Wabbajack Gallery and needs to be installed from the disk.
- Download the [Slidikins' Strenuous Skyrim Wabbajack](https://drive.google.com/file/d/1hutnm0rSFqXB65OTHd0Us35_ZmI-yrSt/view?usp=sharing) from Google Drive.
- Follow the instructions provided by Phoenix's [List Installation](https://thephoenixflavour.com/wj/wj-sse/list-installation/) page.
  - Instead of clicking **Browse Modlists**, click **Install from Disk** and select `Slidikins' Strenuous Skyrim.wabbbajack` from wherever it was saved.
  - Continue following the instructions until finishing the **Game Folder Files** section.

### Creation Club
> If you opted to skip Creations altogether, skip this section.
- Navigate back to your **Creation Club** folder
- In a separate window, navigate to where you installed the list, e.g. `C:\Modlist Name\`.
- From there, navigate to `\mods\[NoDelete] Creation Club`
- Copy the following files from **Creation Club** into **[NoDelete] Creation Club**
  - ccbgssse037-curios.bsa _(if owned)_
  - ccbgssse037-curios.esl _(if owned)_
  - ccqdrsse001-survivalmode.bsa
  - ccqdrsse001-survivalmode.esl
- Resume Phoenix's instructions at [Launching the Game](https://thephoenixflavour.com/wj/wj-sse/list-installation/#launching-the-game).

> **Note:** If you do not own Rare Curios, you will need to deactivate **The Phoenix Flavour - Rare Curios Patch** and **Apothecary - Rare Curios Patch**. They are both found under the **LOOT & CRAFTING - SSS** separator in Mod Organizer 2.

## Final Configurations
Recommended control adjustments and MCM Configuration Settings can be found in the [Installation Guide](https://github.com/Amigoliath/Slidikins-Strenuous-Skyrim/blob/main/Installation%20Guide.md#5-configuration). When starting a new game, it's recommended that you wait until after the carriage enters the town gates to open the menu to set these changes.

Have fun!
