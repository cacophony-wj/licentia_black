# LICENTIA BLACK

![Licentia Black Splash Screen](images/Splash%20Screen%20with%20Logo.jpg)

## Just a touch darker than before.

### Interested in other NSFW lists? Join my Discord Server!

You can find the link to my Discord server at the end of this document.

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

_Licentia BLACK_ grew from a desire to solve outsanding bugs with the original modlist, _Licentia CLASSIC:_. The performance target for the list has been vastly reduced. The vast majority of the old gameplay from _Licentia Classic_ is here, with an emphasis to expanding _Legacy of the Dragonborn_-associated content. Many of the instructions from the _Licentia Classic_ readme still apply, if you find yourself struggling, please consult that document available [here](https://github.com/cacophony-wj/LeS/.md). You might also find other helpful tips in the `TROUBLESHOOTING.md` document found in that repository.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

## Installation

###  Installing Microsoft Visual C++ Redistributable Package

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ and you can download it from _Microsoft._ Download the x64 version under "Visual Studio 2015, 2017 and 2019" [here](https://aka.ms/vs/16/release/vc_redist.x64.exe).

###  Steam Config

**Change Steam's Update Behavior**

To ensure that _Steam_ does not automatically update _Skyrim_ for you and lock you out of playing your _Wabbajack_ modlist(s), open the Properties window of _Skyrim AE_ in _Steam_, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_. It is incompatible with the profile-specific saves of a _Wabbajack_ modlist.

**Set the Game language to English**

_Wabbajack_ will check your game files and make sure that your installed version is the same as my installed version. This also means that any other language than English will fail the installation. You can change the game's language in the Properties window as mentioned above. It may be required to verify your files afterward.

**Install Skyrim** 

The _Anniversary Edition_ upgrade is required. No exceptions will be made. If you do not have the game installed, do so and launch the vanilla game to download all _Creation Club_ content available with the upgrade. If for some reason you have problems with your _Steam_ installation, you may need to verify the local content as described in _Steam's_ documentation.

**Do Not Use Any Part of This List in a Protected Folder**

This includes `Program Files,` `Program Files (x86)`, `Downloads`, `Documents`, the `Desktop` or any other folders that _Windows_ considers "Protected" (essential to the operating system). If the _Wabbajack_ folder, the _Skyrim Special Edition_ folder, the _Steam_ folder, the modlist folder or the downloads folder are in any of these directories, the modlist will not function properly. Relocate offending folders to a non-Protected location such as the root directory of one of your drives. (D:\ for example.)

**Do Not Use Any Protected Folders inside of OneDrive**

You will experience unusual behavior if your `My Games` folder (usually in the `Documents` folder) is part of a _OneDrive_ Cloud Folder. You will need to relocate it or disable _OneDrive._ There are no exceptions.

**Make Exceptions for Anti-Malware Programs**

Exclude antivirus and anti-malware programs from monitoring three directories: those containing the _Wabbajack_ app, the _Skyrim Special Edition_ game folder, and the directory in which you wish to install the modlist. _Wabbajack_ and _Mod Organizer 2_ both use low-level file system virtualization which most anti-malware programs falsely detect as malicious. 

Particularly intrusive malware solutions such as _Bitdefender_ and _Webroot_ don't propery respect exclusions and cannot be completely disabled -- they must be fully uninstalled. Please consider avoiding third-party anti-malware solutions and relying on _Windows Defender,_ which is more compatible with the applications used to install and play _Wabbajack_ modlists. 

**Set Pagefile to 40GB Or Above**

This can be accomplished in the System Settings for Windows. It is recommended to set the minimum and maximum pagefile size to `40,960` all on one solid state drive as mentioned above. MOre than one pagefile is not needed so long as it is large enough and located on a fast enough drive.

**Ensure Enough Free Storage Space**

As of this writing approximately **20GB** is required for the `Steam` folder, **180 GB** for the downloads folder, and **200GB** for the modlist folder. These do not all need to be on the same drive. Approximately **30GB** of free space is required on your `Windows` drive and **30GB** additional free space on your `Wabbajack` drive to leave room for temporary files, patches, and caches. Finally, never reduce the free space on any drive below **15%** (the bar in _File Manager_ will turn red) or you will suffer severe performance problems.
 
##  Using Wabbajack

The download and installation process can take a very long time depending on your system specs. 

It is advised to have ALL relevant folders (for `Wabbajack.exe`, `Steam`, the modlist folder, and the downloads folder) on a solid state drive. Do not place any of these folders on a hard disk drive, flash drive, or external drive of any kind. After the list is installed, you can relocate **only** the downloads folder to such a drive (or delete it, but that may make updating difficult).

##  Problems with Wabbajack

There are a lot of different scenarios where _Wabbajack_ will produce an error. Re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the bare minimum necessary to get the modlist working. 

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

I, cacophony, fully accept any responsibility for difficulties with this list and any conflicts I introduce, so please do not question mod authors on the _Nexus_, _Lover's Lab_, _Vector Plexus_ or any other site about bugs that may result from this lists' use. Direct your questions to me, not the innocent mod authors who should never be expected to support a modlist setup.

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim. This is not negotiable. Purchase it, verify it, delete it and re-download it if necessary, and try again.

**Could not download x:**

Some Internet providers have difficulty accessing the servers which host the files comprising the list. Try using a VPN (Virtual Private Network) with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, you may need to delete all corrupt local copies before trying again.

**Wabbajack could not find my game folder:**

_Licentia Black_ will not work with a GOG or pirated version of the game. If you own the game on _Steam,_ go back to the Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator. **DO NOT ASK FOR HELP WITH PIRATED GAMES.**

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple _Wabbajack_ lists. I can't support circumventing MEGA's bandwith restrictions so either sign up for an account or wait for the timeout to expire.

## Post-Installation

### System Specifications

To better target your system's capabilities, separate ENB configurations are included. The default is "enb medium" for which the specifications are below.

- Intel i5 or AMD Ryzen 5
- NVIDIA GTX 2060 or AMD Radeon RX 580

You can use tool such as `CPU-Z` or `Hwmonitor` to determine your PC's hardware.

If you are on an extreme potato computer (laptop, Intel graphics), consider deleting the ENB-related files `d3d11.dll,` `d3dcompiler_46e.dll` and the `enbseries` folder, which are located within the `Stock Game` folder in the modlist directory. Afterward, uncheck the _Detection Meter_ mod inside the primary pane of _Mod Organizer 2_ or your game will give a "swapchain" error and crash before launching.

If you are on a low end machine (older than 7-10 years) with any of the following:

- Intel i3 or AMD Ryzen 3 or earlier
- NVIDIA GTX 980 or AMD Vega 64 or earlier

Delete the enb files as described above and the copy all of the files inside the "enb low" directory into the base "Stock Game" folder.

If you are on a high-end machine with

- intel i7 or AMD Ryzen 5600 or later
- NVIDIA RTX 2070 SUPER or AMD Radeon 5700 XT or later

Take the same steps as above, but copy all of the files inside the "enb high" directory into the base "Stock Game" folder.

If you have an extremely powerful machine with

- AMD Ryzen 5800x3D or Intel i7 11900K or later
- NVDIA RTX 3090 or later

This list will likely not exploit your system's full capabilities. If that matters to you, please consider another list.

The list is configured for a resolution of `2560x1440` by default. It will upscale to higher resolutions. Lower ones will have truncated UI elements, you must set these manually in the `SkyrimPrefs` INI.

If you are confident you meet the requirements for one of the above targets, but still experience severe performance drops, you may need to customize your `BIOS` settings to maximize your hardware. Refer to your motherboard's documentation about enabling XMP or DOCP Profiles.

### Launching the List

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **SKSE** entry in the drop-down menu.

If you are interested in a profile with none of the adult mods and much fewer instances of nudity, select the "Licentia SAFE" profile from the dropdown above the list of mods before starting your game.

If you are interested in the stablest version of the list featuring the _OSuite_ series of adult mods, select the "Licentia BLACK" profile from the dropdown menu. 

The "Licentia KAIDAN" profile provides a fleshed out male romantic partner, Kaidan, courtesy of the _Kaidan EXPANDED_ series of mods from [https://kaidanmod.com](https://kaidanmod.com) in addition to Serana. Also available are expanded romance options such as _I'm Glad You're Here, A Skyrim Kiss_ and _Destination Weddings._ 

For the more horny degenerates, I also offer the _Licentia PITCH_ profile which emphasizes the most reliable SexLab quests available on Lover's Lab, along with plenty of Coom. Join my Discord and check #list-updates for further information on these profiles if you are interested in them.

You can find a list of all mods hosted on sites other than Nexus [here](LLGUIDE.md). Please consult this document if you choose to play the "PITCH" profile. I will not offer much support for that profile because I want it to exist more than I want to fix broken mods. As the document mentions, a profile based on a _SexLab_ suite is better served by someone who understands what to watch out for.

## MCM CONFIGURATION

## WHEN YOU SPAWN IN HELGEN'S INN, DO NOT TOUCH ANYTHING!

Wait until the _Fertility Mode_ question appears on your screen. It should be a simple prompt whether to enable Pregnancy, Yes or No.

Choose whether to enable pregnancy and reproductive cycles. Keep in mind that the overhead for this mod can be demanding for weak CPUs. Unless you have role-playing plans involving these features I recommend disabling it or minimizing its impact.

If you answer this question with _YES_, open your Mod Configuration Menu and find the entry for _Fertility Mode._ It is important to limit the scope of the mod if you intend a long-term playthrough.

## Settings Page 1

### Automation

#### Player Only

Checked.

#### Randomly Inseminate PC

Unchecked.

## Settings Page 2

### Preferences

#### Show Verbose Messages

Unchecked.

#### The Widget (ONLY IF FEMALE)

Unchecked.

## Diverse Dragons Encounters

Open the _Diverse Dragons Encounters MCM_ (DDC) and under the "Dragons" entry, **UNCHECK** the following:

O Nether

O Sanguine

O Vile

These dragons feature passive buffs and alternate attacks that make them almost impossible to kill. Of course, you can become near-godlike depending on your _Vokriinator Black_ build, so feel free to leave them enabled if you think you can take it.

## Nether Follower Framework

For immersive follower management, including the need to pay their weekly salaries, choose to "Import File" under the _System_ menu. This is not necessary for hiring requirements from the original game. You should probably at least check "Only Sandbox in Town" under _Activity_ to prevent them from wandering off in dangerous areas.

## VioLens

Go to the "Profiles" section and "Load" a profile. "Sane Violence" enables killmoves on the last enemy in combat. "Ultra-Violence" enables kill moves on every kill and unlocks decapitations from the beginning of the game. They both disable killmoves on the player.

## MCM Recorder

You should **ALWAYS** run the "RUN ME FIRST" recording since this establishes the baseline for the games settings. To do so, click the recording, click OK, close the MCM menu, **TOUCH NOTHING**, and click the "Run Recording" button when it appears. Wait for a message to pop up saying playback is finished, then wait for all messages to disappear in the upper-left corner of your screen. If you are on any profile but _BLACK_ you may receive warnings about missing options. They are unimportant. Skip them.

If you are on an adult profile and prefer some of the women in the game be "futanari" (look it up) run the recording entitled "RUN ME TO ADD FUTA". _This will not make your PC into a futanari._ To do so you will need to find the "Player" options in the MCM and select "ERF Futanari CBBE" as your schlong. The schlong can be adjusted from RaceMenu.

If you want the game to be significantly harder, run the "RUN ME TO MAKE IT HARDER" recording. This will add far more enemies to dungeons and encounters, toughen them up, and make dragons a major pain in the bahookas. It is not as difficult as the old "HARD AS FUCK" recording because that option received quite a few crash reports due to the immense number of enemies.

If you want the game to over-emphasize sexual encounters do the "RUN ME TO MAKE IT SLUTTIER" recording. This will make NPCs proposition you as well as make them more receptive to your advances. It does little else.

Any combination of recordings may be run except the first. You must at least run the first recording.

## FINAL NOTES

When you reach your first exterior world location, you will be prompted to enable _Survival Mode_. With this option enabled, you will not be able to fast travel normally, markers can be placed next to other markers, and you will have to eat food, sleep, and stay warm to survive. (Fast travel can, however, be enabled on _Survival Mode_ by consulting the _Conner's Survival Mode_ MCM.) You will also receive a prompt about which Divine and/or Daedra you wish to worship, depending on your race. Choose according to your preference.

## Updating the Modlist

Many times newer versions of _Licentia_ will require an updated version of _Wabbajack_. Please ensure that you run _only_ the `Wabbajack.exe` located in the root of the _Wabbajack_ directory. _Wabbajack_ will automatically update to the latest version if necessary. 

Download the modlist from the Gallery and specify the same directories. Then check the "Overwrite" box. Never update a list without checking this box. If you have customized the list, you can append `[NoDelete]` to the beginning of your added mods in _Mod Organizer 2_ and they will not be deleted. However, they will be unchecked and relocated to the bottom of the list of installed mods. You will need to return them to their rightful place and re-enable or rewrite any patches you created.

It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Licentia BLACK_ folder. 

# IF YOU ENCOUNTER INSTALL PROBLEMS, ERROR MESSAGES, CRASHES, OR OTHER UNEXPECTED BEHAVIOR

Refer to [Troubleshooting](TROUBLESHOOTING.md). If you can't find your answer there, ensure that you have followed **EVERY STEP** of this readme to the letter. Often a reinstall of the list will solve many unusual problems. If your problem involves an inability to continue a mandatory portion of the game, refer to the _Unofficial Elder Scrolls Pages_ and verify that you are not experiencing a vanilla bug. Try loading a save from before the most recent quest stage or dungeon that you started. If you ignore this documentation you will likely be ignored when you ask for help.

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider giving me a tip. Join my private server and check the pins of the #black channels for options to provide compensation. I work on this thing almost constantly!

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
