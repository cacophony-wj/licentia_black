### If you add or update horny or combat animations to the list, or hell even just regular old normie animations, you will likely need to rerun Nemesis or your characters will "T-Pose."

To do so, ensure that you have installed your animation mods properly, along with any _Nemesis_ patches they may require, and placed any `ESP` included in its proper location in your Load Order (most commonly just above `Schlongs of Skyrim.esp`, **NOT THE ESM**).

_Nemesis_ is the tool used to update _Skyrim's_ behavior files so the animations will be used at the proper time. If this is not done, when that animation is supposed to be played, your PC or NPC will "T-Pose" which means stand bolt erect with arms almost akimbo, or otherwise do absolutely nothing. To solve this problem we must run the _Nemesis_ tool.

First, ensure that all antivirus and antimalware applications are temporarily disabled. They often prevent _Nemesis_ from completing correctly.

Next, launch the tool with the "Nemesis Unlimited Behavior Engine" option on the main dropdown menu of MO2. You will need to verify that all of the behavior patches are checked appropriately. For the default version of _Licentia_, these include the following options:

- Archery Gameplay Overhaul SE
- TUDM Attack Cancel
- Extra Drawing Animations
- Combat Gameplay Overhaul SE
- Skyrim's Paraglider
- Retimed Hit Frame
- The Ultimate Dodge Mod

If your chosen animation mod is included anywhere in this list, _it also needs to be checked._

The _Nemesis Engine_ will require an update if you add a mod with behavior changes, so first click "Update Engine" and wait for the bar to reach 100%. If the process errors out you will need to keep trying until it completes. If you can't get it to go after multiple tries something may be wrong with your chosen animation mod's behavior files and you will be forced to discard it.

After that is done, click "Launch Nemesis Behavior Engine." The tool will slowly integrate your animation files into the behaviors. This process may look as if it is stuck or not responding, give it about five minutes before giving up. If it does not complete, or it does not reach 100%, your run has errored out and you must keep trying.

The tool can be rather inconsistent at times. Give it a good old College Try until it finally finishes up for whatever inexplicable reason. 

Sometimes it will never complete regardless of how many times you try and additional troubleshooting is needed. There are still options to fix this however! Find the _KAIDAN Output_ folder (reference to a previous version of the list) and delete **every file located inside,** then **refresh MO2** by striking the `F5` key. 

Ensure that your _KAIDAN Output_ folder is still empty and launch _Nemesis_ a final time. It will prompt for your language -- make certain that it is English -- and you will need to check all the proper boxes again. Then update and run the tool once more. 

If this **STILL** does not work, you must reset all default behavior files by reinstalling the mod _Project New Reign - Nemesis Behavior Engine_ under the **SFW Animations** section of MO2. You can do this by simply right-clicking on it and choosing Reinstall. There shouldn't be any options you need to configure. It should be almost guaranteed to work this time. If it doesn't, I am stumped, and you will need to resort to Google.

Once you do finish running _Nemesis_ successfully, **refresh MO2** with the `F5` key.

You will notice that it created a blank, dummy `ESP` called `FNIS.esp` at the bottom of your Load Order. Right click on it, select "Open Origin in Explorer" and **delete it.** Normally the _XMPSE_ skeleton mod requires this ESP to function, but that requirement has been removed with another mod in this list. This `ESP` is just a waste of space.

That's all there is to it! If you have questions, drop by and ask in my #les-adds-talk channel.
