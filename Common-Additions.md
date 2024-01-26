# CACO's COMMISSIONS - 

### Or: Commonly Requested Additions to LICENTIA BLACK, An ever-evolving document

## UPDATED 11/1/2023.

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

[MINISLOOT patch](/esps/Travis_MINISLOOT.esp) **(Click the RAW link in the upper right)**

That should take care of it. Please be aware that all of this can only be done on a **full new game with the New Game option from the Main Menu.**

Enjoy **MINISLOOT.**

## ADDING SOFIA BACK

**OUT OF DATE, REMOVED**

## ADDING IMPROVED LYDIA BACK

**OUT OF DATE, REMOVED**

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

## ADDING COLDHAVEN

_Coldhaven_, the Vampire City, is currently only available in the **_Licentia DEAD_** profile. This commission -- at the request of @Bistrus -- allows you to add it to **any** of the profiles.

The three mods you'll need are here:

- https://www.nexusmods.com/skyrimspecialedition/mods/22379
- https://www.nexusmods.com/skyrimspecialedition/mods/56193
- https://www.nexusmods.com/skyrimspecialedition/mods/22379

You'll want the **Main Files** from each page and **nothing else.** Install them into _MO2_ in the order listed above and drag them under "Added Mods."

For the Load Order in the Right Pane, you'll want `Coldhaven.esm` below the **last major Quest mod** (for me that's `Undeath.esp`). `ColdhavenOcclusionCulling.esp` goes just above `Dyndolod.esm` **NOT THE ESP.** This is near the top. 

For the xEdit conflicts, attach the following patch at the end of your Load Order. Remember, the easiest way to do this is to drop the `ESP` into "overwrite" and **REFRESH MO2** (strike the `F5` key). Then you can enable it by placing a check in it.

[Coldhaven Patch](/esps/Bistrus_Coldhaven.esp) **Click the RAW link in the upper right)**

## BETTER VAMPIRES NPCs & WEAPONS

This Commission (again for @Bistrus) is a combo. You need both mods:

- https://www.nexusmods.com/skyrimspecialedition/mods/9510
- https://www.nexusmods.com/skyrimspecialedition/mods/34466

Again you'll want the **Main Files Only.** Install them into _MO2_ (any order will do) and drag them under "Added Mods."

They can really go almost anywhere in your Load Order, but for consistency's sake, I recommend just above `Schlongs of Skyrim.esp` **NOT THE ESM.** Follow the same procedure as above to enable them.

This patch goes at the end of your Load Order.

[Better Vampire Patch](/esps/Bistrus_BetterVampires.esp) **Click the RAW link in the upper right)**
