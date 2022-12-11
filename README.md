**Final Project ~ Quake 2**
[*Matthew Barrera*]

***Common Deliverables:***
1. Shortcut that auto-launches your mod. *[Complete]*
2. Mod in a separate folder. *[Complete]*
3. README file in GIT that explains: *[WIP]*
   -  HOWTO install your mod.
   -  HOWTO play/test your mod.
4. UI updates reflecting your Personal Deliverables *[Complete]*
5. Help screen to detail how to play your mod in-game. *[WIP]*


***My Specific Deliverables:***
1. Replace Weapons with God of War Weapons. *[WIP]*
   - 10 Weapons / 10 Moves from the Weapons. (i.e. Kratos weapons, Throwing versions, Atreus weapon, Etc.)
2. Upgradable Stats
   - 5 Stats.
3. Rage Mode.
   - More than just Quad Damage; Create Behavioral Changes. (i.e. New attacks, Attacks have new properties, Etc.)
4. Weapon Upgrades / Blacksmith System. (Random location spawn)
5. Boss Mechanics
   - Enemies with multiple bars of HP; Kill it multiple times to actually kill it.

***Version 2.0 README.md Notes:***

 - Almost all of the files included in this main branch originate from the "...\quake2-full-master\game\release\" directory. These are the files that were editted and compiled in the "game" folder from the quake2.sln. These files do not represent the unchanged code I originally received. I have made changes and comments in the files. The only file in the main branch that didn't come from this directory is... (View next bullet).
 - There is a folder included in this main branch called "modF22GOW", which acts as my 2nd Common Deliverable (Mod in a separate folder). All of the code needed to run my mod can be found in this folder. **To install my mod, simply download the "modF22GoW" folder and all of it's contents. Do not change the contents of this folder after downloading it. Then, place the entire "modF22GoW" folder into the "C:\Program Files (x86)\Steam\steamapps\common\Quake 2\" directory. If done correct, this folder and baseq2 should both be visible inside the same folder at the same time. In order to get access to the UI updates for the new weapons, follow the instructions of the folder inside of "modF22GoW" (Specifically, move the pcx files to the pics folders inside pak0 of baseq2).**
 - There is a file inside the "modF22GoW" folder called "Quake2 ~ modF22GoW", which acts as my 1st Common Deliverable (Shortcut to auto-launch the mod). This is why the exact directory the "modF22GoW" folder goes into is super important; it impacts the target properties of the shortcut. **To play my mod, simply click on the "Quake2 ~ modF22GoW" shortcut. Once inside of the game, select "Game" in the main menu and than any of the difficulties (Easy, Normal, Hard). To test my mod, use the command "modhelp" in the command prompt and try out some of the suggestions given.**

===========================================================================================

- The README is a WIP because (a) there still needs to be work done that would need to be properly documented in the README in the future. Many things have already been documented, but I just need to finalize when the time comes.
- The help screen is a WIP because (a) there still needs to be work done on the mod's functionality. I already have a method to search for the help screen while in-game, but I just need to finalize it when the mod is finished.
- Replacing the weapons is a WIP because (a) I only have a bit of the functionality implemented. For the past few days, I've been stumped trying to limit the bullet travel distance. I've been viewing p_weapon.c and g_weapon.c, but all attempts to change the bullet travel distance so far have failed.
- In regards to UI changes made, they can be found by spawning the guns and viewing their HUD icon. I went with simple designs, but even then I had trouble because the design would often get ruined in-between PNG and PCX file conversion. However, the current PCX files do have distinct and noticeable differences that be viewed from within the small HUD icon. Thus, I would label the UI changes a success.

***This README.md and all of the files in the main branch will most likely change between this and the next branch.***
