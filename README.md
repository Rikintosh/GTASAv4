
# The Unofficial Grand Theft Auto San Andreas V4.00
Just a compilation of fixes and improvements for the Playstation 2 version

Since tools were created to modify the Playstation 2 version, I have been trying to fix and improve the PS2 version. In addition to my own fixes that I created for this version, the vast majority of improvements come from mods created by the community, mainly because of MixMods and its maintainer Junior_Djjr. Many changes were made over the years, I myself no longer remember all of them, but I will list the ones I remember now:


- The game script: My original intention was to use v2.01 (aka V3.00) as it has optimized variables, but unfortunately this requires modifying the executable. So I modified v1.03 to fix two missions (4000 to 2500 points in the car dance mission, and the plane fuel)
- SNPatch by Daniel Santos (editing fileload.nm in the hexadecimal editor removing the name GTA3_1.img) but I also removed GTA_INT_1.
- Several files that rockstar never corrected in the PS2 version
- Corrected vehicles, with the correct reflection texture, chrome, glass, lighting...
- Texture improvement: Generic effects and textures were based on my own mods, and were converted to the PS2, optimizing efficiency to the maximum due to memory and color palette limitations
- A huge amount of textures were manually edited by me, and the pal_4 and pal_8 color palette was optimized.
- All of the game's TXD files were rebuilt and optimized, resulting in a smaller final size and faster loading, even improving the loading speed when the game runs via USB on the OPL.
- The game's memory stream has been carefully edited to slightly improve pop in, and slightly increase space for some fixed textures
- This version has the mod loader from Daniel Santos
- The textures of the car interiors are unique, due to the implementation of my mod "Rikintosh's Small Details Mod", but unfortunately all textures were limited to a size of 128x128 due to hardware limitations.
- The road textures were converted from the PC version, as they have a higher level of detail, despite the size limitation, I used the paint.net resizing algorithm to maintain the best possible level of detail.
- Radar textures that faithfully represent the streets and buildings present in the game (mod "proper radar" by Junior_Djjr)
- Fixed widescreen, 16:9, HUD, FOV, multiplayer mode, working correctly (by ThirteenAG and Daniel Santos)

# How to use:

You will need:

- Backup Grand Theft Auto San Andreas v1.03 (USA) in ISO format.
- GTA-SA Crazy IMG Editor
- UltraISO
- Ps2_patch_engine

Open your ISO with UltraISO, and extract its contents to any folder. Merge the files.
Now open GTA-SA Crazy IMG Editor (make sure to change the language to English through the first menu, in case the interface displays strange characters), open the GTA3.IMG file, and add with replacement (menu edit -> add with replacement ) and add the files from the "(to)GTA3.IMG" folder. Repeat this process for each of the IMG files. After adding the files, there is no need to save or rebuild, just close GTA-SA Crazy IMG Editor.

Now delete the folders (to)GTA3.IMG, (to)GTA_INT.IMG, (to)CUTSCENE.IMG, (to)PLAYER.IMG. Also delete the GTA3_1.img file. Optionally you may want to delete unused files (google it)

Now open your ISO again with UltraISO, and add the files back, replacing the ISO files. Save.

Open ps2_patch_engine.exe, click browse, and choose the iso file you saved. Then, click on pnatch, and below, paste the text content present in the file "patch by daniel santos.txt". Click on patch, save the new file, and that's it!

