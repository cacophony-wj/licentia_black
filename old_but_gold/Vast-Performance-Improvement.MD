# HOW TO VASTLY IMPROVE PERFORMANCE IN LICENTIA 

If your performance is struggling with _Licentia,_ you are going to have to find an alternative to ENB or disable it completely. It's easy to disable, just delete the `d3d11.dll` from the `D:\Licentia\Stock Game` directory. The list will look like crap and everything will be too dark but at least it will be playable for you.

However, there now is a very effective option to increase performance without completely sacrificing the beauty of the list, and it doesn't require a lot of effort. At least compared to previous methods. Let me introduce you to _Community Shaders,_ an alternative to ENB which is **much** less demanding on GPUs and CPUs. With the correct installation of _Community Shaders,_ I was able to maintain over 60fps in almost all exterior areas of _Licentia_ (but I have a 3090).

First off, _Community Shaders_ is not compatible with ENB. You need to delete all remnants of it. Navigate to your "Stock Game" subfolder inside of the directory where you installed "Licentia." Blow away the two files called `d3d11.dll` and `d3dcompiler_46e.dll`. 

Next you need to download _ReShade_, a lightweight means to add visual effects to any _DirectX_ game...

https://reshade.me/

Just download the most recent version. When you launch _ReShade_, it will ask you for the executable for _Skyrim._ I don't recommend scrolling through the entire list, instead just click "Browse..." in the lower right and find the `SkyrimSE.exe` inside _Licentia's_ "Stock Game" folder. Once the path to the EXE appears above, click Next. 

Now it will ask you which version of _DirectX_ you want to use. The correct version, _DirectX 10/11/12_, will already be selected. Click Next.

Now it will ask you for a preset. Just Skip this one.

On the next window, I recommend placing a **FULL CHECKMARK** in **ALL** of the shader boxes here. It's not strictly necessary but I'm a bit fuzzy on what's required and you may want to experiment later anyway. Once you have a **FULL CHECKMARK** in all boxes (sometimes you have to click twice), click Next.

It will take a moment for the shaders to download to the `Stock Game/reshade-shaders` directory. Be patient and then click Finish.

Next up, download the following mods.

**Community Shaders** by doodlez
https://www.nexusmods.com/skyrimspecialedition/mods/86492

**Native Editor ID Fix** by Kitsune
https://www.nexusmods.com/skyrimspecialedition/mods/85260

**KreatE** by Kitsune
https://www.nexusmods.com/skyrimspecialedition/mods/83757

Be sure to get the versions for _Skyrim_ 1.6 or above (specifically the version of the game that I use is 1.6.640). You need to install these into the _Mod Organizer 2_ copy that comes with _Licentia._  Google will give you information on how to install mods into MO2, or you can go to a _Wabbajack_ server and type a command similar to /wjtutorial for a brief video. Load order doesn't matter, as long as the mods are installed and enabled.

The next part is a bit tricky. You're going to have to go to _Community Shaders_ Discord server and download a combination KreatE / ReShade preset called Naturalis. You can find the link on the page above (for _Community Shaders_) underneath the mod's requirements. It reads "Join my server." 

When you arrive in the _Community Shaders_ Discord server, you won't be able to see any of the channels, and Doodlez requires that you verify with _Nexus_ to access them. To do so, click the title of the Server in the upper left (Community Shaders) and choose "Linked Roles" from the dropdown. You need to follow the steps here to login to _Nexus_ and link it to Discord. Hopefully you can figure it out, or you can read this document on how to do so from _Nexus Mods_:

https://modding.wiki/en/nexusmods/discord-bot

When you have your **LINKED ROLE** and a checkmark appears next to _Nexus_ the channels and forums should appear. You're looking for a post called "Naturalis for NAT3" and if you can't find it, the easiest way is probably just to search for "Naturalis" in the search box in Discord's upper right corner.

Scroll through there until you see two files: `Naturalis_for_NAT3_0.2.0.zip` and `Naturalis_for_NAT3_Reshade.zip.` If you click one of the messages in the Search Results and scroll around further, you may be able to find more updated versions of the files. If so, they will probably be a better choice. After that, You need to **EXTRACT** the `Naturalis_for_NAT3_Reshade.zip` file **DIRECTLY** into your "Stock Game" folder. This will put a folder called "Naturalis for NAT3" in "Stock Game."

Now you need to launch _Licentia_ (via the SKSE dropdown in MO2) to begin configuration. The first time the game launches with these mods installed, it will take some time to compile all the shaders (I'd say approximately two minutes). Don't touch anything during this process. 

As soon as the _Licentia BLACK_ main menu comes up, the _ReShade_ UI will appear asking you to go through the tutorial. Press the `HOME` key on your keyboard and choose an option. You can do the tutorial if you wish but I recommend Skipping it. Now you need to select the "Naturalis" preset from the dropdown at the top (it may be in a subfolder). The file is an INI. The effects may not appear immediately so you may need to click a button to reload the shaders.

Sadly, we are going to have to exit the game and come back in. When you launched it the first time, a folder for _KreatE_ presets was spawned inside your MO2 "overwrite" folder. (Refer to Google if you are unsure where to find the overwrite folder.) The Presets folder will be something like `overwrite/KreatE/Presets.` You need to extract and copy the `Naturalis_for_NAT3_0.3.0.zip` in such a way so that the Naturalis preset winds up in the right folder. In 7zip I just double click the first directory, three directories pop up, and I extract those straight to overwrite. Regardless, there needs to be a folder called "Naturalis for NAT3" in this KreatE presets folder with a `PresetInfo.ini` and a bunch of other folders in it.

Now the final step is to load the _KreatE_ preset. Launch _Licentia_ again, wait for the main menu to appear and press the `HOME` key for the _ReShade_ blurb to go away, and then press your `END` key. A small square DOWN ARROW will appear in the upper left corner of the screen. Click this and you will see two options. Select "Editor" (it has a little raincloud to the left of it) and then the "Presets" option from the menu that appears. Here you will see Naturalis under the list of available Presets! Select it, close out of all menus, and press the `END` key again to hide the _KreatE_ menu and enable input into _Skyrim_. Don't worry, once configured, you should only have to do this once.

That should be it! Enjoy your top-end modlist with amazing performance! 
