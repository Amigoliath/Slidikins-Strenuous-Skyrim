# Wabbajack Installation

## What is Wabbajack?

**Wabbajack** is an auto-installer for mod lists. If you have questions about what that means, its legality, its stability, or other frequently asked topics, please refer to Phoenix's article, [About Wabbajack](https://thephoenixflavour.com/wj/about-wabbajack/). If you're still here, I'll assume you want to play as soon as possible, so let's get started!

## Game Setup

Phoenix also wrote a comprehensive article on [setting up your Skyrim SE correctly](https://thephoenixflavour.com/wj/wj-sse/game-setup/) for a Wabbajack list. You're welcome to read that guide as well to make sure your game is properly set up before using Wabbajack. 

### Creations Used (and Downgrading Skyrim)

This list uses the following Creations, all of which are freely available with Special Edition Version 1.6:)
- [Survival Mode](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
- [Rare Curios](https://en.uesp.net/wiki/Skyrim:Rare_Curios)
- [Fishing](https://en.uesp.net/wiki/Skyrim:Fishing)

In order to obtain these files, you will need to upgrade Skyrim to the current version before patching the exe back to the version that works with SKSE and this list. Luckily this process is fairly simple:
- Open your Steam Library and navigate to **The Elder Scrolls V: Skyrim Special Edition**
- Right click and select **Properties...**
- Under **Updates**, make sure **Automatic Updates** is set to `Only Update this game when I launch it`
- Under **Local Files**, select **Verify integrity of game files...**
- Wait for the process to identify and obtain any files it requires

> This step will download the three Creations noted above as well as [Saints and Seducers](https://en.uesp.net/wiki/Skyrim:Saints_%26_Seducers), which I do not support. There may be no harm in having it, but if you want to remove it, just make sure `ccBGSSSE025-AdvDSGS.esm` is disabled in your MO2 load order.

Once that is finished, you'll need to downgrade to a version of Skyrim which works with this list.
- Download [BestofBothWorldPatcher.zip](https://www.nexusmods.com/skyrimspecialedition/mods/57618?tab=files) and unzip it anywhere
- Run **Patcher.exe**
- Verify that the Game Location is correct and select **Start Patching**
- Once it says "Finished Patching, enjoy your game!" you're good to go!

# List Installation

## Wabbajack
Similarly to the vanilla game files, Wabbajack should also not be installed in any UAC protected folders. A top-level folder such as `C:\Wabbajack\` is once again recommended as the installation directory.
- Create a new **Wabbajack** folder.

The Wabbajack app can be downloaded directly from the website:
- Click the **Download** button on the home page of the [Wabbajack](https://www.wabbajack.org/#/) site.
- Move the downloaded **Wabbajack.exe** into the folder you previously created.
- Upon launching it, the latest version of Wabbajack will be downloaded into the same directory.

### Choosing a list
Once Wabbajack has launched, you can click the **Browse Modlists** button to view all currently available lists. If you are following these instructions, you likely already know which mod list you want to install.
- Find **Slidikins' Strenuous Skyrim** in the Gallery and click the download button.

## List Configuration
Once the meta file for your chosen list has been downloaded, a new browser window with the list’s readme will automatically open. You can simply continue here on this page (if your list supports it to begin with).

Before you can begin installing the list, you need to define some file paths:

### Installation Location
The **Installation Location** will be the folder in which Mod Organizer 2 and all mods are installed in.
- It should be outside of aforementioned protected folders.
- It should be on your fastest hard drive (ideally an SSD).
- It should be in or near the root of your drive (top-level folder).
> Though Slidikins' Strenuous Skyrim is a fork of The Phoenix Flavour, it does not require TPF to be installed. If you want to have both lists, install them to two different Installation Locations as one will overwrite the other in the same folder.

### Download Location
The **Download Location** will be the folder in which all downloaded mod archives are stored in. It is a sub-folder of your MO2 directory (Installation Location) by default. However, the downloaded archives are only needed for installing and updating the list, not for playing. Therefore, they do not need to be on the same hard drive as the vanilla game and installed mod files, so the 50GB+ of space they take up would be wasted on an SSD. Any HDD is perfectly sufficient to store these archives.
> Unlike the Installation Location, it is highly encouraged to use the same Download Location for multiple lists. This way, common archives between each list are only downloaded once. This will save you some storage space, but more importantly it will speed up the installation (and update) process tremendously.

## Installation
Once you have set target folders for the **Installation Location** and **Download Location**, the **Start** button (arrow) to the right of the folder paths will light up. Click it to start the installation of the list. If you have Nexus Premium, simply lean back and wait for the process to be completed. It may take several hours depending on the speed of your internet connection. If you do not have Premium, Wabbajack will prompt you with the mod pages where you have to click the download button manually.

### Troubleshooting
While Wabbajack runs perfectly fine in most cases, an installation may fail for various reasons. If it does, diagnosing the issue is possible with the logs generated by Wabbajack which you can find within your Wabbajack installation directory in the logs folder: `\Wabbajack\logs\`. The relevant log will be named **Wabbajack.current.log** with older logs being renamed according to the time of their creation.

If Wabbajack fails, please try restarting it first. You will not lose any progress by closing and reopening the app.

If the issue persists, find the Discord support channel for your chosen list (either on the [Wabbajack](https://discord.com/invite/wabbajack) or [TPF](https://discord.gg/xCPxJFbCTS)) and drop the **Wabbajack.current.log** with a request for support.

## Creation Club
If you opted to skip Creations altogether, skip this section and use the `Slidikins' Strenuous Skyrim (CC-less)` profile in Mod Organizer 2.
- Navigate back to wherever you keep your [Creation Club backups](https://thephoenixflavour.com/wj/wj-sse/game-setup/#creation-club) 
- In a separate window, navigate to where you installed the list, e.g. `C:\Modlist Name\`.
- From there, navigate to `\mods\[NoDelete] Creation Club`
- Copy the following files from **Creation Club** into **[NoDelete] Creation Club**
  - ccbgssse037-curios.bsa _(if owned)_
  - ccbgssse037-curios.esl _(if owned)_
  - ccqdrsse001-survivalmode.bsa
  - ccqdrsse001-survivalmode.esl

> **Note:** If you do not own Rare Curios, you will need to deactivate **The Phoenix Flavour - Rare Curios Patch** and **Apothecary - Rare Curios Patch**. They are both found under the **LOOT & CRAFTING - SSS** separator in Mod Organizer 2.

## Launching the Game
Wabbajack lists must always be start with the **Skyrim Script Extender** which in turn must be launched through **Mod Organizer 2**. Remember that your mod list installation directory is simply a Mod Organizer 2 instance.
- Double-click the **ModOrganizer.exe** within your mod list installation directory.

Now you can see the full setup: The mod order is on the left, likely sorted below separators that may be collapsed by default, and the load order with all plugins on the right. Above the load order (in the right pane), you can see the executables drop-down. Very likely the **Skyrim Script Extender** was already selected here, so you can start the game by clicking **RUN**.
> Note that some Wabbajack lists, including Slidikins' Strenuous Skyrim, may change the name and/or icon of the SKSE launcher. If what is selected in the executables drop-down is named after the list you installed, it is probably what you should run to start the game.

**Always run SKSE through MO2 to start the game.** If you launch the game through Steam or directly with the default executables (e.g. SkyrimSE.exe), your mods will not load and the game will simply be vanilla. If you run the default executables through MO2 (instead of the SKSE launcher), many mods will also not work because they require SKSE.


## Final Configurations
Recommended control adjustments and MCM Configuration Settings can be found in the [Installation Guide](https://github.com/Amigoliath/Slidikins-Strenuous-Skyrim/blob/main/Installation%20Guide.md#5-configuration). When starting a new game, it's recommended that you wait until after the carriage enters the town gates to open the menu to set these changes.

Have fun!
