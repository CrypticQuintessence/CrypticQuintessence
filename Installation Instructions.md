- 👋 Hi, I’m @CrypticQuintessence
- 👀 RECOMMENDED HARDWARE:  16-32 GB of ram, 12-16GB of VRAM. 6-8+ core modern CPU.
- 💞️ HARD REQUIREMENT: At Least 295 GB OF FREE SPACE ON YOUR HARD DRIVE, After Install is Complete the game WILL ONLY TAKE UP 181.7GB 
- 📫 Try reaching me at reddit r/SpaceEngineerGuy420
- 📫 OR [Discord](https://discord.gg/X26qEpPh )
- 📫 OR [Youtube](https://www.youtube.com/channel/UCbpbGRJs70w9Ol4mXUf9t7Q )
- 📫 OR [Reddit](https://www.reddit.com/r/crypticquintessence/ )

--------

Check the Modlist https://loadorderlibrary.com/lists/cryptic-quintessence-v05

Still a very early release! bare with me as we tweak the bugs out, I NEED TESTERS

Featuring 666+ mods . I have spent extensive time modding, 
configuring and problem solving issues. I've done extensive bug testing to maintain a stable, 
long lasting gameplay with nothing to do on your part but play the game and have fun.
 (some installation needed)

Cryptic Quintessence is a ModList with the objective to have the smoothest high framerate gameplay,
with insanely gorgeous scenery and unpresidented immersion.

Absolutely every aspect of the game has been altered in some fashion while still keeping that original skyrim feel, but the graphics of a modern day AAA game. Some features include overhauls of - animations, weapons, armour, skills, scenery, characters, skins, everything is a high poly 2 to 4k resolution. Parallax on the terrain and other objects. A beautiful grass landscape for the exterior and much much more. Be sure to check the entire modlist to see all of the many great features that have been implemented such as overhauls of the alchemy and crafting. 

A stinging realistic economy with many different types of septims to find throughout skyrim. Using the object placer mod you can drop all your gold and jewels onto the ground and then save them in place. As you explore and collect more gold you can bullguard it and keep it out in the open without worry of the items disappearing upon leaving the cell.

A video on this feature will be uploaded soon, showing how this modlist implements that into the game, but were are still only scratching the surface with this massive modlist you are guarenteed to be delved into complete immersion. The audio overhaul and other ini tweaks allow for 5.1 audio so if you have surround sound you will get directional hearing quite well, which was not implemented into the game originally (as far as I know).

I don't want to ruin the experiance of you finding all these new features its better if you just hop in and explore.

But before we can do that lets get this install process underway :D

----

You will need to download Wabbajack first, Which can be found [here](https://www.wabbajack.org/#/) just run that exe and install it into any folder you like. make sure you have room on hard drive.

If you haven't already gotten the required .WABBAJACK files to download the entire modlist yet, [DOWNLOAD THEM HERE](https://drive.google.com/file/d/1r0aIHfMGHu_hGpq2IUMCi6FkC7f9oQEc/view?usp=sharing) (You have to click the download button on the upper top-right hand side.)

Just extract the .rar file containing:

* "Cryptic Quintessence.wabbajack"
* "Cryptic Quintessence.wabbajack.manifest.json" 
* "Cryptic Quintessence.wabbajack.meta.json"

Extract all 3 of the files into the same drive as your wabbajack install directory. ( anywhere with space on the same drive should do.) 

Double click "Cryptic Quintessence.wabbajack", Wabbajack should open up if you installed it correctly.

From here just type in your installation location (the path to your main skyrim se files), it will also prompt you to put in your Download Location as well. 

You also want to determain if you want to overwrite your existing installation, Then click the arrow/play button to begin downloading all the required files. At a few points during the install it will likely stop, at which point you will have to manually download the required files on the page that it brings you to. Let wabbajack finish downloading the rest of the mods.

if you get stuck here at any point you should watch a youtube video on wabbajack installation, or preferably contact me on reddit at r/SpaceEngineerGuy420, as I will be able to nudge you in the right direction.

----------

Once all mods are downloaded, (or not maybe they will require you to download these files first) 

What we want to do is download the SKSE plugins if you havn't already. the process is simple and ill guide you through the way.

1.) Go to [this page](http://enbdev.com/mod_tesskyrimse_v0473.htm ) and download the latest version, the download button is at the bottom of the page.

2.) You will have a file called "enbseries_skyrimse_v0473.zip"

3.) Open up the archive.

4.) once inside the archive you will see 2 folders called "LinuxVersion" and "WrapperVersion".

5.) Go inside the "WrapperVersion" folder 

