# CACO's COMMISSIONS - 

### Or: Commonly Requested Additions to LICENTIA BLACK, An ever-evolving document

## UPDATED 10/23/2023.

#### These additions are only supported on the main UI profile, _Licentia BLACK_ (not _Licentia MAX_). Functionality on other profiles is NOT guaranteed.

#### Hey there!

Occasionally I get requests to make simple additions to the list, and even more occasionally I accept a small tip to do this on behalf of someone. _Wabbajack_ Terms of Use require me to make all such "work" publicly available to anyone who utilizes the app, so here you will find the below guides that I made for my most generous Users. If you have a handful of mods to add, why not stop by https://discord.gg/jolly-coop and ask to make use of my services? I can't guarantee that I'll accept your request, but if I do, I can guarantee you would likely spend more for a shitty almost-food meal at _Taco Bell._

## CONVERTING TO "MINISLOOT"

Some users might like the idea of sexy armors available in boss chests, primarily to use on their character or followers, but feel a bit skeeved out by the idea of every lady in the game walking around with their meat hanging out. For those people, I offer the following guide on how to convert a **SLOOT** profile to **MINISLOOT.** (A commission for @DigitalTravis.)

Begin by enabling the "Non-Skimpy Book of UUNP Patch" in the load order, under the **Merges & Patches** header. If you're having trouble finding it, you can search for it in the box near the bottom of MO2. Just put a check in it and Refresh with `F5`.

Now find the **Optional SLOOT** section of mods and disable the following:

- _Skimped Creation Club AIO_
- _BDs Armor and Clothes Replacer CBBE 3BA_
- _Skyrim Vixens - LOTD Paintings_

