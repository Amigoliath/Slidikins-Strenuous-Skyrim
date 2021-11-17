# Wabbajack Installation

## What is Wabbajack?

**Wabbajack** is an auto-installer for mod lists. If you have questions about what that means, its legality, its stability, or other frequently asked topics, please refer to Phoenix's article, [About Wabbajack](https://thephoenixflavour.com/wj/about-wabbajack/). If you're still here, I'll assume you want to play as soon as possible, so let's get started!

## Game Setup

Phoenix also wrote a comprehensive article on [setting up your Skyrim SE correctly](https://thephoenixflavour.com/wj/wj-sse/game-setup/) for a Wabbajack list. You're welcome to read that guide as well to make sure your game is properly set up before using Wabbajack. 

### Updating to Skyrim Special Edition 1.6

This list uses the following Creations, all of which are freely available with Special Edition Version 1.6:
- [Survival Mode](https://en.uesp.net/wiki/Skyrim:Survival_Mode)
- [Rare Curios](https://en.uesp.net/wiki/Skyrim:Rare_Curios)
- [Fishing](https://en.uesp.net/wiki/Skyrim:Fishing)

In order to obtain these files, you will need to update Skyrim to the current version before patching the exe back to the version that works with SKSE and this list. Luckily this process is fairly simple:
- Open your Steam Library and navigate to **The Elder Scrolls V: Skyrim Special Edition**
- Right click and select **Properties...**
- Under **Updates**, make sure **Automatic Updates** is set to `Only Update this game when I launch it`
- Under **Local Files**, select **Verify integrity of game files...**
- Wait for the process to identify and obtain any files it requires

> Don't worry! Wabbajack will downgrade the necessary files back to 1.5 during installation. Your Skyrim folder will remain as an untouched copy of Special Edition 1.6.

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

If the issue persists, find the **#sss-support** channel on the [TPF Discord](https://discord.gg/xCPxJFbCTS) and drop the **Wabbajack.current.log** with a request for support.

## Launching the Game

- Double-click **ModOrganizer.exe** within your installation directory.

Now you can see the full setup: The mod order is on the left, likely sorted below separators that may be collapsed by default, and the load order with all plugins on the right. Above the load order (in the right pane), you can see the executables drop-down. **Slidikins' Strenuous Skyrim** should already be selected here, so you can start the game by clicking **RUN**.

## Final Configurations
No additional configuration should be required, but all configuration changes have been noted in the [Installation Guide](https://github.com/Amigoliath/Slidikins-Strenuous-Skyrim/blob/main/Installation%20Guide.md#5-configuration). MCM Configurations have been pre-configured for your convenience.

#### Notable Control Changes

**Journal:** `F4`  
**Quick Inventory:** `F2`  
**Quick Magic:** `F3`  
**Quick Stats:** `F1`  
**Lock On:** `Middle Mouse Button`  
**Cycle Targets:** `Mouse Scroll Wheel Up/Down`

**Favorite Groups 1-4:** `9`,`0`, `-`, and `=`

> _SkyUI_'s favorite groups do not work well in SSS. This is because _Item Durability_ changes the name of your equipment often which will break the group. I do not recommend using favorite groups for this reason, but their buttons have been reassigned here.

Have fun!