6.) Select Only These 5 files. "enbseries" (this one is a folder) , "d3d11.dll", "d3dcompiler_46e.dll", "enblocal.ini" and "enbseries.ini"

7.) place the enbseries folder, the two .dll files; and the enbseries and enblocal.ini files into the root of your skyrim install directory, ussually named (The Elder Scrolls V Skyrim - Special Edition) or (Skyrim SE) or whatever you named it too. 

We will be overwriting a few files in this directory shortly in the next few steps. 

----

Before you move on from this step KEEP THIS IN MIND...

Generally you do not want to overwrite and the entire enblocal.ini unless stated to do so. Instead you should be opening your enblocal.ini and copying the text from the new enblocal.ini Don't worry though I'll tell you exactly what to do, follow the steps and you'll be fine.

-------

Here is the ENBseries we will be using, we are only needing this for the effects and we are applying ENBoost overtop of this.

8.) go to [this web page](https://www.nexusmods.com/skyrimspecialedition/mods/39113?tab=files)  and download "Rudy ENB SE for Cathedral Weathers" 

9.) Open up the archive called "Rudy ENB SE for Cathedral Weathers-39113-5-0b-1638131180.rar" that you just downloaded and navigate through the file as shown ----->Rudy for SSE 5.0b CW-->! Catherdral Weathers ELFX-->Normal Game-->[ Skyrim SE folder ]

***IMPORTANT***

10.) Inside the "[ Skyrim SE folder ]" folder, SELECT ONLY the "enbseries.ini" file, and the "enbseries" folder, and extract them to the root of your skyrim install directory. *usually named (The Elder Scrolls V Skyrim - Special Edition)*
Overwrite and Replace the files when and if it asks.

I will provide my own seperate enblocal.ini file for you at the end.

------

Next step is to download ENBoost.

11.) Go to [this webpage](http://enbdev.com/mod_fallout4_v0283.htm) Click the download button on the bottom left. (yes I know it says fallout4, no worries)

12.) Inside the "enbseries_fallout4_v0283.zip" archive you just downloaded, you will see a folder called "patch" open it up.

13.)Copy ONLY the "d3d11.dll" and "d3dcompiler_46e.dll" and paste them into the root of your skyrim install directory, Overwriting and replacing any files when and if it asks. *do not copy the enblocal.ini* finally we can move onto the last part, Parallax shaders fix. 

14.) Go to [this webpage](https://www.nexusmods.com/skyrimspecialedition/mods/31963) and download the file under OPTIONAL FILES called "d3dcompiler_47".

15.) open the "d3dcompiler_47-31963-1-0-1579609721.7z" archive and extract the "d3dcompiler_47.dll" into the root of your skyrim install directory.

16.) Download my enblocal.ini and replace your enblocal.ini with mine. My enblocal.ini file can be found at [this link](https://drive.google.com/file/d/1XshEBVM67ZSMB7M9T36I4hX56DsctGZh/view?usp=sharing)



-------                                                                                                               

17.) Now check out [THIS](https://loadorderlibrary.com/lists/cryptic-quintessence-v05)

18.) on this page you will see all of the files required for your "Default" folder located in MO2 --> profiles --> Default

19.) Copy over all of these files that I provided in [THIS](https://loadorderlibrary.com/lists/cryptic-quintessence-v05) webpage, 
and paste them into your "Default" Folder located in MO2 --> profiles --> Default -->

the files should be

skyrimcustom.ini
skyrim.ini
modlist.txt
loadorder.txt
plugins.txt
settings.ini
skyrimprefs.ini

20.) SETTING UP SCREEN RESOLUTION!                                                                                   
                                                                                                                     
A mod called SSE Display Tweaks should be in the left pane of MO2 with a priority of 632 if you can't find it        
                                                                                                                     
