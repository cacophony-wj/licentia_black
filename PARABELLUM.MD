# PARABELLUM

![Parabellum Image](images/OIG1.png)

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

_Parabellum_ was born because I desperately want to play _Sim Settlements 2_ (someday, sigh...), but I don't want to be completely without my beloved **NSFW Content** and everyone always told me it was impossible to mix _SS2_ and **NSFW**. After testimony from users who had done it themselves and completed the first two chapters, I resolved to see for myself. I am happy to report that I have succeeded. The key appears to be using only the base chapters for _SS2_ and very few **NSFW** frameworks. Since this is how I want to play the game, maybe someone else does too, and so -- I offer this modlist.

I have attempted to make up for the lack of content you might find in something like _Wasteland of Depravity_ by offering a **TON** of quests to do. Almost every well-regarded _Fallout 4_ quest mod is here (along with several poorly-regarded ones), so now you can kill and screw your way across the Wasteland.

Have fun.

#### More Information

If you are interested in examining a complete list of the mods in this modlist, [go here.](https://loadorderlibrary.com/lists/parabellum-1)

For a complete list of the mods included with _Parabellum NUKA_, [visit this link instead.](https://loadorderlibrary.com/lists/parabellum-nuka)

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

# BEFORE YOU BEGIN! VERY IMPORTANT!

You will save yourself a **LOT** of headaches if you download all the _Lover's Lab_ files manually **BEFORE** you begin installing anything with _Wabbajack_. 

You will first need to wade through the [Lover's Lab website](https://www.loverslab.com) -- which features a cringey amount of porn ads. (I recommend an ad blocker.) Create an account with an email you don't care about, then use the registration process to confirm the account via an email you will receive. 

**You cannot avoid creating an account here.** If _Lover's Lab_ is blocked in your location, I recommend against going further, but there are ways around it...

After you confirm your account, log in to _Lover's Lab._

Next, create a directory for your chosen modlist. I recommend something in the root folder of a fast Solid State Drive, or -- ideally -- an M.2 NVME. (Something like `D:\Parabellum` or `D:\NUKA`). 

Within that directory, create another directory called `downloads` -- in all lower case. (`D:\Parabellum\downloads` or `D:\NUKA\downloads`)

Now consult the below URL. Place all the files in the `downloads` directory you created above. **DO NOT EXTRACT THEM.** _Wabbajack_ will take care of that.

**Return to this document when you have downloaded all the necessary files.**

_Parabellum Complete Download Guide:_ https://github.com/cacophony-wj/licentia_black/blob/main/PARABELLUM-Complete-Download-Guide.md

## Installation

### Getting Rid of the High-Resolution DLC

This document assumes you are already familiar with installing games via _Steam._ However, another step is required for this list to ensure maximum compatibility. You must verify that the _Fallout 4_ "High-Resolution DLC" is disabled.

To do so, click on the _Fallout 4_ game entry in your _Steam_ Library. Over on the right, about one or two scrolls down, you will see a collection of banners representing the DLC you have installed. You need **ALL** of the DLC to install this list, but some of it is incompatible. 

In the bottom right corner of the "DLC" Panel, click "Manage My DLC." Listed here, you may or may not find "Fallout 4 - High-Resolution Texture Pack." This particular DLC is a half-finished, slipshod abomination of poorly optimized, ugly textures that will cause "Rusty Face" bugs among other problems. It is also an utter waste of almost 60GB of storage space, as the vast majority of included textures have been replaced by better ones. 

Uncheck this DLC from the list and wait for any _Steam_ configuration changes to finish (the "Play" icon will turn green for the game), and you will be set.

###  Installing Microsoft Visual C++ Redistributable Package

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ and you can download it from _Microsoft._ Download the x64 version under "Visual Studio 2015, 2017 and 2019" [here](https://aka.ms/vs/16/release/vc_redist.x64.exe).

###  Steam Config

**Change Steam's Update Behavior**

To ensure that _Steam_ does not automatically update _Fallout 4_ for you and lock you out of playing your _Wabbajack_ modlist(s), open the Properties window of _Fallout 4_ in _Steam_, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_. It is incompatible with the profile-specific saves of a _Wabbajack_ modlist.

**Set the Game language to English**

_Wabbajack_ will check your game files and ensure that your installed version is the same as my installed version. This also means that any language other than English will fail the installation. You can change the game's language in the Properties window, as mentioned above. You may be required to verify your files afterward.

**Do Not Use Any Part of This List in a Protected Folder**

This includes `Program Files,` `Program Files (x86)`, `Downloads`, `Documents`, the `Desktop` or any other folders that _Windows_ considers "Protected" (essential to the operating system). If the _Wabbajack_ folder, the _Fallout 4_ folder, the _Steam_ folder, the modlist folder or the downloads folder are in any of these directories, the modlist will not function properly. Relocate offending folders to a non-Protected location such as the root directory of one of your drives. (D:\ for example.)

**Do Not Use Any Protected Folders inside of OneDrive**

If your `My Games` folder (usually in the `Documents` folder) is part of a _OneDrive_ Cloud Folder, you will experience unusual behavior. You will need to relocate it or disable OneDrive. There are no exceptions.

**Make Exceptions for Anti-Malware Programs**

Exclude antivirus and anti-malware programs from monitoring three directories: those containing the _Wabbajack_ app, the _Fallout 4_ game folder, and the directory you wish to install the modlist. _Wabbajack_ and _Mod Organizer 2_ both use low-level file system virtualization which most anti-malware programs falsely detect as malicious. 

Particularly intrusive malware solutions such as _Bitdefender_ and _Webroot_ don't propery respect exclusions and cannot be completely disabled -- they must be fully uninstalled. Please consider avoiding third-party anti-malware solutions and relying on _Windows Defender,_ which is more compatible with the applications used to install and play _Wabbajack_ modlists. 

**Set Pagefile to 40GB Or Above**

This can be accomplished in the System Settings for Windows. It is recommended to set the minimum and maximum pagefile size to `20,480` all on one solid state drive as mentioned above. More than one pagefile is unnecessary as long as it is large enough and located on a fast enough drive.

**Ensure Enough Free Storage Space**

As of this writing approximately **170 GB** is required to install this modlist -- **35 GB** for the duplicate _Fallout 4_ folder, **60 GB** for the downloads folder, and **75 GB** for the modlist folder. Approximately **30 GB** of free space is required on your `Windows` drive and **30 GB** additional free space on your `Wabbajack` drive to leave room for temporary files, patches, and caches. Thus the total required space is approximately **230 GB.** These do not all need to be on the same drive.  Finally, never reduce the free space on any drive below **15%** (the bar in _File Manager_ will turn red) or you will suffer severe performance problems.
 
##  Using Wabbajack

The first step is to log in to [The Nexus](https://www.nexusmods.com) with the **GEAR** icon at the top right of _Wabbajack. _ (You have a Nexus account, right?) You will find a login button there. It functions just like the normal Nexus login page, and the "toggle" will switch to "logged in" when you are successful.

If you don't have _Nexus Premium_ you will probably wish for death before this process is over. None of the process will be automated, and you will have to click through hundreds of mod links and interstitial ads, all while enduring torturously slow max download speeds. Please, for your sanity and mine, get at least a month of _Premium._ The money you would save with a free account amounts to about three cents per hour of work clicking on links. You wouldn't take a job for three cents an hour would you? Why would you click on links for hours to save that much money?

The download and installation process can take a very long time depending on your system specs. 

It is advised to have ALL relevant folders (for `Wabbajack.exe`, `Steam`, the modlist folder, and the downloads folder) on a solid state drive. Do not place any of these folders on a hard disk drive, flash drive, or external drive of any kind. After the list is installed, you can relocate **only** the downloads folder to such a drive (or delete it, but that may make updating difficult).

##  Problems with Wabbajack

There are many different scenarios where _Wabbajack_ will produce an error. Re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the minimum necessary to get the modlist working. 

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

I, cacophony, fully accept any responsibility for difficulties with this list and any conflicts I introduce, so please do not question mod authors on the _Nexus_, _Lover's Lab_, _Vector Plexus_ or any other site about bugs that may result from this lists' use. Direct your questions to me, not the innocent mod authors who should never be expected to support a modlist setup.

**Could not download x:**

Some Internet providers have difficulty accessing the servers which host the files comprising the list. Try using a VPN (Virtual Private Network) with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, you may need to delete all corrupt local copies before trying again.

**Wabbajack could not find my game folder:**

_Parabellum_ will not work with a GOG or pirated game version. If you own the game on _Steam,_ return to the Installation step. If this still doesn't work, ensure you are not running Wabbajack as an Administrator. **DO NOT ASK FOR HELP WITH PIRATED GAMES.**

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple _Wabbajack_ lists. I can't support circumventing MEGA's bandwidth restrictions, so either sign up for an account or wait for the timeout to expire.

## Post-Installation

### System Specifications

The system requirements should be just a touch higher than for Vanilla _Fallout 4_. The textures have been significantly upgraded, but no _ENB_ is in use. You won't have performance problems with this list that aren't also in the base game.

The list is configured for a resolution of `2560x1440` by default. It _will_ automatically upscale to higher resolutions at a sacrifice in quality. If you wish to adjust your resolution, select the "INI Editor" from the _Tools_ menu along the icon bar of MO2 and change it via the `Fallout4Prefs.ini` file. Scroll down until you see the `[Display]` header and look for the `iSize` values. Note that the TYPICAL ORDER IS REVERSED, so for 1080p you would set the first value, `iSize H=` to **1080** and the second value, `iSize W=` to **1920.**

If you are confident you meet the above target, but still experience severe performance drops, you may need to customize your `BIOS` settings to maximize your hardware. Refer to your motherboard's documentation.

## NEXT GEN UPDATE

_Parabellum_ once supported **all** _Creation Club_ content in a modular way, where the End User could add as much or as little of it as they wished with no hassles, but unfortunately that has changed with the "Next Gen Update." Most of the _Creation Club Content_ is now incompatible with the version of _Fallout 4_ that I use.

**HOWEVER!** A few of the older versions are compatible, and now that they are included with the game, I can downgrade them to working versions for you. **NEW** to the list, and available without the End User having to take any extra steps, are the following "PAID MODS"...

> Hellfire Power Armor - Kill a psychotic Pyromaniac hiding out in the wilderness to secure this unique, flame-resistant Power Armor.

> X-02 Power Armor - This unique Enclave Power Armor gets co-opted for vigilante justice by a Wasteland Hero known as Black Devil.

> Heavy Incinerator - Brave the Saugus Ironworks to discover this unique Flamer that explodes in a giant fireball to consume clusters of enemies.

> Tesla Cannon - Designed by the US Government pre-war as a lightweight anti-tank weapon, this powerful energy emitter can wreak havoc on armor.

> Enclave Weapon and Armor Skins - I don't know what Sociopath would actually want to use these but I guess they're a good teaser for other Skins.

Unfortunately _Parabellum_ **will not support** any further _Creation Club_ additions until the modlist can be Updated to the most recent version of _Fallout 4._

### Launching the List

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **F4SE** entry in the drop-down menu.

## MCM CONFIGURATION

It may be necessary to press the `Enter` key a few times after you select "New Game" to skip some invisible menu prompts. Then Character Creation will begin.

### WHEN YOU SPAWN IN THE BATHROOM, DO NOT TOUCH ANYTHING!

It may not seem so, but this bathroom is one of the most heavily scripted, system-intensive parts of the whole game because not only are all of _Fallout 4's_ Quests and Scripts initializing, but so are all of _Parabellum's_ Mods, Quests, and NSFW Scripts. This is especially bad with _Sim Settlements 2,_ one of the most heavily scripted, automated _Bethesda_ mods ever, so I **STRONGLY RECOMMEND** just chilling out here for about five minutes. Maybe make yourself a cup of tea, or a sandwich. Hopefully, all of the mods will Initialize, and you will get a bunch of messages appearing and disappearing in the top left of the screen.

This part is easier than with most _Skyrim_ lists. To configure the MCMs, press the `ESC` key and select the top menu option: "MOD CONFIG." At the top left you will see an option to configure MCM settings. Select it. There will be something bad and lazy like "Parabellum Settings" in the large window on the right side. Click "Apply Settings" next to this option, confirm your selection, and wait for a message similar to "30 Settings Applied." Then click the "Reload MCM" option that appears.

That's all there is to it! You're ready to play _Parabellum!_ As a final note, though, I would probably give the list another 5 minutes to finish Initialization after you emerge from Vault 111. Just to be safe. (Seriously, the scripting in this list is absurd, it was strongly recommended that I avoid creating it at all.)

#### A bit of a Note on how to Engage with the NSFW Content

_Parabellum_ uses a new method of playing NSFW animations called _Native Animation Framework_ because it is far less script-heavy than the old method. As a result, many of the mods that allow you to immersively start adult scenes -- such as Persuading people or completing Quests -- don't work with it. The primary way you prompt an adult scene in this modlist is via Hotkeys. 

If you want to proposition someone for sex, hover over them with the crosshair and press `F6.` This will begin a "flirt" dialogue for which success is based on your Charisma and other modifiers. With a small success, you can convince them to remove clothing, which will persist until you re-equip it in their inventory. With a larger success, you can convince them to "get down."

If you want to offer your services to someone as a sex worker, hover over the potential customer with the crosshair and press `F7.` This will begin a negotiation, again based on Charisma, for the price of your services and the customer's willingness to accept your offer.

If you are about to get beat down by **human** enemies (there is no non-human sex in this modlist), you can surrender to them, but you need to do it early. When you are reduced to about half health but remain quite confident you are going to lose, press the `F7` hotkey. This will stop all combat and begin a negotiation with your attacker for "other methods" of getting out of your predicament. Be warned, they may not always go well for you...

If you prefer a much more in-depth, "nasty" take on adult _Fallout 4_, please consider stopping by the _Discord_ server at the bottom of this document and seeking out the _Wasteland of Depravity_ modlist.

#### A Bit of a Note about NUKA RIDE

The _Parabellum NUKA_ version of the modlist has very little content aside from the massive _Nuka Ride_ quest mod and a ton of sexy outfits you can create almost for free on the Chemistry Bench. I don't recommend this version of the modlist if you actually want to play _Fallout 4._ You are meant to create a female character and accept the Eyebot's invitation to be a porn star as soon as he talks to you outside of Vault 111. Then you can make all your **Bimbofication Fantasies** come true.

## Updating the Modlist

Many times newer versions of _Parabellum_ will require an updated version of _Wabbajack_. Please ensure that you run _only_ the `Wabbajack.exe` located in the root of the _Wabbajack_ directory. _Wabbajack_ will automatically update to the latest version if necessary. 

Download the new _Wabbajack_ file, select the "Install From Disk" option, and specify the same directories. Then check the "Overwrite" box. Never update a list without checking this box. If you have customized the list, you can append `[NoDelete]` to the beginning of your added mods in _Mod Organizer 2_ and they will not be deleted. However, they will be unchecked and relocated to the bottom of the list of installed mods. You will need to return them to their rightful place and re-enable or rewrite any patches you created.

It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Parabellum_ folder. 

# IF YOU ENCOUNTER INSTALL PROBLEMS, ERROR MESSAGES, CRASHES, OR OTHER UNEXPECTED BEHAVIOR

Ensure that you have followed **EVERY STEP** of this readme to the letter. Often a reinstall of the list will solve many unusual problems. 

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider giving me a tip. There are donation options ranging from $1 to $35 (with a merch bonus) to extravagant gifts from an Amazon wishlist. Consult my webpage at [cacophony.me](https://cacophony.me) for details. The donation links are at the bottom of the main page.

**cacophony's SubscribeStar:** [https://subscribestar.adult/cacophony](https://subscribestar.adult/cacophony)

**cacophony1979's Patreon:** [https://patreon.com/cacophony1979](https://patreon.com/cacophony1979)

**cacophony1979's Ko-Fi:** [https://ko-fi.com/cacophony1979](https://ko-fi.com/cacophony1979)

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