This may generate an error for Missing Masters in some of the `Synthesis` ESPs. If so you will need to run _Synthesis_ with the guide available [here](https://github.com/cacophony-wj/licentia_black/blob/main/How-To-Run-Synthesis.md).

The last step is to get rid of the SLOOTY replacer BodySlides. Find the mod that reads "SLOOT BodySlide Output" and double-click it. In here you need to click the "Filetree" tab at the top. Expand the `meshes` folder and **RIGHT CLICK -> HIDE** on everything except the one named "DX." Sometimes you will receive a permissions error doing this because of bugs in MO2 so you mey need to just go into this folder and delete these directories.

**EDIT:** One final step that I forgot when I initially made this guide. Some of the outfit records and leveled lists need to be changed. Drop this `ESP` into your `overwrite` folder (something like `D:\Licentia\overwrite`) and press `F5` to Refresh MO2. The ESP will appear at the bottom of your Load Order in the right pane. Place a check mark in the bubble next to it and you should be good to go.

[MINISLOOT patch](/esps/Travis_MINISLOOT.esp)

That should take care of it. Please be aware that all of this can only be done on a **full new game with the New Game option from the Main Menu.**

Enjoy **MINISLOOT.**

## ADDING SOFIA BACK

**Another Commission for @MinuKaizer#7953!** I know some of you enjoy Sofia for some damn reason (probably because she gets so catty with Serana). I removed her to make room for more LOTD mods, as well due to a host of complaints about her annoying-ness, but here is a guide on adding her back to _Licentia 6_ if you would like to have her.

First install all of the following mods, in the order they are listed below. For the _Sofia Bug & Patch Hub,_ be sure to install patches for the mods I use, including "Sofia - USSEP and Hearthfires Patch", "Sofia - RDO Patch," and "Sofia - GDO Patch" _in that order._ It would probably be best if you just "merged" them into the same "mod". For the sex option, be sure to choose the "Flower Girls Add-On", otherwise known as "Shadowman_Sofia_FG"

- https://www.nexusmods.com/skyrimspecialedition/mods/2180
- https://www.nexusmods.com/skyrimspecialedition/mods/38952
- https://www.nexusmods.com/skyrimspecialedition/mods/47383
- https://www.nexusmods.com/skyrimspecialedition/mods/64063
- https://www.nexusmods.com/skyrimspecialedition/mods/71288
- https://www.nexusmods.com/skyrimspecialedition/mods/74656

Locate them at the bottom of the PERSONALITIES header underneath the FOLLOWERS header in the **LEFT PANE OF MOD ORGANIZER** as shown in the first attached image. Enable them by placing a check in the bubble to the left. _Do it slowly, one at a time, or MO2 may crash and screw up your load order._ Then **refresh MO2** by striking the `F5` key.

Multiple `ESP`s will appear at the bottom of your Load order in the **RIGHT PANE OF MO2.** Relocate them just above `018Auri.esp`, the first follower in the list, as shown in the second attached image. Enable them in a similar fashion and **refresh MO2.**

Then all you need to do is copy the attached `ESP` to your "Shared Patches" folder and enable it just above `Schlongs of Skyrim.esp.` 

Keep in mind you will need at least **ONE FULL ESP SLOT** for the primary mod, so if your other additions are at **255** you will need to remove something. (I suggest removing a low-content mod with no patches such as _Smooches of Skyrim_ or _Community Overlays._)

**That should be it,** but if you desire a different appearance for Sofia, or that she wear underwear instead of stripping naked all the time, or other customizations, ping me on my Discord server and I'll see what I can do!

![Sofia Install Order](/images/sofia.load.order.png)
![Sofia Load Ordder](/images/sofia.install.order.png)

[Sofia Patch](/esps/Minus_Sofia.esp) **(Click the RAW link in the upper right)**

## ADDING IMPROVED LYDIA BACK

**If you are missing the awesome _Improved Lydia_ mod from your _BLACK_ playthrough,** I have a patch here to help you out, at the request of @quesoturtle#4588. First, you need to install the following two mods:

https://www.nexusmods.com/skyrimspecialedition/mods/38473?tab=files&file_id=377102
https://www.nexusmods.com/skyrimspecialedition/mods/53432?tab=files&file_id=219517

Place the first one right above the second one right under _Lucien Replacer - Ella's Version_, which is at the bottom of the black _Personalties_ header under the purple _FOLLOWERS_ in the **left pane** of _Mod Organizer 2._ Be sure to enable them by placing a checkmark in the round bubble to the left, and **refresh MO2** by pressing the `F5` key.

Next you need to move the `ImprovedFollowersBoogalo.esp` to is proper location. It needs to go just above `Schlongs of Skyrim.esp`. Don't put it anywhere else.

Next, copy the attached `ESP` into your _Shared Patches_ mod in MO2. You can right-click on it, select "Open in Explorer," and paste the `ESP` anywhere in there. Close out that window and **refresh MO2** by pressing `F5`. The ESP will appear at the **bottom of your Load Order** in the **right pane** of MO2. _Leave it there and place a checkmark next to it to enable it._

This should only be done on a new game, but you should be good to go!

[Lydia Patch](/esps/quesoturtles_lydia.esp) **(Click the RAW link in the upper right)**

## ADDING TAINTED BLOOD OF THE DRAGONBORN

**Like being a _Growl_ werewolf, a _Sacrosanct_ vampire, or an _Undeath_ lich? How would you like to be all three AT THE SAME TIME!?** At the request of @Climanata#7661, I created a Patch for _Tainted Blood of the Dragonborn_ which, with a little effort, allows you to be even more OP than ever before!

To incorporate this mod, first install all three of the following files in the order they are listed below:

https://www.nexusmods.com/skyrimspecialedition/mods/9312?tab=files&file_id=155883
https://www.nexusmods.com/skyrimspecialedition/mods/9312?tab=files&file_id=130548
https://www.nexusmods.com/skyrimspecialedition/mods/9312?tab=files&file_id=151431

Place them at the bottom of the "Transformations" header in order just below _Growl - Werebeasts of Skyrim_. **Refresh MO2.** 

Then you will need to relocate the two `ESP`s which appeared at the bottom of your Load Order (in the right pane of MO2) just above `CACO's FORMLISTS.ESP` **Refresh MO2.** 

Next you will need to extract the `BSA` archive within the main _Tainted Blood_ mod folder. To do so, click the "Archives" tab of MO2 in the **right pane** and find `Tainted_Blood.bsa.` You can't filter or search this list in anyway so just scroll down and hunt for it. After it is found, **right click** on it and select "Extract..." You need to point the dialog box that appears to the directory that the **MAIN** _Tainted Blood_ mod is installed, which will be something like `D:\Licentia\mods\Tainted Blood.` Allow it to extract all the files, then go to this directory and delete the `Tainted_Blood.bsa` that is located there. **Refresh MO2.**

As the last step, copy the attached `ESP` in your _Shared Patches_ folder and enable it at the bottom of your Load Order. **Refresh MO2.**

That's pretty much it!

**However I feel I must leave you with a warning.** Messing with derived forms of the Dragonborn is risky business and I have rarely seen it work as expected, and this mod appears to handle most of its compatibility for the three transformations with scripting (and there is a lot of heavy scripting in this list already), so be wary of bugs. For this reason (and I actually think it's a little too OP even for this list), I can't offer official support for this addition. If you encounter problems with your transformations as a result, you are on your own.

Finally a couple of notes from the comments for the mod. It may be rather buggy depending on which form you choose to succumb to first. I have read unconfirmed reports that it is best to acquire the forms in the same order they are presented originally: first werewolf, then vampire, and finally lich. Lastly, given that the Vampire keywords are sometimes applied via script, if you run into any problems you may be able to solve them by going into the MCM for _Tainted Blood_ and selecting the "Reset" option.

And hey, if it works great and you have a blast with it _without_ turning the whole game into a laughable cakewalk, report back, yeah?

[Tainted Blood Patch](/esps/clminatas_taint.esp) **(Click the RAW link in the upper right)**

## ADDING YURIANA, BUXOM WENCH

**To include _Yuriana, Buxom Wench_ into _Licentia BLACK_** install the mod just as you did the others, under _Lucien Replacer._

https://www.nexusmods.com/skyrimspecialedition/mods/598

Place the attached ESP below at the end of your Load Order. You can select any hairstyle you want because no patches are necessary to include them. She does have custom "tied up" poses, so you will also need to run _Nemesis._ To do so, find the guide for adding animations in the primary readme.

**Warning:** I have received scattered user reports that this mod is damaging to long-term saves, particularly due to Yuriana and other followers' heavily-scripted AoE spells and especially in combination with other _Wenches_ series of mods. If you notice spells being cast repeatedly on you even in the absence of the triggers that are supposed to proc them, you have encountered this bug, which reports suggest only begins to occur after about 50 hours of play. Use with caution.

[Yuriana Patch](/esps/traces_yuriana.esp) **(Click the RAW link in the upper right)**