21.) right click the "SSE Display Tweaks" mod and click "Open In Explorer"    

22.) you will see a folder called "SKSE" double click it.     

23.) you will see a folder called "Plugins" double click it.      

24.) Open the file called "SSEDisplayTweaks.ini" with notepad.      

25.) Here are a ton of options you can change but don't change anything for now just your resolution. Scroll down to "Resolution=3840x2160" and change it to your screen resolution.       

26.)You have to change the resolution on not only the SSEDisplayTweaks.ini as mention above, but also in the default skyrim launcher. to do this just launch "Skyrim Special Edition Launcher" from within ModOrganizer2  and change your resolution on this as well.          

27.)if you still dont have the screen resolution working properly then drop the folder called "BethINI Standalone" onto your desktop. [Here](https://www.nexusmods.com/skyrimspecialedition/mods/4875?tab=files) is a link to download BethINI Standalone

28.) open BethINI.exe and select your resolution and fullscreen options from here, also make sure the paths are setup correctly... when done click save and exit.

29.) YOU DID IT YAY!

----
                                                                                                                      
**IMPORTANT**      When you first start up, MAKE A NEW SAVE (optionally try my savegame to save time)    **IMPORTANT**                                         
                                                                                                                      
Also I'd try not to do vanilla start. You can of course give it a whirl, but if one of the main characters doesn't show up you might crash before you reach the castle with rolaf. If you don't crash or have any ill affects after the beggining cut scene is over and you leave the cave to skyrim, then you should be fine and nothing will crash. Just thought I'd mention that.      

EXTRA EXTRA! READ ALL ABOUT IT!

Below is a link to potential fixes for parallax textures should they arrise. (they shouldn't but you never know)

Link to FIXES https://docs.google.com/document/d/1IrA2a5q-rVWBpDv3DIvZLdxSx5RopMnLbzEmLO2pDlA/edit#heading=h.m4nbqcs9gn8h

```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
Thank you for taking the time to download my modlist, This is the first release and there may be a few unseen bugs,
but throughout my testing and tweaking, I've eliminated all game breaking bugs and am still looking for testers
as modding in and itself is a long drawn out process and the time to do a complete playthrough just is to hard when 
you're constantly working on other stuff. 
```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````

Please do not hesitate to contact me on reddit at r/SpaceEngineerGuy420

I really look forward to seeing what you guys think as this actually took me ages to put togeather. 

OTHER TIPS

* Upon First startup give the scripts a minute to catch up before changing settings in the MCM menu. (you will see alot of stuff loading in, in the top left corner.
* When changing MCM Configurations, try to edit only 2 or 3 mods.. and then exit the MCM window to load the scripts in, then continue to edit the MCM menus until you are finished. configuring all the MCM menus to your liking. 
* I suggest adding gold weight to 0.0038 for full realism.
* Not sure if you will have the save game or not but if you do, I'd reccommend using it. 
* on the save file I've preconfigured all the MCM windows beforehand so all you have to do is load up the save, use the command "showracemenu" in the in-game console and configure your character. I left a male and a female preset in there.


After you've gotten everything set up and it's all playable. 
You've made a save game, can come back to it and play when ever you want...

Then you can OPTIONALLY delete the .rar files located in the "downloads" folder, which is located in the MO2 folder.

Inside the downloads folder are the RAW mods used to put the game togeather along with the .META data needed to figure out where all the files came from.
If you re-install any of the mods you will likely have problems because I've modded each of the mods personally to make ALL of the mods work togeather.
That means many many various edits to individual files, and if you go and try to re-install any of the mods you will likely be re-installing the problems that
i've already fixed and implemented to you via the Wabbajack file.

The .wabbajack File includes all of the edits and patches that I've made to the game so all you have to do is play.

That being said, if you don't know much about modding you're safe to delete the .rar files in the downloads folder of MO2. This will save you nearly double the space.
You can keep the .Meta files inside your downloads folder incase you need the source of a mod, and you wish to modify the modlist yourself.

If you plan on adding mods to the game further I'd recommend leaving the downloads folder inside MO2 IN TACT; meaning don't delete anything.

Good luck on your new adventure, and godspeed.

r/SpaceEngineerGuy420

























