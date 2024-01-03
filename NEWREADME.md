# PLEASE DO NOT CLOSE THIS WINDOW. 

### THIS DOCUMENT MUST BE FOLLOWED FOR LICENTIA TO WORK PROPERLY.

![Licentia Black Logo](images/4k_licentia_logo.webp)

# Licentia

## "All I want to be is a badass comic book hottie who fucks and cuts heads."

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

_Licentia_ is one of _Wabbajack's_ oldest and most well-regarded adult modlists, featuring optional non-fetish content with the _OSuite_ series of _OSA / OStim_ mods and an emphasis on build variety, backed up by an accessible Power Fantasy design philosophy. 

### System Specifications

The recommended setup for an enjoyable experience **at 1080p** is at least

- intel i7 or AMD Ryzen 5600 or later
- NVIDIA RTX 2070 SUPER or AMD Radeon 5700 XT or later

### Requirements

- [Nexus Account](https://nexusmods.com/)
- [LoversLab Account](https://www.loverslab.com/)

These accounts are mandatory, they must be created before continuing. _Nexus Premium_ is strongly recommended or the installation time will take many more hours (possibly days).

## Pre-Installation

The _Lover's Lab API_ (automatic download interface) is no longer available due to technical considerations, so it is recommended to download all mods from there in a normal web browser _before launching Wabbajack._ In addition, several files from other third-party hosts such as _MEGA_ and _Google Drive_ often have difficulty, so those must be downloaded as well. To do so, take the following steps.

Create a directory for your chosen modlist. Something in the root folder of a fast Solid State Drive, or -- ideally -- an M.2 NVME. (Something like `D:\Licentia`). 

Within that directory, create another directory called `downloads` -- in all lower case. (`D:\Licentia\downloads`)

Refer to [this document](DOWNLOADS.md) for links to all of the External Mods you need to download. Place all of the files in the `downloads` directory you created above. **DO NOT EXTRACT THEM,** they need to be _exactly_ as downloaded from the website.

## Installation

The _Skyrim Special Edition 1.6.1130 Update_ appears to have various technical problems with its release that make it difficult to acquire and verify the proper base game files. It is recommended to delete your copy of _Skyrim_ locally before continuing. While not ideal, the process will involve multiple manual file deletions, downloads and verifications if you don't.

Reinstall _Skyrim_ via _Steam,_ then use the internal tool to "Verify Integrity of Game Files." 

This modlist requires the _Skyrim Anniversary Edition Upgrade_ or it cannot be installed. You must ensure that you have purchased this DLC and that it is enabled on your _Steam_ Account. You can verify this information from the game's Store Page. 

Next launch the Vanilla Game from Steam (it doesn't matter what options are chosen in the Launcher), and the game should prompt you to download the _Anniversary Edition Content._ If it does not, click the **Creations** menu option along the bottom right. Click the **[O] OPTIONS** button at the bottom of the screen. From the menu that appears, select **Download all owned Creation Club Creations.**

The download process for the _Anniversary Edition Upgrade Content_ will begin after this and takes about five minutes. _Skyrim_ must remain in the foreground or it will be interrupted.

###  Installing Microsoft Visual C++ Redistributable Package

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ and you can download it from _Microsoft._ Download the x64 version under "Visual Studio 2015, 2017 and 2019" [here](https://aka.ms/vs/16/release/vc_redist.x64.exe).

###  Steam Config

**Change Steam's Update Behavior**

To ensure that _Steam_ does not automatically update, open the Properties window of _Skyrim Special Edition_ in _Steam_, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_. It is incompatible with the profile-specific saves of a _Wabbajack_ modlist.

**Set the Game language to English**

The modlist will not install unless it can verify that _Skyrim_ is in English. If you change the language, you may need to Verify Local Files again.

**Do Not Use Any Part of This List in a Protected Folder**

This includes `Program Files,` `Program Files (x86)`, `Downloads`, `Documents`, the `Desktop` or any other folders that _Windows_ considers "Protected" (essential to the operating system). If the _Wabbajack_ folder, the _Skyrim Special Edition_ folder, the _Steam_ folder, the modlist folder or the downloads folder are in any of these directories, the modlist will not function properly. Relocate offending folders to a non-Protected location such as the root directory. (D:\ for example.)

**Do Not Use Any Protected Folders inside of OneDrive**

You will experience unusual behavior if the `My Games` folder (usually in the `Documents` folder) is part of a _OneDrive_ Cloud Folder. Relocate it or disable _OneDrive._ 

**Make Exceptions for Anti-Malware Programs**

Exclude antivirus and anti-malware programs from monitoring three directories: those containing the _Wabbajack_ app, the _Skyrim Special Edition_ game folder, and the directory in which you wish to install the modlist. The list will not install or run properly otherwise. Particularly intrusive malware solutions such as _Bitdefender_ and _Webroot_ must be fully uninstalled due to technical limitations. Unfortunately, _Windows Defender_ is the only recommended antimalware solution one should use with _Wabbajack._

**Set Pagefile to 40GB Or Above**

On _Windows 11_ you can find this setting in the About page for your PC. [Here](https://www.windowscentral.com/software-apps/windows-11/how-to-manage-virtual-memory-on-windows-11) is a document to find the specific option; other versions of Windows are similar. It is recommended to set the minimum and maximum pagefile size to `40,960` all on one Solid State Drive as mentioned above. 

**Ensure Enough Free Storage Space**

As of this writing approximately **20GB** is required for the `Steam` folder, **228 GB** for the downloads folder, and **386 GB** for the modlist folder. Approximately **30 GB** of free space is required on your `Windows` drive and **30 GB** additional free space on your `Wabbajack` drive to leave room for temporary files, patches, and caches. Thus the total required space is approximately **694 GB.** These do not all need to be on the same drive. 
 
##  Using Wabbajack

Login to _Nexus_ with the _Wabbajack_ app. This login can be found by clicking the **GEAR** icon in the top right. It will toggle over to "logged in" when successful.

The download and installation process can take a very long time depending on your system specs. 

It is advised to have ALL relevant folders (for `Wabbajack.exe`, `Steam`, the modlist folder, and the downloads folder) on a solid state drive. Do not place any of these folders on a hard disk drive, flash drive, or external drive of any kind. After the list is installed, you can relocate **only** the downloads folder to such a drive (or delete it, but that may make updating difficult).

##  Problems with Wabbajack

There are a lot of different scenarios where _Wabbajack_ will produce an error. Re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the bare minimum necessary to get the modlist working. 

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim. This is not negotiable. Purchase it, verify it, delete it and re-download it if necessary, and try again.

**Could not download x:**

Some Internet providers have difficulty accessing the servers which host the files comprising the list. Use a VPN (Virtual Private Network) with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, delete all corrupt local copies before trying again.

**Wabbajack could not find my game folder:**

_Licentia Black_ will not work with a GOG or pirated version of the game. If you own the game on _Steam,_ go back to the Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator. **Asking for help with pirated copies of the game will get you banned from Discord Support.**

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple _Wabbajack_ lists. Sign up for an account or wait for the timeout to expire.

**Unable to Download Archives.**

If _Wabbajack_ terminates without a green "COMPLETE" success box and instead gives you this message, refer to the manual download links at the top of this document. Almost all of the files that commonly fail are listed there. 

## Post-Installation

### Verifying the Modlist

_Licentia_ is over 500GB in size. To install the list, _Wabbajack_ downloads and patches hundreds of thousands of files. During the installation process several of these files are likely to have failed or corrupted in some way. Before finishing up with the _Wabbajack_ app, it is **strongly recommended** to run a file verification step or the modlist may be nearly unplayable.

To verify the modlist, click the Gear icon in the upper right once again. Click the button along the middle-left that reads "Launch Wabbajack CLI." Type the following command:

`wabbajack-cli verify-modlist-install -m "path to the Licentia.wabbajack file" -i "Licentia install folder path"`

Obviously you will need to replace the portions in quotations with the specific file locations on your system. The Command Line Interface will hash and verify every file in the list against a known signature.

You must keep reinstalling the list until every file returns as a 100% match. This may be much more difficult if your Internet connection is poor, or the _Wabbajack_ app is frequently interrupted.

### Tweaking the Modlist

If you wish to change your game's resolution, select the "INI Editor" from the _Tools_ menu along the icon bar of MO2 and change it via the `SkyrimPrefs.ini` file. Scroll down until you see the `[Display]` header and look for the `iSize` values. Note that the TYPICAL ORDER IS REVERSED, the HEIGHT is listed BEFORE the WIDTH.

If you are confident you meet the above target, but still experience severe performance drops, you may need to customize your `BIOS` settings to maximize your hardware. Refer to your motherboard's documentation. The most common failure point is too-low RAM speed, which can often be addressed by enabling either the "XMP" or "DOCP" profiles.

### Launching the Modlist

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **SKSE** entry in the drop-down menu.

### MCM CONFIGURATION

### WHEN YOU SPAWN IN HELGEN'S INN, DO NOT TOUCH ANYTHING!

Wait until all the messages appear then disappear in the upper left corner of the screen. Then you may continue.

### MCM Recorder

Find the _MCM Recorder_ menu in the _Mod Configuration_ menu accessible via the `ESCAPE` key or the `START` button. 

Execute the **"READ README THEN RUN ME"** recording. Confirmation requires that you close the MCM Menu and select "Run Recording." Do not touch anything until all messages disappear in the Upper Left.

If you prefer _futanari_ style content, run the optional **"RUN TO ADD FUTA**" MCM Recording. This will give all females in the game a 10% chance for futanari "enhancement." To add this enhancment to the player, check the "Player/NPC" settings in the _Schlongs of Skyrim_ MCM.

Everything should now be configured automatically. Enjoy the modlist!

## FINAL NOTES

When you reach your first exterior world location, you will be prompted to enable _Survival Mode_. This mod disables fast travel and requires eating, drinking, and staying warm to survive. The option can be changed later in the default "Gameplay" settings of _Skyrim_.

You will also receive a prompt about which Divine and/or Daedra you wish to worship, depending on your race. Choose according to your preference.

### Confused about where to begin?

[Try a helpful _Licentia_ starting guide](https://www.canva.com/design/DAF1LecdP9M/zve9MIfRDE2D50dxXsBEWA/edit) by my friend @Charlistic!

## Updating the Modlist

Download the modlist's `.wabbajack` file again and specify the same directories. _Wabbajack_ will only update what has changed, it will not repeat the entire installation. It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Licentia_ folder. 

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

For more information about me, as well as ways to show your appreciation for my work, visit https://cacophony.me

My _Licentia_ related email is cacophony-wj@outlook.com.

