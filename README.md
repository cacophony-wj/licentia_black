![Licentia Black Logo](images/4k_licentia_logo.webp)

# Licentia

## "All I want to be is a badass comic book hottie who fucks and cuts heads."

## Preamble

**This Modlist contains mods with sexual content, and you must be of legal age in your country (most Western countries: 18+, some Eastern ones: 21+)**.

_Licentia_ is one of _Wabbajack's_ oldest and most well-regarded adult modlists, featuring optional non-fetish content with the _OSuite_ series of _OStim_ mods and an emphasis on build variety, backed up by an accessible Power Fantasy design philosophy. 

**Do you like kicking ass in a high-powered RPG with "spicy," sexually explicit romances?**

Play _Licentia._ (This modlist.)

**Do you like kicking ass in a high-powered RPG but also sometimes roleplaying as a sex slave?**

Play _Servitium._

#### More Information

If you want to examine a complete list of the mods in this modlist, [go here.](https://loadorderlibrary.com/lists/licentia-black-2)

### System Specifications

The recommended setup for an enjoyable experience **at 1080p** is at least

- intel i7 or AMD Ryzen 5600 or later
- NVIDIA RTX 2070 SUPER or AMD Radeon 5700 XT or later

### Requirements

- [Nexus Account](https://nexusmods.com/)

This account is mandatory; it must be created before continuing. Nexus Premium is strongly recommended or the installation will take many more hours (possibly days).

## Installation

Before you do anything with _Wabbajack,_ ensure that _Skyrim_ is installed in a non-protected folder (such as the root of your drive, like `C:\`). It **cannot** be located in _Program Files_ or the list will not function. Relocate the game as necessary.

For _ Wabbajack _ to match its files,_Skyrim_ needs to be set to the English language. Other languages will not work.

_Licentia_ requires the additional _Creation Club Content_ from the _Skyrim Anniversary Edition Upgrade_ or the modlist will not install. The price is about $20. 

Create a directory on the root of one of your Solid State drives (such as `D:\Licentia`) where you wish the modlist to be installed. You need at least **600GB** free for this modlist and a few GBs in the _Wabbajack_ and _OS_ drives for caches. About half of these GBs are mod downloads; the downloads folder can be deleted or relocated after installation.

Ensure you have set antivirus exceptions for this folder, the _Skyrim_ vanilla game folder, and the _Wabbajack_ folder, or the installation will fail. Certain antivirus packages do not properly respect exceptions and cannot be fully disabled (_Webroot_ and _Bitdefender_ are examples of these). These tools must be uninstalled from your system.

Ensure that _OneDrive_ is **uninstalled** or **completely disabled.** This program locks some of _Skyrim_'s configuration files when in use and will cause the modlist to experience errors.

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ and you can download it from _Microsoft._ Download the x64 version under "Visual Studio 2015, 2017 and 2019" [here](https://aka.ms/vs/16/release/vc_redist.x64.exe).

You must set your Advanced Memory Pagefile to at least 40GB or the modlist will constantly crash. On _Windows 11_ you can find this setting in the About page for your PC. [Here](https://www.windowscentral.com/software-apps/windows-11/how-to-manage-virtual-memory-on-windows-11) is a document to find the specific option; other versions of Windows are similar. Setting the minimum and maximum pagefile size to `40,960` on one Solid State Drive is recommended. 

## The One File

The most common support question is a report that the _Kaidan_ file failed to download. Save yourself a lot of trouble and download it in a web browser, outside of _Wabbajack._ You can find this file [here.](https://mega.nz/file/0dcilQ6Y#LZbAPMNQmKdd2ZCOOaJesRi15v6n-9wuT37KM6FiwEA) Save it somewhere you'll remember it; if you receive an error that it failed, copy it into your _Licentia_ Downloads folder and restart the app.
 
##  Using Wabbajack

Login to _Nexus_ with the _Wabbajack_ app. This login can be found by clicking the **GEAR** icon in the top right. It will toggle over to "logged in" when successful.

Depending on your system specs, the download and installation process can take a long time. 

##  Problems with Wabbajack

There are many different scenarios where _Wabbajack_ will produce an error. Re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the minimum necessary to get the modlist working. 

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim, and this is not negotiable. Purchase it, verify it, delete it and re-download it if necessary, and try again.

**Could not download x:**

Some Internet providers have difficulty accessing the servers hosting the list's files. Use a VPN (Virtual Private Network) with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, delete all corrupt local copies before trying again.

**Wabbajack could not find my game folder:**

_Licentia Black_ will not work with a GOG or pirated game version. If you own the game on _Steam,_ return to the Installation step. If this still doesn't work, ensure you are not running Wabbajack as an Administrator. **Asking for help with pirated copies of the game will get you banned from Discord Support.**

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple _Wabbajack_ lists. Sign up for an account or wait for the timeout to expire.

## Post-Installation

### Verifying the Modlist

_Licentia_ is over 500GB in size. Given the likelihood of corrupted files during installation, it is strongly recommended that files be checked after installation.

To verify the modlist, click the Gear icon in the upper right. Click the button along the middle left that reads "Launch Wabbajack CLI." Type the following commands:

`cd cli`

`wabbajack-cli verify-modlist-install -m "path to the Licentia.wabbajack file" -i "Licentia install folder path"`

Obviously, you will need to replace the portions in quotations with the specific file locations on your system. The Command Line Interface will hash and verify every file in the list against a known signature.

I recognize that many people are unfamiliar with file paths and how to type in command-line commands. Most modern devices never require such knowledge. [Here](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands/) is a comprehensive guide on how to use the command line. I realize this solution is not ideal, but until a Verify button is added to _Wabbajack_, this step will remain necessary for larger modlists. Note the location of your `Licentia.wabbajack` file and your `X:\Licentia` directory and do the best you can.

You must reinstall the list until every file returns as a 100% match. This may be much more difficult if your Internet connection is poor, or the _Wabbajack_ app is frequently interrupted. Do note that if you launch _Mod Organizer 2_, you just changed some of the files, so they will not verify. Do not touch anything before verifying.

### Tweaking the Modlist

If you wish to change your game's resolution, select the "INI Editor" from the _Tools_ menu along the icon bar of MO2 and change it via the `SkyrimPrefs.ini` file. Scroll down until you see the `[Display]` header and look for the `iSize` values. Note that the TYPICAL ORDER IS REVERSED, the HEIGHT is listed BEFORE the WIDTH.

If you are confident you meet the above target, but still experience severe performance drops, you may need to customize your `BIOS` settings to maximize your hardware. Refer to your motherboard's documentation. The most common failure point is too-low RAM speed, which can often be addressed by enabling the "XMP" or "DOCP" profiles.

### Launching the Modlist

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **SKSE** entry in the drop-down menu.

### Configuring MCMs for the Modlist

## WHEN YOU SPAWN IN HELGEN'S INN, DO NOT TOUCH ANYTHING!

This modlist now configures itself! Sadly, it takes a long time to accommodate slow CPUs and lower-end systems. After creating your character, sit tight and wait about five minutes. Fix yourself a cup of tea, sip and relax, and wait until you see the Command Word: **QUELISH**

Ignore anything that happens beforehand.

## FINAL NOTES

When you reach your first exterior world location, you will be prompted to enable Survival Mode. This mod disables fast travel and requires eating, sleeping, and staying warm to survive. The option can be changed later in the default "Gameplay" settings of Skyrim.

You will also receive a prompt about which Divine and/or Daedra you wish to worship, depending on your race. Choose according to your preference.

## TROUBLESHOOTING

Refer to [Troubleshooting](TROUBLESHOOTING.md) for answers to common problems with the modlist.

## Updating the Modlist

Download the modlist's `.wabbajack` file again and specify the same directories. _Wabbajack_ will only update what has changed, it will not repeat the entire installation. It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Licentia_ folder. 

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

For more information about me, as well as ways to show your appreciation for my work, visit https://cacophony.me

My _Licentia_ related email is cacophony-wj@outlook.com.

