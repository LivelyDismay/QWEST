# QWEST!

- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Graphical Settings](#graphical-settings)
    - [Getting an ENB](#getting-an-enb)
    - [Profiles](#Profiles)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Performance stuff](#Performance-stuff)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

QWEST! was born after a few friends were talking about how some of their friends couldn't enjoy cool quests in modded Skyrim, even with Wabbajack, due to the hardware requirements. This list has very few graphical enhancements which can be removed if you find you're struggling to run it.

I chose mods that overhaul almost all of the vanilla quests, added some major mods such as Legacy of the Dragonborn, Interesting NPC's, Wyrmstooth and the Forgotten city, and also overhauled the animations a bit. You'll also find new music, new armors and weapons that are linked to LotD and vanilla enhancing weathers and lighting. You even have the choice between EnaiRim and SimonRim with the 2 available Profiles!

If you can run vanilla Skyrim, you should be able to run this.

If you have any questions regarding the list, you're free to ask in the main Wabbajack Discord or mine :[here](https://discord.gg/ZgjVrXp)

It is a fork of the amazing SME/FT list; if you want to build your own list check it out [here](https://github.com/EzioTheDeadPoet/SME-FT-)!

The name and picture are a reference to the amazing and wholesome Quest Sprout comic available on [swordscomic.com](https://swordscomic.com). Their official Twitter is [here](https://twitter.com/swordscomic).

# Noteworthy Mods and what gameplay to expect.

Depending on the choice of profile, you will have a very different approach to the list: Enairim will make you and your enemies stronger overall while Simonrim will remain simple and closer to Vanilla.
If you're unfamiliar with those overhauls, you should read their modpages as their changes are at the base of everything.

- Survival -
If you chose to not make any modifications and go with the survival mods, you will have way more micromanagement to do.
First you'll need to eat and sleep to survive, second you'll need to survive the cold or your stamina will drain and you'll die, third you'll need to clean yourself or you'll have very bad prices and everyone will smell you when trying to sneak.
You should definitely check the Skill Trees within your campfire on top of the vanilla skill trees, your arrows will have a weight and you will need to sleep to level up your Character level.
Fast travel is disabled in multiple of these mods so there's no easy way to reactivate it at all times but there's an alternative: [Horizon Zero Dawn Fast Travel](https://www.nexusmods.com/skyrimspecialedition/mods/35793).
If you're unfamiliar with those mods, have a read on [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667), [The Frozen North](https://www.nexusmods.com/skyrimspecialedition/mods/33068), [Dirt and Blood](https://www.nexusmods.com/skyrimspecialedition/mods/40746), [Keep it Clean](https://www.nexusmods.com/skyrimspecialedition/mods/17846) and [SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/39414).
Lastly, all profiles have horses with their own inventory due to [Saddlebags](https://www.nexusmods.com/skyrim/mods/91395), and a [little light on your belt for the darkest caves](https://www.nexusmods.com/skyrimspecialedition/mods/12633?tab=posts).

- Added Quests -
[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/30980) is the core spine of the list but many new lands aren't integrated with it, I'm especially thinking of [Unslaad](https://www.nexusmods.com/skyrimspecialedition/mods/11789), [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423) or [Undeath](https://www.nexusmods.com/skyrimspecialedition/mods/6180/?).
[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194), [Skyrim Sewers 4](https://www.nexusmods.com/skyrimspecialedition/mods/9320) and [VIGILANT](https://www.nexusmods.com/skyrimspecialedition/mods/11849) are in and provide artifacts aswell as many new stuff to do, on top of those there is still The [Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168), [G.R.I.M](https://www.nexusmods.com/skyrimspecialedition/mods/41816), [The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179), [Wyrmstooth](https://tes-mods.fandom.com/wiki/Wyrmstooth), [Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673) or [Beyond Reach](https://www.nexusmods.com/skyrimspecialedition/mods/3008). A much more detailled Spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/15h4lGfMr4z_1hqPp8LDVbTLLRqgjaQBUUSIYc6XtJGU/edit#gid=0).

- Overhaul-ed Quests -
From [Finding Derkeethus](https://www.nexusmods.com/skyrimspecialedition/mods/19550) to [Save the Icerunner](https://www.nexusmods.com/skyrimspecialedition/mods/34681) with [Thieves' Guild Night On the Town](https://www.nexusmods.com/skyrimspecialedition/mods/42069) or [Missives](https://www.nexusmods.com/skyrimspecialedition/mods/26788), many quests are changed.
You should know that the [Thieves Guild have Requirements](https://www.nexusmods.com/skyrimspecialedition/mods/33256) now, and you can [Renounce the Daedra if you will](https://www.nexusmods.com/skyrimspecialedition/mods/36100), while [Vampires can skip Fort Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/25783).  A much more detailled Spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/15h4lGfMr4z_1hqPp8LDVbTLLRqgjaQBUUSIYc6XtJGU/edit#gid=0).

- Followers -
[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194#) will provide a nice amount of high quality followers but there is still the unforgettable [Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461), [Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) or [Auri](https://www.nexusmods.com/skyrimspecialedition/mods/11278) ([with her cute face overhaul!](https://www.nexusmods.com/skyrimspecialedition/mods/29345)). 
There is also Serana [Dialogue Edit](https://www.nexusmods.com/skyrimspecialedition/mods/16222) and [Add-on](https://www.nexusmods.com/skyrimspecialedition/mods/32161) for all the love for the goth cutie.

- Loot, Artefacts and Leveling -
[Reliquary of Myth](https://www.nexusmods.com/skyrimspecialedition/mods/31612) overhauls all vanilla Artifacts and [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308) coupled with [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/11342) makes sure you do not find spider webs in the dungeon chests.
[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) handles levels, quests will level your character levels, skills will not level it anymore, but they'll level independently. Also there's a skill cap to avoid powerleveling, it is determined by the Player Character level, you really should check the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/17751)!

## Installation
### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Library

If you have your steam library in program files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133).

If you ever used Vortex to mod Skyrim SE, using the Shredder becomes a critically important step, as Vortex will conflict heavily with any Wabbajack installation, so backup your stuff or shred it.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

## Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

## Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Browse the Gallery and Select QWEST!
3. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "QWEST!".
4. Select the created folder in 3. as your installation folder.
5. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish.
6. Select the created folder in 5. as your downloads folder.
7. Click the Go/Begin button.
8. Wait for Wabbajack to finish.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

## Copy Game Folder Files

Copy the all of the files from the `QWEST!/Game Folder Files` directory into your game folder.

## Graphical Settings

On a Ryzen 5 2400G paired with a GTX 950 2GB VRAM and 24GB RAM (never used more than 14GB, so 8GB RAM should be fine, **WHEN** installed on an SSD, if you use an HDD 16GB RAM minimum is recommended):
BethINI is located within `QWEST!/Tools`.
Make sure that Bethini is configured to the profile folder you will use in MO2 and not your vanilla INIs or any change will be rendered worthless!

- BethINI(Low)(locked to 60 FPS):
  - Everywhere(where it got tested): 60FPS

- BethINI(Normal)(locked to 60 FPS): 
  - Outdoors: 30-40 FPS (average 40)
  - Cities: 40-60 FPS (average 50)
  - Indoors: 60FPS

- If you have 8GB RAM and **NO SSD** or if it still has frame drops, then I recommend:
  - Disabling:
    - The following mods in MO2 : [Stuff below the Separator](http://prntscr.com/x2p70m)
  - And testing:
    - BethINI(Normal) -> BethINI(Poor) and stopping by the preset that has a playable framerate for you.

## Getting an ENB

This list is aimed towards very low end PCs, but that doesn't mean ENB isn't an option.

I recommend anyone with a 2GB card to skip this step and test in game, then check afterwards for what's following, ENB is the biggest performance hit in modding (if you don't go nuts with textures which I didn't). For the lucky ones with more than 2GB of VRAM but still low end, I really recommend [The Truth](https://www.nexusmods.com/skyrimspecialedition/mods/9162) which is the best enb in my opinion for how little it impacts FPS.
There is also another option which is ReShade, it's even less heavy but does less, instructions on this option are below The Truth ENB's installation instructions.

To install The Truth ENB, follow these:
- Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.
- Download The Truth ENB from [here](https://www.nexusmods.com/skyrimspecialedition/mods/9162) and copy the contents of the .rar to your game folder.
**Note : Please check that vsync is set to disable in enblocal.ini otherwise you will be stuck compiling shaders**

Now Let's talk about the ReShade option.
ReShade is simpler than ENBs, they generally focus on color correction but if rightly used, they can enhance the game graphics nicely with even lower fps loss, couple that with a SKyrim set on Low and even the weaker gpus can experience more than vanilla Skyrim lighting.
For Skyrim, it's very common for ReShade to be made with a certain ENB in mind, but some exist to be used on top of Vanilla Skyrim. I'll introduce you to 2 of them.
- [BTS - Beautifully Textured Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/25489)
- [Ulver](https://www.nexusmods.com/skyrimspecialedition/mods/40433)

You can have both at the same time in your Skyrim, so if you want to try both you can download them and follow the installation instructions:

- Download the latest ReShade Version from [here](https://reshade.me/)
- Open ReShade.exe, Select SkyrimSE.exe as the game you want to install it to. 
- Select Direct3D 10/11/12 as the rendering API
- Check/Tick every single box until ReShade is installed.
Now we'll go back to the presets downloaded
- Open the ReShade Preset archive and paste it to your game folder.
- When Skyrim launches (Refer to the next step in the readme if lost on this step), press the home button on your keyboard and select the .ini file you just put in your Skyrim Folder as the loaded .ini
- Press home again to close the window.
Know that you can switch any ini at anytime during your gameplay, so if you want to compare between the 2 that I recommend, you can totally do that in game.

## Profiles 

QWEST! has 2 profiles, one with EnaiRim, one with SimonRim. The main difference is that EnaiRim is kinda unbalanced and very strong while SimonRim is kinda like what vanilla Skyrim should've been.
You can look them up here: [EnaiRim](https://www.nexusmods.com/skyrimspecialedition/users/3959191) and [SimonRim](https://www.nexusmods.com/skyrimspecialedition/users/67410746)

To change the profile, there's a dropdown menu on the top left of MO2, the default profile is EnaiRim, so only change if you want the SimonRim one.

## Personalization

On top of the 2 Profiles available for the core gameplay mods, QWEST! comes with some Quality of Life changes and gameplay mods that some may or may not enjoy. All of those are supported as written here, other modifications fall under Rule 11: No support will be given if modifications happen.

First possible modifications is the [Survival Setup](http://prntscr.com/xnxial). It is enabled by default as it has to be patched by Synthesis to work correctly. But if you follow carefully what I'm about to write, you will be able to remove it entirely. Yes entirely as I do not support removing only hypothermia or cleaning and washing while keeping food and sleep needs. There are 2 steps:
- Untick all the mods under ``Survival Stuff`` ( [those](http://prntscr.com/yv90oj) ) 
- Open Synthesis by clicking [the mushroom icon on top right](https://prnt.sc/yv11sk), a window shall appear, it is loading the patchers, simply wait until [the little arrow on bottom left appears](https://prnt.sc/yv10a0), once here, click it. Synthesis will patch stuff, you'll know it's finished when the window looks like [this](https://prnt.sc/yv18gd), at that point you can close it and it's done!

Note: If you get those errors [Example 1](https://cdn.discordapp.com/attachments/793809552353132566/809381202044780575/unknown.png) [Example 2](https://cdn.discordapp.com/attachments/793809552353132566/809391791542501386/unknown.png), make sure you got [.NET](https://dotnet.microsoft.com/download), especially [both of those](https://cdn.discordapp.com/attachments/793809552353132566/809423761215979560/unknown.png) [(core should be this one)](https://cdn.discordapp.com/attachments/793809552353132566/809424580451631244/unknown.png). If you keep having problems, don't hesitate to come to [my Discord](https://discord.gg/ZgjVrXp) and I'll gladly help you.

Second modification: [Paper Ui](http://prntscr.com/xb9im1). It is enabled by default but you can disable one or both of those depending on what you want.

Third modification: [Unequip Quiver](http://prntscr.com/xb9k5u). Disabled by default, it'll make your Player Character unequip it's ammunition everytime you go out of combat if turned on.

Fourth modification: [Oblivion Style HUD](http://prntscr.com/xb9lrc). Disabled by default, it'll make the UI have an oblivion style like [this](https://staticdelivery.nexusmods.com/mods/1704/images/463/463-1511538957-694432832.png)

Fifth and last modification: [Gamepad Guide](http://prntscr.com/xb9op3). Disabled by default, ask for the Gamepad guide in [MY Discord](https://discord.gg/ZgjVrXp) (not Wabbajack's) if you want the details on how to use a controller with QWEST!

## How to start up QWEST!

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
Once the game has loaded. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

MCMs are not automated due to a personal choice: There are many, many important tweaks, informations, and usefull stuff in them that can solve problems or make your experience better. Those are my own and what I recommend for the least amount of problems and a balanced experience.

#### Game Difficulty
- The difficulty in this game is very vanilla like but still generally harder, if you're used to Legendary you will have a hard time. I suggest playing in Expert or Master and if found too easy, crank it up.

#### A Matter of Time

- Presets :
  - Load User Settings

#### AGO
- Settings
  - Enable/Disable
    - Bow Camera : Disabled
    - Bow Crosshair : Disabled
    - Arrow Wounds (Player) : Disabled
    - Arrow Wounds (NPCs) : Disabled
    - Persistant Arrows : Disabled
    
#### All Geared up Derivative
- Misc. Player :
  - Enable Misc. Item Display : Disabled
  - Require Torso Armor : Enabled
- NPC :
  - Enable Weapons : Enabled
  - Enable Misc. Item Display : Disabled

#### Campfire (Survival)
- Gameplay
  - Hotkeys
    - Set your Hotkeys however you want
    - I go by :
    - Create item : C
    - Build Campfire : B
    - Harvest wood : H
    - Instincts : Nothing

#### Follower Framework
- System :
  - Load From File

#### Growl Werebeasts 
- Features
  - Invulnerable During Transformation: Enabled
- If you want to be a Werebear instead:
  - Immersion : Werebear : Enabled
  
#### Immersive HUD
- Activation
  - Compass Activation
    - Key press toggles : Enabled

#### Imperious Racials
- Nothing is really important, you can toggle stuff depending on your Race though!
Remember that you can't switch race/sex using Showracemenu because of such a mod!

#### Keep It Clean (Survival)
- MAKE SURE THE MOD IS DEACTIVATED, WE DO NOT USE IT's SYSTEMS, IT'S ONLY HERE FOR THE SHOWERS IN INNS AND MORE SOAPS.

#### LOTD Settings
- LOTD Settings → General → Shippment Crate Locations : 
  - Carriages: Enabled
  - Inns: Enabled
  - Player Houses: Enabled

#### moreHUD
- Presets
  - Save Settings with FISS
    - Load User Settings? : GO
    
#### Simple Horse
- Call Horse Key : change it if you want to! (I leave it on default)

#### SkyUI
- General → Item List :
  - Font Size : Small
  - Category Icon Theme : CELTIC
- Advanced → SWF Version Checking : 
  - Map Menu : Disabled
  - Favorites Menu : Disabled
  - Inventory Menu : Disabled
  - Barter Menu : Disabled
  - Container Menu : Disabled
  - Crafting Menu : Disabled

#### SmoothCam  -for 3rd person players-
- Presets
  - Load Preset
    There are 2 presets available for your to use, I personally prefer the Modern one but some prefer EasyEase's, try both and see which you prefer!
    
#### SunHelm (Survival)
- General Settings
  - SunHelm Suvival : Enabled (close MCMs and wait a bit in game)
- It is a fully customizable mod so if something bothers you in game, you can go back to this MCM and tweak it.
    
#### Tentapalooza (Survival)
- Set all tents in all tabs as "Rain and Snow" instead of "No Protection"
    
#### The Ultimate Dodge Mod  
 - Configure your dodge key and your sneak key! As written, it is your vanilla sneak key. This step is very important
   - A Keybinding example would be:
      - Vanilla Sneak key within Options: C
      - Sneak key within TUDM's MCM: Left Control
  - Now your character will roll/sidestep with C and Sneak with Left Control
  - I also would recommend to use sidestep (personal preference)
  - Please Note: 
    - You cannot dodge in the Starting Cell, you need to choose a path first.
    - The first time you'll dodge, you'll be stuck in a weird position in the air, Press G (or your dodge swap key) 2 times to be un stuck.


- Npc Settings :
  - NPC Dodge AI: Disabled

#### Thieves Guild Requirements
- Misc Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)
  
#### Timing is Everything
- Extra Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)

#### VioLens
- Load Preset

#### Wildcat
- Disable Injuries: Enabled
- Allow Wildcat to manage difficulty: Enabled

## How to start playing

Simply step up to the statue of mara and choose a start.

## FAQ

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Ultrawide Options

Although I do not see why someone would have such a screen with the targetted minimals of the list, here's a document made by Mantis to help you solve such problems. [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

## I have a question

Ask it in my Discord, link [here](https://discord.gg/ZgjVrXp). The support channel in the Wabbajack Discord is for Installation questions, not support over in game stuff or suggestions.

## I have a bug

Report it in my Discord, link [here](https://discord.gg/ZgjVrXp). The support channel in the Wabbajack Discord is for Installation questions, not bug reports.

## I want to support your work!

I thank you for that thought but you should probably donate to Wabbajack first. Link [here](https://www.patreon.com/user/overview?u=11907933). If you still want to only support me, my patreon is [here](https://www.patreon.com/Sovn).

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Xanza, Jdsmith inspiring me to make this, y'all are neat.
- Luca for all the testing, feedback and recommendations, you are amazing.
- Althro for being such a resourceful person and helping with the Discord and development a lot.
- Every each of my Patreons for supporting me, and with the Special Folks of my discord, for helping with the development.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the Discord. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU** but you can safely ping me in #qwest-support or my own Discord, I'll answer whenever I can.

## Changelog

See [Changelog](https://github.com/SovnSkyrim/QWEST/blob/main/Changelog.md).
