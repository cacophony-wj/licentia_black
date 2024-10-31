
### How to run BodySlide.

First, launch the _BodySlide_ app from the dropdown in _MO2_ (same place that _SKSE_ can be found). You may wish to ensure that the _BodySlide_ data folder is set correctly so that each armor's textures and meshes from the modlist appear. To do so, click the "Settings" button near the bottom right corner. Along the top you will see a directory marked "Game Data Path." Make certain this is your `Stock Game`'s `data` folder inside your modlist folder (on my system that's `D:\Wabbajack\Licentia\Stock Game\data`). If not, you may preview an armor or body and see blank or incorrect textures.

The _BodySlide_ window _looks_ complicated, but it becomes simpler the more you become familiar with it. The first step is to clear out any remainder of old BodySlide runs that I may have made. In the top right corner are two boxes, the "Group Filter" and the "Outfit Filter." You need to click the gray `X` in each of these boxes to clear any filters that are there, so that you can select from all of the outfits that are installed for the list. 

This process involves running _BodySlides_ for **all** bodies first, and then any _SLOOT_ or _HIMBO_ options you prefer afterward, to overwrite the originals. The first step is to close _MO2_ and create a folder in the `\Licentia\mods` folder called something like "[NoDelete] My BodySlide Output." (The `[NoDelete]` will ensure that when you Update the list, your _BodySlides_ will not be deleted.) Once this is done, re-launch _MO2_ and you will see your "My BodySlide Output" folder at the bottom. Just ensure that it is checked and leave it there.

Next you need to choose the proper _BodySlide_ preset. The selection you make can vary depending on whether or not you have _OBody_ in your modlist. I have found that _OBody_ has frequent enough crashes that I prefer not to use it for my primary profile, so this mod is not present in _Licentia_ but remains in _Servitium_

**If you are using _OBody_** only the "- Zeroed Sliders -" option from the "Preset" dropdown will work properly in this list, because of how _OBody_ works. Don't worry, you will be able to customize your proportions via _OBody_ while in-game. Select it and continue.

**If you are not using _OBody_** you can either choose my variable preset "Cacophony-Varied" or install your own. (Which is outside the scope of this guide.) "Cacophony-Varied" mimics the effects of _Obody_ by making each female petite or voluptuous based on the default "Weight" value for each NPC created by _Bethesda._ (Most of them are Weight 100, which is pretty thicc.) 

After you have chosen your _BodySlide_ Preset, **HOLD DOWN THE LEFT CONTROL BUTTON ON YOUR KEYBOARD** (very important) and click "Batch Build..." in the lower left corner of BodySlide. A list of bodies and outfits will appear -- you need to **RIGHT CLICK AND CHOOSE SELECT ALL** and click the "Build" button.

A prompt will appear asking you which Windows directory you want your BodySlide meshes to be saved to. **This step is important because without it, the meshes will overwrite the ones that are already installed in the list with your new proportions -- instead of creating copies elsewhere.** You are going to have to navigate to the "My BodySlide Output" directory you created earlier. (This should be something like `C:\Licentia\mods\[NoDelete] My BodySlide Output`) Once this directory is selected, click the "Select Folder" button.

There may be some situations in which you have to choose options when multiple versions of the same body or outfit are installed. You need to ensure that you choose the "3BBB or 3BA" options or the physics will not work properly. For the Nude Body, you need to **ALWAYS** choose "CBBE 3BA Body Amazing" for the female and "HIMBO SOS Thong" for the male (the body will only have a thong until the SOS Schlong becomes attached -- usually in milliseconds.) If you are concerned about how these variants look, cancel out of this Batch Build Process and preview the various versions in _BodySlide_ to see which you prefer.

The outfits will build to the proper directory rather quickly. Ignore any error messages unless they are related specifically to your chosen outfit. If you receive them, drop a note in my #les-modified channel for assistance. (A little searching and reading of old _Discord_ messages may be necessary -- as well as waiting around for someone to respond -- so please, have a smoke or a cup of Chai Tea or something and ready yourself to be patient.)

Afterward, you need to repeat the process for any SLOOT and HIMBO options you wish to use. (If you are not concerned about these options, you can ignore this part.) For HIMBO, you need to click the "Group Filter" option in the top right again and **place checkboxes in each of the HIMBO options.** The rest of the process will be same, you specify the exact same Output folder and everything, you simply need to ensure that:

**If you are using _OBody_** only the "HIMBO - Zeroed" option from the "Preset" dropdown will work properly.

**If you are not using _OBody_** I recommend my Preset called "HIMBO Varied" but you can install or create your own.

Follow the same steps as before with batch building, selecting all, specifying your options and whatnot.

Lastly, if you are wanting to make your PCs and NPCs wear slooty outfits you will need to build them over the top of the Non-SLOOTY versions. This process will require a little deduction on your part -- the Sloot Armor is called "BD's Armor Replacers" for the females and "KSO Himbo Outfits" for the males, as well as any _DeserterX_ armors (only in _Servitium_) or custom outfits you may have added. These are the entries you need to check in the "Group Filter" mentioned earlier. **DO NOT PLACE CHECKBOXES IN ANY OTHER FILTERS.**

That is all you need to do to get them working, but you may wish to verify that they were placed in the proper folder before you finish up. To do so, find the directory you built the BodySlides to with Windows File Explorer and check it. There should be a `meshes` folder inside with a bunch of other directories, and inside that `meshes` folder **there must not be a second meshes folder.** If there is, the BodySlide building process glitched out and you will not see them in game. You need to delete any errored meshes folders and do the process all over again, ensuring that you have chosen the proper "BodySlide Output" directory.

For Final Confirmation, you can double click your "My BodySlide Output" "mod" in _MO2_ and check the "Conflicts" tab. Ensure that all of your outfits in this folder are overwriting the versions already in the list, and **Are not overwritten themselves.** If they are overwritten, you will need to move the "My BodySlide Output" "mod" lower down in the list of mods (higher priority.)

That's all you need to know. Please remember that if you get impossibly lost or your list becomes horribly messed up, one of the greatest advantages of _Wabbajack_ is that you can simply install over your copy of the list and return to a fully working setup.

For all other questions or problems, stop by my #les-modified forum available at https://discord.gg/jolly-coop!!

### ENJOY!
