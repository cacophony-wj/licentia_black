# LICENTIA BLACK!

## Just a touch darker than before.

### Interested in other NSFW lists? Join my Discord Server!

You can find the link to my Discord server at the end of this document.

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

_Licentia BLACK_ grew from a desire to solve outsanding bugs with the original modlist, _Licentia CLASSIC:_. The performance target for the list has been vastly reduced. The vast majority of the old gameplay from _Licentia Classic_ is here, with an emphasis to expanding _Legacy of the Dragonborn_-associated content. Many of the instructions from the _Licentia Classic_ readme still apply, if you find yourself struggling, please consult that document available [here](https://github.com/cacophony-wj/LeS/blob/master/README.md).

## FEATURING ARTIFACTS OF SKYRIM REVISED AND STAFF ENCHANTING!

Go [here](MODGUIDE.md) for credits and descriptions of the major mods in _Licentia_.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

### System Specs

- CPU: >= 7th gen Intel, OR >= AMD Ryzen 3000 series
- GPU: >= NVIDIA RTX 1080, OR >= AMD 5700XT
- RAM: >= At least 8GB
- PAGEFILE: >= At least 20 GB
- SSD with at least 350 GB of space available

## Installation

##  Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to **Updating**  in the **Troubleshooting** section.

###  Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017 and 2019". <a href="https://aka.ms/vs/16/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

###  Steam Config

**Change Steam's Update Behavior**

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you and lock you out of playing your _Wabbajack_ modlist(s), head over to the Properties window, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_ while you're at it.

**Set the Game language to English**

Wabbajack will check your game files and make sure that we have the same version. This also means that any other language than English will fail the installation.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

**Install Skyrim** 

The _Anniversary Edition_ upgrade is required. No exceptions will be made. If you do not have the game installed, do so and launch the vanilla game to download all _Creation Club_ content available with the upgrade.

**Disable or Uninstall Offensive Anti-Malware Programs**

Exclude antivirus and anti-malware programs from monitoring three directories: those containing the _Wabbajack_ app, the _Skyrim Special Edition_ game folder, and the directory in which you wish to install the modlist. _Wabbajack_ and _Mod Organizer_ 2 both use low-level file system virtualization which most anti-malware programs falsely detect as malicious. 

Particularly intrusive malware solutions such as _Bitdefender_ and _Webroot_ don't propery respect exclusions, they must be completely uninstalled. Please consider avoiding third-party anti-malware solutions and relying on _Windows Defender,_ which is more compatible with the applications used to install and play _Wabbajack_ modlists. It is more than sufficient for legitimate Internet activity.

##  Using Wabbajack

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. 

    Adjust the Installation Location to a directory located on the root directory of one of your drives
    For example, this might be "C:\Licentia", "D:\Licentia", or "E:\Licentia"
    Ensure the Download Location is where you wish it to be, it defaults to a location within the directory just above
    Click the Go/Begin button

To have the highest amount of threads and thus the fastest speed, it is advised to have ALL of the folders (for `Wabbajack.exe`, the modlist folder, and the downloads folder) on an SSD. 

##  Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

I, cacophony, fully accept any responsibility for difficulties with this list and any conflicts I introduce, so please do not question mod authors on the _Nexus_, _Lover's Lab_, _Vector Plexus_ or any other site about bugs that may result from this lists' use. Direct your questions to me, not the innocent mod authors who should never be expected to support a modlist setup.

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim. This is not negotiable. Purchase it, verify it, delete it and re-download it if necessary, and try again.

**Could not download x:**

Some Internet providers have difficulty accessing the servers which host the files comprising the list. You might try using a VPN with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, you may need to delete all corrupt local copies before trying again.

**x is not a whitelisted download:**

This can happen when update the modlist receives an update. Check if a new update to the modlist is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the Pre-Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator. DO NOT ASK FOR HELP WITH PIRATED GAMES ON THE WABBAJACK DISCORD.

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple Wabbajack lists. I can't support circumventing MEGA's bandwith restrictions so either sign up for an account or wait for the timeout to expire.

## Post-Installation

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **SKSE** entry in the drop-down menu.


## MCM CONFIGURATION

## WHEN YOU SPAWN IN HELGEN'S INN, DO NOT TOUCH ANYTHING!

Wait until the _Fertility Mode_ question appears on your screen. 

Choose whether to enable pregnancy and reproductive cycle issues by answering yes or no. Keep in mind that the overhead for this mod can be demanding for weak CPUs. Unless you have role-playing plans involving these features I recommend disabling it or minimizing its impact.

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

You should only run **ONE** of these! (Please choose at least one, each configures a baseline setup that is recommended for this modlist.) 

O I want it fun!
O I want it immersive.

Then close the MCM Menu, **TOUCH NOTHING**, and click the "Run Recording" button when it appears. Wait for all messages to stop and a message to pop up saying playback is finished. 

You might have noticed there are several other options here. You can run as many of them additionally as you wish.

"I want it hard as FUCK!" vastly increases the difficulty of dragon and modded encounters as well as adds up to 40 - 80 additional enemies in every dungeon or zone. 

 "I want it slutty!" makes it so that NPCs are more responsive to your advances, enables your clothes being knocked off during combat, and increases the frequency that you get exploited in other ways rather than killed. 

Controller options will be updated soon.

## FINAL NOTES

When you reach your first exterior, you will be prompted to enable _Survival Mode_. It is recommended for playthroughs using the immersive setting, and not recommended otherwise. Even with it enabled, you can still use fast travel by consulting the _Conner's Survival Mode_ MCM. You will also receive a prompted about which deity you wish to worship, depending on your race. Choose according to your preference.

## Updating the Modlist

Many times newer versions of _Licentia_ will require an updated version of _Wabbajack_. Please ensure that you run _only_ the `Wabbajack.exe` located in the root of the _Wabbajack_ directory. _Wabbajack_ will automatically update to the latest version if necessary. 

Download the modlist from the Gallery and specify the same directories. Then check the "Overwrite" box. 

It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Licentia BLACK_ folder. 

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider donating to me in any amount of one dollar or more via my [Patreon](https://www.patreon.com/cacophony1979) or my [Ko-Fi](https://ko-fi.com/cacophony1979). Your donation will better the quality of my life and ensure that I can spend more time improving _Licentia,_  as well as providing a healthy dose of motivation.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
